---
title: Seedance 스펙·프롬프트 요약
type: reference
status: draft
tags: [요약, Seedance, ByteDance, 스펙, image-to-video]
sources: [src-seedance-techreport, src-seedance-arxiv, src-byteplus-modelark-pro, src-fal-seedance-i2v, src-fal-learn-2-0, src-imagineart-2-0]
created: 2026-06-18
updated: 2026-06-18
---

# Seedance 스펙·프롬프트 요약

> Seedance 1.0 기술 보고서·BytePlus 스펙·호스팅 플랫폼 문서의 핵심을 정리함. 영상 단계의 출처 모음임.

## 스펙 (공식 A)
- 개발: ByteDance Seed, 1.0 출시 2025-06, T2V+I2V 단일 모델 (출처: src-seedance-techreport, src-seedance-arxiv).
- 1.0 Pro: 480p/720p/1080p, 24fps, 2~12초 (출처: src-byteplus-modelark-pro).
- 네이티브 멀티샷: 10초에 ~2~3 샷 전환, 와이드/미디엄/클로즈업 일관 (출처: src-seedance-techreport).

## I2V 프롬프트 (B/C)
- 입력 이미지=첫 프레임, 선택적 end_image로 시작→끝 전환 (출처: src-fal-seedance-i2v).
- 이미지에 있는 외형은 재묘사 X, 동작+카메라만 (출처: src-fal-learn-2-0, src-imagineart-2-0).
- 샷당 주 동작 1개+카메라 무빙 1개, 컷은 "Shot 1/2"·"Cut to:" 라벨 (출처: src-fal-learn-2-0).
- "fast" 남용 금지, 카메라/주체 움직임 분리 (출처: src-fal-learn-2-0, src-imagineart-2-0).

> ⚠️ BytePlus 공식 프롬프트 가이드 본문은 추출 불가 → 프롬프트 공식은 플랫폼/커뮤니티(B/C) 근거임.

## 관련 문서
- [[영상 프롬프트 원리]]
- [[Seedance]]
- [[Seedance 모션 프롬프트 템플릿]]
