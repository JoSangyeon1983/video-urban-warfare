# Sources — 원본 레지스트리

`sources/`는 **불변(immutable) 원본 레이어**임. LLM은 읽기만 함 (CLAUDE.md §2).
웹 자료는 URL + 접근일(accessed)로 등록해 출처를 추적함. 모든 위키 주장은 아래 source-id로 역추적 가능해야 함.

## 등록 규칙
- source-id는 `src-<출처약칭>-<주제>` 형식.
- 신뢰도: **A** = 공식 문서(개발사) / **B** = 호스팅 플랫폼 문서 / **C** = 커뮤니티·블로그 / **D** = 보도(2차).
- 본문 인용은 `(출처: source-id)`로 표기하고, 페이지 frontmatter `sources:`에 나열함.

## source-id 인덱스

### ChatGPT / GPT-4o 이미지 생성

| source-id | 제목 | 출처/발행 | 신뢰도 | URL | accessed |
|-----------|------|-----------|--------|-----|----------|
| `src-openai-cookbook-imggen` | GPT Image Generation Models Prompting Guide | OpenAI Cookbook | A | https://developers.openai.com/cookbook/examples/multimodal/image-gen-models-prompting-guide | 2026-06-18 |
| `src-openai-api-imggen` | Image generation — OpenAI API guide | OpenAI | A | https://developers.openai.com/api/docs/guides/image-generation | 2026-06-18 |
| `src-openai-cookbook-genimg` | Generate images with GPT Image (cookbook) | OpenAI | A | https://developers.openai.com/cookbook/examples/generate_images_with_gpt_image | 2026-06-18 |
| `src-openai-4o-announce` | Introducing 4o Image Generation | OpenAI | A | https://openai.com/index/introducing-4o-image-generation/ | 2026-06-18 |
| `src-promptingguide-4o` | 4o Image Generation Guide | DAIR.AI Prompting Guide | C | https://www.promptingguide.ai/guides/4o-image-generation | 2026-06-18 |
| `src-learnprompting-4o` | GPT-4o Image Generation: Complete Guide + 12 Prompt Examples | Learn Prompting | C | https://learnprompting.org/blog/guide-openai-4o-image-generation | 2026-06-18 |
| `src-selfielab-charsheet` | ChatGPT Image Gen: Character Sheet Mastery | selfielab (blog) | C | https://selfielab.me/blog/chatgpt-image-gen-character-sheet-mastery-tutorial-20260220 | 2026-06-18 |
| `src-bigprompthub-turnaround` | Consistent Model Sheets with character turnarounds | Big Prompt Hub | C | https://www.bigprompthub.com/extract-character-turnarounds-sheet-prompt/ | 2026-06-18 |
| `src-infoq-4o` | OpenAI Releases Improved Image Generation in GPT-4o | InfoQ | D | https://www.infoq.com/news/2025/04/gpt-4o-images/ | 2026-06-18 |
| `src-venturebeat-4o` | OpenAI introduces GPT-4o native image generation | VentureBeat | D | https://venturebeat.com/ai/insane-openai-introduces-gpt-4o-native-image-generation-and-its-already-wowing-users | 2026-06-18 |

### Seedance (ByteDance) 영상 생성

| source-id | 제목 | 출처/발행 | 신뢰도 | URL | accessed |
|-----------|------|-----------|--------|-----|----------|
| `src-seedance-techreport` | Tech Report of Seedance 1.0 Is Now Publicly Available | ByteDance Seed | A | https://seed.bytedance.com/en/blog/tech-report-of-seedance-1-0-is-now-publicly-available | 2026-06-18 |
| `src-seedance-paper` | Seedance 1.0: Exploring the Boundaries of Video Generation Models | ByteDance Seed | A | https://seed.bytedance.com/en/public_papers/seedance-1-0-exploring-the-boundaries-of-video-generation-models | 2026-06-18 |
| `src-seedance-arxiv` | Seedance 1.0 (arXiv 2506.09113) | ByteDance Seed | A | https://huggingface.co/papers/2506.09113 | 2026-06-18 |
| `src-byteplus-modelark-pro` | seedance-1.0-pro — ModelArk 스펙 | BytePlus | A | https://docs.byteplus.com/en/docs/ModelArk/1587798 | 2026-06-18 |
| `src-byteplus-what-is` | What is Seedance 1.0? | BytePlus | A | https://www.byteplus.com/en/topic/577572 | 2026-06-18 |
| `src-fal-seedance-i2v` | Seedance v1.5 Pro (Image-to-Video) API | fal.ai | B | https://fal.ai/models/fal-ai/bytedance/seedance/v1.5/pro/image-to-video | 2026-06-18 |
| `src-replicate-seedance` | ByteDance Seedance 1 Pro | Replicate | B | https://replicate.com/bytedance/seedance-1-pro | 2026-06-18 |
| `src-scenario-seedance` | Seedance 1.0 Video Models — Essentials | Scenario | B | https://help.scenario.com/en/articles/seedance-models-the-essentials | 2026-06-18 |
| `src-fal-learn-2-0` | How to Use Seedance 2.0 Like a Pro | fal.ai/learn | C | https://fal.ai/learn/tools/how-to-use-seedance-2-0 | 2026-06-18 |
| `src-imagineart-2-0` | Seedance 2.0 Prompt Guide (70 prompts) | Imagine.art | C | https://www.imagine.art/blogs/seedance-2-0-prompt-guide | 2026-06-18 |
| `src-geelark-variants` | Seedance Pro vs Pro Fast vs Lite | GeeLark | C | https://www.geelark.com/blog/seedance-pro-vs-pro-fast-vs-lite/ | 2026-06-18 |

> ⚠️ 검수 메모: BytePlus 공식 프롬프트 가이드(ModelArk 1631633/2222480)는 JS 렌더링으로 본문 추출 불가.
> 프롬프트 공식(formula) 관련 주장은 플랫폼·커뮤니티(B/C) 근거이며 공식 가이드 원문이 아님.

### 애니메이션 작화 스타일 (사용자 제공 로컬 자료)

| source-id | 제목 | 파일 | 신뢰도 | 비고 | accessed |
|-----------|------|------|--------|------|----------|
| `src-itano-circus-report` | 이타노 서커스 연구 보고서 | `sources/ItanoCircus.md` | C | 인터뷰·공식 페이지·논문을 종합한 **2차 합성 보고서**. 본문에 미상/추정 항목 다수 명시 | 2026-06-18 |
| `src-kanada-style-report` | 카나다 스타일의 작화 문법과 현대적 계승 | `sources/KanadaStyle.md` | C | 동상. 타임스탬프·프레임 수치는 보고서 자체가 **추정치**로 표기 | 2026-06-18 |

> ⚠️ 검수 메모: 위 두 보고서는 `citeturn…` 형식의 깨진 인용 마커를 포함함(원 출처 URL 직접 추적 불가).
> 보고서 자체가 다수 항목을 "미상/추정/자료 간 불일치"로 명시하므로, 위키 인용 시 그 한정을 보존함.
