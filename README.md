# 팀명 : 도파민


## 서비스 소개
* 서비스명
  *  돌봄
* 서비스설명
  *  유치원교사를 위한 OpenAI기반 업무관리서비스
<br>

## 프로젝트 기간
- 2023.12.15 ~ 2024.01.24 (4주)
<br>

## 주요 기능

### [시연 영상]()

<details>

<summary>ChatGPT를 활용한 일지 요약</summary>

<!-- summary 아래 한칸 공백 두어야함 -->
<img src="ReadMeImg/colorSelect.png"  alt="colorSelect"/>

<br>

- 기간을 설정하면 교사가 기존에 작성해둔 일지를 3/1 분량으로 요약해주는 기능
  
</details>

<details>

<summary>FullCalendarAPI로 구현한 캘린더</summary>

<!-- summary 아래 한칸 공백 두어야함 -->
<img src="ReadMeImg/imageSelect.png"  alt="imageSelect"/>

<br>

- 

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
 
<summary>마이 페이지</summary>

<!-- summary 아래 한칸 공백 두어야함 -->
<img src="ReadMeImg/myPage.png"  alt="mypage"/>

<br>

- 
  
</details>

<details>

<summary>관리자 페이지</summary>

<!-- summary 아래 한칸 공백 두어야함 -->
<img src="ReadMeImg/admin.png"  alt="admin"/>

<br>

- 
  
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
        </td>
    </tr>
    
</table>


<br>

## 📌 시스템 아키텍처(구조) 예시 
<img src=""/>
<br>

## 📌 서비스 흐름도
<img src="">
<br>

## 📌 E-R Diagram
<img src=""/>
<br>

<!-- ## 🖥 화면 구성 -->
<!-- 시연영상 잘라서  -->

## 팀원 역할
<table>

</table>
