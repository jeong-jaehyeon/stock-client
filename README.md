# 📈 Stock Portfolio Client

주식 포트폴리오 관리 서비스의 프론트엔드입니다.  
[stock-server](https://github.com/jeong-jaehyeon/stock-server)와 연동하여 실시간 주가 조회 및 포트폴리오 관리 기능을 제공합니다.

## 🛠 Tech Stack

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

## 📌 주요 기능

- **로그인 / 회원가입** — JWT 기반 인증
- **포트폴리오 조회** — 보유 종목, 평균 매수가, 현재가, 수익률 확인
- **포트폴리오 상세** — 종목별 매수/매도 내역 확인
- **주식 매수/매도** — Twelve Data API 기반 실시간 주가 반영
- **거래 내역** — 전체 매수/매도 히스토리 조회

## 📁 프로젝트 구조

```
src/
├── api/          # axios 기반 API 호출 (auth, portfolio, stocks, history)
├── pages/        # 페이지 컴포넌트 (Login, SignUp, Portfolio, Detail, TradeHistory)
├── routes/       # 라우팅 설정
└── utils/        # 공통 유틸
```

## 🚀 시작하기

```bash
yarn install
yarn dev
```

> 백엔드 서버([stock-server](https://github.com/jeong-jaehyeon/stock-server))가 먼저 실행되어 있어야 합니다.

