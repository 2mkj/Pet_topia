# 🐶 ‘펫토피아’ 반려동물 서비스 중개 웹사이트

반려동물과 관련된 서비스를 예약 및 관리 할 수 있는 웹사이트

## 📌 프로젝트 기간

2022년 9월 26일 ~ 2022년 10월 25일 (약 4주)

## 📌 개발인원

총 4인

## 📌 사용언어 & TOOLS

[![Java](https://img.shields.io/badge/-Java-000?logo=java)](https://java.com/)
[![Spring-Boot](https://img.shields.io/badge/-SpringBoot-000?logo=Spring-Boot)](https://spring.io/projects/spring-boot)
[![Oracle](https://img.shields.io/badge/-Oracle-000?logo=Oracle&logoColor=white)](https://www.Oracle.com/downloads/)
[![JavaScript](https://img.shields.io/badge/-JavaScript-000?logo=JavaScript)](https://www.javascript.com/)
[![CSS](https://img.shields.io/badge/-CSS-000?logo=CSS3)](https://en.wikipedia.org/wiki/CSS)
[![HTML](https://img.shields.io/badge/-HTML-000?logo=HTML5)](https://www.w3schools.com/html/)
[![Bootstrap](https://img.shields.io/badge/-Bootstrap-000?logo=Bootstrap)](https://getbootstrap.com/)
[![Eclipse](https://img.shields.io/badge/-Eclipse-000?logo=Eclipse)](https://www.eclipse.org/)
[![Git](https://img.shields.io/badge/-Git-000?logo=Git)](https://git-scm.com/)

## 📌 프로젝트 소개
국내 반려동물 양육 인구가 증가함에 따라 펫코노미(Pet+Economy) 시장이 꾸준한 성장세를 보이고 있다. 미용, 교육, 치료 등의 반려동물 서비스 관련 수요가 늘고 있고 이러한 서비스들을 제공하는 판매자와 구매하는 소비자 모두 만족 할 수 있는 반려동물 서비스 중개 생태를 구축하려 한다.

## 📌 구현 기능
- 메인화면의 UI 배치 및 디자인
- 회원가입 처리(mail api, 국세청 사업자 진위여부 api 활용한 본인인증 구현)
- 로그인 처리(Spring Web Security 활용)
- 아이디/비밀번호 찾기
- 통합검색
- 커뮤니티 게시판 (Summernote에디터를 활용하여 이미지 업로드 처리)
- 리뷰 작성 및 별점 기능 구현
- 예약 내역 리스트
- 실시간 채팅

## 📌 배운 점 & 아쉬운 점
- Springboot 어노테이션을 보다 깊이 이해할 수 있게 되었다.
- pom.xml을 통한 Maven추가를 통해 gson, Lombok등의 라이브러리를 활용할 수 있게 되었다.
- 레이어팝업, ajax를 통한 api호출, countdown함수 등 javascript를 적극 활용하여 front-end에대한 이해도를 높혔다.
- 별점 기능 구현에 있어서 jsp의 소스코드에 아쉬움이 남는다. jstl을 활용했지만 생각만큼 코드가 간소화되지 않았다.
- 웹소켓을 활용하여 실시간 채팅을 구현하였다. 원래 '당근마켓'을 참고한 중고거래 채팅방을 구현하려고했으나 시간부족으로 단순한 자유채팅방이 되었다.
