<img src="https://github.com/user-attachments/assets/09ad07f1-217f-4a6f-8b75-475516eed1f5" width="30%" />

# DamDa
- 개발 기간: 2024.11.20 ~ 2024.12.26 (5주)
- 데모 영상: https://youtu.be/0oqwCB-EGio

## 💡프로젝트 소개
- 여행 준비 과정에서 편의성이 증가와 생소한 장소를 여행하는데 도움을 주는 서비스입니다.
- 사용자 맞춤 여행 계획을 여행 추천 AI를 통해 계획할 수 있습니다.

## 👩🏻‍🤝‍👨🏻팀 구성

|이하영(풀스택) |강성엽(풀스택)|
|:---:|:---:|
|<img src="https://github.com/user-attachments/assets/36869c48-51a0-4b9d-9b2f-2089cfcb3cc2" width="100px"/>|<img src="https://github.com/user-attachments/assets/1b70cf6c-9b18-4694-a19d-0c5d5e9fd2d8" width="100px"/>|
|[lha0](https://github.com/lha0)|[PoeySK](https://github.com/PoeySK)|

## 🖼️개발 환경

로컬 환경에서 진행

### 👀화면

<img src="https://github.com/user-attachments/assets/bba40b46-c177-4f35-bf63-f98ffdc87f55" width="500px" height="240px" />

<img src="https://github.com/user-attachments/assets/6e4d40bd-8556-4eb8-94ef-775733307b19" width="500px" height="240px" />

<img src="https://github.com/user-attachments/assets/f31ec580-b1e8-4444-b36b-c95f97969b8e" width="500px" height="240px" />

<img src="https://github.com/user-attachments/assets/988aac2a-75ce-4fe1-ab6a-4cec2b3864b0" width="500px" height="240px" />

<img src="https://github.com/user-attachments/assets/9e854dda-0195-4e27-9793-0f7e2054c825" width="500px" height="240px" />

<img src="https://github.com/user-attachments/assets/4a0f4d76-d031-4ea6-9de0-26ed9a134b0a" width="500px" height="240px" />

### 🛠️기술 스택

<img src="https://img.shields.io/badge/Vue-4FC08D?style=flat-square&logo=Vuedotjs&logoColor=white"/> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=Javascript&logoColor=white"/> <img src="https://img.shields.io/badge/Pinia-FFD859?style=flat-square&logo=Pinia&logoColor=white"/> <img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=Java&logoColor=white"/> <img src="https://img.shields.io/badge/SpringBoot-6DB33F?style=flat-square&logo=SpringBoot&logoColor=white"/> <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=MySQL&logoColor=white"/>

## 🔧시스템 아키텍쳐

<img src="https://github.com/user-attachments/assets/58809f16-020f-46c5-8763-c183bb48bdff"/>

## 📊ER Diagram

<img src="https://github.com/user-attachments/assets/90032f32-e43f-4f19-9e05-5e9a044e1479" />

## ✨역할

### 강성엽

- JSP → Vue 마이그레이션

  - 기존 JSP로 구상됐던, .jsp 코드를 .vue로 마이그레이션

- 데이터 처리

  - 여행 장소에 대한 페이지네이션

- 로그인

  - JWT 로그인 방식 구현 (`LocalStorage`와 `SessionStorage` 활용)

  - pinia를 활용해 token의 유효 기간 측정

- 검색

  - `contenttypes`테이블의 요소들을 태그로 구현하여 해당 컨텐츠의 장소들이 `or`로 묶어 나오도록 구현

- 달력

  - 라이브러리나 내장 달력이 아닌 `<table>`태그를 이용해 달력 구현

  - 이전 여정 확인
    - 사용자의 여정을 달력에 이벤트 바로 표시

    <img src="https://github.com/user-attachments/assets/277ef362-8740-438a-bb37-6fd10a086aa2" width="400px" />
  - 날짜 선택

    - 사용자 경험을 위해 `<input>`태그 달력을 이용한 선택이 아닌 화면 내에서 바로 날짜를 선택할 수 있도록 구현

    <img src="https://github.com/user-attachments/assets/40402c7c-3f1d-4f8d-9bd7-be2e36eab552" width="350px" />

### 이하영

- GPT를 활용해 AI 여행 추천 구현

  - 절차형으로 장소, 기간, 인원, 활동을 입력 받고 프롬프트에 적용하여 사용자 맞춤 여행 경로 추천

  - 추천과 동시에 해당 장소들에 맞는 YouTube 영상 제공

- 직접 여행 계획 구현

  - 사용자가 제목과 기간, 인원을 선택하고 일차에 맞는 장소를 선택하여 여행 계획 작성

- AI 여행 계획 리뷰

  - AI로 계획한 여행에 사용자가 리뷰를 남길 수 있도록 구현

- 검색

  - `sidos`테이블과 `gugus`테이블을 이용해 지역 자동 완성 검색 구현

  <img src="https://github.com/user-attachments/assets/2ba63d78-ba01-4882-898b-60eb19728192" width="300px" />
