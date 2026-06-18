---
title: ChatGPT 이미지 생성 (GPT-4o / gpt-image)
type: entity
status: draft
tags: [이미지생성, OpenAI, GPT-4o, gpt-image, 프롬프트]
sources: [src-openai-cookbook-imggen, src-openai-api-imggen, src-openai-cookbook-genimg, src-openai-4o-announce, src-promptingguide-4o, src-infoq-4o]
created: 2026-06-18
updated: 2026-06-18
---

# ChatGPT 이미지 생성 (GPT-4o / gpt-image)

> OpenAI의 이미지 생성 기능. ChatGPT 내 기능명은 "GPT-4o 이미지 생성", API 모델명은 `gpt-image-1` 계열임. 본 파이프라인에서 **캐릭터 시트**와 **스토리보드 이미지**를 만드는 도구임.

## 핵심 내용
- 개발사: **OpenAI**. ChatGPT 기능으로는 2025-03 출시, API 모델은 `gpt-image-1` (출처: src-openai-4o-announce).
- 작동 방식: 별도 디퓨전 모델이 아니라 **자기회귀(autoregressive)** 방식으로 모델에 내장됨 → 텍스트 렌더링·정밀 편집·이미지 입력 편집에 강함 (출처: src-openai-4o-announce, src-infoq-4o).
- 모델 계열(버전별 스펙 상이): `gpt-image-1` / `gpt-image-1.5` / `gpt-image-2` 등. 프롬프트 **원리는 공유**하나 **해상도·투명도 옵션은 버전마다 다름** (출처: src-openai-cookbook-imggen, src-openai-api-imggen).
- 입력: 텍스트 + **참조 이미지**(편집 엔드포인트 `/images/edit`는 입력 이미지 최대 10장, 마스크는 첫 이미지에 적용·알파채널 필요) (출처: src-openai-cookbook-genimg).

## 해상도·품질 (버전별 — 공식)

| 항목 | gpt-image-1 / 1.5 / mini | gpt-image-2 |
|------|--------------------------|-------------|
| 크기 | `1024x1024` · `1536x1024` · `1024x1536` · `auto` | 거의 임의(최대 변 ≤3840px, 변은 16의 배수, 비율 ≤3:1, 총픽셀 655,360~8,294,400) |
| 품질 | low / medium / high / auto | 동일 |
| 투명 배경 | 지원(PNG/WEBP) | **미지원** |

(출처: src-openai-api-imggen, src-openai-cookbook-genimg, src-openai-cookbook-imggen)

## 강점·한계
- 강점: **텍스트 렌더링**(이미지 내 글자), 참조 이미지 기반 리텍스처·스타일 변환, 멀티턴 정밀 편집 (출처: src-openai-cookbook-imggen, src-openai-4o-announce).
- 한계:
  - 한 이미지에 신뢰성 있게 담을 객체/개념 **약 10~20개** 한계 (출처: src-openai-4o-announce, src-infoq-4o).
  - 국소 편집 시 **다른 영역이 의도치 않게 변함** (출처: src-openai-4o-announce).
  - 비(非)라틴 문자 텍스트는 부정확·환각 가능 (출처: src-openai-4o-announce).
  - 복잡 프롬프트는 생성에 최대 ~2분 (출처: src-openai-api-imggen).

## 관련 문서
- [[이미지 프롬프트 원리]]
- [[캐릭터 시트]]
- [[스토리보드]]
- [[AI 애니메이션 제작 파이프라인]]

## 참고
- 본 페이지의 핵심 출처는 OpenAI Cookbook 프롬프트 가이드(src-openai-cookbook-imggen)임.
