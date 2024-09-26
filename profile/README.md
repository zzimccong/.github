![image](https://github.com/user-attachments/assets/b087b565-9df9-49ab-b8a1-3afde271f159)



<br>

## 프로젝트 소개

- 
- 
- 
- 

<br>

## 팀원 구성

<div align="center">

| **신동구** | **도권재** | **정지영** | **한지혜** |
| :------: |  :------: | :------: | :------: |
 FE & BE |   FE & BE |  FE & BE | FE & BE

</div>

<br>

## 1. 개발 환경

- Front : React, Pwa, js, Axios
- Back-end : Spring Boot, Spring Security, JWT, MySql
- 버전 및 이슈관리 : Github, Github Issues, Github Project
- 협업 툴 : Discord, Notion
- 서비스 배포 환경 : AWS
- 디자인 : ()
- [커밋 컨벤션](https://github.com/likelion-project-README/README/wiki/%EC%BB%A4%EB%B0%8B-%EC%BB%A8%EB%B2%A4%EC%85%98)
- [코드 컨벤션](https://github.com/likelion-project-README/README/wiki/%EC%BD%94%EB%93%9C-%EC%BB%A8%EB%B2%A4%EC%85%98)
- [스프라이트](https://github.com/likelion-project-README/README/wiki/%EC%8A%A4%ED%94%84%EB%9D%BC%EC%9D%B4%ED%8A%B8)
<br>

## 2. 채택한 개발 기술과 브랜치 전략

### React, styled-component

- React
    - 컴포넌트화를 통해 추후 유지보수와 재사용성을 고려했습니다.
    - 유저 배너, 상단과 하단 배너 등 중복되어 사용되는 부분이 많아 컴포넌트화를 통해 리소스 절약이 가능했습니다.
- styled-component
    - props를 이용한 조건부 스타일링을 활용하여 상황에 알맞은 스타일을 적용시킬 수 있었습니다.
    - 빌드될 때 고유한 클래스 이름이 부여되어 네이밍 컨벤션을 정하는 비용을 절약할 수 있었습니다.
    - S dot naming을 통해 일반 컴포넌트와 스타일드 컴포넌트를 쉽게 구별하도록 했습니다.
    
### Recoil

- 최상위 컴포넌트를 만들어 props로 유저 정보를 내려주는 방식의 경우 불필요한 props 전달이 발생합니다. 따라서, 필요한 컴포넌트 내부에서만 상태 값을 가져다 사용하기 위해 상태 관리 라이브러리를 사용하기로 했습니다.
- Redux가 아닌 Recoil을 채택한 이유
    - Recoil은 React만을 위한 라이브러리로, 사용법도 기존의 useState 훅을 사용하는 방식과 유사해 학습비용을 낮출 수 있었습니다.
    - 또한 Redux보다 훨씬 적은 코드라인으로 작동 가능하다는 장점이 있었습니다.
- 로그인과 최초 프로필 설정 시 유저 정보를 atom에 저장하여 필요한 컴포넌트에서 구독하는 방식으로 사용했습니다.

### eslint, prettier

- 정해진 규칙에 따라 자동적으로 코드 스타일을 정리해 코드의 일관성을 유지하고자 했습니다.
- 코드 품질 관리는 eslint에, 코드 포맷팅은 prettier에 일임해 사용했습니다.
- airbnb의 코딩 컨벤션을 참고해 사용했고, 예외 규칙은 팀원들과 협의했습니다.
- 협업 시 매번 컨벤션을 신경 쓸 필요 없이 빠르게 개발하는 데에 목적을 두었습니다.

### 브랜치 전략

- Git-flow 전략을 기반으로 main, develop 브랜치와 feature 보조 브랜치를 운용했습니다.
- main, develop, Feat 브랜치로 나누어 개발을 하였습니다.
    - **main** 브랜치는 배포 단계에서만 사용하는 브랜치입니다.
    - **develop** 브랜치는 개발 단계에서 git-flow의 master 역할을 하는 브랜치입니다.
    - **Feat** 브랜치는 기능 단위로 독립적인 개발 환경을 위하여 사용하고 merge 후 각 브랜치를 삭제해주었습니다.

<br>

## 3. 프로젝트 구조



<br>

## 4. 역할 분담

### 🍊신동구

- **UI**

- **기능**


<br>
    
### 👻도권재

- **UI**
  

- **기능**
- 음식점 정보 크롤링
- 날짜 인원 별 예약 기능
- 

<br>

### 😎정지영

- **UI**

- **기능**


<br>

### 🐬한지혜

- **UI**
   
- **기능**

    
<br>

## 5. 개발 기간 및 작업 관리

### 개발 기간

- 전체 개발 기간 : 2024-07-10 ~ 2024-08-28
- UI 구현 : 2024-07-00 ~ 2024-08-00
- 기능 구현 : 2024-07-00 ~ 2024-08-00

<br>

### 작업 관리

- GitHub Projects와 Issues를 사용하여 진행 상황을 공유했습니다.
- 주간회의를 진행하며 작업 순서와 방향성에 대한 고민을 나누고 GitHub Wiki에 회의 내용을 기록했습니다.

<br>

## 6. 신경 쓴 부분

- [접근제한 설정](https://github.com/likelion-project-README/README/wiki/README-6.%EC%8B%A0%EA%B2%BD-%EC%93%B4-%EB%B6%80%EB%B6%84_%EC%A0%91%EA%B7%BC%EC%A0%9C%ED%95%9C-%EC%84%A4%EC%A0%95)

- [Recoil을 통한 상태관리 및 유지](https://github.com/likelion-project-README/README/wiki/README-6.%EC%8B%A0%EA%B2%BD-%EC%93%B4-%EB%B6%80%EB%B6%84_Recoil%EC%9D%84-%ED%86%B5%ED%95%9C-%EC%83%81%ED%83%9C%EA%B4%80%EB%A6%AC-%EB%B0%8F-%EC%9C%A0%EC%A7%80)

<br>

## 7. 페이지별 기능

### [초기화면]

| 초기화면 |
|----------|

<br>

### [회원가입]

| 회원가입 |
|----------|

<br>

### [프로필 설정]

| 프로필 설정 |
|----------|

<br>

### [로그인]


| 로그인 |
|----------|

<br>

### [로그아웃]

| 로그아웃 |
|----------|

<br>

### [상하단 배너]


| 상하단 배너 |

<br>

### [홈 피드]

<br>

### [검색]

<br>

### [프로필]

#### 1. 내 프로필

<br>

#### 2. 타 유저의 프로필

<br>

#### 3. 프로필 수정

<br>

### [게시글]


<br>

### [상품]


<br>

## 8. 트러블 슈팅



<br>

## 9. 개선 목표


    
- **23-01-17 성능 개선 내용**
    
 
    
<br>

## 10. 프로젝트 후기

### 🍊 신동구


<br>

### 👻 도권재



<br>

### 😎 정지영



<br>

### 🐬 한지혜

