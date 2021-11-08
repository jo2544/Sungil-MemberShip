# MemberShip
회원관리 프로그램

프로세스 : 회원가입, 로그인, 회원정보 수정
구현언어 : javaFx + SceneBuilder + Oracle

# 버전 및 환경
javaJDK , JavaFX SDK 15 버젼

SQL  테이블명 : smember
               필드 : USERID,USERPWD,UNAME,UNUMBER,UPHONE,UMAJOR,UADDRESS
               
--module-info.java 파일 내 추가내용--

	requires javafx.controls;
	requires javafx.fxml;
	requires java.sql;
	opens application;
--


# 프로그램 화면
(1)로그인

![login](https://user-images.githubusercontent.com/93318468/140670337-7d7177d0-4fee-4b20-a90b-6983c8e1a648.jpg)

(2) 회원가입

![reg](https://user-images.githubusercontent.com/93318468/140670343-a0239797-bb66-4127-a2fe-1c1dce7fc58c.jpg)

(3)회원정보수정

![reg_e](https://user-images.githubusercontent.com/93318468/140670350-bdb0dfc6-eb30-48bd-9054-e2de7d2ddff9.jpg)
