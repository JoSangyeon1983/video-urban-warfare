# Log (append-only)

포맷: `YYYY-MM-DD | <작업유형> | <대상> | <한 줄 설명>` (CLAUDE.md §9). 최신 항목을 아래에 추가함.

2026-06-18 | MAINT | vault 골격 | PARA 폴더(00_Index~05_Logs, sources, assets) 생성
2026-06-18 | INGEST | sources/README.md | ChatGPT 이미지생성·Seedance 웹 리서치 21개 소스 등록(신뢰도 A~D)
2026-06-18 | CREATE | 01_Concepts/ChatGPT 이미지 생성.md | GPT-4o/gpt-image 엔티티 페이지 (draft)
2026-06-18 | CREATE | 01_Concepts/Seedance.md | ByteDance 영상모델 엔티티 페이지 (draft)
2026-06-18 | CREATE | 01_Concepts/이미지 프롬프트 원리.md | 이미지 프롬프트 원리 concept (draft)
2026-06-18 | CREATE | 01_Concepts/영상 프롬프트 원리.md | Seedance 프롬프트 원리 concept (draft)
2026-06-18 | CREATE | 01_Concepts/캐릭터 일관성.md | 캐릭터 일관성 concept (draft)
2026-06-18 | CREATE | 01_Concepts/캐릭터 시트.md | 캐릭터 시트 concept (draft)
2026-06-18 | CREATE | 01_Concepts/스토리보드.md | 스토리보드 concept (draft)
2026-06-18 | CREATE | 01_Concepts/AI 애니메이션 제작 파이프라인.md | 3단계 파이프라인 overview (draft)
2026-06-18 | CREATE | 02_HowTo/캐릭터 시트 프롬프트 템플릿.md | 복붙용 템플릿 (draft)
2026-06-18 | CREATE | 02_HowTo/스토리보드 프롬프트 템플릿.md | 복붙용 템플릿 (draft)
2026-06-18 | CREATE | 02_HowTo/Seedance 모션 프롬프트 템플릿.md | 복붙용 템플릿 (draft)
2026-06-18 | CREATE | 03_References/OpenAI 이미지 생성 프롬프트 가이드 요약.md | 소스 요약 reference (draft)
2026-06-18 | CREATE | 03_References/Seedance 스펙·프롬프트 요약.md | 소스 요약 reference (draft)
2026-06-18 | CREATE | 04_Projects/UrbanWarfare.md | 프로젝트 노트 stub (자료 대기)
2026-06-18 | CREATE | 00_Index/MOC.md | 전체 색인 생성
2026-06-18 | INGEST | sources/ItanoCircus.md, KanadaStyle.md | 사용자 제공 작화 스타일 2종 sources/README.md 등록(신뢰도 C)
2026-06-18 | CREATE | 01_Concepts/이타노 서커스.md | 작화 스타일 concept + 프롬프트 적용 (draft)
2026-06-18 | CREATE | 01_Concepts/카나다 스타일.md | 작화 스타일 concept + 프롬프트 적용 (draft)
2026-06-18 | UPDATE | UrbanWarfare.md, MOC.md, 스토리보드/Seedance 템플릿 | 작화 스타일 상호연결(스타일 앵커)
2026-06-18 | REVIEW | 캐릭터 시트/스토리보드 프롬프트 템플릿 | Codex 검수 — 두 템플릿 "상당한 수정" 판정(비율 오류·뷰 과다·스타일 충돌 등)
2026-06-18 | UPDATE | 캐릭터 시트/스토리보드 프롬프트 템플릿 | Codex 피드백 반영(크기 수정, 4뷰+헤드샷 분리, 첫프레임 안정화, 스타일 가드)
2026-06-18 | CREATE | 02_HowTo/프롬프트 검수 워크플로.md | 이미지 프롬프트 Codex 검수 절차 문서화 (draft)
2026-06-18 | UPDATE | AI 애니메이션 제작 파이프라인.md, MOC.md | ①②단계에 Codex 검수 스텝 추가·색인 등록
2026-06-18 | CREATE | 03_References/이타노 서커스 연구 정리.md | sources/ItanoCircus.md 가공 reference (draft)
2026-06-18 | CREATE | 03_References/카나다 스타일 연구 정리.md | sources/KanadaStyle.md 가공 reference (draft)
2026-06-18 | UPDATE | 이타노 서커스/카나다 스타일 concept, MOC.md | 연구 정리 reference 상호연결·색인 등록
2026-06-18 | UPDATE | 03_References/이타노 서커스·카나다 스타일 연구 정리.md | 과압축 지적 반영 — 장면별 상세 분석·서술 복원해 원본 깊이 유지(개조식 재구성)
2026-06-18 | UPDATE | 03_References/이타노 서커스·카나다 스타일 연구 정리.md | "원문에 더 가까이" 요청 반영 — 원본 본문 거의 그대로 전사(깨진 citeturn 마커·이미지 임베드만 제거, 위키 형식만 부가)
2026-06-18 | CREATE | 02_HowTo/스타일 적용 규칙.md | 컷별 이타노/카나다 적용 절차 + 복붙 치트시트(스토리보드/Seedance) + 가드 (draft)
2026-06-18 | MAINT | memory/style-application-rule.md, MEMORY.md | 스타일 적용 절차를 프로젝트 메모리에 저장(자동 적용)
2026-06-18 | UPDATE | MOC.md, 이타노/카나다 concept, 스토리보드/Seedance 템플릿 | 스타일 적용 규칙 상호연결·색인 등록
2026-06-18 | INGEST | 04_Projects/UrbanWarfare.md | 사용자 확정 자료(캐릭터·강화복·기존 캐릭터/장비 시트 프롬프트) 정본 정리, stub→draft 승격
2026-06-18 | CREATE | 04_Projects/UrbanWarfare.md | 클라이맥스 이타노 서커스 미사일 바라지 씬 스토리보드+Seedance 프롬프트 초안 작성(스타일 적용 규칙 적용)
2026-06-18 | UPDATE | 04_Projects/UrbanWarfare.md | 사용자 지적 반영 — 스토리 미확정 상태에서 지어낸 클라이맥스 씬 프롬프트(①②) 삭제, "도시전" 추정 표기, 씬은 스토리 확정 후 작성으로 변경
2026-06-18 | INGEST | 04_Projects/UrbanWarfare.md | 적 전투 드론 시트 프롬프트 정본 추가, 드론 설정 정리. 드론 프롬프트 근거로 폐허 도시전/고가도로 배경 확정(추정→확정)
2026-06-18 | UPDATE | 04_Projects/UrbanWarfare.md | 주인공 이름·계급 확정 — LT. HAN SEOJIN(한서진 중위), 이름 TODO 해소
2026-06-18 | REVIEW | 04_Projects/UrbanWarfare.md 이미지 프롬프트 3종 | Codex GPT 이미지 생성 적합성 검수 — 캐릭터(경미)/장비(상당,분리)/드론(상당,분리+무기표현 완화). 권고만 기록, 원본 보존
2026-06-18 | UPDATE | 04_Projects/UrbanWarfare.md | 검수 반영 개정 프롬프트 v2 작성 — 크기 1536x1024, 시트 분리(캐릭터/2A·2B/3A·3B), 라벨 최소화, 무기표현 가공화, 앵커 워크플로. v1은 원본 보존
2026-06-18 | UPDATE | 04_Projects/UrbanWarfare.md | 사용자 의도 정정 — v2를 시트 분리(2A/2B/3A/3B)에서 컨셉당 1장(캐릭터/장비/드론)으로 변경, 요소를 한 장에 맞게 축소. 제외 항목 명시
2026-06-18 | UPDATE | 04_Projects/UrbanWarfare.md | 무기 표현 완화 되돌림 — 드론 "armed combat drone/machine-gun pods/weapon hardpoints", carbine "prop carbine" 원본 유지(원본이 ChatGPT에서 정상 생성됨). 검수 #5 미적용 처리
2026-06-18 | MAINT | 04_Projects/UrbanWarfare.md | 용어 통일 — 한글 본문 "바라지"→"일제 발사"(영어 프롬프트 내 barrage/BARRAGE는 입력값이라 유지)
