<h1 align="center">안녕하세요</h1>

<p align="center">
  사용자가 체감하는 속도와 끊김 없는 경험을 만드는 데 집중하는 프론트엔드 개발자입니다.<br/>
  코드 퀄리티 및 설계 방식이 최선이 맞는가 재검증하고 최적화하는 일, 그리고 측정 가능한 성능 개선을 좋아합니다.<br/>
  React와 Svelte를 오가며 교육 플랫폼과 맛집 추천 서비스를 실무에서 개발했고,<br/>
  기획 단계부터 참여해 요구사항 정의와 화면 설계에도 의견을 내는 것을 즐깁니다.
</p>

<p align="center">
  <a href="https://leesj.vercel.app/">
    <img src="https://img.shields.io/badge/Portfolio-Visit_Site-000000?style=flat-square&logo=vercel&logoColor=white" alt="Portfolio"/>
  </a>
  <a href="mailto:hensin12@gmail.com">
    <img src="https://img.shields.io/badge/Email-hensin12@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://github.com/leesj3857">
    <img src="https://img.shields.io/badge/GitHub-leesj3857-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub"/>
  </a>
</p>

<p align="center">
  🔗 <strong>Portfolio</strong> — <a href="https://leesj.vercel.app/">leesj.vercel.app</a>
</p>

---

### 🛠 Tech Stack

**Frameworks**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Svelte](https://img.shields.io/badge/Svelte-FF3E00?style=for-the-badge&logo=svelte&logoColor=white)

**Language**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**State & Data**

![Redux](https://img.shields.io/badge/Redux-764ABC?style=for-the-badge&logo=redux&logoColor=white)
![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=for-the-badge&logo=reactquery&logoColor=white)
![Axios](https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white)

**Styling & Motion**

![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=for-the-badge&logo=framer&logoColor=white)

**Tooling**

![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Chrome DevTools](https://img.shields.io/badge/Chrome_DevTools-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white)
![pnpm](https://img.shields.io/badge/pnpm-F69220?style=for-the-badge&logo=pnpm&logoColor=white)

---

### 🎓 Background

- **학력** — 고려대학교 정보대학 컴퓨터학과 (서울) · `2021.03 – 2027.02 (졸업 예정)`
- **병역** — 육군 병장 만기전역 · `2022.04 – 2023.10`
- **자격증** — 정보처리기사 · ADsP
- **어학** — OPIc `IH`

---

### 💼 Experience

**(주)어떤사람들** — 프론트엔드 개발 · 인턴 · `2026.03 – 2026.08`
> 맛집 추천 서비스 **뽈레**의 사용자 웹과 사내 관리자 페이지를 전면 리뉴얼·신규 구축
> - 노후화된 레거시 환경을 걷어내고 **Svelte 5 + SvelteKit + TypeScript** 기반으로 사용자 웹과 사내 어드민 두 축을 동시에 재구축
> - 무한스크롤 피드에 **페이지 단위 가상 스크롤**을 직접 설계·도입해 메모리 상한 확보 — 200장 스크롤 기준 DOM 노드 `21,248 → 4,400`(**-79%**), 이미지 캐시 `498MB → 189MB`(**-62%**), JS 힙 `30.3MB → 10.5MB`(**-65%**)
> - 서버 상태 캐시를 **정규화 엔티티 스토어**로 재설계 — 갱신 비용을 O(1)로 낮추고 낙관적 갱신·참조 유지 적용. 좋아요·팔로우 1회 기준 응답 처리 `17.7ms → 0.66ms`, 클릭 후 화면 반영 `약 26ms → 11ms`
> - 반복 UI와 공통 로직을 재사용 단위로 추상화 — 복잡한 렌더링·상태 관리 로직을 컴포넌트 내부에 감추는 인터페이스 설계
> - 관리자 페이지는 개발을 완료해 기존 시스템을 대체하고 현재 실제 운영 중, 사용자 웹은 퇴사 시점까지 핵심 화면 설계와 주요 기능 구현 마무리
> - **기획에 일부 참여**하여 요구사항 정의·화면 설계에 의견 제시
>
> `Svelte 5` `SvelteKit` `TypeScript` `TanStack Query` `Tailwind CSS`

**(주)스마트앤와이즈** — 프론트엔드 개발 · 인턴 · `2024.07 – 2025.02`
> 교육용 학습 플랫폼의 프론트엔드 웹 개발
> - 홈페이지, 교사용 콘텐츠 제작 도구, 학생용 웹 시뮬레이션, 대시보드 등 핵심 기능 구현
> - 서버 데이터와 클라이언트 상태가 Redux에 혼재된 구조를 **TanStack Query 도입으로 분리**. 라이브러리 선정과 도입을 직접 제안해 서버 상태 관리 코드의 유지보수성을 개선
>
> `React` `JavaScript`

---

### 🚀 Projects

| 프로젝트 | 구분 | 시기 | 핵심 |
|---|---|---|---|
| [**KOREAT**](https://github.com/leesj3857/2025-NE-XT-FE) | 소프트웨어 경진대회 | `2025.05` | 🏆 **장려상** · 방한 외국인 맛집·볼거리 가이드 · 지도 마커 시각화, 다국어 번역, 리뷰·별점·북마크 |
| [**어디GO**](https://github.com/leesj3857/eodi-go-meeting-place) | 학회 프로젝트 · 개발 중단 | `2025 상반기` | 참여자 위치 기반 공평한 중간 지점 추천 · 평균 소요시간·이동시간 편차 시각화 |
| [**나의 조각집**](https://github.com/leesj3857/INTHON_Team9_FE) | 해커톤 (INTHON) | `2024.11` | 🏆 **장려상** · 감정을 잇는 조각글 매칭 · 매칭 → 답장 교환 → 예술작품 추천 |

> 🏆 **수상**
> - **KOREAT** — 고려대학교 정보대학 소프트웨어 경진대회 **장려상** (2025.05)
> - **나의 조각집** — 고려대학교 정보대학 해커톤 (INTHON) **장려상** (2024.11)
>
> 세 프로젝트 모두 **기획부터 개발까지 전 과정**에 프론트엔드로 참여했습니다.

---

### 🌿 Open Source

**[toss/overlay-kit](https://github.com/toss/overlay-kit)** · [PR #152](https://github.com/toss/overlay-kit/pull/152) `Merged ✅` · `2025.06`
> docs: Add useCurrentOverlay, useOverlayData document (+556 lines, Fixes #34)
> - 오버레이 상태 접근 훅 `useCurrentOverlay`·`useOverlayData`의 한국어 공식 가이드 문서 신규 작성
> - Material UI 다이얼로그 기반 실제 사용 예제 제공 및 오버레이 메타데이터(`id`, `componentKey`, `isOpen`, `controller`) 정리
> - `close`와 `unmount` 동작 차이를 명확히 문서화
