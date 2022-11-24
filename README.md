
# 공공데이터를 통한 서울 상권 분석

<p align="center">
  <br>
  <img src="./images/logo.png">
  <br>
</p>

## 프로젝트 소개

<p align="justify">
공공데이터를 활용한 지역구별 매장 분포, 연도별 매출, 개업 및 폐업률을 분석 및 시각화 하여 <br>
정보가 필요한 현, 예비 자영업자에게 지표가 될 수 있는 서비스를 제공합니다.
</p>

<br>

## 기술 스택
* Front
	* HTML, CSS, JavaScript, AJAX, Bootstrap

* Back
	* Java, Spring, MyBatis, JSP
* DB, Server
	* Oracle, Tomcat, AWS
<br>

## 구현 기능
### [상권 지도]
* 지도: 카카오맵 API 사용
* 지도 검색: 원하는 지역구, 도로명 주소를 통한 공공데이터 검색
* 검색 기록: 회원별 검색했던 연도, 분기, 주소, 일자 출력
* 분기별 그래프: 검색한 지역구의 업종별 매출액, 매출건수, 점포수 제공
* 자세한 분석 정보: 검색한 지역구의 14~21년도 별 데이터 시각화 제공
### [로그인]
* 로그인: 미 로그인 시 홈페이지 이용 제약
* 아이디찾기: DB에 이름과 이메일을 통한 아이디 반환 기

### [회원 정보]
* 아이디 중복 확인: 중복 여부 판별하여 안내문구 표시
* 비밀번호: 유효성 검사기능 추가
* 주소: 다음 주소 찾기 API 사용

### [게시판]
* 글쓰기: 게시글 작성/수정/삭제 기능
* 댓글쓰기: 작성한 게시글의 댓글 작성 기능
* 검색 범위: 셀렉트 박스를 통한 검색 타입 선택
* 페이징: 10개 단위로 페이징 설정 

### [기타]
* 배포: AWS EC2 + AWS RDS를 이용한 배포 (jar파일로 빌드)
* DB: AWS RDS에 공공데이터(Martket, MarketOpenClose)와 새로 생성되는 데이터(Member, Board, Reply) 저장

<br>

## 개발 기간
* 2022.10.14 ~ 2022.11.23 (5주)
<br>

## 화면 설계도
![image](https://user-images.githubusercontent.com/96763658/203797032-8725e4af-156a-4451-8daf-ce3552772773.png)
<br>

## Usecase Diagram
![image](https://user-images.githubusercontent.com/96763658/203796692-a81854e4-7299-4a46-bf50-1735140fb00f.png)
<br>

## Class Diagram
![image](https://user-images.githubusercontent.com/96763658/203796809-fbc4ac7a-a2dd-4b9d-8376-00aed39af08c.png)
<br>

## Entity Relationship Diagram
![image](https://user-images.githubusercontent.com/96763658/203796861-be9f2d44-76b9-4016-8b24-70f907b4321e.png)
<br>

## 라이센스

MIT &copy; [NoHack](mailto:lbjp114@gmail.com)

<!-- Stack Icon Refernces -->

[js]: /images/stack/javascript.svg
[ts]: /images/stack/typescript.svg
[react]: /images/stack/react.svg
[node]: /images/stack/node.svg
