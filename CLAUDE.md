# Workspace: play-ground

## 워크스페이스 규칙

- 모든 문서 산출물은 반드시 wiki/ 하위에만 작성한다
- wiki/ 내 기존 파일은 수정하지 않는다 (append-only)
- 작업 중 발견한 프로젝트 지식은 wiki/knowledge/에 기록한다

## 파이프라인 커맨드

| 커맨드 | 설명 |
|--------|------|
| /add-req | 신규 요구사항을 wiki/requirements/에 등록한다 |
| /explain | 요구사항 구현 방향을 사용자와 대화로 결정한다 |
| /teams | Dev 사이클 파이프라인 실행: REQ → PRD → SDD → Mockup → Tests → TDD → Deploy → Wiki Views |
| /add-bug | 신규 버그를 wiki/bugs/README.md에 등록한다 |
| /bugfix-teams | Bug 사이클 파이프라인 실행: Bugfix → SDD → Tests → TDD → Deploy → Wiki Views |

## 사용 가능한 스킬

| 스킬 | 설명 |
|------|------|
| req-manage | 요구사항 정의 및 PRD 작성. /teams 파이프라인의 Step 1. |
| dev-design | 개발 설계서(SDD) 작성. /teams Step 2, /bugfix-teams Step 2. |
| ui-mockup | SDD UI 설계 기반 HTML 목업 생성. /teams Step 2.5. |
| test-design | 테스트 설계서 작성. /teams Step 3, /bugfix-teams Step 3. |
| tdd-cycle | TDD(Red-Green-Refactor) 사이클 구현. /teams Step 4, /bugfix-teams Step 4. |
| deploy | 빌드, 검증, 배포. /teams Step 5, /bugfix-teams Step 5. |
| bugfix | 버그 원인 분석 및 수정 보고서 작성. /bugfix-teams Step 1. |
| project-knowledge | 프로젝트 지식 기록. /teams Step 7, /bugfix-teams Step 7. |
| wiki-views | wiki/views/index.html 사이클 기반 뷰어 갱신. /teams Step 6, /bugfix-teams Step 6. |
