# 🗓️ Zzimccong Plan - 찜꽁플랜
![image](https://github.com/user-attachments/assets/b087b565-9df9-49ab-b8a1-3afde271f159)
> 음식점 예약, 추첨 이벤트, 회식 문서화까지 모두 가능한 올인원 예약 서비스

---

## 🔎 프로젝트 개요

| 항목       | 내용                                   |
|------------|----------------------------------------|
| 프로젝트명 | Zzimccong Plan - 찜꽁플랜                |
| 개발 기간  | 2024.07.10 ~ 2024.08.29                 |
| 주요 목적  | 회식 예약 자동화, 노쇼 방지, 문서화 기능 제공 |
| 기여도     | 4인 팀 프로젝트 (프론트엔드 + 백엔드 공동 개발) |

> 직장인의 회식 장소 예약 스트레스를 줄이고, 점주의 노쇼 피해를 방지하며, 기업의 시간과 비용을 절감하기 위한 **B2B 예약 플랫폼**입니다.

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

## 🧩 핵심 기능

### 🙋‍♂️ 고객 (User)
- 회원가입 / 로그인 / 아이디찾기 / 비밀번호 초기화
- 음식점 검색, 예약, 리뷰 작성
- 예약권 및 추첨권 결제
- 추첨 이벤트 참여 / 쿠폰 수령

### 🏢 기업 (Corporation)
- 음식점 장바구니 담기
- PDF 문서화 (회식 계획서 자동 출력)
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
com.zzimccong
├── config           # Security 설정
├── controller       # REST API 컨트롤러
├── service          # 비즈니스 로직 처리
├── repository       # JPA Repository
├── domain           # Entity 클래스들
├── dto              # 요청/응답 DTO
├── security         # JWT, 필터 구성
```

### 📁 Frontend
```
src
├── api              # Axios 모듈
├── components       # 공통 컴포넌트
├── pages            # 기능별 페이지
├── store            # 상태 관리
├── utils            # 토큰, 유틸 함수
```




