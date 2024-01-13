# ↩️ ENTER - 고객 만족도 조사 자동화 서비스
<img width="500" src="https://github.com/undervi/ENTER/assets/95211722/81e15cf8-a9bd-4d93-9e31-dfe13ee59d4c" />
<br/>

### 1️⃣ Repositories 
> organizations에서 관리한 프로젝트로 분야별로 아래 레포지토리 참고 부탁드립니다.

Front-End: https://github.com/AIVLE-ENTER/ENTER-FE<br/>
Back-End: https://github.com/AIVLE-ENTER/ENTER-BE<br/>
AI: https://github.com/AIVLE-ENTER/ENTER-AI<br/>

### 2️⃣ 기간 : 2023.12.11 ~ 2024.01.12<br/>

### 3️⃣ 목차

1. [**팀원 소개**](#team)
   
2. [**서비스 소개**](#service)

3. [**기술스택**](#stacks)

4. [**기능 소개**](#func)

5. [**시연 영상**](#testing)

<br />


<div id="team">
   
  ## 🧏 팀원 소개
  ### WEB
  ![image](https://github.com/undervi/ENTER/assets/95211722/135d5b1d-80b9-4d74-9def-65cf9af932a6)
  ### AI
  ![image](https://github.com/undervi/ENTER/assets/95211722/72cd0497-e859-47b8-8bee-87b0308e1f3a)
  
</div><br />

<div id="service">
   
  ## ✨ 서비스 소개
  ![image](https://github.com/undervi/ENTER/assets/95211722/2fca7bfc-0a43-4b42-8dd5-8c6cc90bf95c)
  ><b>ENTER</b>는 기업이 제품 및 서비스에 대한 고객의 의견을 효율적으로 수집하고, 이를 토대로 비용과 시간을 절약하여 전립을 수립할 수 있게 도와주는 자동화된 소비자 만족도 조사 서비스입니다.
</div><br/>

<div id="stacks">

  ## 🛠️ 기술 스택
  ### Tools
  ![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=Notion&logoColor=white)
  ![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=Git&logoColor=white)
  ![Github](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white)
  ![VScode](https://img.shields.io/badge/Visual%20Studio%20Code-007ACC?style=for-the-badge&logo=VisualStudioCode&logoColor=white)
  ![AWS](https://img.shields.io/badge/aws-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
  ![Amazon RDS](https://img.shields.io/badge/amazon%20Rds-527FFF?style=for-the-badge&logo=amazonRds&logoColor=white)
<br/>
  
  ### Development
  ![그림1](https://github.com/undervi/ENTER/assets/95211722/b937cd30-1b07-4410-94ee-da1814a5ff9e)
  
</div><br />

<div id="func">

  ## 🤖 기능 소개

  1. 회원가입 & 탈퇴
  - 이메일 인증 후 회원가입을 진행합니다.
  - 마이페이지에서 탈퇴를 진행할 수 있습니다.
  
  2. 로그인/로그아웃 & 소셜 로그인
  - jwt 토큰을 프론트엔드로 전달하여 로그인을 진행합니다. (프론트에서 LocalStrage에 토큰 보관)
  - SHA256 개인정보 암호화 적용하였습니다.
  - LocalStorage에서 jwt토큰을 제거하여 로그아웃합니다.
  - 카카오/구글/네이버 계정을 연동하여 소셜 로그인을 지원합니다.

  3. 아이디 찾기 & 비밀번호 변경
  - 이름과 이메일을 입력하여 아이디를 찾을 수 있습니다.
  - 아이디를 입력하고 이메일 인증을 진행하면 비밀번호 변경을 할 수 있습니다.

  4. 프롬프트
  - AI 설정(크롤러 설정 등)을 할 수 있습니다.
  - 원하는 주제로 채팅방을 생성하고, 질문을 할 수 있습니다.
  - 답변에 메모를 남길 수 있습니다. (조회/생성/수정/삭제 가능)

  4. 마이페이지
  - 본인의 정보를 조회할 수 있습니다.
  - 개인정보 표시 제한 보호 조치 적용 (이름에 마스킹)
  
  5. 문의 게시판
  - 회원가입한 사용자들은 게시판에 글 작성, 수정, 삭제를 할 수 있습니다.
  - 관리자는 회원들의 글 삭제 및 답변을 작성할 수 있습니다.
  - 회원은 본인의 글만 수정/삭제 할 수 있습니다.
  - 비회원은 조회만 가능합니다.
  - 검색과 페이징 기능을 구현하였습니다.

</div><br />

