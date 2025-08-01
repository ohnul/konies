# CLAUDE.md



## Document Writing Rules

This document establishes rules for collaborative novel writing between AI and human teams.

### General Rules

- All documents are written in markdown format by default.
- Considering context window limitations, rules documents are written in English while other documents are written in Korean.
- Rules documents should be kept as concise as possible.

### Structural Unit Definitions

Higher-level and lower-level units may be equivalent. For example, a single moment might constitute one scene, or a single sequence might form one episode.

- **Beat**(비트): A single emotional change or information delivery. Ranges from sentence to paragraph level.
- **Moment**(모멘트): A period where specific tension or atmosphere is sustained. Temporally spans from several minutes to dozens of minutes.
- **Scene**(장면/씬): A collection of moments. A complete event occurring in a single spatiotemporal setting with clear starting and ending points.
- **Sequence**(시퀀스): A collection of related scenes, representing a subplot or major event. A collection of scenes aimed at achieving one plot "objective."
- **Episode**(에피소드): Maintains reader interest and creates anticipation for the next installment. Includes mini-climax and hook. May serve as a serialization unit.
- **Chapter**(장/챕터): Serves readability functions. Physical division considering reader's cognitive load and rest needs. Appropriate length and sense of closure.
- **Act**(막): Major units based on narrative turning points. Three-act structure or equivalent to introduction-development-climax-resolution structure.
- **Part**(부): May present entirely different stories within the same setting or different stories with the same theme, sometimes forming complete standalone works.
- **Work**(작품): The complete novel

#### Example

> The elevator doors opened, and there she was. It had been ten years. Neither could speak. Even as other passengers got on and off, their gazes never wavered. 3rd floor, 4th floor, 5th floor... only the numbers changed quietly.

Multiple beats (door opening + recognition + silence + eye contact + time passage) create a unified moment within a single tension.

### Higher-Level Documents

When the work is small in scale, `character-overview` and `setting-overview` may be omitted, or these documents may contain relatively specific content while related detailed setting documents are omitted.

- **README**: Accessible to first-time readers to understand the work's overview. Includes work introduction, large-scale work composition, major document list, etc. Also includes theme, major materials, genre, target audience, main themes, core conflicts, production intent, main characters, setting, overall plot, work's originality and distinctive points.
- **rules**: The `CLAUDE.md` document serves as rules. Content that must be referenced every time (files that LLMs mechanically reference always). Keep concise. Includes style guidelines, narrative perspective, tense, character addressing, consistency rules to note, major motifs and symbols, prohibited items, etc. Includes simple structural unit document rules and template lists.
- **characters-overview**: Overview of major characters. Includes character relationships, core characteristics, personality keywords, speech and behavior patterns, rough story arcs, background stories, etc.
- **settings-overview**: Overview of work background. Includes temporal and spatial background, social/political/economic structures, culture and customs, technology level, unique social rules, geographical information, etc.
- **plot-structure**: Definitions for sub-documents (structural unit documents). Varies according to work scale. Some works may need Part-level units while others may conclude with just a few scenes, so the structure of documents under this category is defined here. Also includes a list of higher-level structural unit documents, serving an index function. Basic unit usage for this work is also briefly mentioned in the rules document to avoid multiple references.

### Detailed Setting Documents

- **character-SOMEONE**: If there is substantial content about characters, detailed separate documents are written for each.
- **setting-SOMETHING**: If there is substantial content about background and settings, detailed separate documents are written for each.

### Structural Unit Documents

Detailed content is defined in the plot-structure document. The basic rule is that files start with numbers and end with units. For example, `01-act.md` contains explanations about Act 1. `01-03-chapter.md` contains content about Act 1, Chapter 3. As explained earlier, depending on scale, there may be `04-chapter.md` files or `03-24-scene.md` files. Which scale and units are used for this work is defined in the plot-structure document.

### Templates

Documents like `template-seq.md` define templates for corresponding structural unit documents. Generally, higher-level unit documents include lists for lower-level unit documents and have structures corresponding to each unit's purpose. For example, scene documents include time and space, and how the scene begins and ends, while episode documents describe how the rise and fall flow within the episode and what hook leads to the next episode. When certain units are omitted, higher-level unit documents include the functionality of the omitted units.

### File Encoding Rules (CRITICAL)

- ALWAYS ensure files are saved with UTF-8 encoding
- When creating or modifying files with Korean text:
	1. First delete the corrupted file if it exists (using rm command)
	2. Then create a new file with proper UTF-8 encoding
	3. Never attempt to edit files with corrupted encoding
- If Korean text appears as garbled characters (e.g., "ì¤ì¹ ë° ì¤í"), immediately recreate the file
- Always verify file encoding after creation by reading the file
