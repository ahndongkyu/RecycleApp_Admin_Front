# 불쑥 (Bulssuk) - 관리자 페이지 (Admin Panel) 🛠

불쑥 관리자 페이지는 운영자가 분리수거 활동 데이터를 관리하고, 사용자/업체 정보를 효율적으로 운영할 수 있도록 제공되는 전용 플랫폼입니다.  
React 기반으로 구축되었으며, 다양한 환경 정보, 트리 성장, 사용자 포인트 관리 등 기능을 시각화 및 설정할 수 있습니다.

---

## 🔧 주요 기능

- **관리자 대시보드**  
  사용자 수, 나무 성장 현황, 방문 통계 등을 차트로 시각화  
- **사용자 관리**  
  사용자 검색, 상세 정보, 포인트 현황, 쿠폰 발급 등
- **배출일 관리**  
  지역/카테고리 기반 분리수거 일정 관리 및 등록
- **FAQ 및 회사 등록 관리**  
  자주 묻는 질문, 제휴업체 정보 등록
- **쿠폰 시스템**  
  쿠폰 발급, 이력 확인 및 사용자에게 직접 전송
- **트리 성장 기능 설정**  
  이벤트 기반 트리 성장 포인트 관리
- **투표 기능**  
  환경 관련 설문 등록 및 결과 확인

---

## 📁 폴더 구조 요약

```
src/
├── App.js                     # 관리자 라우팅 구성
├── dashboard/
│   ├── Dashboard.js           # 메인 대시보드 화면
│   └── components/
│       ├── user/              # 사용자 관리 기능
│       ├── calendar/          # 분리수거 일정 등록
│       ├── recycle/           # 카테고리/항목 등록
│       ├── company/           # 업체 정보 관리
│       ├── coupon/            # 쿠폰 발급 관리
│       ├── tree/              # 나무 관련 성장 기능
│       ├── faq/               # FAQ 관리
│       └── vote/              # 투표 관리
├── context/                   # 관리자 전역 상태 관리
├── theme/                     # 테마 및 커스터마이징
└── shared-theme/              # 공통 스타일 설정
```

---

## 🧰 사용 기술

- **Frontend**: React.js
- **UI Framework**: Material UI
- **State Management**: Context API
- **Charting**: Recharts
- **Routing**: React Router v6
- **통신 방식**: REST API (불쑥 백엔드와 연동)

---

## ⚙️ 실행 방법

```bash
npm install
npm start
```

---

## 📁 연동 백엔드

- API 연동: [`RecycleApp_back`](https://github.com/ahndongkyu/RecycleApp_back)
- JWT 기반 관리자 인증 방식 사용

---

