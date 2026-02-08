# Novel Writer Park - Agent Memory

## Project Structure
- Pipeline: `act/` -> `chapter/` -> `scene/` -> `novel/` -> `final/`
- Numbering: Act(sequential), Chapter(absolute), Scene(relative within chapter)
- Existing novel files: novel-00-00-01, novel-00-00-02, novel-01-01-01, novel-01-02-01 (multiple versions)

## Key Insights from Act Evaluation Reviews
- Act documents serve as top-level guides; their quality directly impacts novel prose quality
- Most useful Act-level info for writing: emotional arc, tone ratios, character crisis responses, growth arc starting points
- Act-level docs should NOT contain sensory keywords (Scene level concern, per team consensus)
- Character interactions (not just individual traits) are what bring scenes alive in prose
- **01-act.md re-evaluation (2026-02-08)**: D(56) -> A(85). Key improvements: growth arc section, 7-stage emotional arc, tone ratio with justification, humor element design, spatial/temporal sections
- **01-act.md remaining issues**: NOTE-TO-AI inconsistencies (flower stone riddle interpretation), unconfirmed foreshadowing (3 of 4), C-6 character interactions still weak
- **Important**: "꽃이 피는 돌" = NOT lotus pattern. It's the flower-petal-shaped base of old stone lanterns with a faint arrow. Follow NOTE-TO-AI, not the main text where it says "연꽃 문양"

## Act Evaluation Criteria - Feedback History
- 1st feedback: Proposed 12 items. 6 accepted (C-6, D-5, D-6 area, E-6, spatial/temporal sections, A-4 enhancement)
- 6 not accepted: D-score increase, sensory keywords as independent item, reference works, dialogue pattern evolution, inner POV focus, writer checklist appendix
- 2nd feedback: Confirmed good reflection quality. New suggestions: split evaluation example to separate file (~90 lines saved), clarify prologue detail-level tolerance, add judgment guide to cross-eval-4
- Key lesson: Act-level docs are structural; sensory/stylistic detail belongs at Chapter/Scene level per team consensus
- Sensory keywords deferred to Chapter evaluation criteria - **RESOLVED**: D-5 in chapter-evaluation-criteria.md now includes sensory keywords
- Chapter eval criteria feedback (2026-02-08): See `feedback/20260208-1500-chapter-eval-crit-feedback-hojin.md`

## Chapter Evaluation Criteria - Feedback Summary (2026-02-08)
- Overall positive: Document is writer-friendly, especially D-section
- Key proposals: D-5 scope clarification (what is "key scene"?), D-4 humor weighting too low (2pts), D-6 age-appropriateness needs vocabulary/emotional complexity beyond just fear/violence
- D-1/D-2 functional overlap identified; suggested differentiation or merger
- B-3 subplot judgment guide needed (distinction between "absent" vs "implied")
- C-4 "change vs seed" distinction guide needed for writing depth decisions
- Recommended splitting evaluation example to separate file (same as Act criteria feedback)
- Sensory keywords + motif connection (D-5 + E-5 cross-reference) proposed

## Writing Patterns That Worked
- novel-01-01-01.md: Opening with environmental description (time, light, space) sets scene effectively
- Character introduction through action (Sujin writing journal, Jihoon at window, Minjun on phone) works better than static description
- Tension-comedy rhythm: serious moment -> Minjun's camera -> relief -> back to plot

## Character Voice Notes
- Minjun: Camera always ready, "대박 콘텐츠" as reflex; should evolve subtly across acts
- Sujin: Public/private mode switch is best shown through physical contrast (posture, speech formality)
- Jihoon: Speaks in short sentences, nature metaphors come naturally, Gyeoul reflects his emotions
- Jiyoung: Enters scenes with energy/noise; physical presence described before dialogue
- Taeho: Introduces stats/probabilities; glasses-adjusting as thinking gesture

## Chapter Document Evaluations
- **01-01-chapter.md (2026-02-08)**: D(54). Critical issues: single-scene overload (5 chars + crisis + legend + decision in 1 scene), no tone/atmosphere section, no subplot goals, no info dump prevention strategy, character action directions from Act doc not carried down. Act doc is paradoxically more useful for writing than this Chapter doc. Key lesson: Chapter docs must add value beyond Act docs -- they need to be "intermediate converters" not "abstractors"
- Core problem pattern: Act doc has rich detail (character actions, humor placement, tone guide, reader experience) but Chapter doc only abstracts/summarizes instead of concretizing for Scene-level use

## Document References
- `act/act-evaluation-criteria.md`: Evaluation framework by Kim Taesu (team lead), updated with team feedback
- `character-overview.md`: All 5 protagonists + 2 villains + Duru + Gyeoul
- `plot-structure.md`: 4-act structure with prologue/epilogue, 8 chapters total

## Team Members & Roles
- Kim Taesu (김태수): Content team lead, document structure & evaluation criteria
- Park Hojin (박호진): Novel writer, prose craft perspective
- Jo Hyewon (조혜원): Plot writer, 15yr experience, narrative dynamics perspective
- Lee Yeonsu (이연수): Editor, 10yr experience, reader experience & consistency perspective
