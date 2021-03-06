<!-- 서비스 간략설명  -->
<img width="100" alt="modal1" src="https://user-images.githubusercontent.com/98807506/171565945-5a4e4ec0-fa18-43e7-a5fa-1e0e981e47d7.png" align="left">
<h1 align="left"> 성공적인 팀플을 위한 체크인/팀관리 서비스<br/>아무튼 출석!</h1>



<center>
<a href="https://www.a-chool.com/"><img width="200" alt="modal1" src="https://user-images.githubusercontent.com/98807506/171565120-50a28594-4326-41ac-ab1e-4f099d9cfc16.png" align="left"></a>      
  
</center>

<br>
<br>
<br>
<br>


## 🍀 Service Architecture
![서비스 아키텍쳐](https://user-images.githubusercontent.com/98807506/171581919-4f903fe2-92e1-48ac-a31b-7e900ce4b1fe.png)

## 🗓 프로젝트 기간
- 2022년 4월 22일 ~ 2022년 6월 3일
- 1차 배포 : 2022년 5월 25일
- 최종 배포 : 2022년 6월 1일
- 유튜브 링크 : https://www.youtube.com/watch?v=n9tQKqhaXOQ

<br>

# ⭐️ 팀 구성
| 이름     | 깃허브 주소                                                | 포지션     |
|:--------:|:----------------------------------------------------------:|:-----------:|
| 이경태🔰 | [https://github.com/kyeongbong](https://github.com/kyeongbong)                     | Frontend     |
| 최경민   | [https://github.com/kyngmn](https://github.com/kyngmn)                     | Frontend     |
| 김호빈   | [https://github.com/hobit22](https://github.com/hobit22) | Backend     |
| 심현웅   | [https://github.com/hyun-woong](https://github.com/hyun-woong)                     | Backend |
| 김일권   | [https://github.com/jjems](https://github.com/jjems)                     | Backend |
| 장유진   | [https://github.com/A-Chool](https://github.com/A-Chool)                     | Designer |
| 전하경   | [https://github.com/A-Chool](https://github.com/A-Chool)                     | Designer |

<br>

# 📎 구현기능


| 이름     | 구현기능                                                | 포지션     |
|:--------:|:----------------------------------------------------------|:-----------:|
| 이경태🔰 | Admin page : <p>유저관리, 팀관리</p> Client page : <p>체크인 / 체크아웃, 팀 대시보드, 학습통계 / 랭킹 </p>                  | Frontend     |
| 최경민   | Client page : <p>채팅,프로필 수정</p>       | Frontend     |
| 김호빈   | Admin page : <p>주차/멤버/팀 조회, 추가, 삭제, 수정</p> Client page : <p>팀 대시보드, WebSocket과 Redis 를 이용한 채팅, 랭킹</p> Common : <p>Jmeter Test, 슬랙 알림</p>| Backend     |
| 심현웅   | Admin page : <p>전체 유저 조회, 삭제, 권한 변경</p> Client page : <p>체크인 시스템, 학습통계, 소셜로그인(kakao, naver),</p><p>마이페이지 이미지 업로드, 수정, 태그</p>Common : <p>CI/CD, RefreshToken, Security, SSL</p>                     | Backend |
| 김일권   | Common : <p>Jmeter Test</p>| Backend     |

# 🎯 핵심 기능 Key Feature

<details>
<summary>📚 그룹 채팅</summary>
<div markdown="1">
 <br>
  → 팀별 그룹 채팅 서비스를 지원
  <br> → 대화 내용은 저장되어, 페이지를 벗어났다 다시 돌아와도 유지
</div>
</details>

<details>
<summary>⏰ 공부 타이머</summary>
<div markdown="1">
<br>
  → 유저별 공부 시간을 기록할 수 있는 타이머 제공
  <br> → 타이머는 매일 오전 5시에 초기화 됨
  <br> → checkOut을 누르지 않은 유저의 경우 마지막 checkIn 시간에서 한 시간이 추가된 상태로 저장
</div>
</details>
<details>
<summary>🏆 랭킹 및 당근밭 콘텐츠</summary>
<div markdown="1">
 <br>
   → 유저의 일별 누적 공부시간을 기준으로 랭킹이 집계되며, 일별 공부시간에 비례해 당근 밭에 당근이 심어짐
</div>

</details>

<br>

## 📜 기술스택

> ## Frontend

<p align="center">
<img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
<img src="https://img.shields.io/badge/Axios-764ABC?style=for-the-badge&logo=Axios&logoColor=white">
<img src="https://img.shields.io/badge/html-E34F26?style=for-the-badge&logo=html5&logoColor=white">
  
<br>
<img src="https://img.shields.io/badge/WebRTC-333333?style=for-the-badge&logo=WebRTC&logoColor=white">
<img src="https://img.shields.io/badge/Route53-E68B49?style=for-the-badge&logo=Route53s&logoColor=white">
<img src="https://img.shields.io/badge/Amplify-FBBD62?style=for-the-badge&logo=Amplify&logoColor=white">
  
<br>
<img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white">
<img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
<img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=React&logoColor=black">

 <br>
 <img src="https://img.shields.io/badge/Redux-764ABC?style=for-the-badge&logo=Redux&logoColor=white"> 
 <img src="https://img.shields.io/badge/Styled Components-F893D1?style=for-the-badge&logo=styledComponents&logoColor=white">
 <img src="https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=Socket.io&logoColor=white">
  
<br>
<br>
<br>

> ## Backend

<p align="center">

<img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=Spring&logoColor=white">
<img src="https://img.shields.io/badge/Java-EC2025?style=for-the-badge&logo=Java&logoColor=white">
<img src="https://img.shields.io/badge/Gradle-39D52D?style=for-the-badge&logo=Gradle&logoColor=white">
  
<br>
<img src="https://img.shields.io/badge/Jenkins-D73634?style=for-the-badge&logo=Jenkins&logoColor=white">
<img src="https://img.shields.io/badge/jwt-000000?style=for-the-badge&logo=jwt&logoColor=white">
<img src="https://img.shields.io/badge/Docker-4DCBFE?style=for-the-badge&logo=Docker&logoColor=white">
<img src="https://img.shields.io/badge/AWS EC2 SDK-F58536?style=for-the-badge&logo=AWS&logoColor=white">
  
<br>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white">
<img src="https://img.shields.io/badge/Amazon S3-E15343?style=for-the-badge&logo=S3&logoColor=white">
<img src="https://img.shields.io/badge/Elasticache-5294CF?style=for-the-badge&logo=Elasticache&logoColor=white">
<img src="https://img.shields.io/badge/Redis-D82A20?style=for-the-badge&logo=Redis&logoColor=white">

<br>
<img src="https://img.shields.io/badge/Notion-181818?style=for-the-badge&logo=Notion&logoColor=white">
<img src="https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=Socket.io&logoColor=white">
<img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
<img src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=Slack&logoColor=white">
  

<br>
  
# ⚓️ Links

- Project homepage: https://www.a-chool.com/
- Repository: https://github.com/A-Chool

- 프론트엔드 깃허브 주소 : https://github.com/A-Chool/FE
- 백엔드 깃허브 주소 : https://github.com/A-Chool/BE

<br> 
  
  

# 🖥 more info
  
  <details>
<summary>🖨 API 명세서</summary>
<div markdown="1">

![Admin](https://user-images.githubusercontent.com/98807506/171592425-072c43c7-d621-4d63-84ce-d01be14db1ed.png)
![User](https://user-images.githubusercontent.com/98807506/171592532-61eec599-1501-4fe2-adc2-243da9aacb21.png)

</div>
</details>

<details>
<summary>🐳 ERD</summary>
<div markdown="1">
  
![erd](https://user-images.githubusercontent.com/98807506/171581214-5687b031-695d-436c-80bc-441c911f48f3.png)
  
</div>
</details>
  
  <details>
<summary>📄 서비스 기획 배경</summary>
<div markdown="1">
  
![01](https://user-images.githubusercontent.com/98807506/172096592-b263fc8c-c69b-4cd9-ac49-57dbb3505180.png)

</div>
</details>
  
<details>
<summary>🪄 서비스 기술 도입 배경</summary>
<div markdown="1">
  
![1](https://user-images.githubusercontent.com/98807506/172096141-ca84af64-180a-424f-b7e8-599af40fdd09.png)
![2](https://user-images.githubusercontent.com/98807506/172096137-a9417ce7-234c-40d4-bce7-323582bad679.png)
![3](https://user-images.githubusercontent.com/98807506/172096129-da4ff841-aa03-497d-a2e6-c6cb395349c1.png)

</div>
</details>
  
<details>
<summary>📬 고객 반응 및 개선사항</summary>
<div markdown="1">
  
![User](https://user-images.githubusercontent.com/98807506/172095737-f139564e-c11c-4387-8496-ed957d3807ff.png)
![User](https://user-images.githubusercontent.com/98807506/172095735-300f5f2c-50d9-4d5c-8859-f2c2a4f46a4d.png)
![User](https://user-images.githubusercontent.com/98807506/172095734-7298e431-d365-422e-80d8-f24233187093.png)
![User](https://user-images.githubusercontent.com/98807506/172095724-8017d72e-f21e-4191-9455-1e9f41c4b147.png)

</div>
</details>
  

## 📌 Personal Trouble Shooting
<a href="https://github.com/A-Chool/BE/wiki/%5BHobinKim%5DTrouble-Shooting" target="_blank"><img height="40"  src="https://img.shields.io/static/v1?label=Spring&message=김호빈 &color=08CE5D&style=for-the-badge&>"/></a>
<a href="https://github.com/A-Chool/BE/wiki/%5BHyunWoong%5DTrouble-Shooting" target="_blank"><img height="40"  src="https://img.shields.io/static/v1?label=Spring&message=심현웅 &color=08CE5D&style=for-the-badge&>"/></a>
<a href="https://github.com/A-Chool/FE/wiki" target="_blank"><img height="40"  src="https://img.shields.io/static/v1?label=React&message=이경태 &color=95D0F6&style=for-the-badge&>"/></a>
