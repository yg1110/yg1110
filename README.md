# 👋 안녕하세요, 풀스택 개발자 정영길입니다.

**백엔드 API·데이터 모델부터 화면과 운영까지, 한 제품의 전 구간을 맡습니다.**

## 🚀 About Me

- 🧭 **웹 개발 3년 6개월 (총 경력 5년 3개월)** — WPF에서 시작해 React Native, Next.js를 거쳐 NestJS·PostgreSQL까지 범위를 넓혔습니다.
- 🏭 **멈추면 안 되는 제품을 다룹니다** — 고객사 공장에 설치되어 24시간 무중단으로 도는 산업 검사 장비의 운영 대시보드를 개발·운영합니다. 웹 개발자가 없던 초기 4개월간 단독으로 만들었고, 지금은 2인 체제로 운영하며 온보딩을 맡고 있습니다.
- 🗄️ **운영 DB를 세우지 않고 바꾸는 일** — 점검 창을 잡기 어렵고 고객사마다 환경이 다른 조건에서 스키마 변경과 마이그레이션을 해왔습니다.
- 🔍 **재현되지 않는 장애의 원인을 끝까지 찾습니다** — 증상이 아니라 원인을 치고, 고칠 때는 재발 시 확인할 진단 수단을 함께 배포합니다.
- ✍️ **해결 과정은 글로 남깁니다** — 배경과 검토한 선택지, 그중 무엇을 왜 택했는지까지 정리해 [기술 블로그](https://velog.io/@yg1110)에 공개하고 있습니다.

## 📌 최근 1년

| | |
| --- | --- |
| 🗃️ **700GB / 12개 테이블** | 무중단 RANGE 파티셔닝 전환 — 공장 가동 중단 0분, 정리 작업 수동 10~30분 → 스케줄러 자동 |
| 🐌 **3억 2,804만 행** | 장비 기동을 막던 87초 `COUNT(*)` 추적·제거 → 배포 없이 설정 변경만으로 당일 양산 재개 |
| ✅ **E2E 40개** | CI가 없던 프론트엔드에 도입 — 푸시마다 고객사 5곳을 9분 43초에 검증 |
| 📦 **150MB → 10.9MB** | Electron 래퍼를 Go/Wails로 재작성 (93% 감소, 단일 exe) |

## 🛠 Tech Stack

### ⚙️ Backend & Data

<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=TypeScript&logoColor=white"> <img src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=NestJS&logoColor=white"> <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=Node.js&logoColor=white"> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=PostgreSQL&logoColor=white"> <img src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=Prisma&logoColor=white"> <img src="https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=Redis&logoColor=white">

### 💻 Frontend

<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=React&logoColor=black"> <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=Next.js&logoColor=white"> <img src="https://img.shields.io/badge/React%20Native-61DAFB?style=flat-square&logo=React&logoColor=black"> <img src="https://img.shields.io/badge/TanStack%20Query-FF4154?style=flat-square&logo=React%20Query&logoColor=white"> <img src="https://img.shields.io/badge/Zustand-443E38?style=flat-square&logo=React&logoColor=white"> <img src="https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=Tailwind%20CSS&logoColor=white"> <img src="https://img.shields.io/badge/Storybook-FF4785?style=flat-square&logo=Storybook&logoColor=white"> <img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=Playwright&logoColor=white">

### ☸️ Infra & Tools

<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=Docker&logoColor=white"> <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=Kubernetes&logoColor=white"> <img src="https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=Helm&logoColor=white"> <img src="https://img.shields.io/badge/Argo%20CD-EF7B4D?style=flat-square&logo=Argo&logoColor=white"> <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=Git&logoColor=white"> <img src="https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=Claude&logoColor=white">

### 🧪 Etc

<img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=Go&logoColor=white"> <img src="https://img.shields.io/badge/Wails-DF0000?style=flat-square&logo=Go&logoColor=white"> <img src="https://img.shields.io/badge/WPF%20%2F%20C%23-512BD4?style=flat-square&logo=C+Sharp&logoColor=white">

## 📝 자주 읽히는 글

- [디스크가 꽉 차서 멈춘 검사 장비, 삭제를 없애기까지 — 대용량 테이블 파티셔닝 삽질기](https://velog.io/@yg1110)
- [파티션 정리가 부팅을 막았다 — 로그 한 줄을 위한 COUNT(\*) 3억 건](https://velog.io/@yg1110)
- [연결은 살아있는데 데이터가 안 온다 — 새로고침해야만 복구되던 SSE 고치기](https://velog.io/@yg1110)
- [끝까지 자동인 배포에 검증 한 칸 넣기 — 목을 쓰지 않는 E2E](https://velog.io/@yg1110)

## 🔗 Links

[![Portfolio](https://img.shields.io/badge/Portfolio-222222?style=flat-square&logo=GitHub%20Pages&logoColor=white)](https://yg1110.github.io/resume)
[![Blog](https://img.shields.io/badge/Blog-20C997?style=flat-square&logo=Velog&logoColor=white)](https://velog.io/@yg1110)
[![Email](https://img.shields.io/badge/younggil94@naver.com-03C75A?style=flat-square&logo=Naver&logoColor=white)](mailto:younggil94@naver.com)
