# 🥕 팀명 : 도파민


## 서비스 소개
* 서비스명:
  *  돌봄
* 서비스설명:
  *  유치원교사를 위한 OpenAI기반 업무관리서비스
<br>

## 📅 프로젝트 기간
- 2023.12.15 ~ 2024.01.24 (4주)
<br>

## ⭐ 주요 기능

### [🎥 시연 영상]()

<details>

<summary></summary>

<!-- summary 아래 한칸 공백 두어야함 -->
<img src="ReadMeImg/colorSelect.png"  alt="colorSelect"/>

<br>

- 
-
- 
  
</details>

<details>

<summary></summary>

<!-- summary 아래 한칸 공백 두어야함 -->
<img src="ReadMeImg/imageSelect.png"  alt="imageSelect"/>

<br>

- 유저는 메인페이지에서 Select image 버튼을 통해 로컬에 저장된 자신이 좋아하는 이미지를 선택할 수 있음.
- 이미지 선택 후 자신의 주 사용 언어를 선택하고 버튼을 클릭하면 이미지 내부에 주요 색상 5종과 유사한 색상을 가진 테마 8개를 추천 받을 수 있음.
- 추천 받은 페이지에서 테마 이름을 클릭하면 테마 상세보기 페이지로 이동함.
> [이미지 기반 테마 추천 알고리즘 상세 설명](https://www.notion.so/1acc4fa14ba64faab8cace798c2adc7b#708cb75f000e4659b4ff3330be8a3e50)
</details>


<details>

<summary>로그인, 로그아웃</summary>

<!-- summary 아래 한칸 공백 두어야함 -->
<img src="ReadMeImg/login.png"  alt="login"/>

<br>

- 사용자가 가입한 아이디와 비밀변호를 정확히 입력하면 로그인 할 수 있음
- 가입하지 않은 아이디 입력 혹은 비밀번호를 정확히 입력하지 않을 시 경고 창을 띄우며 입력란을 초기화함
- 카카오 API를 이용하여 간편 로그인 기능 구현
- 카카오로 간편 로그인한 회원은 자동으로 회원 가입됨
- 로그인한 회원의 회원 정보는 세션에 저장되어 유지되며 로그아웃 버튼을 클릭시 세션을 초기화하며 로그아웃 됨
  
</details>

<details>

<summary>회원가입</summary>

<!-- summary 아래 한칸 공백 두어야함 -->
<img src="ReadMeImg/register.png"  alt="register"/>

<br>

- 사용자는 아이디, 패스워드, 닉네임을 입력하면 회원가입 할 수 있음
- 이미 가입된 아이디, 패스워드와 패스워드 확인이 일치하게 입력하지 않을 시 혹은 입력 값 중 하나라도 공백을 입력한다면 각각 알림창을 띄워 사용자의 올바른 입력을 유도함
  
</details>

<details>

<summary>커뮤니티 게시판</summary>

<!-- summary 아래 한칸 공백 두어야함 -->
<img src="ReadMeImg/communityBoard.png"  alt="board"/>

<br>

- 커뮤니티 게시판은 인기글 게시판, 언어별(Python, Java, Html...) 게시판으로 구분됨
- 인기글 게시판은 전체 게시글을 조회수별로 정렬하여 보여줌, 언어별 게시판은 해당 카테고리별 게시글을 시간순으로 정렬하여 보여줌
- 게시판에서 게시글 제목을 클릭하면 게시글 상세보기 페이지로 이동하며 게시글에 좋아요를 누를 수 있음
- 로그인한 회원은 글 쓰기 및 자신이 쓴 글에 대한 수정, 삭제 권한을 가짐.
- 로그인한 회원은 댓글 쓰기 및 자신이 쓴 댓글에 대한 삭제 권한을 가짐.
- 게시판은 한번에 최대 20개의 게시글을 볼 수 있으며 더 많은 게시글을 보기 위해서는 페이지를 통해 이동해야함
- 유저는 한 화면상에서 최대 5개의 페이지를 클릭할 수 있고, 버튼을 통해 한번에 +-5페이지를 이동할 수 있음
  
</details>

<details>

<summary>테마 게시판</summary>

<!-- summary 아래 한칸 공백 두어야함 -->
<img src="ReadMeImg/themeBoard.png"  alt="theme"/>

<br>

- 테마 게시판은 Vscode에서 제공하는 테마 플러그인 설치시 적용할 수 있는 테마들을 테마 이름으로 구분된 형태로 확인할 수 있음.
- 테마 게시판에서 테마 이름을 클릭시 테마 상세보기 페이지로 이동함.
- 테마 상세보기 페이지는 기본적으로 테마 제작자, 테마 설치 횟수 유저들의 좋아요 개수등을 확인 할 수 있음
- 테마 상세보기 페이지에서 유저는 언어별, 폰트별 다른 테마 적용화면을 확인할 수 있음
- 테마 상세보기 페이지에서 유저는 좋아요 버튼을 통해 테마에 좋아요를 누를 수 있으며 이미 한번 좋아요한 테마에 좋아요를 클릭시 좋아요 취소됨.
- 테마 상세보기 페이지에서 유저는 인스톨 버튼을 통해 테마 설치 페이지로 이동할 수 있음.
- 테마 게시판은 한번에 최대 16개의 게시글을 볼 수 있으며 더 많은 게시글을 보기 위해서는 페이지를 통해 이동해야함
- 유저는 한 화면상에서 최대 5개의 페이지를 클릭할 수 있고, 버튼을 통해 한번에 +-5페이지를 이동할 수 있음.
  
</details>

<details>

<summary>마이 페이지</summary>

<!-- summary 아래 한칸 공백 두어야함 -->
<img src="ReadMeImg/myPage.png"  alt="mypage"/>

<br>

- 로그인한 사용자는 헤더의 메뉴를 통해 마이 페이지로 이동할 수 있음.
- 회원가입을 통해 가입한 회원은 마이페이지에서 닉네임과 패스워드를 수정할 수 있으며 회원 탈퇴 할 수 있음. 카카오 로그인한 회원은 마이페이지에서 회원 탈퇴만 가능함.
- 회원은 마이페이지 좌측 버튼을 통해 자신이 좋아요한 테마 및 작성한 게시글을 볼 수 있음.
- 좋아요한 테마는 한번에 최대 4개의 테마를 보여주며 더 많은 테마에 좋아요를 했을 시 하단의 버튼을 누르면 더 많은 테마를 확인 할 수 있으며 테마명을 클릭하면 테마 상세보기 페이지로 이동함
- 작성한 게시글은 제목, 작성일자, 조회수, 좋아요 수 등의 간략한 정보를 확인 할 수 있으며, 제목을 클릭시 상세보기 페이지로 이동함
  
</details>

<details>

<summary>테마 검색 기능</summary>

<!-- summary 아래 한칸 공백 두어야함 -->

- 사용자는 메인페이지의 검색란에서 키워드를 통해 해당 키워드를 가진 테마를 검색 할 수 있음.
- 해당 키워드를 가진 테마가 있다면 최대 8종류가 보여지고 테마명을 클릭하면 테마 상세보기 페이지로 이동할 수 있음
  
</details>

<details>

<summary>익스텐션</summary>

<!-- summary 아래 한칸 공백 두어야함 -->

- 사용자는 메인페이지 하단에서 Vscode의 유용한 익스텐션 정보를 확인 할 수 있음.
- 익스텐션 아이콘을 클릭 시 설치 페이지로 이동함
  
</details>

<details>

<summary>관리자 페이지</summary>

<!-- summary 아래 한칸 공백 두어야함 -->
<img src="ReadMeImg/admin.png"  alt="admin"/>

<br>

- 관리자 아이디로 로그인 시 헤더에서 관리자 페이지로 이동할 수 있음.
- 관리자는 모든 유저에 대한 삭제 권한을 가지며 유저 삭제를 할 수 있음.
  
</details>
<br>

## ⛏ 기술스택
<table>
    <tr>
        <th>구분</th>
        <th>내용</th>
    </tr>
    <tr>
        <td>사용언어</td>
        <td>
            <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white" style="border-radius:15px"/>
            <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white" style="border-radius:15px">
            <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=HTML5&logoColor=white" style="border-radius:15px"/>
            <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=CSS3&logoColor=white" style="border-radius:15px"/>
            <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white" style="border-radius:15px"/>
        </td>
    </tr>
        <tr>
        <td>프론트앤드</td>
        <td>
            <img src="https://img.shields.io/badge/BootStrap-7952B3?style=for-the-badge&logo=BootStrap&logoColor=white" style="border-radius:15px"/>
            <img src="https://img.shields.io/badge/jquery-0769AD?style=for-the-badge&logo=jquery&logoColor=white" style="border-radius:15px"/>
        </td>
    </tr>
    <tr>
        <td>백앤드</td>
        <td>
            <img src="https://img.shields.io/badge/spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white" style="border-radius:15px"/> 
            <img src="https://img.shields.io/badge/Jsp-007396?style=for-the-badge&logo=java&logoColor=white" style="border-radius:15px"/>
            <img src="https://img.shields.io/badge/Ajax-007396?style=for-the-badge&logo=java&logoColor=white" style="border-radius:15px"/>
            <img src="https://img.shields.io/badge/jstl-007396?style=for-the-badge&logo=java&logoColor=white" style="border-radius:15px"/>
            <img src="https://img.shields.io/badge/MyBatis-007396?style=for-the-badge&logo=java&logoColor=white" style="border-radius:15px"/>
        </td>
    </tr>
    <tr>
        <td>서버환경</td>
        <td>
            <img src="https://img.shields.io/badge/Apache Tomcat-D22128?style=for-the-badge&logo=Apache Tomcat&logoColor=white" style="border-radius:15px"/>
            <img src="https://img.shields.io/badge/flask-000000?style=for-the-badge&logo=flask&logoColor=white" style="border-radius:15px"/>
        </td>
    </tr>
    <tr>
        <td>개발도구</td>
        <td>
            <img src="https://img.shields.io/badge/VSCode-007ACC?style=for-the-badge&logo=VisualStudioCode&logoColor=white" style="border-radius:15px"/>
            <img src="https://img.shields.io/badge/Eclipse-2C2255?style=for-the-badge&logo=Eclipse&logoColor=white" style="border-radius:15px"/>
            <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logoColor=white" style="border-radius:15px"/>
            <img src="https://img.shields.io/badge/dbeaver-003B57?style=for-the-badge&logoColor=white" style="border-radius:15px"/>
            <img src="https://img.shields.io/badge/sql developer-003B57?style=for-the-badge&logoColor=white" style="border-radius:15px"/>
        </td>
    </tr>
    <tr>
        <td>데이터베이스</td>
        <td>
            <img src="https://img.shields.io/badge/Oracle 11g-F80000?style=for-the-badge&logo=Oracle&logoColor=white" style="border-radius:15px"/>
        </td>
    </tr>
    <tr>
        <td>라이브러리</td>
        <td>
            <img src="https://img.shields.io/badge/Anaconda-44A833?style=for-the-badge&logo=Anaconda&logoColor=white" style="border-radius:15px"/>        
            <img src="https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=Selenium&logoColor=white" style="border-radius:15px"/>
            <img src="https://img.shields.io/badge/opencv-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" wstyle="border-radius:15px"/>
            <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=NumPy&logoColor=white" style="border-radius:15px"/>
            <img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" style="border-radius:15px"/>
            <img src="https://img.shields.io/badge/Scikit learn-F7931E?style=for-the-badge&logo=Scikit-learn&logoColor=white" style="border-radius:15px"/>
        </td>
    </tr>
    <tr>
        <td>협업도구</td>
        <td>
            <img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white" style="border-radius:15px"/>
            <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white" style="border-radius:15px"/>
            <img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white" style="border-radius:15px"/>
            <img src="https://img.shields.io/badge/slack-4A154B?style=for-the-badge&logo=slack&logoColor=white" style="border-radius:15px"/>
            <img src="https://img.shields.io/badge/discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" style="border-radius:15px"/>
        </td>
    </tr>
    
</table>


<br>

## 📌 시스템 아키텍처(구조) 예시 
<img src="ReadMeImg/systemA.png" alt="E-R Diagram" style="border-radius:15px"/>
<br>

## 📌 서비스 흐름도
<img src="ReadMeImg/서비스흐름도.png">
<br>

## 📌 E-R Diagram
<img src="ReadMeImg/default_erd.png" alt="E-R Diagram" style="border-radius:15px"/>
<br>

<!-- ## 🖥 화면 구성 -->
<!-- 시연영상 잘라서  -->

## 👨‍👩‍👦‍👦 팀원 역할
<table>
  <tr>
    <!-- 정충근 -->
    <td align="center"><img src="ReadMeImg/정충근.png" width="100" height="100"/></td>
    <!-- 안지수 -->
    <td align="center"><img src="ReadMeImg/안지수.png" width="100" height="100"/></td>
    <!-- 강성훈 -->
    <td align="center"><img src="ReadMeImg/강성훈.png" width="100" height="100"/></td>
    <!-- 양서현 -->
    <td align="center"><img src="ReadMeImg/양서현.png" width="100" height="100"/></td>
    <!-- 김은지 -->
    <td align="center"><img src="ReadMeImg/김은지.png" width="100" height="100"/></td>
    <!-- 김화영 -->
    <td align="center"><img src="ReadMeImg/김화영.png" width="100" height="100"/></td>
  </tr>
  <tr>
    <td align="center"><strong>정충근</strong></td>
    <td align="center"><strong>안지수</strong></td>
    <td align="center"><strong>강성훈</strong></td>
    <td align="center"><strong>양서현</strong></td>
    <td align="center"><strong>김은지</strong></td>
    <td align="center"><strong>김화영</strong></td>
  </tr>
  <tr>
    <!-- 정충근 -->
    <td align="center"><b>• 기능개발 총괄</b></td>
    <!-- 안지수 -->
    <td align="center"><b>• 화면개발 총괄</b></td>
    <!-- 강성훈 -->
    <td align="center"><b>• DB설계 및 관리</b></td>
    <!-- 양서현 -->
    <td align="center"><b>• 화면개발 서브 <br> • 기능개발 서브</b></td>
    <!-- 김은지 -->
    <td align="center"><b>• 화면개발 서브 <br> • 기능개발 서브</b></td>
    <!-- 김화영 -->
    <td align="center"><b>• 화면개발 서브 <br> • 기능개발 서브</b></td>
  </tr>
  <tr>
    <!-- 정충근 -->
    <td align="center"><a href="https://github.com/PringlesHair" target='_blank'>github</a></td>
    <!-- 안지수 -->
    <td align="center"><a href="https://github.com/Scarlett0JS" target='_blank'>github</a></td>
    <!-- 강성훈 -->
    <td align="center"><a href="https://github.com/tmxjvm5" target='_blank'>github</a></td>
    <!-- 양서현 -->
    <td align="center"><a href="https://github.com/pyth1007" target='_blank'>github</a></td>
    <!-- 김은지 -->
    <td align="center"><a href="https://github.com/eunji78" target='_blank'>github</a></td>
    <!-- 김화영 -->
    <td align="center"><a href="https://github.com/dotoritoring" target='_blank'>github</a></td>
  </tr>
</table>
