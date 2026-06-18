---
title: Seedance 모션 프롬프트 템플릿
type: howto
status: draft
tags: [템플릿, Seedance, image-to-video, 모션, 카메라]
sources: [src-fal-seedance-i2v, src-fal-learn-2-0, src-imagineart-2-0, src-byteplus-what-is, src-scenario-seedance, src-byteplus-modelark-pro]
created: 2026-06-18
updated: 2026-06-18
---

# Seedance 모션 프롬프트 템플릿

> 스토리보드 이미지를 첨부해 Seedance로 애니메이션 클립을 만드는 복붙용 틀. **이미지가 첫 프레임**이므로 프롬프트는 동작·카메라만 기술함. 원리는 [[영상 프롬프트 원리]] 참고.

## 사용법
1. 스토리보드 이미지를 **첫 프레임**으로 첨부 (출처: src-fal-seedance-i2v).
2. **이미지에 이미 있는 외형은 재묘사하지 않음** — 동작+카메라+제약만 (출처: src-fal-learn-2-0, src-imagineart-2-0).
3. 샷당 **주 동작 1개 + 카메라 무빙 1개** (출처: src-fal-learn-2-0).

## 템플릿 — 단일 샷 (I2V)

```
[첨부: 첫 프레임 이미지]

Subject motion: {주체가 하는 단일 동작, 현재형 동사}.
Camera: {shot size} + {movement: slow pan / dolly in / tracking / handheld / locked-off} + {angle}.
Atmosphere: {조명 변화/분위기, 예: dust drifting, flickering light}.
Style: {cinematic, 35mm film 등 비주얼 앵커}.
Keep composition and colors consistent with the source image.
```

## 템플릿 — 멀티샷

```
[첨부: 첫 프레임 이미지]

Shot 1: {주체 동작} — Camera: {무빙}.
Cut to:
Shot 2: {주체 동작} — Camera: {무빙}.
```
- 컷은 "Shot 1/2" 또는 "Cut to:"로 명시 (출처: src-fal-learn-2-0, src-byteplus-what-is).

## 카메라 무빙 어휘

| 무빙 | 효과 |
|------|------|
| slow pan / tilt | 완만한 시점 이동(빠르게 X) |
| dolly in / out | 전진/후진 |
| tracking shot | 주체 추적 |
| handheld | 미세 흔들림(현장감) |
| locked-off / `camera_fixed=true` | 고정 샷 (출처: src-fal-seedance-i2v) |
| whip-pan | 빠른 전환 |

## 파라미터·길이 (fal/1.0 Pro 기준)
- `resolution`: 반복은 480p, 최종은 720p↑ / `duration`: 5초·10초 프리셋(1.0 Pro 2~12초) / `aspect_ratio`: 기본 16:9 / `seed`: −1 랜덤 / `generate_audio`(2.0) (출처: src-fal-seedance-i2v, src-byteplus-modelark-pro).

## 실패 회피
- **"fast" 남용 금지** — 빠른 카메라+빠른 컷+복잡 장면 → 떨림/아티팩트 (출처: src-fal-learn-2-0, src-imagineart-2-0).
- **카메라 움직임과 주체 움직임을 분리해 기술** (혼동이 최다 실수) (출처: src-imagineart-2-0).
- 캐릭터 표정·바디랭귀지로 성격 운반 (출처: src-scenario-seedance).

## 스타일 앵커 (선택)
- 액션 컷은 작화 스타일을 `Style:` 슬롯에 반영: [[이타노 서커스]](붙여 팬·트레일·속도감) · [[카나다 스타일]](포즈투포즈→키 포즈 컷 분할 권장).
- 컷별 스타일 지정·복붙 키워드는 [[스타일 적용 규칙]] 참고.

## 관련 문서
- [[영상 프롬프트 원리]]
- [[Seedance]]
- [[스토리보드 프롬프트 템플릿]]
- [[캐릭터 일관성]]
- [[이타노 서커스]]
- [[카나다 스타일]]
