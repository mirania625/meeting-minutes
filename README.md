# 🎙️ MeetAI - 스마트 AI 회의 비서 (Serverless Standalone App)

> **서버 설치 0개!** 스마트폰 단독으로 음성을 녹음하고, Google Gemini AI로 **화자 분리, 3줄 핵심 요약, 결정 사항, 담당자별 실행 과제(Action Items)**를 자동 추출 및 분류해주는 스마트 회의록 웹앱(PWA)입니다.

---

## ✨ 주요 기능
* 📱 **서버 없는 독립형 (Serverless)**: 스마트폰과 Google Gemini AI가 직접 HTTPS로 통신 (PC 불필요)
* 🎙️ **실시간 녹음 & 파형 시각화**: 고음질 녹음 및 실시간 Audio Waveform 렌더링
* 📍 **실시간 중요 마킹**: 회의 중 중요 발언 시 타임스탬프 북마크 기록
* 📋 **3개 탭 회의록 뷰**:
  - **핵심 요약**: 3줄 요약 + 주요 결정 사항 (Key Decisions)
  - **할 일 (Action Items)**: `[담당자] - [할 일] - [기한]` 체크박스 인터랙션 (완료 상태 로컬 저장)
  - **대화록 (Transcript)**: 발화자별 시간대 스크립트
* 🏷️ **카테고리 자동 분류 & 태깅**: 스프린트, 고객 미팅, 기획/아이디어, 1:1 면담, 일반 회의 등
* 📑 **원클릭 마크다운 복사**: Notion, Slack, 이메일로 바로 붙여넣기 지원
* 🔒 **보안 & 프라이버시**: API 키와 회의 데이터는 외부 서버를 거치지 않고 오직 내 스마트폰 로컬 저장소(LocalStorage)에만 안전하게 보관됩니다.

---

## 🚀 GitHub Pages로 1분 만에 무료 배포하기

1. GitHub에서 **새 레포지토리(New Repository)**를 생성합니다. (예: `meet-ai`)
2. 이 폴더의 파일들(`index.html`, `manifest.json`, `sw.js`, `README.md`)을 업로드합니다.
3. 레포지토리 상단 **[Settings]** 탭으로 이동합니다.
4. 좌측 메뉴에서 **[Pages]** 클릭:
   - **Build and deployment > Source**: `Deploy from a branch` 선택
   - **Branch**: `main` (또는 `master`), 폴더 `/ (root)` 선택 후 **[Save]** 클릭
5. 약 1분 후 생성되는 URL(예: `https://[깃허브아이디].github.io/meet-ai/`)로 접속합니다.

---

## 📱 스마트폰에 정식 앱(PWA)으로 설치하는 방법

1. 스마트폰 **Chrome(안드로이드)** 또는 **Safari(아이폰)** 브라우저로 배포된 GitHub Pages 주소에 접속합니다.
2. 우측 상단 `⋮ (메뉴)` → **`[홈 화면에 추가]`** 또는 **`[앱 설치]`** 터치
3. 스마트폰 홈 화면에 생성된 **MeetAI 아이콘**을 누르면 일반 안드로이드 앱과 똑같이 전체화면으로 실행됩니다!
4. 첫 실행 시 우측 상단 ⚙️ 설정에서 **Google Gemini API Key**를 1회만 등록해 두시면 이후 영구적으로 무료 사용이 가능합니다.

---

## 📄 라이선스
MIT License
