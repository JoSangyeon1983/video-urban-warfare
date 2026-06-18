---
title: UrbanWarfare (프로젝트)
type: project
status: draft
tags: [프로젝트, 애니메이션, UrbanWarfare, 강화복, 전투드론, 이타노서커스]
sources: []
created: 2026-06-18
updated: 2026-06-18
---

# UrbanWarfare (프로젝트)

> 근미래 밀리터리 SF AI 애니메이션. **제트 점프가 가능한 강화복 군인**이 싸우다 마지막에 **이타노 서커스로 다량의 미사일을 일제 발사**하는 클라이맥스가 핵심. 제작 흐름은 [[AI 애니메이션 제작 파이프라인]], 스타일 적용은 [[스타일 적용 규칙]]을 따름.

## 작품 개요
- 장르: 근미래 밀리터리 SF, **폐허 도시전(ruined urban warfare)** (캐릭터·드론 시트 프롬프트 근거).
- 배경: 부서진 고가도로 기둥(ruined elevated highway pillars) 사이 등 폐허 도시 (드론 시트 프롬프트 근거).
- 핵심 비주얼: 슬림 택티컬 강화복(파워드 아머) + 제트팩 점프 기동(시트 프롬프트 근거).
- 적: 대형 무장 전투 드론이 강화복 군인을 추격(드론 시트 프롬프트 근거) → §적 — 전투 드론.
- 클라이맥스(사용자 제공): 마지막에 **[[이타노 서커스]] 식 다량 미사일 일제 발사**.
- 룩: 한국/일본 애니 스타일, 셀 셰이딩, 리얼 밀리터리 SF 영향(시트 프롬프트 근거).

## 주인공 캐릭터 (정본)
- **이름/계급: LT. HAN SEOJIN (한서진 중위)** — LT = Lieutenant(위관급 장교, 통상 중위).
- 인물: 20대 후반 한국인 여성 특수 강화복 군인. 슬림·애슬레틱 체형, 긴 다리, 차분하고 날카로운 눈, 침착한 역전의 표정.
- 헤어: 짧은 다크 브라운~블랙(전투용, 헬멧 벗으면 보임).
- 아머: 슬림 택티컬 엑소슈트(과하게 벌키하지 않음). 반투명 바이저 헬멧(얼굴 일부 노출).
- 장비: 등의 컴팩트 제트팩, 백팩에 통합된 접이식 미사일 포드, 전완 택티컬 디바이스, 하퇴 부스터, 미래형 프롭 카빈.
- **색 팔레트**: matte navy(주) · gunmetal gray(주) · orange accent(강조광) · dark undersuit.

- 향후 프롬프트의 "{캐릭터명}" 슬롯에는 **LT. HAN SEOJIN**을 사용. (기존 정본 시트 프롬프트는 이름 슬롯이 없어 그대로 둠.)

### 장비 — 백팩 멀티셀 포드 시스템
- 제트팩과 통합된 **전개식 이펙트 포드 시스템**. 다수의 소형 스타일화 미사일 셀이 레이어드/접이식 포드에 배열 → 고용량 애니 메카 일제 발사 장치 인상.
- 포드는 컴팩트·엘레강트(벌키 금지). 폴드/스토리지 상태 ↔ 디플로이/오픈 상태.
- **콘텐츠 가드(중요)**: 미사일류는 **실제 무기 설계가 아니라 가공의 애니 마이크로 미사일 이펙트 캡슐**로 스타일화. 리얼한 엔지니어링 디테일 회피, 가독성·실루엣·애니메이션 어필 우선. (이미지 생성기 정책·일관성 양쪽에 유리 → 모든 씬 프롬프트에 유지)

## 적 — 전투 드론 (정본)
- 정체: 폐허 도시전에 쓰이는 **대형 무장 전투 드론**. 소형 쿼드콥터·귀여운 드론 아님. **강화복 군인의 약 2~3배 크기**.
- 구조: 중장갑 중앙 동체, 측면 덕티드 팬/컴팩트 스러스터, 머신건 포드, 무장 하드포인트, 하부 센서 터렛, 후방 부스터 노즐.
- 실루엣: 공격적·기능적, 빠른 액션 장면에서도 식별 쉬움. 멀리서도 읽히는 디자인.
- 색: dark gray + gunmetal 동체, 작은 빨간 센서 라이트. 무기화된 산업 디자인.
- 역할: 부서진 고가도로 기둥 사이로 제트팩 군인을 추격.
- **디자인 가드**: 작은 토이 드론·곤충·새·제트 전투기·우주선·귀여운 로봇으로 보이면 안 됨.

## 원본 이미지 프롬프트 (v1 — 기존 작업, 보존)
> 이력 보존용. **실제 생성은 검수 반영 개정본 §개정 이미지 프롬프트(v2) 권장.**

### 캐릭터 시트 프롬프트
참조 틀: [[캐릭터 시트 프롬프트 템플릿]]

```
2D anime character reference sheet, Korean/Japanese anime style, clean lineart, cel shading, high detail, plain white background, professional model sheet layout.

Character: a late-20s Korean female special powered-armor soldier in a near-future military sci-fi setting. She has a slim athletic build, long legs, calm and sharp eyes, and a composed, battle-hardened expression. Hair is short dark brown to black, practical for combat, visible when helmet is off. Her armor is a slim tactical exosuit, not overly bulky, with matte navy and gunmetal gray as main colors and orange accent lights/details. She wears a semi-transparent visor helmet that partially reveals the face. The armor includes a compact jetpack on the back, folded missile pods integrated into the backpack area, forearm tactical devices, and lower-leg booster units.

Create a character sheet with the following layout:
- top row: full-body front view, side view, and back view in neutral standing pose
- bottom row: helmet ON portrait close-up, helmet OFF portrait close-up, and one small full-body relaxed standing pose
- include small color swatches for the main palette: matte navy, gunmetal gray, orange accent, dark undersuit
- show the armor silhouette clearly and consistently
- labels in English
- keep the face, body proportions, armor shapes, and colors identical across all views

Style notes: Korean/Japanese anime aesthetic, realistic military sci-fi influence, sleek but functional powered armor, readable silhouette, polished concept-art presentation.
```

### 장비/액션 시트 프롬프트
```
2D anime equipment and action reference sheet, Korean/Japanese anime style, clean lineart, cel shading, high detail, plain light-gray or white background, professional fictional mecha concept sheet layout.

Character: the same late-20s Korean female sci-fi powered-armor heroine from the main reference sheet. Keep the exact same face, proportions, hairstyle, armor design, and color palette: matte navy, gunmetal gray, orange accents. Same semi-transparent visor helmet, same slim powered exosuit, same lower-leg boosters, same futuristic prop carbine.

Important equipment update:
This is a fictional anime mecha design for a stylized action scene, not a real-world weapon design. The missile-like elements should be small, compact, and clearly stylized as fictional anime micro-missile effect capsules rather than realistic weapons. Avoid realistic engineering details. The design should focus on visual readability, silhouette, and animation appeal.

The character has a sleek backpack-mounted deployable effect pod system integrated with the jetpack. The backpack unit contains many small stylized missile cells arranged in layered or foldable pods, creating the impression of a high-capacity anime mecha barrage system. The pods should be compact and elegant, not bulky or oversized. Small forearm equipment modules may also be visible, but the main visual feature is the backpack-mounted multi-cell pod system.

Create a reference sheet focused on equipment details and action poses with the following layout:
* left side: detailed back view of the integrated jetpack and backpack-mounted multi-cell effect pod system
* small inset: backpack pod folded/storage state
* small inset: backpack pod deployed/open state
* small inset: compact stylized micro-missile capsule size example
* small inset: forearm equipment module detail
* small inset: lower-leg booster detail
* small inset: futuristic prop carbine detail
* right side: three dynamic full-body action poses:
  1. jet jump launch pose
  2. mid-air evasive maneuver pose
  3. anime barrage pose with backpack pods deployed and many small stylized projectiles launching as visual effects
* optional small effect notes showing booster flame direction and curved anime projectile trails
* labels in English

Design notes:
The backpack pod system should clearly read as a fictional high-capacity anime mecha barrage device. The small projectile capsules should be visibly compact and numerous, not large realistic missiles. The backpack unit should feel mechanically integrated with the jetpack, sleek, readable, and suitable for a fast-moving anime powered-armor character.

Important:
This is a fictional anime concept sheet, not a real-world military design. Keep the background simple. Show the mechanics as stylized visual design only. Preserve character consistency across all poses. Make the action poses dynamic but readable.
```

### 적 전투 드론 시트 프롬프트
```
2D anime mechanical enemy drone reference sheet, Korean/Japanese anime military sci-fi style, clean lineart, cel shading, high detail, plain white background, professional mecha concept sheet layout.

Subject: a large near-future armed combat drone used in ruined urban warfare. This is not a tiny quadcopter and not a cute small drone. It is a bulky military attack drone, roughly 2 to 3 times larger than a powered-armor soldier. It has a heavily armored central body, side-mounted ducted fans or compact thruster units, visible machine-gun pods, weapon hardpoints, a lower sensor turret, and rear booster nozzles. The silhouette should be aggressive, functional, and easy to recognize in fast action scenes.

Create a mechanical reference sheet with:
- front view
- side view
- rear view
- top view
- small detail inset of the machine-gun pod
- small detail inset of the sensor turret
- small detail inset of the thruster or ducted fan unit
- small scale comparison silhouette with a powered-armor soldier, showing the drone is much larger
- small damaged/exploding silhouette example for action scenes

Design style:
near-future military drone, armored, angular, practical, heavy combat equipment, dark gray and gunmetal body, small red sensor lights, weaponized industrial design.

Important:
Make the drone look like a large armed combat drone that can chase a jetpack soldier between ruined elevated highway pillars.
Keep the design readable from a distance.
Do not make it look like a small toy drone, insect, bird, jet fighter, spaceship, or cute robot.
Plain background, clean layout, labeled parts in English.
```

## 프롬프트 검수 결과 (Codex, 2026-06-18)
[[프롬프트 검수 워크플로]]로 위 3개 프롬프트의 GPT 이미지 생성 적합성 검수. **원본 프롬프트는 그대로 두고 권고만 기록** — 적용 여부는 사용자 결정.

| 프롬프트 | 판정 | 핵심 지적 |
|----------|------|-----------|
| 캐릭터 시트 | **경미한 수정** | 한 장에 뷰·포트레이트·스와치·라벨 ≈10+ 작업 → 상한 근처 / 크기 미지정 / 라벨 신뢰성 낮음 |
| 장비·액션 시트 | **상당한 수정** | 과적(백뷰+인셋6+액션3+이펙트) → **2A 장비 / 2B 액션 분리 권장** / 시트 간 일관성엔 앵커 이미지 필요 / "prop carbine" 인셋은 실총 쪽으로 끌릴 위험 |
| 적 전투 드론 시트 | **상당한 수정** | 정투상4+인셋3+스케일+파손 실루엣 과적 → **3A 정투상 / 3B 디테일·액션 분리** / "machine-gun pods·weapon hardpoints·armed combat drone"는 실무기에 가까워 **가공 메카 하드포인트로 완화 권장** / 파손 실루엣은 별도 시트로 |

### 공통 권고
1. **크기 명시** — 전부 `1536x1024`(가로) 권장. gpt-image-1은 1024²/1536×1024/1024×1536만 지원.
2. **과적 해소** — 객체 수 ~10~20 한계. (Codex는 시트 분리를 권했으나 **사용자 결정: 분리 대신 한 장에 맞게 요소를 축소**.)
3. **인-이미지 라벨 최소화** — GPT 텍스트 렌더링 불안정 → 짧은 라벨만, 최종 라벨은 Photoshop/Figma 등에서 후처리.
4. **일관성 워크플로(중요)** — ①캐릭터 시트 먼저 생성→베스트 1장을 **앵커 이미지**로 → ②장비 시트 생성 시 앵커를 **참조 이미지로 첨부**. 드론은 별도 생성.
5. **안전 표현(미적용)** — Codex는 드론 무기 표현을 가공 메카로 완화 권장. **사용자 결정: 완화 되돌림** — 원본 프롬프트("armed combat drone", "machine-gun pods", "weapon hardpoints", "prop carbine")가 ChatGPT에서 문제없이 생성됨.

→ 아래 §개정 이미지 프롬프트(v2)에 반영함 (크기·요소 축소로 한 장 유지·라벨 최소화·앵커 워크플로). **무기 표현 완화는 미적용(원본 유지).**

## 개정 이미지 프롬프트 (v2 — Codex 검수 반영, 시트당 1장)
전부 `1536x1024`(가로). **시트는 컨셉당 한 장 유지하되, 한 장에 깔끔히 담기도록 요소를 추림.** 인-이미지 라벨 최소화(최종 라벨은 Photoshop/Figma 등 후처리). (무기 표현 완화는 **되돌림** — 원본 프롬프트가 ChatGPT에서 문제없이 생성됨.)

> **일관성(앵커 워크플로)**: ① 캐릭터 시트 생성→베스트 1장을 **앵커 이미지**로 확정 → ② 장비 시트 생성 시 캐릭터 시트를 **참조 이미지로 첨부** → ③ 드론 시트는 별도 생성. 매 생성에 앞 산출물을 참조로 첨부해 일관성 확보.

### 1. 캐릭터 시트 (앵커)
참조 틀: [[캐릭터 시트 프롬프트 템플릿]].
```
Output size: 1536x1024 landscape.

2D anime character reference sheet, Korean/Japanese anime style, clean lineart, cel shading, high detail, plain white background, professional model sheet layout. Use a clean 3-column by 2-row layout with generous spacing; prioritize consistent character design over decorative detail.

Create the canonical reference design for LT. HAN SEOJIN, a late-20s Korean female special powered-armor soldier in a near-future military sci-fi setting. Slim athletic build, long legs, calm sharp eyes, composed battle-hardened expression. Short dark brown-black practical hair, visible when the helmet is off.

Armor: slim tactical powered exosuit, sleek and functional, not bulky. Matte navy and gunmetal gray main armor, dark undersuit, small orange accent lights. Semi-transparent visor helmet partially revealing the face. Compact jetpack on back, folded fictional pod units integrated into the backpack, forearm tactical devices, lower-leg booster units.

Layout:
- Top row: three full-body neutral standing views — FRONT, SIDE, BACK.
- Bottom row: two portrait close-ups — HELMET ON, HELMET OFF — plus four clean color swatches (matte navy, gunmetal gray, orange accent, dark undersuit).

Use only short, widely-spaced English labels (FRONT, SIDE, BACK, HELMET ON, HELMET OFF, PALETTE), separated from the art; no tiny technical annotations. Keep face, proportions, armor silhouette, helmet, backpack, and colors identical across all views.
```

### 2. 장비·액션 시트 (한 장 / 앵커: 캐릭터 시트 첨부)
참조 틀: [[스타일 적용 규칙]](일제 발사 포즈는 이타노 키워드 추가 가능).
> 한 장에 맞춰 추림. **포함**: 후방뷰(제트팩+포드) · 포드 전개 인셋 · 하퇴 부스터 인셋 · 제트 점프 포즈 · 일제발사 포즈(5요소). **제외(필요시 교체)**: 전완 모듈, 캡슐 크기 인셋, 프롭 카빈, 공중 회피 포즈.
```
Output size: 1536x1024 landscape.

Use the approved LT. HAN SEOJIN character sheet image as the visual reference. Preserve her face, hairstyle, proportions, armor silhouette, palette, helmet, and backpack.

2D anime equipment & action reference sheet for one character, Korean/Japanese anime mecha style, clean lineart, cel shading, plain white background. This is a fictional anime mecha design, not a real-world weapon design. Avoid realistic engineering details; focus on visual readability, silhouette, and animation appeal.

Keep the sheet to these elements only, clearly spaced in one image:
- Large left: three-quarter rear view of LT. HAN SEOJIN showing the compact jetpack and backpack-mounted fictional effect pod system (folded).
- Small inset: pod deployed/open state (many compact stylized effect capsules).
- Small inset: lower-leg booster detail.
- Right: two dynamic full-body action poses — (1) jet jump launch, (2) barrage pose with pods deployed and stylized capsules launching as curved light trails.

Pod cells read as compact fictional anime capsules, not realistic missiles. Use only short labels (POD FOLDED, POD DEPLOYED, BOOSTER, JET JUMP, BARRAGE). Keep it readable and uncluttered; do not add extra insets or text.
```

### 3. 적 드론 시트 (한 장)
> 한 장에 맞춰 추림. **포함**: 정면/측면/후면 뷰 · 강화복 군인 스케일 실루엣 · 머신건 포드 디테일 1개(5요소). **제외(필요시 교체)**: 탑뷰, 센서 터렛·팬 인셋, 파손 실루엣.
```
Output size: 1536x1024 landscape.

2D anime mechanical enemy drone reference sheet, Korean/Japanese anime military sci-fi style, clean lineart, cel shading, high detail, plain white background.

Subject: a large near-future armed combat drone used in ruined urban warfare, 2-3x larger than a powered-armor soldier. Heavily armored central body, side-mounted ducted fans or compact thruster units, visible machine-gun pods, weapon hardpoints, a lower sensor turret, and rear booster nozzles. Aggressive, functional, readable silhouette. Dark gray and gunmetal body, small red sensor lights, weaponized industrial design.

Keep the sheet to these elements only, clearly spaced in one image:
- Three large orthographic views: FRONT, SIDE, REAR.
- One simple scale-comparison silhouette of a powered-armor soldier beside the FRONT view (drone clearly much larger).
- One detail callout of a machine-gun pod.

Use only short labels (FRONT, SIDE, REAR, SCALE, GUN POD). Make it look like a large armed combat drone that can chase a jetpack soldier between ruined elevated highway pillars; keep it readable from a distance. Do not make it look like a toy drone, insect, bird, jet fighter, spaceship, or cute robot.
```

## 씬 / 스토리 (미확정 — 사용자 입력 대기)
- **확정(사용자 제공)**: 클라이맥스 한 줄 — "제트 점프 강화복 군인이 싸우다 마지막에 [[이타노 서커스]]로 다량의 미사일을 일제 발사(탄막)".
- **미확정**: 전체 스토리, 씬 구성, 장소·시간대·분위기, 적/상황, 샷 리스트, 컷 수. → 아직 작성하지 않음.
- 스토리·씬 설정을 받은 뒤 [[스토리보드 프롬프트 템플릿]]·[[Seedance 모션 프롬프트 템플릿]]로 씬 프롬프트를 작성하고, 클라이맥스에 [[스타일 적용 규칙]]대로 [[이타노 서커스]]를 적용함(키워드·가드는 준비됨).

> ⚠️ 씬 프롬프트는 스토리가 정해진 뒤 작성함. 장소·시간대·분위기·구도 등은 **지어내지 않음**.

## 다음 작업 (TODO)
- [ ] **스토리·씬 설정** 확정 (장소·시간대·분위기·적/상황·샷 리스트) → 이후 씬 프롬프트 작성
- [x] 캐릭터 이름 확정 → **LT. HAN SEOJIN (한서진 중위)**
- [ ] (스토리 확정 후) 클라이맥스 씬 프롬프트 작성 → [[프롬프트 검수 워크플로]] Codex 검수
- [ ] 생성 산출물(시트/스토리보드 이미지)을 `assets/`에 보관·연결

## 관련 문서
- [[AI 애니메이션 제작 파이프라인]]
- [[이타노 서커스]]
- [[스타일 적용 규칙]]
- [[캐릭터 시트 프롬프트 템플릿]]
- [[스토리보드 프롬프트 템플릿]]
- [[Seedance 모션 프롬프트 템플릿]]
- [[캐릭터 일관성]]
- [[프롬프트 검수 워크플로]]
