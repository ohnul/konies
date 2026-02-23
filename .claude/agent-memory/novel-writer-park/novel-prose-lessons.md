# Novel Prose Writing Lessons

Compiled from team feedback analysis (2026-02-23) on 7 novel files + human feedback (2026-02-13).

## Human vs AI Core Gap (Team Consensus)

All four agents independently identified the same core issue: **human prose achieves multi-function sentences while AI prose uses single-function sentences**.

| Metric | Human Confirmed | AI + Feedback | AI Unfeedback |
|--------|----------------|---------------|---------------|
| Functions per sentence | 1.8 avg | 1.2 avg | 1.1 avg |
| Show-don't-tell ratio | 90% | 75% | 70% |
| Sensory dump frequency | 0 | Reduced | Frequent |
| Narrator commentary | Near zero | Occasional | Frequent |
| Dialogue ratio | 45-55% | 40-45% | 35% |

## Five Techniques from Human Confirmed Prose

### T1: Camera-Pan Character Introduction
Order: spatial position -> appearance -> action -> closing sensory image.
Each character intro ends with a sensory image ("펜 소리의 리듬", "꼬리 끝만 흔들었다").
Never introduce two characters the same way.

### T2: Small Object Movement Before Emotional Shift
Before a big emotion, show wind/dust/leaves/poster fluttering in silence.
This builds energy in stillness, making the contrast explosive.
Example: Before Jihoon's "아직 포기하기엔 일러" -- wind, poster, "우리 마을 사랑하기" text.

### T3: Narrator Never Judges Before Character Discovers
WRONG: "사람이 일부러 깎아서 만든 것이 분명했다" (narrator verdict)
RIGHT: Show character's eyes widening, then character speaks the discovery.
The narrator must not steal the character's moment of realization.

### T4: Dialogue Length/Type as Character Fingerprint
- Sujin: mid-length complete sentences, repeated key words for emotional weight ("진짜래. 진짜 확정이래")
- Minjun: short reactive questions and exclamations ("마지막이라니?", "무슨 말이야?")
- Jihoon: short factual observations, always about nature/physical world ("숲도 물에 잠기겠네")
This pattern must be CONSISTENT across all files.

### T5: Showing's Minimum Unit = One Sentence
"차체가 미세하게 기울었다" = the reader understands "거구" without being told.
One physical consequence > three sentences of description.

## AI Prose Anti-Patterns (Must Avoid)

### AP1: Sensory Dump Blocks
Scene doc [감각:] tags get transplanted as multi-sentence blocks at transitions.
FIX: Distribute 1 sense at a time within character actions. Never 3+ consecutive sensory sentences.

### AP2: "바로 그때" Overuse
Human: 4 total in 3 files, ONLY for physical collisions (door slam, alarm).
AI: 11 total in 4 files, also used for mood shifts and ideas.
RULE: "바로 그때"/"그때" ONLY for sudden physical events. Mood transitions use sensory change attached to character perception.

### AP3: Narrator Tell After Show
Pattern: good showing sentence -> unnecessary explaining sentence.
"겨울이가 낑낑거리며 비볐다. 개도 주인의 슬픔을 느끼는 것 같았다."
Second sentence is tell -- delete it. The showing already did the work.

### AP4: Consecutive Dialogues Without Physical Breaks
Max 4 dialogues in a row. After 4, insert action/sense/silence 1-2 sentences.
Human prose ALWAYS has physical behavior between dialogues:
"눈가가 촉촉해졌다" / "고개를 숙였다" / "창밖의 산을 바라보며"

### AP5: "~기 시작했다" Pattern
Replace with simple past: "달려나가기 시작했다" -> "달려나갔다"
Exception: when the "beginning" aspect is genuinely important.

### AP6: Scene Doc End-Situation Leaking Into Prose
"---" separator + summary paragraph at scene end = scene doc structure leaking.
Novel prose must end with a single flowing narrative. Never use "---" within a scene.
End with sensory image, not narrator declaration.

### AP7: Narrator Meta-Commentary
"새로운 이야기가 시작되려 하고 있었다" = narrator speaking to reader, not narrating story.
"모든 조각이 맞물려 돌아갔다" = tell. Show the characters' reactions instead.

### AP8: Cross-File Pattern Repetition
- Gyeoul "마치 ~라고 말하는 것처럼" appears in 01-02-01 AND 01-02-02
- "어떻게? 라는 질문이 공기 중에 떠올랐다" appears identically in 01-02-03 AND 01-02-04
- Evening landscape descriptions (smoke, lights, sky) repeat across 02/03/04
RULE: Track distinctive phrases. Never reuse the same structure across adjacent files.

## Minjun Dialogue Quality Guide

### Good Minjun (content-CREATOR thinking):
- "썸네일이 안 되잖아!" (content value calculation)
- "이 장면 편집 안 해도 되겠다!" (production thinking)
- "불꽃도 꽃이잖아!" (wordplay habit solving real problems)
- "카메라 뒤에 있으면 용기가 나거든" (camera as defense mechanism)
- "클로즈업 각이다" (filming technique language)

### Bad Minjun (broadcast host persona):
- "구독자 여러분!" (generic opening -- max 1x per scene)
- "카메라는 계속 돌아갑니다!" (broadcast narration)
- "이거 대박인데!" (no specific reason)
- "잠깐, 이거 찍어야 해!" (no narrative function)

## Gyeoul Foreshadow Rule
Show half of Gyeoul's meaningful behaviors WITHOUT Jihoon's interpretation.
Only let Jihoon interpret the other half.
When Gyeoul's behavior IS the answer (e.g., south petal -> arrow location), EXPLICITLY connect them: "겨울이가 맡았던 바로 그 갈래에 화살표가 있었다."

## Pacing Rules

### Sentence-Level Speed Control
Human writers vary sentence density WITHIN scenes. AI maintains uniform density.
- Tension rising: sentences get shorter, description drops, dialogue only
- Emotional peak: 1-3 word sentences ("이거다!")
- Wonder/awe: slow descriptive sentences, sensory layering
- Comic beats: rapid ping-pong, 3-5 paragraphs max

### Paragraph Length Must Match Moment Speed
- M1 (fast pursuit): short paragraphs (1-3 sentences)
- M2 (slowing approach): paragraphs lengthen (3-5 sentences)
- M3 (observation/tension): longest paragraphs (4-7 sentences)
Uniform paragraph length = uniform speed = no reader engagement

### Climax Peak Compression
The emotional peak beat (B3) should be the SHORTEST in the climax moment.
Brevity = impact. Long celebrations dilute the punch.
B4 (bridge/transition) should handle aftermath and setup, not B3.

## Emotional Differentiation Rule
When two scenes have similar emotions (e.g., two "찾았다!" moments):
- First discovery = SURPRISE center ("놀라움")
- Second discovery = CONFIDENCE center ("확신")
Same word, different emotional quality. Describe surrounding physical reactions differently.

## "3-Function Test" (from human feedback 2026-02-13)
Every sentence must serve at least ONE of: info delivery, character reveal, mood shift.
Sentences that fail all three = delete candidates.
Human prose averages 1.8 functions per sentence. Target: minimum 1.5.

## Grammar/Style Quick Reference
- "수밖에" (붙여쓰기, not "수 밖에")
- "열린" (not "열려진" -- 이중 피동)
- "그녀" -> use character name (아동문학 convention)
- "-겠었다" -> "알 수 없었다"
- "스스로" is correct per CLAUDE.md (known false positive)
- "박력 있는" (띄어쓰기)
- "없는 거야" (띄어쓰기)
- "말씀드리는 게" (띄어쓰기)

## Rule-Based vs Style-Based Corrections
Kim's key insight: Rule-based corrections (호칭, 소품, grammar) apply immediately.
Style-based corrections (대사 변주, 종료 방식, pacing, emotion density) need repeated practice.
Implication: Encode style insights as CONCRETE RULES with examples, not abstract principles.
