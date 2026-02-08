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

## Evaluation Criteria (Created 2026-02-07, Updated 2026-02-07)
- Act evaluation criteria doc: /Users/donghyunkim/Documents/codes/konies/act/act-evaluation-criteria.md
- 5 evaluation categories (unchanged): Structure(25), Narrative Function(25), Character(20), Tone(15), Consistency(15) = 100pts
- Grade system: S(90+), A(80+), B(70+), C(60+), D(<60); B+ required for Chapter doc creation
- Cross-evaluation (횡단 평가) covers: tension curve, character balance, motif tracking, volume ratio, foreshadowing tracking
- **2026-02-07 v2 changes from team feedback**:
  - Added sub-criteria scoring tables for all items (A-E)
  - B items coded B-1(Prologue)~B-6(Epilogue)
  - New criteria: C-6(character interaction), D-5(expanded to pacing+rhythm+triggers), D-6(reader experience design), E-6(foreshadowing design)
  - Required sections added: spatial route summary, time frame
  - Prologue/Epilogue format exceptions explicitly stated
  - Setting conflict resolution protocol added to E-4
  - Cross-evaluation status clarified (separate phase, after all Acts reach B+)
  - Cross-5 foreshadowing tracking table added
  - [v] -> [x] standardized, subjective comment removed from sec 1
  - Example re-scored: 02-act.md 89->84 (A grade maintained, stricter with new criteria)
- Key finding during creation: "꽃이 피는 돌/석등" motif has a gap in Acts 2-4 (only appears in Act 1 and Epilogue)
- Key finding: Act 4 has 6 scenes at 15% volume - may be too dense, consistent with earlier observation about compression
- Key finding: Epilogue has 0 scenes designed - needs scene breakdown
- **2nd review (2026-02-07)**: Rated document A grade, pipeline-ready. Minor items: cross-5 foreshadowing table needs sample data, changelog entry too compressed. D-5/D-6 low point values (2-3pts) may need monitoring for discriminatory power.
- **v3 final edits (2026-02-07)**: Cross-5 foreshadowing table filled with 3 examples (민준 chocolate, 겨울이 loyalty, bronze mirror rules). Evaluation result recording location specified (feedback/ folder). Setting conflict arbiter clarified (content director decides). Cross-2 character note generalized (removed specific Act references for maintainability). Changelog entries restructured into 4 groups. Document finalized at 435 lines. All 4 reviewers rated A grade.

## Act 1 Evaluation & Reinforcement (2026-02-08)
- 01-act.md evaluated by 4 reviewers: Taesoo(C/60), Hyewon(D/54), Hojin(D/56), Yeonsu(D/57)
- Common issues: missing spatial route/time frame, missing growth arc, poor Jiyoung/Taeho roles, no tone ratio, no foreshadowing section
- Reinforcement added: 6 new sections (spatial route, time frame, growth arc, foreshadowing, humor elements, prologue connection)
- Emotional arc expanded from 4 to 7 stages; turning points from 3 to 5
- Legend narrator corrected: Sujin -> Jihoon (matching scene doc 01-01-01)
- Tone ratio set: friendship/humor 55%, adventure/tension 45% (deviation from 60/40 default justified for setup act)
- Time frame corrected: removed 30-min overlap between Ch1 and Ch2
- "전설과 현실" motif: kept as Act 1 sub-motif, linked to parent motif "욕심 없는 자만 열 수 있는 상자"
- Rejected items (consistent across feedback docs): plot-structure.md scene example mismatch (예시, not prescriptive); Act-level sensory keyword requirement (Scene-level concern); identical density requirement to Act 2 (structural role difference)

## Act 1 Re-evaluation (2026-02-08)
- Re-evaluated after reinforcement: A grade (83/100), up from C (60)
- Breakdown: A=21/25, B=22/25, C=16/20, D=12/15, E=12/15
- All items at 80%+ = well-balanced improvement
- Biggest gains: Structure(+7), Narrative Function(+5)
- Chapter doc creation now APPROVED (B+ threshold exceeded)
- Quality parity with 02-act.md (84pts) achieved

## Act 1 - 2nd Round Feedback Processing (2026-02-08)
- 4 reviewers re-evaluated: Taesoo(A/83), Hojin(A/85), Yeonsu(A/83), Hyewon(A/83)
- Team leader comments added to all 4 feedback docs
- **Accepted & applied to 01-act.md**:
  1. [E-4] "꽃이 피는 돌" body-NOTE conflict RESOLVED: "연꽃 문양" -> "불꽃이 피어나는 돌(석등)" throughout
  2. [C-6] Character interaction section ADDED: 5 key combos with narrative functions
  3. [D-6] Reader experience design ADDED: hook, anchor scene ("불꽃도 꽃이잖아!" moment), page-turner (light in abandoned hall)
  4. [E-6] Foreshadowing split into "confirmed" (탈옥범 뉴스) and "under review" (3 others) with deliberation notes
  5. [D-5] Pacing summary ADDED: "전반=대화 중심 느린 설정, 후반=행동 중심 빠른 탐색" + relaxation zones specified
- **Accepted but separate task**:
  - [E-4] "마을 빚 50억" needs to be formalized in setting-overview.md (Yeonsu's finding; already used in scene/novel/final files)
- **Rejected items**:
  - Scene-level detail requests (Scene별 비중, 지훈 대사 예시, 지훈 직설 화법 행동 설계) -> Chapter/Scene docs
  - 3-stage transition time gap annotation -> unnecessary meta-info
  - 전환점 1->2 connective tissue -> already covered by emotional arc "균열" stage
  - "왜 아이들이 직접 나서는가" explicit motivation -> Chapter doc level
  - 지영의 열정 발현 다양화 -> intentional design (growth arc: "열정이 제지로만 향하는" = starting weakness)
  - Prologue foreshadowing 1막 유지/회수 mapping -> cross-evaluation phase
  - Ch1 single scene split -> Chapter doc creation phase
  - "현실 80% + 환상 20%" ratio mention -> irrelevant for setup act (no fantasy elements yet)
- **01-act.md now at 147 lines** (up from 127), structurally more complete
- Next: evaluate remaining Acts (00-prologue, 02-act, 03-act, 04-act, 05-epilogue)

## Evaluation Criteria - Next Steps (as of 2026-02-08)
1. ~~Re-evaluate 01-act.md after reinforcement~~ DONE: A grade (83pts)
2. ~~Process 2nd round feedback for 01-act.md~~ DONE: 5 items applied, comments on all 4 feedback docs
3. Run evaluation on remaining Act docs (00-prologue, 02-act, 03-act, 04-act, 05-epilogue)
4. Run cross-evaluation after all Acts reach B+
5. Create Chapter evaluation criteria (incorporate rejected Act-level suggestions: info revelation strategy, sensory keywords, dialogue pattern evolution, cognitive load)
6. Formalize "마을 빚 50억" in setting-overview.md (separate task, triggered by Yeonsu feedback)

## Team Feedback Patterns (2026-02-07, updated 2026-02-08)
- All 3 team members flagged: foreshadowing management, reader experience/pacing, subjective comments in criteria docs
- Hyewon (plot): strongest on narrative dynamics, foreshadowing vs motif distinction, information revelation strategy; also flags 지영 character depth issues and prologue foreshadowing mapping
- Hojin (writing): strongest on practical writing needs - space/time info, sensory details, character interaction chemistry; "숲의 설계도" metaphor well captures Act doc function evolution
- Yeonsu (editing): strongest on formal consistency, cross-verification with actual docs, process/protocol gaps; uniquely found "마을 빚 50억" setting-overview gap
- Rejected pattern: all 3 suggested item F or expanded scoring - kept at 5 items to avoid document bloat
- "스스로" flagged as typo by 2 members but confirmed as correct Korean standard spelling
- 2nd round pattern: 지영's "열정" direction was flagged by Hyewon in both rounds - track this for Act 2+ reviews

## Key File Paths
- Rules: /Users/donghyunkim/Documents/codes/konies/CLAUDE.md
- Plot structure: /Users/donghyunkim/Documents/codes/konies/plot-structure.md
- README: /Users/donghyunkim/Documents/codes/konies/README.md
- Scene example: /Users/donghyunkim/Documents/codes/konies/01-01-01-scene.md
- Final prologue: /Users/donghyunkim/Documents/codes/konies/final/f-0-prologue.md
- Final ch1: /Users/donghyunkim/Documents/codes/konies/final/f-1-friends.md
- Detailed review: /Users/donghyunkim/Documents/codes/konies/.claude/agent-memory/content-director-kim/full-review-2026-02-06.md
