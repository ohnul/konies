# Novel Writer Park - Agent Memory

## Project Structure
- Pipeline: `act/` -> `chapter/` -> `scene/` -> `novel/` -> `final/`
- Numbering: Act(sequential), Chapter(absolute), Scene(relative within chapter)
- Existing novel files: novel-00-00-01, novel-00-00-02, novel-01-01-01 (confirmed), novel-01-02-01 (revised 2026-02-09), novel-01-02-02 (new 2026-02-09), novel-01-02-03 (new 2026-02-09)

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
- **novel-01-02-02 (2026-02-09)**: Exploration scene pacing = location episodes need distinct mini-arcs (each with arrival, investigation, disappointment). Avoid making them feel like a checklist by giving each location a unique sensory/comic moment.
  - Zelkova tree: elder interaction + Sujin's acting skill (comic)
  - Well: Minjun's ghost fear + Gyeoul's surprise entrance (jump scare comic)
  - Pavilion: Gyeoul's mysterious sniffing (foreshadow) + failing morale
  - Shrine: sacred atmosphere + escalating frustration
  - Central square: fatigue -> intellectual breakthrough -> physical discovery
- **"불꽃도 꽃이잖아!" moment**: Best achieved by building up fatigue/despair BEFORE the eureka. Minjun's physical action (벌떡 일어남, bench shaking) makes the moment visceral. Short sentences + exclamations = rapid tempo shift.
- **Scene doc vs Chapter doc inconsistency handling**: Scene 01-02-02 says "연꽃 문양" but Chapter confirmed doc says "꽃받침 형태 받침". Always follow Chapter confirmed + NOTE-TO-AI over unrevised Scene docs. In prose, described as "꽃받침" shape, not "연꽃 문양".
- **novel-01-02-03 (2026-02-09)**: Mini-climax peak scene. Key writing techniques:
  - **Trio synergy as prose structure**: The three contributions (Minjun's "불꽃" idea from 01-02-02, Sujin's flashlight solution, Jihoon's arrow discovery) must be explicitly connected in narration. Used a reflective paragraph ("아까 벤치에서 민준이... 방금 수진이... 그리고 지금 지훈이...") to make the synergy pattern visible to readers.
  - **Climax pacing**: M3 builds slowly (B1 wonder at light -> B2 Jihoon's focused discovery -> B3 emotional explosion -> B4 quiet bridge). The key is holding B1's wonder long enough before B2's tension. Don't rush to the discovery.
  - **Comedy placement**: All humor (Minjun-Gyeoul collision, "감옥" overreaction) concentrated in M1-M2 so M3's emotional payoff stays pure.
  - **Sensory layering at discovery**: Flash light creating "flower blooming from stone" effect is the visual climax. Described light passing through hwasaseok and seeping through flower-petal gaps. This is the moment "꽃이 피는 돌" transforms from riddle to lived experience.
  - **Gyeoul's south-facing behavior as planted payoff**: M1-B2 establishes Gyeoul fixating on the south petal -> M3-B2 this pays off when Jihoon finds the arrow there. Not supernatural, just animal behavior responding to owner's interest direction.
  - **Structural marker avoidance**: Caught and fixed "이전 씬에서" -> "아까 벤치에서" -- novel prose must never reference structural units. Replace with temporal/spatial references the characters would naturally use.

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
- novel-01-02-02 starts: arriving at village center, zelkova tree exploration
- novel-01-02-02 ends: stone lantern discovered at central square, kids celebrating, sunset, leads to next scene (detailed stone lantern observation)
- novel-01-02-02 route: zelkova tree -> well -> pavilion -> shrine -> central square bench (rest) -> stone lantern
- Time in novel-01-02-02: ~5:30pm to ~6:30pm (per scene doc)
- novel-01-02-03 starts: Sujin touching stone lantern base, close observation of flower-petal base
- novel-01-02-03 ends: arrow found pointing east, another stone lantern visible in distance, Sujin says "가자. 저 석등에도 분명 화살표가 있을 거야", Gyeoul already turning east
- novel-01-02-03 route: stone lantern close observation -> flashlight idea -> discovery of arrow in moss
- Time in novel-01-02-03: ~6:00pm to ~6:30pm (sunset deepening to red)
- Next scene (01-02-04) should start heading east toward the next stone lantern, dusk/darkness setting in

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
- **01-02-02-scene.md 1st eval (2026-02-10)**: C(61). Same structural issues as 01-02-01 pre-revision. Critical issues: (1) Time mismatch -- Scene says "5:30pm~6:30pm" but Chapter says "4:30pm~6:00pm" (1hr gap from previous scene), (2) Zero beat-level emotion keywords (all 11 beats), (3) No transition triggers between moments (M1->M2, M2->M3), (4) No [감각:] tags in beats (sensory keywords siloed), (5) No pacing guide (3-line description only), (6) No beat function labels, (7) No reference document section, (8) "연꽃 문양" setting conflict with Chapter confirmed ("꽃받침 형태"). Strengths: rich dialogue quality, good foreshadow management, adequate character voice differentiation.
  - Key difference from 01-02-01 eval: This is a 40%-weight scene (vs 15% for 01-02-01), so the M1 monotony problem (4 exploration beats with no emotion differentiation) is more impactful. Chapter doc designed specific character humor for each location (elder interaction, Gyeoul's surprise, tired complaints, Sujin's stumble) but Scene doc doesn't implement most of them.
  - **Previous scene's ending hook ("번쩍임") is completely ignored** in this scene's start -- a missed opportunity flagged as [권장] item.
  - Expected revision path: same as 01-02-01. Apply beat-level emotion tracking + transition triggers + sensory tags + pacing guide + function labels. Should reach B(73) with mandatory items, A(85+) with all items.
- **Key pattern (Scene level)**: Same lesson as Chapter level -- "don't just transcribe upper doc, create lower-doc-unique value". Scene doc must add: beat-level emotion tracking, moment transition triggers with sensory changes, pacing guide, sensory integration into beat structure. Dialogue richness alone (which this doc has) is insufficient.
- **Specific lesson**: A Scene doc with rich dialogue but no emotion/sensory/pacing integration scores D. The "대사 대본 vs 집필 설계도" distinction is critical. Scene docs need beats that combine dialogue + emotion state + sensory cue + narrative function.
- **Key pattern confirmed (Scene level)**: Same revision formula as Chapter level works at Scene level. Core formula = Scene-unique value (beat-level emotion tracking + moment transition with sensory + pacing guide + [감각:] tag integration + subplot progress + foreshadow table). D(53) -> A(85) with +32pt improvement, consistent with Chapter-level improvements (+34~37pts).
- **Writing readiness assessment**: At A(85), Scene doc is immediately usable for novel prose writing. Start/end situations enable first/last paragraph drafting without additional imagination. Dialogue examples are directly quotable. Sensory [감각:] tags in beats tell writer which senses to deploy at which moment.
- **Cross-scene continuity lesson**: When scene N's ending hook sets up a mystery/image (e.g., "번쩍임"), scene N+1 MUST acknowledge it in the start situation. Ignoring it breaks the reader's narrative thread and wastes the hook investment. This should be a standard checklist item for Scene doc review.
- **01-02-03-scene.md 1st eval (2026-02-10)**: D(47). Lowest score among Ch2 scenes so far. Critical issues: (1) "연꽃 문양" setting conflict throughout (5+ occurrences), (2) Zero beat-level emotion tracking in a mini-climax PEAK scene, (3) Zero transition triggers between moments, (4) No [감각:] tags in beats, (5) Trio synergy completion (Chapter's core design) not implemented -- Jihoon's arrow discovery role shifted to Minjun, Sujin's synthesis reduced to speculation, (6) Time mismatch (Scene says 6:30pm start, Chapter says 6:00pm~6:30pm), (7) No pacing guide, (8) No reference doc section, (9) No subplot progress, (10) No foreshadow management table.
  - **New lesson for climax scenes**: Mini-climax peak scenes require MORE emotion design precision, not less. The emotional payoff of the entire chapter depends on this scene's beat-level emotional architecture. When a Scene doc for a climax scene lacks emotion tracking, it's more damaging than the same absence in a setup scene.
  - **Character role fidelity**: When Chapter doc assigns specific discovery roles to specific characters (e.g., "Jihoon discovers the arrow"), Scene doc MUST NOT redistribute these roles. Role redistribution breaks the trio synergy design that Chapter carefully constructed.
  - **"연꽃 문양" recurring problem**: This is the THIRD document where "연꽃 문양" appears instead of "꽃받침 형태 받침" (01-02-chapter initial, 01-02-02-scene initial, now 01-02-03-scene). Suggests the Scene docs were written before Chapter confirmed revision. All remaining Scene docs should be checked for this setting conflict.
- **01-02-04-scene.md 1st eval (2026-02-09)**: D(58). Team eval scored B(75.5) -- significant disagreement. Key issues: (1) No beat-level emotion tracking (10 beats, zero emotion tags), (2) No transition triggers M1->M2, M2->M3, (3) No [감각:] tags in beats, (4) No pacing guide (1-line only), (5) M1's 4 beats are mechanical "run-find-confirm-next" repetition with no differentiation (unlike 01-02-02's distinct location episodes), (6) Chapter's critical ending hook "희미한 빛이 새어나오고 있었다" missing from beat text AND end situation, (7) Time mismatch (Scene 6:45pm vs Chapter 6:30pm, creates 15min gap from previous scene), (8) No reference doc section.
  - **No "연꽃 문양" conflict** -- positive progress. Strongest element: end situation's sensory description ("텅 빈 눈구멍처럼" metaphor).
  - **Scoring disagreement analysis**: B-2(team 4 vs writer 1), D-6(team 1 vs writer 0), E-5(team 3 vs writer 1). Core issue: team scored "inferrable from dialogue" as sufficient; writer perspective requires "explicit design" for writability.
  - **Scene-specific lesson**: Chase/pursuit scenes (연쇄 석등 추적) need even MORE pacing design than discovery scenes. The risk of "and then" mechanical repetition is highest in sequential discovery patterns. Each waypoint needs a unique mini-episode, just as 01-02-02 gave each exploration location (zelkova, well, pavilion, shrine) its own character.
  - **Act-ending scene lesson**: The final scene of an act carries the ending hook for the entire act. "희미한 빛" is not just a scene ending -- it's the 1st act's final image and 2nd act's opening question. Its absence from beat text is a structural failure, not just a detail omission.
  - Expected revision path: same core formula + M1 beat redesign + "희미한 빛" hook placement + 지영/태호 미행 미세 암시. D(58) -> A(82~87).

## Document References
- `act/act-evaluation-criteria.md`: Evaluation framework by Kim Taesu (team lead), updated with team feedback
- `character-overview.md`: All 5 protagonists + 2 villains + Duru + Gyeoul
- `plot-structure.md`: 4-act structure with prologue/epilogue, 8 chapters total

## Team Members & Roles
- Kim Taesu (김태수): Content team lead, document structure & evaluation criteria
- Park Hojin (박호진): Novel writer, prose craft perspective
- Jo Hyewon (조혜원): Plot writer, 15yr experience, narrative dynamics perspective
- Lee Yeonsu (이연수): Editor, 10yr experience, reader experience & consistency perspective
