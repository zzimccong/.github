# 🗓️ Zzimccong Plan - 찜꽁플랜
![image](https://github.com/user-attachments/assets/b087b565-9df9-49ab-b8a1-3afde271f159)
> 음식점 예약, 추첨 이벤트, 회식 문서화까지 모두 가능한 올인원 예약 서비스

## 🔗 관련 문서 / 프로젝트 링크

- 📘 [팀 노션 페이지](https://equinox-gull-ade.notion.site/10fdc25e4b1680f0acd5f4bf86ab49f3?v=10fdc25e4b1681a2aa36000cae291731)
- 📑 [API 명세서](https://www.notion.so/API-10fdc25e4b16814badabd4224eb974b0)
- 🧭 [트러블 슈팅](https://www.notion.so/10fdc25e4b1681d4816dffdcd49f083d)
- 🗺️ [ERD 설계 (ERDCloud)](https://www.erdcloud.com/d/XddgJ9nNpakHRkAdG)
- 🎨 [피그마 프로토타입](https://www.figma.com/design/8MGTwmpq17Pdjn7Lja1NVp/%EC%B0%9C%EA%BD%81%ED%85%8C%EC%9D%B4%EB%B8%94?node-id=0-1&p=f&t=ZQ8AfYLbbnsWBX3N-0)

---

## 🔎 프로젝트 개요

| 항목       | 내용                                   |
|------------|----------------------------------------|
| 프로젝트명 | Zzimccong Plan - 찜꽁플랜                |
| 개발 기간  | 2024.07.10 ~ 2024.08.29                 |
| 주요 목적  | 회식 예약 자동화, 노쇼 방지, 문서화 기능 제공 |
| 기여도     | 4인 팀 프로젝트 (프론트엔드 + 백엔드 공동 개발) |

> 직장인의 회식 장소 예약 스트레스를 줄이고, 점주의 노쇼 피해를 방지하며, 사용자와 점주 모두의 편의를 높이기 위한 회식 예약 통합 플랫폼입니다.

---

## 🛠 기술 스택

### 🖥 Frontend
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=white)
![React Router](https://img.shields.io/badge/ReactRouter-CA4245?style=flat-square&logo=reactrouter&logoColor=white)
![Styled Components](https://img.shields.io/badge/Styled--Components-DB7093?style=flat-square&logo=styled-components&logoColor=white)
![Axios](https://img.shields.io/badge/Axios-5A29E4?style=flat-square&logo=axios&logoColor=white)
![jsPDF](https://img.shields.io/badge/jsPDF-F6C915?style=flat-square&logo=javascript&logoColor=black)
![Swiper](https://img.shields.io/badge/Swiper-6332F6?style=flat-square&logo=swiper&logoColor=white)
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=flat-square&logo=chartdotjs&logoColor=white)
![React Calendar](https://img.shields.io/badge/ReactCalendar-00C49F?style=flat-square)
![React Modal](https://img.shields.io/badge/ReactModal-333333?style=flat-square)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)

### ⚙ Backend
![Spring Boot](https://img.shields.io/badge/SpringBoot-6DB33F?logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Security-6DB33F?logo=springsecurity&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?logo=jsonwebtokens&logoColor=white)
![JPA](https://img.shields.io/badge/JPA-007396?logo=hibernate&logoColor=white)
![QueryDSL](https://img.shields.io/badge/QueryDSL-4B8BBE?logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white)

### ☁ Infra & DevOps
![AWS EC2](https://img.shields.io/badge/AWS_EC2-FF9900?style=flat-square&logo=amazonec2&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?logo=jenkins&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?logo=nginx&logoColor=white)

### 🤝 협업 도구
![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-000000?logo=notion&logoColor=white)
![Draw.io](https://img.shields.io/badge/Draw.io-F08705?logoColor=white)
![ERDCloud](https://img.shields.io/badge/ERDCloud-0092FF?style=flat-square)
![Discord](https://img.shields.io/badge/Discord-5865F2?style=flat-square&logo=discord&logoColor=white)
![Google Drive](https://img.shields.io/badge/Google_Drive-4285F4?style=flat-square&logo=googledrive&logoColor=white)

---

## 🧱 시스템 아키텍처

> 백엔드, 프론트 개발부터 배포까지의 전체 흐름과 구조를 한눈에 볼 수 있도록 시각화한 다이어그램입니다.
![image](https://github.com/user-attachments/assets/64011c04-491e-4020-aa9c-d22a7d0e596f)


---


## 🧩 핵심 기능

### 🙋‍♂️ 고객 (User)
- 회원가입 / 로그인 / 아이디찾기 / 비밀번호 초기화
- 음식점 검색, 예약, 리뷰 작성
- 예약권 및 추첨권 결제
- 추첨 이벤트 참여 / 쿠폰 수령

### 🏢 기업 (Corporation)
- 음식점 장바구니 담기
- PDF 문서화 (회식 계획서 양식 자동 출력)
- 예약 통계 확인

### 🧑‍🍳 점주 (Owner)
- 음식점 등록 및 정보 수정
- 예약 상태 변경 (확정 / 거절)
- 리뷰 답글 작성

### 🔐 관리자 (Admin)
- 유저, 점주, 기업 정보 관리 (CRUD)
- 음식점 승인, 이벤트 종료 관리



## 🗂️ 프로젝트 구조

### 📁 Backend
```
zzimccong_backend/
├── build.gradle
├── settings.gradle
├── docker-compose.yml
├── Dockerfile
├── dev-Jenkinsfile
├── .gitignore
├── gradlew, gradlew.bat
├── nginx/                          # 배포용 Nginx 설정
├── .github/                        # GitHub Actions 등 설정
├── src/
│   ├── main/
│   │   ├── java/com/project/zzimccong/
│   │   │   ├── config/             # Spring Security, CORS, JWT 설정
│   │   │   ├── controller/         # API 컨트롤러 (예약, 회원, 리뷰 등)
│   │   │   ├── service/            # 비즈니스 로직
│   │   │   ├── repository/         # JPA 기반 DB 접근
│   │   │   ├── model/              # Entity, DTO, VO
│   │   │   ├── security/           # JWT 인증/인가 필터
│   │   │   ├── util/               # 공통 유틸
│   │   │   └── ZzimccongApplication.java  # 메인 실행 클래스
│   │   └── resources/
│   │       ├── application.yml     # 환경 설정
│   │       └── static/             # 정적 리소스
│   └── test/                       # 테스트 코드

```

### 📁 Frontend
```
zzimccong_front/zzimccong/
├── package.json
├── Dockerfile
├── .env
├── .gitignore
├── public/
│   └── index.html                  # 루트 HTML
├── postcss.config.js
├── src/
│   ├── App.js, App.css             # 메인 앱
│   ├── index.js, index.css         # React DOM 진입
│   ├── pages/                      # 페이지별 화면 컴포넌트
│   ├── components/                 # 공통 재사용 컴포넌트
│   ├── api/                        # Axios API 모듈
│   ├── context/                    # 글로벌 컨텍스트 관리
│   ├── hooks/                      # 커스텀 훅
│   ├── firebase/                   # Firebase 초기화 및 FCM
│   ├── assets/                     # 이미지, gif 등 정적 리소스
│   ├── utils/                      # 유틸리티 함수 모음
│   ├── service-worker.js           # PWA 서비스워커
│   ├── serviceWorkerRegistration.js
│   └── setupTests.js               # 테스트 환경
├── chatbot-server/                # Dialogflow 챗봇 백엔드 서버 (Node.js)
│   ├── index.js                    # 챗봇 응답 API
│   ├── package.json
│   └── ...

```
## 🎬 주요 기능 시연

찜꽁플랜은 회식 예약의 효율을 높이고, 점주의 노쇼 피해를 줄이며,  
기업과 일반 사용자 모두에게 편리한 예약 경험을 제공합니다.

---

### 🧾 기업 회원가입  
기업 사용자는 회사명, 사업자 번호, 주소 등을 입력해 회원가입을 진행합니다.

![gif-corp-signup](https://github.com/user-attachments/assets/44924261-10bb-422f-878d-f896a30ecb14)

---

### 🔍 검색 및 필터  
카테고리, 지역, 평점 등을 기반으로 원하는 가게를 빠르게 찾을 수 있습니다.

![gif-search-filter](https://github.com/user-attachments/assets/84c390d4-981d-4c54-b065-88e67fdfe4d4)

---

### 🏪 가게 상세보기  
음식점 상세 페이지에서 사진, 운영 시간, 편의 시설, 위치 등을 확인할 수 있습니다.

![gif-store-detail](https://github.com/user-attachments/assets/5a6dbbfd-90d7-4687-a945-d6a56f62aed8)

---

### 📄 기업 장바구니 문서화 및 예약  
장바구니에 담은 음식점을 PDF로 출력하고, 회식을 예약할 수 있습니다.

![gif-corp-document](https://github.com/user-attachments/assets/65f558f5-1f02-4841-84e6-be29cf2c890f)

---

### 📝 리뷰 작성 (기업)  
회식을 완료한 기업 사용자는 음식점에 대한 평가와 리뷰를 작성할 수 있습니다.

![gif-corp-review](https://github.com/user-attachments/assets/8b0a4863-01a2-4106-b841-7bc108056c0f)

---

### 📬 문의 생성  
사용자가 관리자에게 문의사항을 등록할 수 있으며, 마이페이지에서 조회 가능합니다.

![gif-inquiry-create](https://github.com/user-attachments/assets/ec95c29a-b164-4ead-951b-f75ad62ebb8f)

---

### 👤 사용자 회원가입  
일반 사용자가 이메일, 이름, 연락처 등을 입력해 간편하게 회원가입합니다.

![gif-user-signup](https://github.com/user-attachments/assets/89b8af39-4cf1-466d-a6b5-74e2aa6ebdee)

---

### 📅 사용자 회원 예약  
일반 사용자가 원하는 날짜와 시간에 회식 예약을 진행합니다.

![gif-user-reservation](https://github.com/user-attachments/assets/01d1b6fe-77d3-4318-b1a2-cdb4de00d144)

---

### 🤖 사용자 챗봇 결제  
Dialogflow 기반 챗봇과 연동하여 예약권 또는 추첨권을 구매할 수 있습니다.

![gif-chatbot-payment](https://github.com/user-attachments/assets/8bf9c9ec-2a64-4227-9c8c-8dad81a36643)

---

### 🎯 사용자 추첨 응모  
사용자는 보유한 추첨권으로 이벤트에 응모할 수 있습니다.

![gif-user-lottery](https://github.com/user-attachments/assets/3581c306-004e-408b-b09e-c6b2f1ab054a)

---

### 🧑‍🍳 점주 예약 상태 변경  
점주는 고객의 예약에 대해 상태를 확인하고 승인/거절할 수 있습니다.

![gif-owner-reservation-change](https://github.com/user-attachments/assets/84e01167-4894-43ef-be65-c3e0148d9d0b)

---

### 🎟 점주 추첨 생성  
점주는 새로운 추첨 이벤트를 생성하여 사용자 참여를 유도할 수 있습니다.

![gif-lottery-create](https://github.com/user-attachments/assets/c2549c44-f0bd-4dd5-8436-1ed92bbcf31d)


## 👥 팀원 소개

| 도권재 | 한지혜 | 신동구 | 정지영 |
|:---:|:---:|:---:|:---:|
| <img src="https://github.com/user-attachments/assets/ae4f1924-39aa-4156-b6de-f6f592c5f184" width="100"/> | <img src="https://github.com/user-attachments/assets/601ee1d4-d3fe-4501-9849-d7eb8b632df6" width="100"/> | <img src="https://github.com/user-attachments/assets/bd0717c4-f1ab-4f98-8e79-87816d12ded9" width="100"/> | <img src="https://github.com/user-attachments/assets/e9957a1f-5be3-4d0d-a88b-8dc96e4c036f" width="100"/> |
| **Full-Stack**, **Leader** | **Full-Stack** | **Full-Stack** | **Full-Stack** |
| [@dokwonjae](https://github.com/dokwonjae) | [@hanwinnie](https://github.com/hanwinnie) | [@shsh99](https://github.com/shsh99) | [@ji-xux](https://github.com/ji-xux) |




