# Human Feedback Analysis - Editing Checklist

## Source
- Date: 2026-02-13
- File: novel-01-02-01.md
- Feedback count: 20 NOTE-TO-AI items from human team
- Full analysis: `feedback/20260213-0008-novel-01-02-01-human-feedback-yeonsu.md`

## Editing Checklist (A~G Categories)

### A. Format/Consistency
- A-1: Dialogue+action layout consistency (short action=same line, 2+ sentences=separate para)
- A-2: Single character's continuous action+dialogue grouped in same paragraph
- A-3: Paragraph split/merge matches content flow

### B. Setting Consistency
- B-1: Character honorifics match speaker/listener gender+age (형/누나 vs 오빠/언니)
- B-2: Physical descriptions age-appropriate (no "넓은 손바닥" for 13-14yo)
- B-3: Village environment (rural, small-scale) doesn't contradict details (학원, 편의점)
- B-4: Scene doc errors not propagated into novel
- B-5: Time/distance/physical conditions match descriptions

### C. Physical Plausibility
- C-1: Character movement directions consistent within space (camera hiding direction)
- C-2: Props physically operable as described
- C-3: Sensory descriptions (smell, sound) within realistic reach

### D. Sentence Structure/Naturalness
- D-1: Cause-effect sentence order correct
- D-2: No awkward endings (~겠었다 pattern)
- D-3: Parallel particle structures don't create reading friction
- D-4: Narrator uses character's vocabulary system when describing their inner state

### E. Dialogue Quality
- E-1: Each line matches character's established speech pattern
- E-2: Dialogue not abrupt without transition
- E-3: No "deadweight" lines (would character actually say this here?)
- E-4: Vocabulary appropriate for character age/environment

### F. Narrative Structure/Pacing
- F-1: "Start/departure" declarations not repeated (max 1x)
- F-2: Stop-and-go pattern (depart->stop->depart again) not repeated 3+ times
- F-3: Scene ending not overwritten by narrator summary (tell) after image/action conclusion
- F-4: Sensory tags not literally translated into dialogue-breaking positions

### G. Reader Experience
- G-1: Ambiguous expressions discussed by characters to prevent reader confusion
- G-2: Dialogue motivation sufficiently set up in preceding narration

## Key Anti-Patterns Found
1. "모르겠었다" -> "알 수 없었다"
2. "완벽한 학생회장" direct tell -> delete (show already sufficient)
3. Camera lens sparkle during dialogue -> sensory tag literal translation, delete
4. "카메라 뒤로 숨기" -> physically impossible direction
5. "시작" 3x in one scene -> max 1x, last sentence only
6. Result->cause sentence order -> cause->result
7. "머리도 안 감았는데" at school -> context mismatch (just left classroom, not home)
8. "학원" in 5-student rural village -> setting contradiction

## Scene Doc Error Propagation Cases
- 01-02-01-scene-confirmed.md line 35: "형과 누나" (should be 오빠와 언니 for 수진's POV)
- 01-02-01-scene-confirmed.md line 87: 삼각대 (modern 10s use gimbal)
- 01-02-01-scene-confirmed.md line 101: "카메라 뒤로 숨기" (wrong direction)
- 01-02-01-scene-confirmed.md line 154: "학원" (impossible in rural setting)

## Recommended Process Change
- Add "2-b pass" to editing: physical plausibility + setting consistency check
- Separate from existing "2-a pass" (sentence rhythm, tell/show, character voice)
