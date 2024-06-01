

# HitechAutoworks

<br/>
<div align="center"><img src="https://github.com/panghunJO/HitechProject/assets/157236060/13534f0a-dcf9-4198-9a05-31b9faa7bd2b" alt="로고" width="700px"></div>
<br/>

**프로젝트 기간** : 2024.04.08 ~ 2023.06.03

🔗 [HitechAutoworks 서비스 둘러보기](http://confoous.com:1818/) (데스크탑/모바일 환경에서 이용 가능)


<br/>

## ✨ 프로젝트 소개

### Develop Together, Grow Together, Hi-Tech Auto Service

- HitechAutoworks 자동차 정비소 정비성 효율화 플랫폼입니다.
- 현재 진행 중인 프로젝트는 정비소의 문제점을 개선하고 효율성을 증대시키는 것을 목표로 합니다.
- 프로젝트를 통해 현장 서비스 문제 해결과 정비 효율성 향상을 실현할 수 있습니다.

<br/>

**프로젝트 문서**
 
| 📒 [팀 Notion ](https://adorable-entree-2a6.notion.site/HitechAutoWorks-746bb8d780ce4f07957e2efccb4a37d8?pvs=4) | 🎉 [Figma](https://www.figma.com/design/c94BWil0qqwGGDw6tKQNzd/Hi-Tech-Auto-Works_Homepage?m=dev&node-id=0-1&t=hvOzNdFkjmxLUJpJ-1) | 💌 [Miro](https://miro.com/welcomeonboard/a0ZNT0Rua3pMemR6M1ZVQ2xkc0JveDlxNDhFdE5yV0E1cWwwYlhhQ2VLeWE3Sk1YVlpJN2RPbnVNTEFHMmdxRnwzNDU4NzY0NTg3Mjk1NzY0MjI4fDI=?share_link_id=468227781974)
<br/>
<br/>
<br/>

## 🙌 팀원 소개

<br/>
<br/>
<br/>

## 📅 프로젝트 일정
<img src="https://github.com/panghunJO/HitechProject/assets/157236060/6037da66-e176-41b3-956b-dd9fd051d550" alt="일정1">
<img src="https://github.com/panghunJO/HitechProject/assets/157236060/a464105e-0f04-4bc9-98bf-17291736bd4e" alt="일정2">
<br/>
<br/>
<br/>

## 🖥 기술 스택

| 구분                 | 사용 기술          |
| -------------------- | ------------------ |
| 언어                 | Java (JDK-17), HTML/CSS, JAVAScript |
| UI                   | BootStrap            |
| 서버               | Apache Tomcat/10.1.20   |
| 프레임워크                  | Spring Framework 3.2.5, MyBatis 3.0.3 |
| DB             | MySQL            |
| IDE      | Intellij Ultimate, HeidiSQL, DBeaver    |
| API, 라이브러리  | chart.js, fullcalender, Java Mail Sender, nurigo   |
| 협업툴  | Notion, Github   |


<br/>
<br/>
<br/>

## 🗂 디렉토리 구조

├── README.md
├── build
│   ├── classes
│   ├── generated
│   ├── libs
│   ├── reports
│   ├── resolvedMainClassName
│   ├── resources
│   ├── test-results
│   └── tmp
├── build.gradle
├── gradle
│   └── wrapper
├── gradlew
├── gradlew.bat
├── img
├── log
│   ├── test.log
├── settings.gradle
└── src
    ├── main
    └── test
<br/>
<br/>

## 물리 데이터 모델
<img src="https://github.com/panghunJO/HitechProject/assets/157236060/ce2fb658-0fe9-414e-b090-19953231fff3" alt="model">

## ⭐️ 주요 기능

### 📌 프로젝트 찾기

- 포지션 별로 필터링 된 프로젝트를 확인할 수 있습니다.
    
 <img src="https://user-images.githubusercontent.com/82587107/224244006-a5381fbf-59c0-4bcb-b719-2b6f58735935.gif" alt="필터링" width="60%">   
    
 <br/>   

### 📌 프로젝트 지원 / 초대

- 유저는 참여하고 싶은 프로젝트에 지원할 수 있습니다.
- 작성자는 지원자 목록에서 함께 하고 싶은 지원자를 프로젝트에 초대할 수 있습니다.

<div>
    <img src="https://user-images.githubusercontent.com/82587107/224249794-9c3d1b24-8461-437a-979f-849f2087511f.gif" alt="지원하기" width="50%"><img src="https://user-images.githubusercontent.com/82587107/224249842-4872decf-b911-4ccf-ad10-95347fc29d00.gif" alt="초대하기" width="50%">    
</div>

<br/>

### 📌 쪽지 / 알림

- 유저는 다른 유저에게 쪽지를 보내고 받으며 커뮤니케이션 할 수 있습니다.
- 프로젝트에 초대되거나, 지원한 프로젝트가 마감한 경우 알림이 갑니다.

<div>
    <img src="https://user-images.githubusercontent.com/82587107/224250012-1ad627b8-3a48-4ccc-bc39-69609a0162c2.gif" alt="쪽지보내기" width="50%"><img src="https://user-images.githubusercontent.com/82587107/224250016-0958e399-c7c7-41e9-93eb-31a9e989fd9f.gif" alt="쪽지-알림확인" width="50%">    
</div>

<br/>
<br/>
<br/>

## 💡 구현 기능

**로그인/회원가입**

- 소셜 로그인 (구글, 페이스북, 깃허브)
- 로그인/회원가입 완료 후 프로필, 기술 스택, 포지션 설정
- 유효성 검사

**헤더**

- 로그인 / 비 로그인 시 네비게이션 다르게 노출
- 페이지 이동 시 해당 메뉴 활성화

**메인**

- 캘린더로 모집중인 프로젝트 조회
- 조회순/관심순 프로젝트 조회
- 포지션 별 팀원 추천

**프로젝트 찾기**

- 포지션 별 프로젝트 조회
- 모집 중인 프로젝트 조회

**프로젝트 구인 게시글 상세**

- 모집 인원, 필요 스택, 예상 기간, 프로젝트 마감일 조회
- 조회수
- 관심 기능
- 공유 기능
- 작성자에게 쪽지 보내기
- 작성자 ➡️ 수정, 삭제, 지원한 인원 프로필 열람 가능, 모집 마감
- 지원자 ➡️ 지원 / 지원 취소 기능

**구인 게시글 작성**

- 모집 포지션 인원, 기술 스택, 시작/종료/마감 기간 설정
- 썸네일 이미지 추가 가능
- Toast UI 에디터로 마크다운 작성 가능
- 유효성 검사
- 페이지 벗어날 시 경고 모달창

**공개 프로필**

- 유저 정보 조회
- 쪽지 보내기
- 경력 1년 미만일 경우 새싹 배지
- 참여한/작성한 프로젝트 리스트 조회

**마이페이지**

- 닉네임, 프로필 이미지, 기술스택, 포지션, 경력 수정
- 유효성 검사
- 회원탈퇴
- 지원한/참여한/작성한/관심있는 프로젝트 리스트 조회

**쪽지**

- 쪽지 읽기/보내기/답장하기
- 보낸 쪽지함/받은 쪽지함
- 유효성 검사

**알림**

- 게시글 작성자 ➡️ 지원자 있을 때 알림
- 지원자 ➡️ 매칭 되었을 때, 신청한 프로젝트가 마감 되었을 때 알림
- 알림을 클릭했을 때 해당 프로젝트/프로필 링크로 이동

<br/>
<br/>
