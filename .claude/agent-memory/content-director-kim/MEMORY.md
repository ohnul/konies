# Content Director Kim - Agent Memory

## Project Structure Decisions
- 4-Act structure (not 3-Act) with Prologue/Epilogue
- Units: Act > Chapter > Scene; Beat/Moment used inside Scene docs (not as separate files)
- Omitted units: Part, Episode (absorbed by Chapter), Sequence (absorbed by Chapter)
- Chapter numbering: Absolute across entire work (e.g., 02-03 = Act 2, Chapter 3 globally)
- Templates: No separate template files; structure definitions inline in plot-structure.md

## Known Document Inconsistencies (as of 2026-02-06)
- CLAUDE.md lists template files that don't exist (template-scene.md, template-seq.md, etc.)
- Chapter doc structure in plot-structure.md missing "mini-climax" and "subplot objective" (Episode/Sequence function absorption)
- README.md has wrong filenames: `characters-overview.md` should be `character-overview.md`, `settings-overview.md` should be `setting-overview.md`
- README.md and plot-structure.md have different Act subtitles for Acts 2 and 3
- CLAUDE.md example uses relative numbering (`01-03-chapter.md` = Act 1, Chapter 3) but actual files use absolute numbering
- CLAUDE.md says "Three-act structure" but work uses 4-act structure
- Prologue numbering inconsistent: 00-prologue-v2.md (act doc) vs scenes named 00-00-01/00-00-02

## Completed Work Status
- Act 1 fully structured: 2 chapters, 5 scenes (01-01-01 through 01-02-04)
- Prologue structured (00-prologue-v2.md) with 2 scenes
- Novel files: prologue final (final/f-0-prologue.md), Act 1 Ch1 final (final/f-1-friends.md)
- Novel directory also has: novel-00-00-01, novel-00-00-02, novel-01-01-01, novel-01-02-01 (+ gpt/cla variants)
- Acts 2-4 act docs created (02-act.md, 03-act.md, 04-act.md, 05-epilogue.md) on 2026-02-07
- Acts 2-4 chapter/scene docs: not yet created
- Dual output paths: /novel/ (working drafts) and /final/ (polished versions)

## Editorial Observations (Full Review 2026-02-06)
- Scene docs richly detailed with Beat/Moment structure, dialogue drafts, [NOTE-TO-AI] markers
- Chapter docs serve as solid intermediate summaries
- Act docs properly aggregate chapter-level information
- 60/40 adventure-tension/friendship-humor balance well-articulated but needs verification in novel files
- 4th Act at 15% likely too compressed for "final confrontation + treasure discovery" - recommend 20%
- Act 1 scene imbalance: Ch1 has 1 scene, Ch2 has 4 scenes (1:4 ratio)
- Ch1's single scene carries too much narrative load (5 characters + crisis + legend + decision)
- Time continuity issue: Scene doc says 3-4pm but chapter doc says 4-5pm
- Act docs for Acts 2-4 and epilogue created (2026-02-07), chapter docs still needed
- Final novel prose quality is strong - f-0-prologue.md and f-1-friends.md show good execution
- Character voice differentiation excellent in novel files
- Prologue effectively establishes villain threat without excessive violence

## File Organization Notes
- Three output locations exist: /novel/, /final/, /old/novel/ - needs consolidation
- old/ directory contains legacy versions (v0, v1 prologues, dated novel drafts)
- _prompt-memo.md contains human team's working notes (marked DO NOT REFERENCE)

## Key File Paths
- Rules: /Users/donghyunkim/Documents/codes/konies/CLAUDE.md
- Plot structure: /Users/donghyunkim/Documents/codes/konies/plot-structure.md
- README: /Users/donghyunkim/Documents/codes/konies/README.md
- Scene example: /Users/donghyunkim/Documents/codes/konies/01-01-01-scene.md
- Final prologue: /Users/donghyunkim/Documents/codes/konies/final/f-0-prologue.md
- Final ch1: /Users/donghyunkim/Documents/codes/konies/final/f-1-friends.md
- Detailed review: /Users/donghyunkim/Documents/codes/konies/.claude/agent-memory/content-director-kim/full-review-2026-02-06.md
