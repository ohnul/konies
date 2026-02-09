# Novel Writer Park - Agent Memory

## Project Structure
- Pipeline: `act/` -> `chapter/` -> `scene/` -> `novel/` -> `final/`
- Numbering: Act(sequential), Chapter(absolute), Scene(relative within chapter)
- Existing novel files: novel-00-00-01, novel-00-00-02, novel-01-01-01 (confirmed), novel-01-02-01 (revised 2026-02-09)

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
- **novel-01-02-01 revision (2026-02-09)**: Scene doc transition triggers are critical for prose structure:
  - M1->M2: Physical sound (삼각대 찰칵) breaks intellectual mood into comic mood
  - M2->M3: Sensory change (wind direction + evening cooking smells + shadow growth) signals time passage
- **Pacing by moment type**: M1(추리)=description between dialogue lines, M2(코믹)=rapid ping-pong minimal description, M3(출발)=gradual acceleration with walking rhythm
- **Sokkup-chingu dynamic**: Sujin-Jihoon friendship shown through Sujin taking Jihoon's unconventional nature ideas seriously. Subtler than direct mention.

## Character Voice Notes
- Minjun: Camera always ready, "대박 콘텐츠" as reflex; should evolve subtly across acts. "썸네일이 안 되잖아!" is peak Minjun voice.
- Sujin: Public/private mode switch best shown through physical contrast. Camera triggers private mode most effectively. Leader mode = direction + action verb sentences.
- Jihoon: Short sentences, nature metaphors, Gyeoul reflects his emotions. **Avoid "맞아" as opening word** -- replace with sensory/literal observations ("돌은 만져봐야 하니까", "마을 한가운데라면 가장 오래된 것들이 있을 거야")
- Jiyoung: Enters scenes with energy/noise; physical presence described before dialogue
- Taeho: Introduces stats/probabilities; glasses-adjusting as thinking gesture

## Novel File Continuity Notes
- novel-01-01-01-confirmed ends: three kids running across schoolyard, Jiyoung shouting "거기 서!", Sujin's journal left behind
- novel-01-02-01 starts: running, Jiyoung's voice fading, kids stop at schoolyard middle
- novel-01-02-01 ends: kids pass school gate, see Jiyoung/Taeho silhouettes in 2F window, heading toward village zelkova tree with mysterious flash
- Time gap between 01-01-01 and 01-02-01: ~15min (school exit to schoolyard middle)
- Next scene (01-02-02) should start at village, near zelkova tree, ~4:30pm

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

## Scene Evaluation Criteria - Feedback Summary (2026-02-09)
- Feedback file: `feedback/20260209-1700-scene-eval-crit-feedback-hojin.md`
- Overall positive: "집필 설계도" identity well-established, pipeline awareness strong
- **Top priority**: D-3 sensory description level adjustment. "묘사 문장 수준" for ALL beats is too prescriptive; propose: start/end situations = sentence-level, transition points = direction + 1 concrete image, general beats = keyword + sense type only. Key argument: prevents Scene doc from becoming novel draft, preserves writer's creative freedom
- **D-6 pacing guide**: Moment-level tempo design = useful. Beat-level sentence rhythm prescriptions = not useful in practice. Propose "템포와 밀도" instead of "문장 길이/호흡". Added scale anchors (2/1/0pt). Eval example gave 0pt to doc that had moment-level pacing = too harsh.
- **C-2 dialogue (6pts)**: Highest score in C-section, absolutely correct. But propose emphasizing "indirect direction" value alongside direct quotes to prevent forced filler dialogue. Also propose 5pt anchor between 4pt and 6pt gap.
- **D-4 humor (2pts)**: Still low per my view (same as Chapter feedback), but this time proposed strengthening criteria instead of raising score: add "narrative function" checkpoints
- **C-5 character movement (2pts)**: Score appropriate but needs scope guide (fixed-space scenes vs movement scenes)
- **A-2 start/end situations**: "첫 문단을 쓸 수 있는 수준" is intuitive but interpretation varies; propose clarifying 3pt anchor
- **New issues**: 11 mandatory sections = high document burden (propose streamlining 2 sections), B-2 emotion tracking format needs guide, A-2/E-2 role overlap needs differentiation, motif-sensory cross-reference (D-3/E-5) still missing (was promised from Chapter feedback), prologue application needs B-1/E-3 substitution guide

## Scene Document Evaluations
- **01-02-01-scene.md 1st eval (2026-02-09)**: D(53). Critical issues: (1) Time mismatch -- Scene says "3:30pm" but Chapter says "4:15pm~4:30pm", (2) Beat structure is "dialogue script" not "writing blueprint" -- no emotion tracking, no sensory integration in beats, no function labels, (3) Moment 2 (Minjun filming) lacks independent justification as separate moment, (4) No transition triggers between moments, (5) Sensory keywords siloed in separate section rather than integrated into beats, (6) No pacing guide, (7) No reference document section, (8) Foreshadow management lacks install/maintain/retrieve classification
- **01-02-01-scene.md 2nd eval (2026-02-09)**: D(53) -> A(85), +32pts. All 7 mandatory items reflected. Key improvements: time corrected to 4:15~4:30, beat-level emotion tracking with 10-beat emotion arc overview, moment transition triggers with sensory changes (M1->M2: 찰칵 sound, M2->M3: wind direction change + smell), [감각:] tags integrated into beats, pacing guide with moment-level tempo table + ASCII diagram, reference document section, foreshadow table with classification/status/beat-position. Subplot progress section added.
- Remaining improvements for S(90+): M1-B2/B3 emotion differentiation ("호기심" repeated), Jihoon's "맞아" agreement pattern in M1-B4/M3-B1, Sujin-Jihoon childhood friend interaction missing, "번쩍임" setting basis in ending, M1 internal relaxation beats
- **Key pattern (Scene level)**: Same lesson as Chapter level -- "don't just transcribe upper doc, create lower-doc-unique value". Scene doc must add: beat-level emotion tracking, moment transition triggers with sensory changes, pacing guide, sensory integration into beat structure. Dialogue richness alone (which this doc has) is insufficient.
- **Specific lesson**: A Scene doc with rich dialogue but no emotion/sensory/pacing integration scores D. The "대사 대본 vs 집필 설계도" distinction is critical. Scene docs need beats that combine dialogue + emotion state + sensory cue + narrative function.
- **Key pattern confirmed (Scene level)**: Same revision formula as Chapter level works at Scene level. Core formula = Scene-unique value (beat-level emotion tracking + moment transition with sensory + pacing guide + [감각:] tag integration + subplot progress + foreshadow table). D(53) -> A(85) with +32pt improvement, consistent with Chapter-level improvements (+34~37pts).
- **Writing readiness assessment**: At A(85), Scene doc is immediately usable for novel prose writing. Start/end situations enable first/last paragraph drafting without additional imagination. Dialogue examples are directly quotable. Sensory [감각:] tags in beats tell writer which senses to deploy at which moment.

## Document References
- `act/act-evaluation-criteria.md`: Evaluation framework by Kim Taesu (team lead), updated with team feedback
- `character-overview.md`: All 5 protagonists + 2 villains + Duru + Gyeoul
- `plot-structure.md`: 4-act structure with prologue/epilogue, 8 chapters total

## Team Members & Roles
- Kim Taesu (김태수): Content team lead, document structure & evaluation criteria
- Park Hojin (박호진): Novel writer, prose craft perspective
- Jo Hyewon (조혜원): Plot writer, 15yr experience, narrative dynamics perspective
- Lee Yeonsu (이연수): Editor, 10yr experience, reader experience & consistency perspective
