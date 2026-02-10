# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This repository contains the documentation and planning materials for "구름골의 보물/Treasure of Cloud Valley", a Korean children's adventure fantasy novel. The project is a collaborative novel writing effort between AI and human teams, targeting elementary to middle school readers (Harry Potter Book 1 reading level).

## Document Writing Rules

This section establishes rules for collaborative novel writing between AI and human teams.

**IMPORTANT**: The Document Writing Rules section should not be modified unless explicitly requested by the user.

### General Rules

- All documents are written in markdown format by default.
- Considering context window limitations, rules documents are written in English while other documents are written in Korean.
- Rules documents should be kept as concise as possible.
- **Proper nouns**: In CLAUDE.md, all proper nouns (character names, place names, etc.) must be written in both Korean and English format as "Korean/English" to maintain consistency. Example: 구름골/Cloud Valley, 임수진/Im Su-jin.

### Structural Unit Definitions

Higher-level and lower-level units may be equivalent. For example, a single moment might constitute one scene, or a single sequence might form one episode.

- **Beat**(비트): A single emotional change or information delivery. Ranges from sentence to paragraph level.
- **Moment**(모멘트): A period where specific tension or atmosphere is sustained. Temporally spans from several minutes to dozens of minutes.
- **Scene**(장면/씬): A collection of moments. A complete event occurring in a single spatiotemporal setting with clear starting and ending points.
- **Sequence**(시퀀스): A collection of related scenes, representing a subplot or major event. A collection of scenes aimed at achieving one plot "objective."
- **Episode**(에피소드): Maintains reader interest and creates anticipation for the next installment. Includes mini-climax and hook. May serve as a serialization unit.
- **Chapter**(장/챕터): Serves readability functions. Physical division considering reader's cognitive load and rest needs. Appropriate length and sense of closure.
- **Act**(막): Major units based on narrative turning points. The number of acts varies by work (e.g., 3-act, 4-act/기승전결). Prologue and Epilogue, while listed alongside acts for convenience, are framing devices rather than acts proper.
- **Part**(부): May present entirely different stories within the same setting or different stories with the same theme, sometimes forming complete standalone works.
- **Work**(작품): The complete novel

#### Example

> The elevator doors opened, and there she was. It had been ten years. Neither could speak. Even as other passengers got on and off, their gazes never wavered. 3rd floor, 4th floor, 5th floor... only the numbers changed quietly.

Multiple beats (door opening + recognition + silence + eye contact + time passage) create a unified moment within a single tension.

### Higher-Level Documents

When the work is small in scale, `character-overview` and `setting-overview` may be omitted, or these documents may contain relatively specific content while related detailed setting documents are omitted.

- **README**: Accessible to first-time readers to understand the work's overview. Includes work introduction, large-scale work composition, major document list, etc. Also includes theme, major materials, genre, target audience, main themes, core conflicts, production intent, main characters, setting, overall plot, work's originality and distinctive points.
- **rules**: The `CLAUDE.md` document serves as rules. Content that must be referenced every time (files that LLMs mechanically reference always). Keep concise. Includes style guidelines, narrative perspective, tense, character addressing, consistency rules to note, major motifs and symbols, prohibited items, etc. Includes simple structural unit document rules and template lists.
- **character-overview**: Overview of major characters. Includes character relationships, core characteristics, personality keywords, speech and behavior patterns, rough story arcs, background stories, etc.
- **setting-overview**: Overview of work background. Includes temporal and spatial background, social/political/economic structures, culture and customs, technology level, unique social rules, geographical information, etc.
- **plot-structure**: Definitions for sub-documents (structural unit documents). Varies according to work scale. Some works may need Part-level units while others may conclude with just a few scenes, so the structure of documents under this category is defined here. Also includes a list of higher-level structural unit documents, serving an index function. Basic unit usage for this work is also briefly mentioned in the rules document to avoid multiple references.

### Detailed Setting Documents

- **character/character-SOMEONE**: If there is substantial content about characters, detailed separate documents are written for each. Stored in the `character/` directory.
- **setting-SOMETHING**: If there is substantial content about background and settings, detailed separate documents are written for each.

### Structural Unit Documents

Detailed content is defined in the plot-structure document. The basic rule is that files start with numbers and end with units. As explained earlier, depending on scale, there may be `04-chapter.md` files or `03-24-scene.md` files. Which scale and units are used for this work is defined in the plot-structure document.

**This work uses Act-Chapter-Scene 3-tier structure.** Omitted units (Beat, Moment, Sequence, Episode) have their functions absorbed by adjacent units: Beat/Moment functions are absorbed by Scene, and Sequence/Episode functions are absorbed by Chapter.

**Folder structure**: Each structural unit is stored in its corresponding folder. The production pipeline flows as: `act/` → `chapter/` → `scene/` → `novel/` → `final/`.
- `act/`: Act-level documents (including prologue/epilogue)
- `chapter/`: Chapter-level documents
- `scene/`: Scene-level documents
- `novel/`: Draft novel prose converted from scene documents
- `final/`: Finalized, publication-ready chapter files

**Numbering convention**:
- **Act**: Sequential number (e.g., `act/01-act.md`, `act/02-act.md`)
- **Chapter**: Absolute numbering across the entire work (e.g., `chapter/02-03-chapter.md` = Act 2, Chapter 3 overall)
- **Scene**: Relative numbering within each chapter (e.g., `scene/02-03-01-scene.md` = Act 2, Chapter 3, Scene 1 of that chapter)

### Templates

Documents like `template-seq.md` define templates for corresponding structural unit documents. Generally, higher-level unit documents include lists for lower-level unit documents and have structures corresponding to each unit's purpose. For example, scene documents include time and space, and how the scene begins and ends, while episode documents describe how the rise and fall flow within the episode and what hook leads to the next episode. When certain units are omitted, higher-level unit documents include the functionality of the omitted units.

**Template status**: No templates exist yet. Templates will be created as the project structure stabilizes. Planned templates:
- `template-scene.md`: Should include Beat functions (emotional changes per beat) and Moment functions (tension/atmosphere tracking) since these units are omitted in this work.
- `template-chapter.md`: Should include Episode functions (mini-climax, start/end hooks) and Sequence functions (subplot objectives) since these units are omitted in this work.
- Additional templates created as needed for specific structural units

### Feedback File Timestamp Rules

- **Timestamp generation**: The main agent generates the KST timestamp using `date '+%Y%m%d-%H%M'` before launching sub-agents.
- **Filename specification**: The main agent specifies the complete filename (including timestamp) and passes it to each sub-agent.
- **Sub-agent compliance**: Sub-agents must use the provided filename exactly as given, without generating their own timestamps.
- **File naming**: `feedback/{timestamp}-{description}-{agent}.md` format. The description part is flexible depending on the type of feedback (e.g., `20260210-0930-01-02-03-scene-eval-hyewon.md`, `20260210-0930-novel-01-02-01-review-yeonsu.md`, `20260210-0930-scene-eval-crit-feedback-hojin.md`)

### File Encoding Rules (CRITICAL)

- ALWAYS ensure files are saved with UTF-8 encoding
- When creating or modifying files with Korean text:
	1. First delete the corrupted file if it exists (using rm command)
	2. Then create a new file with proper UTF-8 encoding
	3. Never attempt to edit files with corrupted encoding
- If Korean text appears as garbled characters (e.g., "ì¤ì¹ ë° ì¤í"), immediately recreate the file
- Always verify file encoding after creation by reading the file

### Final Novel Files

Final novel files are the complete prose versions of the smallest structural unit documents. These files contain the actual novel text that readers will consume.

- **File naming**: `novel/novel-[numbers].md` format (e.g., `novel/novel-02-03-11.md` for Act 2, Chapter 3, Scene 11)
- **Location**: All final novel files are stored in the `novel/` directory
- **Content**: Full prose narrative converted from structural unit documents
- **Format**:
  - Written in Korean following all style guidelines
  - Complete narrative prose without structural markers or metadata
  - Maintains all elements from the structural document but in novel form
- **Creation process**: Transform the smallest unit documents (scenes, moments, etc.) into flowing narrative text

### Finalized Chapter Files

Finalized chapter files are the publication-ready versions assembled from novel files. These represent the final confirmed text.

- **File naming**: `final/f-{chapter number}-{chapter name}.md` format (e.g., `final/f-0-prologue.md`, `final/f-1-friends.md`)
- **Location**: All finalized files are stored in the `final/` directory
- **Content**: Complete, reviewed chapter text ready for publication

## Style and Agent Guidelines

For comprehensive style guidelines, character specifications, paragraph structure requirements, and agent instructions, see **`style-guide.md`**.

This includes:
- Narrative perspective, tense, and writing style
- Target audience and content guidelines
- Character dialogue patterns and comic elements
- Paragraph structure and flow
- Agent-specific instructions for novel writers and editorial writers

## Multi-Agent Review Protocol

When the user requests "모든 에이전트를 호출하라" (call all agents), call all four agents without exception:
- `plot-writer-hyewon`
- `editor-yeonsu`
- `content-director-kim`
- `novel-writer-park`

## Known Issues and Workarounds

### Korean Word Encoding Issue: "스스로" (oneself / on one's own)

**Issue Description**: The Korean word "스스로" has been intermittently flagged by validation systems despite correct UTF-8 encoding and proper character composition.

**Verification Method**:
```bash
# Check hex encoding
echo "스스로" | od -x
# Verify UTF-8 bytes: EC 8A A4 EB A1 9C (correct Korean encoding)
```

**Policy**:
- **ACCEPT AS-IS**: "스스로" is correctly encoded in UTF-8 and compositionally valid in Korean.
- **NO CORRECTION NEEDED**: Do not replace, re-encode, or modify this word.
- **Documentation**: This is a known false-positive from LLM validation. Proceed with the word unchanged.
- **Locations**: Appears in character arc descriptions (e.g., 02-04-chapter.md). Keep as written.

**Action**: If flagged by future validators, inform user this is a known false positive. Do not treat as an error.
