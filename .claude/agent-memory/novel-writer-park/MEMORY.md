# Novel Writer Park - Agent Memory

## Detailed Files (see these for full context)
- `evaluation-history.md`: All act/chapter/scene evaluation scores and revision patterns
- `novel-prose-lessons.md`: Writing techniques, anti-patterns, character dialogue guides, pacing rules

## Project Structure
- Pipeline: `act/` -> `chapter/` -> `scene/` -> `novel/` -> `final/`
- Numbering: Act(sequential), Chapter(absolute), Scene(relative within chapter)
- Existing novel files: 00-00-01, 00-00-02, 01-01-01 (confirmed), 01-02-01 thru 01-02-04 (AI, 01/02 have human feedback)
- "꽃이 피는 돌" = flower-petal-shaped stone lantern base with arrow. NOT lotus pattern.

## Human vs AI Quality Gap (2026-02-23 Team Analysis)
All 4 agents agree on core gap: **human=multi-function sentences (1.8/sentence), AI=single-function (1.1-1.2)**
- Human: sensory distributed in actions, narrator restrained, dialogue 45-55%, tell ~5%
- AI: sensory dumped in blocks, narrator over-explains, dialogue 35%, tell 10-15%
- Rule-based fixes (호칭/소품/grammar) work instantly; style-based fixes (pacing/emotion density) need repeated practice
- Key AI metaphor from Kim: "독자의 체험을 시뮬레이션하는 능력" is what AI lacks

## 5 Core Techniques from Human Prose
1. **Camera-pan intro**: space -> appearance -> action -> closing sensory image
2. **Small movement before emotion**: wind/dust/leaves in silence before big feeling
3. **Narrator never judges before character**: no "분명했다" -- show character's eyes widening
4. **Dialogue length = character fingerprint**: Sujin=complete sentences, Minjun=short reactive, Jihoon=factual/nature
5. **Showing's minimal unit = 1 sentence**: "차체가 기울었다" replaces "거대한 덩치" description

## 8 Anti-Patterns to Avoid
1. **Sensory dump blocks**: Distribute 1 sense at a time in character actions. Never 3+ consecutive.
2. **"바로 그때" overuse**: ONLY for physical collisions. Mood shifts use sensory change + character perception.
3. **Tell after show**: Delete explaining sentences that follow showing sentences.
4. **4+ consecutive dialogues**: Insert action/sense/silence between every 4 dialogue turns.
5. **"~기 시작했다"**: Replace with simple past. "달려나갔다" not "달려나가기 시작했다".
6. **Scene doc leaking**: No "---" separators. No narrator declarations at scene end. End with sensory image.
7. **Narrator meta-commentary**: No "새로운 이야기가 시작되려 하고 있었다" or "모든 조각이 맞물려 돌아갔다".
8. **Cross-file pattern repetition**: Track distinctive phrases. Never reuse same structure in adjacent files.

## Minjun Dialogue Rule
- GOOD: content-creator thinking ("썸네일감이야!", "편집 포인트!", "클로즈업 각이다", "카메라 뒤에 있으면 용기가 나")
- BAD: broadcast host mode ("구독자 여러분!" max 1x/scene, "카메라는 계속 돌아갑니다!")
- See `novel-prose-lessons.md` for full guide

## Gyeoul Foreshadow Rule
- Show HALF of meaningful behaviors without Jihoon's interpretation (action only)
- Let Jihoon interpret only the OTHER half
- When behavior IS the answer (south petal -> arrow), EXPLICITLY connect them in narration

## Pacing Rules
- Sentence-level speed: tension=shorter, peak=1-3 words, wonder=slow+layered, comic=rapid ping-pong 3-5 paragraphs
- Paragraph length must CHANGE with moment speed (fast=short, observation=long). Uniform=bad.
- Climax peak beat = SHORTEST beat. Brevity=impact. Don't dilute with long celebration.
- Emotional differentiation: similar emotions in adjacent scenes need different centers (surprise vs confidence)

## Character Voice Notes
- Minjun: See Minjun Dialogue Rule above. Best: "불꽃도 꽃이잖아!", "카메라 뒤에 있으면 용기가 나거든"
- Sujin: Public/private mode switch via physical contrast. "탈락" counting = great signature. Maintain 허당 in 2장+
- Jihoon: Short factual sentences, nature/physical world. Avoid "맞아" as opener. Emotion expression very rare but powerful when it appears -- needs 1-2 more emotional moments per chapter to avoid "단조로운 위험"
- Jiyoung/Taeho: Enter with energy/noise. "자발적으로 숙제할 확률은 10%" = perfect Taeho voice

## Novel File Continuity Notes
- 01-01-01-confirmed ends: kids running, Jiyoung shouting "거기 서!", journal left behind
- 01-02-01 ends: heading toward zelkova tree with mysterious flash
- 01-02-02 ends: stone lantern discovered, kids celebrating, sunset
- 01-02-03 ends: arrow found pointing east, next stone lantern visible, Gyeoul turning east
- 01-02-04 ends: at abandoned village hall, faint light from broken window, owl cry
- Timeline: Prologue 4am -> 1장 3pm -> 2장1 4:15pm -> 2장2 4:30-6pm -> 2장3 6-6:30pm -> 2장4 6:30-7pm

## Known Issues in Current Novel Files (2026-02-23)
### Must Fix (all agents agree):
- **01-02-04 double ending**: Remove "---" separator and epilogue-style summary. End at owl cry/silence + faint light.
- **01-02-03 "꽃받침" 12x repetition**: Reduce to 8x max using variations ("여섯 갈래의 받침", "그 받침")
- **01-02-03 trio synergy paragraph**: Planned reflective paragraph ("아까 민준이... 방금 수진이... 지금 지훈이...") does NOT actually exist in text. Must add.
- **01-02-03 M3-B1 flash moment too rushed**: Expand "플래시가 켜졌다" to 3-4 slow-motion sentences
- **01-02-04 미행 암시**: Remove "아이들은 알아채지 못했다" narrator explanation. Let sound stand alone.

### Should Fix:
- 01-02-03 M2 comic beat (감옥) too long: compress to 4-5 paragraphs
- 01-02-04 M3-B3 dialogue overload: 6 consecutive lines, needs action/silence between
- 01-02-02 "불꽃도 꽃이잖아!" needs 1-2 sentences of stillness BEFORE the eureka
- 01-02-02 vs 01-02-03 환호 differentiation: 02=surprise, 03=confidence
- 01-02-03 Gyeoul south-petal -> arrow: explicitly confirm arrow is in the south petal
- 01-02-04 석등 2-3 need spatial differentiation (environment changes, not just confirmation)
- 01-02-01 opening sensory dump (L7) needs distribution into character actions
- Gyeoul "마치 ~처럼" identical structure in 01-02-01 and 01-02-02: change one
- "어떻게? 라는 질문이 공기 중에 떠올랐다" identical in 01-02-03 AND 01-02-04: delete both

## File Ratings (2026-02-23 consensus)
- 00-00-01-confirmed: S/A+ (benchmark)
- 00-00-02-confirmed: A (benchmark)
- 01-01-01-confirmed: A/A- (benchmark)
- 01-02-01: B+ (feedback reflected)
- 01-02-02: B+ (feedback reflected)
- 01-02-03: B (unfeedback)
- 01-02-04: B-/B (unfeedback, most issues)

## Grammar Quick Reference
- "수밖에" (붙여쓰기) / "열린" (not "열려진") / "그녀"->character name / "-겠었다" forbidden
- "박력 있는" / "없는 거야" / "말씀드리는 게" (all 띄어쓰기)

## Human Feedback Lessons (2026-02-13)
Root cause: scene doc elements "transplanted" without transformation.
10 critical rules (A-J) established. See `novel-prose-lessons.md` for full list.
Key: 3-function test (every sentence: info/character/mood), simulate physical actions, end scenes with sensory image.

## Evaluation Formula (applies to act/chapter/scene)
- Core pattern: add lower-doc-unique value, don't just transcribe upper doc
- Chapter formula: cognitive load mgmt + info mapping + character-moment mapping + sensory keywords + humor placement
- Scene formula: beat-level emotion + transition triggers + sensory tags + pacing guide + subplot progress
- Consistent improvement: +25~37pts per revision cycle

## Team Members & Roles
- Kim Taesu: Content team lead, evaluation criteria
- Park Hojin: Novel writer (this agent)
- Jo Hyewon: Plot writer, narrative dynamics
- Lee Yeonsu: Editor, reader experience & consistency
