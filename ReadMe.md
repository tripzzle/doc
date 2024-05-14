# TDG

# 목차

1. 개요
2. 개발 환경
3. 서비스 화면
4. 기술 소개
5. 설계 문서

# 1. 개요

---

### 여행 계획을 만들고 친구/사람들과 공유하는 여행 플래너 서비스

# 2. 개발 환경
---

### ⚙ Management Tool
![Notion](https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white) ![GitLab](https://img.shields.io/badge/gitlab-%23181717.svg?style=for-the-badge&logo=gitlab&logoColor=white) ![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white) ![Google Cloud](https://img.shields.io/badge/GoogleCloud-%234285F4.svg?style=for-the-badge&logo=google-cloud&logoColor=white)

### 🛠 IDE
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white) ![WebStorm](https://img.shields.io/badge/webstorm-143?style=for-the-badge&logo=webstorm&logoColor=white&color=black) ![IntelliJ IDEA](https://img.shields.io/badge/IntelliJIDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white) ![Windows Terminal](https://img.shields.io/badge/Windows%20Terminal-%234D4D4D.svg?style=for-the-badge&logo=windows-terminal&logoColor=white)

### 🧲 Infra
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white) ![Nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) ![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)

### 🎨 FrontEnd
<img src="https://img.shields.io/badge/vue.js-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white">

### 💻 BackEnd
![Gradle](https://img.shields.io/badge/Gradle-02303A.svg?style=for-the-badge&logo=Gradle&logoColor=white) ![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white) ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)

# 3. 서비스 화면

### 메인화면

![main](/img/main.png)

### 일정 생성

![Schedlue1](/img/Schedlue1.png)

![Schedlue2](/img/Schedlue2.png)

![Schedlue3](/img/Schedlue3.png)

### 일정 상세 보기

![SchedlueDetail](/img/SchedlueDetail.png)

### 마이 페이지

![Mypage](/img/Mypage.png)

# 4. 기술소개

---

## BackEnd

---

- Member
    - Security Filter와 JWT Token을 사용하여 API 요청 시 요청자의 권한을 검사한다.
    - OAuth2 인증을 이용해 깃허브 회원가입, 로그인, 계정 연동을 통해 불필요한 개인정보 최소화
- Schedule
  - 
- Attracton
    - 공공 데이터 포탈에서 제공한 국내 관광지 API를 전처리를 통해 두개의 테이블을 하나의 테이블로 만들어 DB 부하를 줄였다.

# 5. 설계 문서

---

- ERD

![ERD](/img/ERD.png)

- API 명세서

![API1](/img/API1.png)

![API2](/img/API2.png)

![API2](/img/API2.png)
