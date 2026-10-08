<a href="https://project-hub-youngho.vercel.app"><img src="https://project-hub-youngho.vercel.app/opengraph-image" alt="신영호 포트폴리오 — 현장의 반복 업무를 직접 찾아 자동화합니다" width="100%"></a>

## 신영호 · 현장의 반복 업무를 직접 찾아 자동화합니다

QC 1년 7개월 · Python · ERP 연동 · AI 에이전트

### 포트폴리오 사이트: [project-hub-youngho.vercel.app](https://project-hub-youngho.vercel.app)

프로젝트별 문제, 결정과 이유, 측정한 효과를 정리했습니다. 사이트 소스: [youngho930/project-hub](https://github.com/youngho930/project-hub)

### 대표 숫자

- **30초** 재고 확인 시간 — 이전 건당 1~2분 ([재고 대시보드](https://project-hub-youngho.vercel.app/projects/inventory-dashboard))
- **8배** 엑셀 취합 속도 — 11분 42초 → 1분 27초 실측 ([엑셀 취합·검증기](https://project-hub-youngho.vercel.app/projects/excel-merger))
- **6개월+** 무보수 운영 — 퇴사 후 유지보수 없이 사용 중 ([재고 대시보드](https://project-hub-youngho.vercel.app/projects/inventory-dashboard))
- **15% → 90%** 자비스 적절 응답 — 한도 대기 14건 → 0건, 같은 20문항·무료 등급 기준 ([자비스](https://project-hub-youngho.vercel.app/projects/jarvis))

### 프로젝트

| 프로젝트 | 설명 | 링크 |
|---|---|---|
| 재고 대시보드 | 이카운트 ERP API와 연동한 사내 재고 조회·BOM 관리·메모 게시판 | [저장소](https://github.com/youngho930/inventory-dashboard) · [사이트](https://shinyoungho.pythonanywhere.com) |
| 엑셀 취합·검증기 | 여러 엑셀 파일을 자동으로 합치고 오류를 검증하는 도구 | [저장소](https://github.com/youngho930/excel-merger) · [사이트](https://excel-merger-youngho.streamlit.app) |
| 자비스 | 음성 호출·웹 검색·일정·채용 검색을 갖춘 개인 AI 비서 (웹·에이전트·호출어) | [소개](https://project-hub-youngho.vercel.app/projects/jarvis) · [사이트](https://jarvis-vercel-gray.vercel.app) |
| 검사 보고·승인 시스템 | 검사 결과를 올리고 품질책임자가 승인하는 결재 웹 시스템 | [저장소](https://github.com/youngho930/qc-report-system) |
| Job Jarvis | 고용24 API로 AI·자동화·품질 관련 공고를 매일 모으고, 마감 7일 안의 미지원 공고를 아침 9시에 메일로 알려주는 채용 알림 프로그램 | [저장소](https://github.com/youngho930/job-jarvis) |
| QC AI 챗봇 (개발 중) | 부족한 부품 재고와 연락할 협력업체를 한 번에 알려주는 AI 챗봇 | [저장소](https://github.com/youngho930/qc-ai-assistant) · [사이트](https://qc-ai-assistant.streamlit.app) |
| Jira 주간보고 자동화 (구상 중) | Jira 이슈를 REST API로 읽어 주간 업무 보고를 자동 생성 | [소개](https://project-hub-youngho.vercel.app/projects/jira-weekly-report) |

### 일하는 방식

- **숫자를 의심한다** — 주간 리포트가 실제 지원 2건을 47건으로 보고하던 오류를, 과거 메일을 같은 공식으로 재현해 원인을 확정하고 고쳤습니다.
- **AI와 코드의 역할을 나눈다** — 모델이 날짜 계산을 자주 틀려, 확실한 계산은 코드가 하고 애매한 판단만 모델에 맡기도록 설계를 바꿨습니다.
- **쓰는 사람 입장에서 바꾼다** — 엑셀은 누구나 수정할 수 있고 매번 다시 배포해야 해서, 재고 확인을 웹페이지로 전환했습니다.

### 주로 쓰는 기술

Python · Gemini API · Streamlit · Upstash Redis · Vercel · Playwright · 이카운트 ERP API

### 연락

이메일은 [포트폴리오 사이트](https://project-hub-youngho.vercel.app) 맨 아래 "이메일 복사" 버튼으로 받을 수 있습니다.
