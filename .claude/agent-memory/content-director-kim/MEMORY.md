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

## Chapter Evaluation Criteria (Created 2026-02-08, v2 2026-02-08)
- Chapter evaluation criteria doc: /Users/donghyunkim/Documents/codes/konies/chapter/chapter-evaluation-criteria.md
- 5 evaluation categories matching Act structure: Structure(25), Narrative+Absorption(25), Character(20), Tone/Pacing/Reader(15), Consistency(15) = 100pts
- Key differences from Act evaluation:
  - A-2 "씬 분할의 적절성": evaluates Scene decomposition quality (new, Chapter-specific)
  - A-3 "후크 설계": Episode function absorption (start hook, end hook; mini-climax location only, effect -> B-4)
  - B-2 "정보 공개 전략": info revelation strategy (deferred from Act criteria)
  - B-3 "서브플롯 진행": Sequence function absorption (subplot objectives per chapter)
  - B-4 "미니 클라이맥스와 서사적 완결감": Episode self-containment evaluation added in v2
  - D-3 "인지 부하 관리": cognitive load for target readers (new, Chapter-specific)
  - D-5 "감각 키워드와 분위기 전환": sensory keywords per scene (deferred from Act criteria)
  - No chapter-type-specific criteria (unlike Act's B-1~B-6); chapters evaluated uniformly
- Grade system: same S/A/B/C/D; B+ required for Scene doc creation
- Balance check appendix: covers volume ratio, character distribution, tone continuity, hook chain, foreshadowing chain (5 items, v2)
- Evaluation example: 01-02-chapter.md scored C (67/100) - weakest in B-3 (no subplot goals) and D (tone/pacing details)
- Feedback file naming: `YYYYMMDD-HHMM-{막번호}-{장번호}-chapter-eval.md`
- 01-01-chapter.md expected to score similarly low: single scene overload, missing Episode/Sequence absorption elements
- **v2 changes from 4-person feedback (2026-02-08)**:
  - A-3/B-4 mini-climax dual evaluation resolved: A-3 = hooks + location only, B-4 = effect + self-containment
  - D-1/D-2 role differentiation clarified: D-1 = base tone + mood keywords, D-2 = tension/release dynamics
  - Scoring scale anchors added for A-2 (6pt) and B-1 (6pt): 4-level anchors (6/4/2/0)
  - Required sections: 10 -> 11 (added "예상 분량/비중"), section omission penalty: -1/missing, -0.5/distributed
  - D-5 minimum standard: sensory keywords mandatory for mood-transition scenes, recommended for others
  - D-6 expanded: vocabulary level appropriateness added
  - A-2: spatiotemporal unit principle added as first checkpoint
  - Balance-5 foreshadowing chain added to appendix
  - B-1/E-3 role separation clarified (narrative function vs formal data consistency)
  - Double-penalty prevention principle added
  - Prologue/epilogue exemption stated
  - plot-structure.md template relationship stated
  - C-2: villain character evaluation conditionally added
  - E-5: scene-foreshadowing mapping added
  - Evaluation example E-4 error corrected (연꽃 문양 inconsistency flagged), A-4/B-3 scores adjusted
  -補完 priority tags ([필수]/[권장]) added to evaluation output guide
  - "챕터" -> "장" unified throughout appendix
  - B-3: subplot target phrasing guide (verb+result) and absence scoring guide added
- **Feedback patterns (Chapter eval criteria)**:
  - 3/4 flagged A-3/B-4 mini-climax duplication (Hyewon, Yeonsu, Taesoo)
  - 3/4 flagged balance-5 foreshadowing missing (Taesoo, Hyewon, Yeonsu)
  - 2/4 flagged D-1/D-2 overlap (Hojin directly, Hyewon indirectly)
  - 2/4 flagged scoring scale anchors (Taesoo, Yeonsu)
  - D item scoring increase (15->20): rejected (Hyewon strongly, Hojin/Yeonsu indirectly) - will revisit after 3+ evaluations
  - B-5 scoring increase (4->5): rejected (Hyewon) - will revisit after evaluation experience
  - Hyewon's 연꽃 문양 E-4 error catch was most impactful single finding

## Chapter Evaluation Results (2026-02-08)
- **01-01-chapter.md 1st eval**: D grade (42/100) by Taesoo. A=10/25(40%), B=11/25(44%), C=10/20(50%), D=3/15(20%), E=8/15(53%)
  - D항목 20% = 항목별 최소 기준(40%) 심각 미달, 필수 보완 대상
  - Root causes: no tone/pacing section, no subplot goals, no mini-climax designation, no cognitive load management
  - Single-scene structure (01-01-01 only) confirmed as major structural concern
  - Key learning: Chapter docs written before evaluation criteria existed lack Episode/Sequence absorption features almost entirely
- **01-01-chapter.md 4-person eval (1st round)**: Taesoo(D/42), Hyewon(D/51), Yeonsu(D/53), Hojin(D/54)
  - All 4 unanimous D grade; average 50pts
  - Common issues: no tone section, no subplot goals, no mini-climax, no info disclosure strategy, no cognitive load management
  - Key insights: Act doc has rich content that Chapter doc failed to inherit; Scene doc has detailed Beat/Moment info that Chapter should bridge

## Chapter 01-01 Reinforcement (2026-02-08)
- **Rewrite completed**: ~134 lines -> ~359 lines (2.7x expansion)
- All 11 required sections now present (was missing 2+)
- **Feedback processing results** (4 evaluation files updated with "김태수 팀장 응답"):
  - Accepted items applied: tone section, subplot goals (seed-level), mini-climax (Moment 4), info disclosure strategy, cognitive load management (3+2 intro), sensory keywords, character interaction design, humor placement, tension/relaxation rhythm, foreshadowing management, reader experience design
  - **Scene split decision**: Maintained single scene (spacetime principle) with 5-moment internal structure + cognitive load management. Partially accepted from all 4 reviewers - enhanced moment-level guidance instead of splitting
  - Deferred: scene split re-evaluation after re-grading
  - Character tag behaviors added: 수진(펜 떨어뜨림), 지훈(창가 겨울이), 민준(카메라), 지영(문 쾅), 태호(확률 계산)
  - Start hook changed: vague "peaceful classroom" -> "전교생 5명뿐인 교실에서, 학생회장이 펜을 떨어뜨렸다"
  - End hook: "복도를 달리는 세 아이와 한 마리의 발소리 뒤로, 형과 누나의 날카로운 의심이 쫓아온다"
  - Subplot goals at seed level: 수진 가면벗기, 민준 현실/가상 괴리, 지영/태호 미행
  - Info dump prevention: 3-stage legend disclosure, character intro via behavior not description, economic info -> emotional translation
  - Tone ratio: 55% friendship/humor, 45% adventure/tension (matching Act doc)
- **Awaiting re-evaluation**: target B+(75+) for Scene doc creation approval

## Evaluation Criteria - Next Steps (as of 2026-02-08)
1. ~~Re-evaluate 01-act.md after reinforcement~~ DONE: A grade (83pts)
2. ~~Process 2nd round feedback for 01-act.md~~ DONE: 5 items applied, comments on all 4 feedback docs
3. Run evaluation on remaining Act docs (00-prologue, 02-act, 03-act, 04-act, 05-epilogue)
4. Run cross-evaluation after all Acts reach B+
5. ~~Create Chapter evaluation criteria~~ DONE: 2026-02-08, v1=378 lines
6. ~~Process Chapter eval criteria feedback~~ DONE: 2026-02-08, v2=421 lines, 19 changes from 4 reviewers
7. Formalize "마을 빚 50억" in setting-overview.md (separate task, triggered by Yeonsu feedback)
8. ~~Evaluate 01-01-chapter.md~~ DONE: D grade (42/100), 4-person avg 50pts
9. ~~Reinforce 01-01-chapter.md~~ DONE: rewritten 134->359 lines, all 11 sections, feedback responses added
10. Re-evaluate 01-01-chapter.md (target B+/75+)
11. Evaluate 01-02-chapter.md (formal evaluation, not just criteria example)
12. Reinforce 01-02-chapter.md to B+ for Scene doc creation
11. Create Chapter docs for Acts 2-4 (02-03, 02-04, 03-05, 03-06, 04-07, 04-08)
12. D항목 배점 재조정: Chapter 평가 3회 이상 실시 후 재검토 (Hyewon/Hojin 요청, 현재 거절). 1st evaluation (01-01) shows D항목 IS the weakest area - this strengthens the case for eventual rebalancing
13. Add CLAUDE.md "서브플롯" term definition (Yeonsu request, separate task)

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
