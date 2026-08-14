# 👋 My Portfolio

Frontend Developer & AI Service Builder

<p>
  <img src="https://img.shields.io/badge/Frontend-React-61DAFB?style=flat-square&logo=React&logoColor=black">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=TypeScript&logoColor=white">
  <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=Vite&logoColor=white">
  <img src="https://img.shields.io/badge/Student-Chungbuk National University-orange?style=flat-square">
</p>

---

# 🙋‍♀️ About Me

- 🎓 **소속** : 충북대학교 소프트웨어학부 인공지능전공 (3학년 / 2024042083 류민지)
- 💻 **Position** : Frontend Developer
- ⚡ **Main Stack** : React · TypeScript · Vite · Tailwind CSS
- 🎨 **Focus** : 사용자 중심 UI/UX 구현 & 반응형 인터페이스 설계
- 🤖 **Interest** : 생성형 AI 기반 서비스 프론트엔드 연동 및 프로토타이핑

---

# 📂 Projects

## 📅 2025

### 🏛 ACT:ON - 국민 참여형 법안 피드백 대시보드

> **"국회 공공 API 데이터를 직관적으로 시각화하여 시민들의 찬반 투표와 실시간 토론을 이끄는 양방향 디지털 민주주의 플랫폼"**

* **진행 기간** : 2025.03 ~ 2025.06 (충북대학교 오픈소스 기초 프로젝트, 2인 팀)
* **담당 역할** : **Full-stack & UI/UX Design** (기획, Figma 프로토타입, DB 설계, 프론트엔드/백엔드 연동)
* **주요 기여 & 구현** :
  - **공공 API 비동기 파싱** : `useEffect`와 `useParams`를 활용한 국회 의안 목록 및 상세 조회 동적 렌더링
  - **투표 및 토론 인터랙션** : 실시간 찬반 투표 퍼센티지 게이지 바 업데이트 로직 및 토론방 CRUD 구현
  - **위기 극복 및 100% 완수** : 팀원 중도 이탈 상황에서 2인 체제로 역할을 재조정하여 기획된 모든 기능과 DB 연동 누락 없이 배포 완료
* **Tech Stack** : `React`, `Python FastAPI`, `Django`, `SQLite`, `ERDCloud`, `Figma`
* 🔗 [GitHub Repository](https://github.com/lgh04/MGP)

---

### ⚽ We Play - 스포츠 커뮤니티 웹 서비스

> **"KBO 경기 일정 조회, 실시간 응원 채팅, 커뮤니티를 한 곳에서 즐기는 올인원 스포츠 팬 플랫폼"**

* **진행 기간** : 2025.09 ~ 2025.12 (충북대학교 오픈소스 개발 프로젝트, 4인 팀)
* **담당 역할** : **Frontend Lead** (React 컴포넌트 아키텍처 및 실시간 인터랙션 전담)
* **주요 기여 & 구현** :
  - **실시간 채팅 연동** : Socket.io 기반 실시간 양방향 응원 채팅방 UI 구현 및 지연 없는 메시지 렌더링
  - **계층형 트리 구조 댓글** : `parent_id` 기반 데이터를 가공하여 대댓글 재귀 컴포넌트 렌더링 구현
  - **경기 일정 대시보드** : TheSportsDB API 연동 및 새로고침 없는 React 상태(useState) 기반 날짜/구단별 실시간 필터링 구축
  - **인증 및 이미지 연동** : `localStorage` 기반 자동 로그인 세션 유지 및 Multer 기반 프로필/게시글 이미지 업로드 처리
* **Tech Stack** : `React`, `JavaScript (ES6+)`, `Node.js`, `Express`, `Socket.io`, `Railway MySQL`, `Cloudflare Pages`
* 🔗 [GitHub Repository](https://github.com/ikikiik/open-source-06)

---

## 📅 2026

### 🎵 똑똑 (TokTok) - 시니어 AI 생애여정 음악 지도 서비스 (진행중)

> **"주야간보호센터 어르신의 10분 회상 대화를 AI 맞춤형 노래로 제작하고, 공단 평가용 일지 패키지를 자동 완성하는 주야간보호 전용 B2B SaaS"**[cite: 4, 8]

* **진행 기간** : 2026.07 ~ 2026.08 (멋쟁이사자처럼 14기 중앙 해커톤)[cite: 1, 4]
* **담당 역할** : **Frontend Lead** (UI/UX 설계 및 화면 전체 구현)[cite: 5, 8]
* **주요 기여 & 구현** :
  - **시니어 맞춤형 인터랙션** : 인지 상태별 3단계 질문 흐름 UI 및 대화형 녹음 화면 구현[cite: 5]
  - **AI 데이터 검수 & 오디오 플레이어** : STT 전사 텍스트 오타 교정 UI, 장르별 AI 작곡 프로그레스 시각화 및 버전별 음원 미리듣기 플레이어 개발[cite: 2, 5, 6]
  - **대형 자막 노래방 & 일지 자동화** : 시설 TV 연동용 대형 자막 뷰 및 관찰 반응 태그 기반 일지 자동 렌더링/내보내기 구축[cite: 5, 6, 8]
  - **컴플라이언스 방어 로직** : 5종 분리 동의 UI 및 출처 미확인 데이터 가사 차단 상태 제어 로직 적용[cite: 2, 5]
* **Tech Stack** : `React`, `TypeScript`, `Vite`, `Tailwind CSS`, `Supabase`, `Figma`[cite: 2, 8, 10]
*🔗 [GitHub Repository](https://github.com/TokTok-lion/TokTok)
---

# 🏆 Awards & Activities

## 📅 2025

* **[2025.03 ~ 2025.06] 충북대학교 오픈소스 기초 프로젝트**
  - 국민 참여형 법안 피드백 대시보드 **"ACT:ON"** 풀스택 개발 및 기획/설계 완료
* **[2025.09 ~ 2025.12] 충북대학교 오픈소스 개발 프로젝트**
  - 스포츠 팬 올인원 커뮤니티 플랫폼 **"We Play"** 프론트엔드 리드 개발 및 Cloudflare Pages 배포

## 📅 2026

* **[2026.03 ~ 현재] 멋쟁이사자처럼 충북대학교 14기 (프론트엔드 트랙)**
  - 프론트엔드 정기 기술 세션 수료 (Git 브랜치 전략, React Hooks, TypeScript, Tailwind CSS, JWT 인증, Vercel 배포) [🔗 Repo](https://github.com/CBNU-likelion/2026_14th_final_study_FE)
  - **[2026.05] 멋쟁이사자처럼 14기 중앙 아이디어톤** : AI 서비스 기획 및 프론트엔드 프로토타입 구현 [🔗 Repo](https://github.com/CBNU-likelion/ideathon-4th-frontend)
  - **[2026.07 ~ 2026.08] 멋쟁이사자처럼 14기 중앙 해커톤** : '똑똑(TokTok)' 프론트엔드 리드 개발 (진행중)[cite: 1, 4, 8]
* **[2026.07 ~ 2026.08] 코멘토(Comento) 프론트엔드 직무 부트캠프 (수료)**[cite: 15]
  - 현직자 1:1 코드 리뷰 4회 수행 (BEM 네이밍, CSS 아키텍처, Vanilla JS 기반 계산기/시계/To-Do List/회원가입 폼 구축)[cite: 11, 12, 13, 16, 17, 20]
  - 인라인 이벤트의 `addEventListener` 분리, `textContent` 기반 DOM XSS 방어, 상태(State)와 뷰(UI)의 책임 분리(SRP) 체화[cite: 14, 16, 17, 19]
* **[2026.07 ~ 2026.08] 충북대학교 2026 직무(기업)분석 경진대회**[cite: 29]
  - 토스증권(Toss Securities) Server Developer 3원 조직(Product·Platform·Market Platform) 및 대규모 금융 트랜잭션 아키텍처 분석[cite: 30, 31, 33]
  - 30명 규모 IT 동아리 이식을 위한 'Problem-to-Product' 14주 실전 스프린트 및 Game Day 장애 대응 프레임워크 설계[cite: 30, 31, 34]
* **[2026.07 ~ 2026.08] 충북대학교 AI-Tutor 학습 플러스 (수료 및 장학금 수혜)**[cite: 28]
  - 6주간 대화형 AI 시스템을 활용한 코드 트레이싱(Tracing) 및 자바 OOP(다형성, 인터페이스, 제네릭, 컬렉션)와 프론트엔드 상태/타입 매핑 집중 학습[cite: 22, 23, 24, 25, 28]
* **[2026.07] 오라클 사업단 3주 몰입형 AI 부트캠프 (수료)**
  - Python/Pandas 기반 음원 특성 결측치(Median) 정제, 빌보드 데이터 2D 밀도 히트맵 시각화 및 Scikit-learn Random Forest 앙상블 분류 파이프라인 실습[cite: 21]

---

# 🛠 Tech Stack

## Frontend

<p>
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=React&logoColor=black">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=TypeScript&logoColor=white">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=black">
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=Vite&logoColor=white">
  <img src="https://img.shields.io/badge/Tailwind CSS-06B6D4?style=for-the-badge&logo=TailwindCSS&logoColor=white">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=HTML5&logoColor=white">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=CSS3&logoColor=white">
</p>

## Backend & Collaboration

<p>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=FastAPI&logoColor=white">
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=Node.js&logoColor=white">
  <img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=Express&logoColor=white">
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white">
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=Supabase&logoColor=white">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=Git&logoColor=white">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white">
  <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=Figma&logoColor=white">
</p>

---

# 📬 Contact & Link

- 📧 **Email** : [rm3319@chungbuk.ac.kr](mailto:rm3319@chungbuk.ac.kr)
- 📝 **Velog** : https://velog.io/@_minnlux/posts
- 🐙 **GitHub** : https://github.com/ryu-min-ji
