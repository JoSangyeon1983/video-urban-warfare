---
title: OpenAI 이미지 생성 프롬프트 가이드 요약
type: reference
status: draft
tags: [요약, OpenAI, 프롬프트, 이미지생성]
sources: [src-openai-cookbook-imggen, src-openai-api-imggen, src-openai-cookbook-genimg]
created: 2026-06-18
updated: 2026-06-18
---

# OpenAI 이미지 생성 프롬프트 가이드 요약

> OpenAI Cookbook의 이미지 생성 프롬프트 가이드(및 API 문서)의 핵심을 정리함. 본 위키 이미지 단계의 **가장 신뢰도 높은(A) 출처**임 (출처: src-openai-cookbook-imggen).

## 핵심 권고
- 프롬프트 구조: 배경/장면 → 주체 → 디테일 → 제약, 복잡 시 라벨/줄바꿈 분절 (출처: src-openai-cookbook-imggen).
- 형식 자유(최소·서술·JSON·지시·태그형 모두 가능), 묘사 부족분은 모델이 채움 (출처: src-openai-cookbook-imggen).
- 텍스트 렌더링: 품질 medium/high, 따옴표·대문자, 폰트·위치 명시, 난단어는 철자 단위 (출처: src-openai-cookbook-imggen).
- 참조 이미지: 인덱스+설명으로 지칭, 편집 엔드포인트 입력 최대 10장, 마스크는 첫 이미지+알파채널 (출처: src-openai-cookbook-genimg).
- 일관성: 영속 메모리 없음 → 스타일·팔레트·제약 매번 반복, 앵커 이미지+"Do not redesign" (출처: src-openai-cookbook-imggen).
- 카메라/구도 어휘: 프레이밍·앵글·조명·인물 배치 지정 (출처: src-openai-cookbook-imggen).

## 스펙(버전별)
- 크기: gpt-image-1/1.5는 3종+auto, gpt-image-2는 거의 임의(변≤3840·16배수·비율≤3:1) (출처: src-openai-api-imggen, src-openai-cookbook-genimg).
- 품질: low/medium/high/auto. 투명배경: gpt-image-1 지원, gpt-image-2 미지원 (출처: src-openai-api-imggen, src-openai-cookbook-genimg).

## 관련 문서
- [[이미지 프롬프트 원리]]
- [[ChatGPT 이미지 생성]]
- [[캐릭터 일관성]]
