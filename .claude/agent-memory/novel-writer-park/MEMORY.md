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
- **01-01-chapter.md 1st eval (2026-02-08)**: D(54). Critical issues: single-scene overload, no tone section, no subplot goals, no info dump prevention, character actions not carried down from Act. Key lesson: Chapter docs must be "intermediate converters" not "abstractors"
- **01-01-chapter.md 2nd eval (2026-02-08)**: D(54) -> A(88), +34pts. All 13 feedback items (6 mandatory + 7 recommended) reflected. Key improvements: 5-moment internal structure, cognitive load management strategy, info disclosure mapping table, character-specific dialogue/action directions with moment mapping, tension/relaxation rhythm with transition triggers, sensory keywords per moment, subplot goals in verb+result form. Chapter now provides unique value beyond Act doc.
- Remaining minor issues: subplot table missing Jihoon/Taeho seeds, moment 3->4 transition coincidence, tactile senses underrepresented, terminology handling not systematized
- **Key pattern**: Effective Chapter revision strategy = add Chapter-unique value (cognitive load mgmt, info mapping, character-moment mapping) rather than just expanding Act content
- **01-02-chapter.md 1st eval (2026-02-08)**: D(50). Critical issues: "연꽃 문양" setting error (must be "꽃받침 형태의 받침"), no subplot goals section, no character arc progression, no character interaction design, no tension/relaxation rhythm, no sensory keywords, no humor placement plan, time frame mismatch with Act (Ch ends 6pm vs Act 7pm). C(8/20) and D(6/15) at 40% minimum threshold.
- **01-02-chapter.md 2nd eval (2026-02-09)**: D(50) -> A(87), +37pts. All 3 critical issues resolved: (1) "연꽃 문양" -> "꽃받침 형태 받침" corrected throughout, (2) Full character sections with dialogue/action directions, interaction design, arc progression, (3) Complete reader experience design (tension/relaxation rhythm, humor placement, sensory keywords, cognitive load mgmt). Quality gap with 01-01-confirmed essentially eliminated.
- Remaining minor issues: Scene 2 internal pacing guide, sensory transition strategy between scenes, taste sense absent, 탈옥범 복선 유지 방안 needs concrete device
- **Key pattern confirmed**: Same revision strategy as 01-01 works for 01-02. Core formula = Chapter-unique value (character-moment mapping + sensory keywords + humor placement + cognitive load mgmt + info disclosure mapping). Both chapters went from D to A with +34~37pt improvement.
- **Key lesson repeated**: Chapter docs that only list role keywords without scene-specific actions/dialogue directions are useless for prose writing. The confirmed 01-01 should be the template for all future Chapter docs.

## Document References
- `act/act-evaluation-criteria.md`: Evaluation framework by Kim Taesu (team lead), updated with team feedback
- `character-overview.md`: All 5 protagonists + 2 villains + Duru + Gyeoul
- `plot-structure.md`: 4-act structure with prologue/epilogue, 8 chapters total

## Team Members & Roles
- Kim Taesu (김태수): Content team lead, document structure & evaluation criteria
- Park Hojin (박호진): Novel writer, prose craft perspective
- Jo Hyewon (조혜원): Plot writer, 15yr experience, narrative dynamics perspective
- Lee Yeonsu (이연수): Editor, 10yr experience, reader experience & consistency perspective
