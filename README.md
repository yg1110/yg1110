# 👋 안녕하세요, 풀스택 개발자 정영길입니다.

**백엔드 API·데이터 모델부터 화면과 운영까지, 한 제품의 전 구간을 맡습니다.**

## 🚀 About Me

- 🧭 **웹 개발 3년 6개월 (총 경력 5년 3개월)** — WPF에서 시작해 React Native, Next.js를 거쳐 NestJS·PostgreSQL까지 범위를 넓혔습니다.
- 🏭 **멈추면 안 되는 제품을 다룹니다** — 고객사 공장에 설치되어 24시간 무중단으로 도는 산업 검사 장비의 운영 대시보드를 개발·운영합니다. 웹 개발자가 없던 초기 4개월간 단독으로 만들었고, 지금은 2인 체제로 운영하며 온보딩을 맡고 있습니다.
- 🗄️ **운영 DB를 세우지 않고 바꾸는 일** — 점검 창을 잡기 어렵고 고객사마다 환경이 다른 조건에서 스키마 변경과 마이그레이션을 해왔습니다.
- 🔍 **재현되지 않는 장애의 원인을 끝까지 찾습니다** — 증상이 아니라 원인을 치고, 고칠 때는 재발 시 확인할 진단 수단을 함께 배포합니다.
- ✍️ **해결 과정은 글로 남깁니다** — 배경과 검토한 선택지, 그중 무엇을 왜 택했는지까지 정리해 [기술 블로그](https://velog.io/@yg1110)에 공개하고 있습니다.

## 📌 최근 1년

> 각 항목은 그 작업을 정리한 글로 이어집니다.

| | |
| --- | --- |
| 🗃️ **700GB / 12개 테이블** | 무중단 RANGE 파티셔닝 전환 — 공장 가동 중단 0분, 정리 작업 수동 10~30분 → 스케줄러 자동 · [글](https://velog.io/@yg1110/%EB%94%94%EC%8A%A4%ED%81%AC%EA%B0%80-%EA%BD%89-%EC%B0%A8%EC%84%9C-%EB%A9%88%EC%B6%98-%EA%B2%80%EC%82%AC-%EC%9E%A5%EB%B9%84-%EC%82%AD%EC%A0%9C%EB%A5%BC-%EC%97%86%EC%95%A0%EA%B8%B0%EA%B9%8C%EC%A7%80-%EB%8C%80%EC%9A%A9%EB%9F%89-%ED%85%8C%EC%9D%B4%EB%B8%94-%ED%8C%8C%ED%8B%B0%EC%85%94%EB%8B%9D-%EC%82%BD%EC%A7%88%EA%B8%B0) |
| 🐌 **3억 2,804만 행** | 장비 기동을 막던 87초 `COUNT(*)` 추적·제거 → 배포 없이 설정 변경만으로 당일 양산 재개 · [글](https://velog.io/@yg1110/%EB%A1%9C%EA%B7%B8-%ED%95%9C-%EC%A4%84-%EC%B0%8D%EC%9E%90%EA%B3%A0-3%EC%96%B5-%EA%B1%B4%EC%9D%84-%EC%84%B8%EA%B3%A0-%EC%9E%88%EC%97%88%EB%8B%A4-%ED%8C%8C%ED%8B%B0%EC%85%94%EB%8B%9D-%EB%B0%B0%ED%8F%AC-%EB%91%90-%EB%8B%AC-%EB%92%A4%EC%9D%98-%EC%B2%AD%EA%B5%AC%EC%84%9C) |
| 🧯 **112,835건** | 스토리지 용량 사고로 밀린 건 복구 — 검사 결과 전 구간, 이미지 68,990건 · [글](https://velog.io/@yg1110/%EC%8A%A4%ED%86%A0%EB%A6%AC%EC%A7%80%EA%B0%80-%EC%B0%AC-%EB%92%A4-%EB%82%A8%EC%9D%80-11%EB%A7%8C-%EA%B1%B4-%EC%96%B4%EB%94%94%EA%B9%8C%EC%A7%80-%EB%B3%B5%EA%B5%AC%ED%95%A0-%EC%88%98-%EC%9E%88%EC%97%88%EB%82%98) |
| ✅ **E2E 40개** | CI가 없던 프론트엔드에 도입 — 푸시마다 고객사 5곳을 9분 43초에 검증 · [글](https://velog.io/@yg1110/%EB%81%9D%EA%B9%8C%EC%A7%80-%EC%9E%90%EB%8F%99%EC%9D%B8-%EB%B0%B0%ED%8F%AC%EC%97%90-%EA%B2%80%EC%A6%9D-%ED%95%9C-%EC%B9%B8-%EB%84%A3%EA%B8%B0-%EB%AA%A9%EC%9D%84-%EC%93%B0%EC%A7%80-%EC%95%8A%EB%8A%94-E2E) |
| 📦 **150MB → 10.9MB** | Electron 래퍼를 Go/Wails로 재작성 (93% 감소, 단일 exe) · [글](https://velog.io/@yg1110/%EC%9B%B9-%ED%99%94%EB%A9%B4-%ED%95%98%EB%82%98-%EB%9D%84%EC%9A%B0%EC%9E%90%EA%B3%A0-150MB%EB%A5%BC-%EA%B9%94%EA%B3%A0-%EC%9E%88%EC%97%88%EB%8B%A4-Electron-%EB%9E%98%ED%8D%BC%EB%A5%BC-Go%EB%A1%9C-%EA%B0%88%EC%95%84%EC%97%8E%EA%B8%B0) |

## 🛠 Tech Stack

### ⚙️ Backend & Data

<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=TypeScript&logoColor=white"> <img src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=NestJS&logoColor=white"> <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=Node.js&logoColor=white"> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=PostgreSQL&logoColor=white"> <img src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=Prisma&logoColor=white"> <img src="https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=Redis&logoColor=white">

### 💻 Frontend

<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=React&logoColor=black"> <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=Next.js&logoColor=white"> <img src="https://img.shields.io/badge/React%20Native-61DAFB?style=flat-square&logo=React&logoColor=black"> <img src="https://img.shields.io/badge/TanStack%20Query-FF4154?style=flat-square&logo=React%20Query&logoColor=white"> <img src="https://img.shields.io/badge/Zustand-443E38?style=flat-square&logo=React&logoColor=white"> <img src="https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=Tailwind%20CSS&logoColor=white"> <img src="https://img.shields.io/badge/Storybook-FF4785?style=flat-square&logo=Storybook&logoColor=white"> <img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=Playwright&logoColor=white">

### ☸️ Infra & Tools

<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=Docker&logoColor=white"> <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=Kubernetes&logoColor=white"> <img src="https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=Helm&logoColor=white"> <img src="https://img.shields.io/badge/Argo%20CD-EF7B4D?style=flat-square&logo=Argo&logoColor=white"> <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=Git&logoColor=white"> <img src="https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=Claude&logoColor=white">

### 🧪 Etc

<img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=Go&logoColor=white"> <img src="https://img.shields.io/badge/Wails-DF0000?style=flat-square&logo=Go&logoColor=white"> <img src="https://img.shields.io/badge/WPF%20%2F%20C%23-512BD4?style=flat-square&logo=C+Sharp&logoColor=white">

## 🔗 Links

[![Portfolio](https://img.shields.io/badge/Portfolio-222222?style=flat-square&logo=GitHub%20Pages&logoColor=white)](https://yg1110.github.io/resume)
[![Blog](https://img.shields.io/badge/Blog-20C997?style=flat-square&logo=Velog&logoColor=white)](https://velog.io/@yg1110)
[![Email](https://img.shields.io/badge/younggil94@naver.com-03C75A?style=flat-square&logo=Naver&logoColor=white)](mailto:younggil94@naver.com)
