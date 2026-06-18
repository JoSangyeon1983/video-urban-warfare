---
title: Seedance (ByteDance 영상 생성)
type: entity
status: draft
tags: [영상생성, Seedance, ByteDance, image-to-video, 프롬프트]
sources: [src-seedance-techreport, src-seedance-arxiv, src-byteplus-modelark-pro, src-byteplus-what-is, src-fal-seedance-i2v, src-replicate-seedance, src-scenario-seedance, src-fal-learn-2-0, src-geelark-variants]
created: 2026-06-18
updated: 2026-06-18
---

# Seedance (ByteDance 영상 생성)

> ByteDance Seed 팀의 영상 생성 모델. 텍스트→영상(T2V)과 **이미지→영상(I2V)**을 한 모델에서 지원함. 본 파이프라인에서 생성한 스토리보드 이미지를 첨부해 **애니메이션 클립으로 만드는** 도구임.

## 핵심 내용
- 개발사: **ByteDance Seed** 팀 (국제 브랜드 BytePlus / 火山引擎 Volcano Engine) (출처: src-seedance-techreport, src-byteplus-what-is).
- 최초 출시: **Seedance 1.0**, 2025-06 (기술 보고서 2025-06-11 공개) (출처: src-seedance-techreport).
- 입출력: 단일 모델이 **T2V + I2V** 모두 지원 (출처: src-seedance-arxiv).
- 멀티샷: **네이티브 멀티샷** — 10초 영상에 ~2~3개 샷 전환을 와이드/미디엄/클로즈업으로 일관되게 생성 (출처: src-seedance-techreport, src-seedance-arxiv).
- 다국어: 중국어/영어 프롬프트 네이티브 지원 (출처: src-seedance-arxiv).

## 버전별 스펙 (버전마다 다름 — 반드시 확인)

| 버전 | 해상도 | fps | 길이 | 비고 | 신뢰도 |
|------|--------|-----|------|------|--------|
| 1.0 Pro | 480p/720p/1080p | 24 | 2~12초 | 시네마틱·프로덕션 (출처: src-byteplus-modelark-pro) | A |
| 1.0 Pro Fast | 동일 | 24 | 2~12초 | 속도 최적화 (출처: src-byteplus-modelark-pro, src-geelark-variants) | A/C |
| 1.0 Lite | ~1080p(주로 720p) | — | ~5초(무료 캡) | 속도·비용 최적화·워터마크 가능 (출처: src-byteplus-what-is, src-geelark-variants) | C |
| 1.5 Pro | 네이티브 1080p | 24 | 4~12초(기본 5초) | 폭넓은 비율 (출처: src-fal-seedance-i2v) | B |
| 2.0 | 최대 720p(문서 기준) | — | — | **네이티브 오디오/립싱크** 추가 (출처: src-fal-learn-2-0) | C |

- 표준 프리셋 길이: **5초·10초**가 보편, 1.0 Pro API는 2~12초 전 구간 허용 (출처: src-byteplus-modelark-pro, src-replicate-seedance).
- 비율(플랫폼 기준): 21:9·16:9·4:3·1:1·3:4·9:16(·9:21), 기본 16:9 (출처: src-fal-seedance-i2v, src-scenario-seedance).
  > ⚠️ 비율 목록은 **플랫폼(fal/Scenario)** 근거이며, 1.0 Pro 공식 스펙 페이지엔 명시되지 않음.

## 주요 API 레버 (fal 기준)
- `camera_fixed`(true=고정/삼각대 샷) · `resolution`(반복은 480p, 최종은 720p↑) · `generate_audio` · `seed`(−1=랜덤) · `duration` · `aspect_ratio` (출처: src-fal-seedance-i2v).

## 관련 문서
- [[영상 프롬프트 원리]]
- [[캐릭터 일관성]]
- [[AI 애니메이션 제작 파이프라인]]

## 참고
- 벤치마크 #1 주장(Artificial Analysis, 2025-06)은 **벤더 자체 보고**임 (출처: src-seedance-arxiv).
