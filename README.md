# 안녕하세요, 프론트엔드 개발자 황순환입니다 👋

**복잡한 기능을, 쉽게 쓰는 화면으로 만듭니다.**

React · Next.js · TypeScript를 중심으로 제품을 개발하는 **6년차 프론트엔드 개발자**입니다. (2021.03 첫 입사)
React 편집 도구와 공통 UI를 설계하고, Next.js(Pages Router · SSR/SSG) 웹 서비스를 개발·운영했습니다.
웹뿐 아니라 iOS·LG TV 앱을 개발하고 출시한 경험도 있습니다.

**[포트폴리오](https://harry1757.vercel.app)** · **[이력서 PDF](https://harry1757.vercel.app/resume.pdf)** · **[메일 보내기](mailto:hsw9724@gmail.com)**

## 주로 이런 일을 합니다

- **복잡한 편집 흐름 설계** — 이미지 조작, 실행 취소, 자동 저장과 충돌·실패 처리를 연결합니다.
- **공통 UI와 개발 기준 정리** — 컴포넌트·타입·스타일을 공통화하고 여러 앱에 적용합니다.
- **실제 사용 흐름 검증** — 단위 테스트, 브라우저 테스트, 팀원의 실제 제작 과정으로 결과를 확인합니다.

## 경력

| 회사 | 기간 | 주요 경험 |
| --- | --- | --- |
| **바로인터랙티브** | 2026.08–현재 | BAROS 2.0 에디터 프론트엔드 전담 · 공통 UI 패키지 설계·3개 앱 적용 |
| **Clesson** | 2022.05–2026.02 | 음악·콘텐츠 서비스 웹 공동 개발 · Tracks iOS·webOS 개발·출시 · SignAil iOS 단독 개발 |
| **테스트웍스** | 2021.03–2022.05 | AI 학습 데이터 플랫폼 Aiworks · PHP 화면의 Next.js 재구현·공통 모듈 개발 |

### 최근 작업: BAROS 2.0 · Landing Studio

출시 전·사내 제품의 에디터 프론트엔드를 맡아 **이미지 조작·실행 취소 묶음·설정 구조**를 직접 설계했습니다.

- 드래그 중에는 CSS 변수와 미리보기만 갱신하고, 손을 떼면 문서에 한 번 반영합니다. 동일한 포인터 이동 60회를 전후 코드에 재생해 **문서 쓰기 116회 → 1회**를 확인했습니다.
- 서버 초안·편집 잠금·자동 저장을 연결하고, 버전(ETag) 충돌이나 저장 실패 시 편집 내용을 보존합니다.
- **Vitest 29개는 CI**, **Playwright 검증 스크립트 70여 개는 로컬**에서 실행해 조작·저장·복구 흐름을 확인합니다.

BAROS는 사내 비공개 제품으로, 화면과 소스 대신 [포트폴리오에 설계 판단과 검증 방법](https://harry1757.vercel.app/#career-company-0)을 정리했습니다.

### 함께 만든 서비스

| 서비스 | 제가 맡은 부분 | 당시 공식 자료 |
| --- | --- | --- |
| **Tracks** | 웹 지갑 공동 개발 · iOS 재생·TV 리모컨 탐색 · 앱 출시 대응 | [iOS 소개](https://m.blog.naver.com/PostView.naver?blogId=labelfoundation&logNo=223148538280) · [webOS 소개](https://m.blog.naver.com/PostView.naver?blogId=labelfoundation&logNo=223333614038) |
| **Haio** | 출금 대기·완료·실패 상태 처리 · Live 지연 로딩 · 브라우저 영상 합성 프로토타입 | [서비스 소개](https://medium.com/haio-music/introducing-channel-creation-playlist-curation-on-haio-4487c09c9546) |
| **Sonic AI** | 웹 공동 개발 · 음악 생성 요청·오디오 조작·발행 UI | [공식 소개](https://m.blog.naver.com/PostView.naver?blogId=labelfoundation&logNo=223656038975) |
| **SignAil** | iOS 단독 개발 · 음성 녹음·전송·번역 메시지·대화 이력 병합 | [iOS 소개](https://m.blog.naver.com/PostView.naver?blogId=labelfoundation&logNo=223502561485) |

## 직접 만든 도구들

| 프로젝트 | 한 줄 소개 | 확인하기 |
| --- | --- | --- |
| **Agent Messenger** | 팀원의 에이전트에게 자료를 묻고 답을 받는 팀 메신저. 팀에서 실제 사용 중 | [공개 소스](https://github.com/Harry1757/agent-messenger-public) · [설명](https://harry1757.vercel.app/#personal-project-0) |
| **뭐해먹지? 뚝딱!** | 냉장고 사진의 재료 인식 → 레시피 추천 → 장보기. iOS 앱과 API 서버를 개발해 App Store 출시 | [App Store](https://apps.apple.com/app/id6769651796) · [설명](https://harry1757.vercel.app/#personal-project-3) |
| **AgentTown** | AI 코딩 세션의 작업·응답 대기를 도트 마을로 표시하고 아케이드 대결을 더한 데스크톱 도구 | [GitHub](https://github.com/Harry1757/agenttown) · [설명](https://harry1757.vercel.app/#personal-project-1) |
| **WindowShade · 창 가리개** | 창의 필요한 영역만 가리고 창 이동을 따라가는 macOS 앱. 얼굴·손동작 감지는 실험 기능 | [GitHub](https://github.com/Harry1757/windowshade) · [설명](https://harry1757.vercel.app/#personal-project-2) |

## 주력 기술

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![SwiftUI](https://img.shields.io/badge/SwiftUI-0D84F3?style=flat-square&logo=swift&logoColor=white)

- **웹** — React · Next.js · TypeScript · JavaScript
- **공통 UI** — Tailwind CSS · Radix UI
- **상태·데이터** — TanStack Query · Zustand · Recoil · Redux-Saga
- **테스트·개발 환경** — Vitest · Playwright · Jest · ESLint · Vite · pnpm workspace
- **앱** — Swift · SwiftUI · AVFoundation · Combine · webOS/Enact

## AI와 일하는 방식

Codex·Claude Code를 활용합니다. 작업 전에 요구사항과 완료 기준을 정리하고, 반복 구현을 맡긴 뒤 **코드 리뷰·자동화 테스트·실제 사용**으로 확인합니다.
에이전트 간 자료 조회와 질문·응답을 연결하는 실험은 Agent Messenger로 이어가고 있습니다.

더 자세한 구현 경험과 검증 근거는 [포트폴리오](https://harry1757.vercel.app)에서 확인할 수 있습니다.
