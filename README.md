# Psychological Test
> 성격 유형 테스트


![image](https://user-images.githubusercontent.com/113402301/201002903-5102ca46-95ee-4ff4-bf3c-ffd8e76c3b79.png)


## 1. 개요

- 개발 기간 : 2022/09/12~2022/09/19
- 주요 기능 :  하나의 페이지에서 12가지 문항의 선택하는 인터렉션 구현,  심리 테스트가 종료된 후, 사용자의 정보를 입력 받아 결과 페이지에서 출력, 문항 및 답변을 배열로 구성하여 답변에 따라 변경되는 로직 적용

## 2. 개발 환경

- 사용 언어 : JAVA
- 프로그램 : IntelliJ IDEA
- 서버 :  apache-tomcat-9.0
- DB :  MySQL
- 그 외 : css, html, springboot, JPA, thymeleaf , Jquery 등

## 3. DB 관계도 (ERD)

![image](https://user-images.githubusercontent.com/113402301/201002936-4e226b47-3069-4aa0-b9cd-99e35156cfb3.png)

## 4. 설명

**최근 MBTI 열풍에 따라 각종 성격 유형 테스트가 인기를 얻고 있는 만큼 관심 있던 주제로 토이 프로젝트를 진행**하였습니다. 

6명이 참여한 프로젝트이며, 각자 성격 테스트 모듈 개발 후, Index 페이지에서 각각의 서비스 페이지를 링크로 구성하였습니다.

‘나에게 어울리는 아이스크림은?’ 이라는 주제로 css, Jquery를 이용하여 슬라이드로 화면이 이동 되는 모습을 구현했습니다. 기본 정보가 담기는 user 테이블과 답변을 저장하는 test 테이블로 구성하여  JPA 방식으로 DB 연결을 했습니다. 각각의 정보를 저장 및 결과 리스트를 보여주기 위해 Ajax를 사용하면서 ajax의 개념을 한 번 더 깊게 다질 수 있었습니다. 또, jquery를 사용해보며, javaScript와의 차별적인 유용성을 느낄 수 있었습니다.

## 5. 프로젝트 구조

> 기본 정보 입력 화면
> 

![image](https://user-images.githubusercontent.com/113402301/201002968-9c029f3a-7835-4228-88a5-585fcdfc3a2d.png)

---

> 테스트 진행 화면
> 

![image](https://user-images.githubusercontent.com/113402301/201002991-dd1f0213-19ce-4422-ba6c-90eb4e66e740.png)

---

> 테스트 저장 화면
> 

![image](https://user-images.githubusercontent.com/113402301/201003015-2f2bc739-6059-49ee-9316-2c8ec2b6b8ee.png)

---

> 테스트 결과 화면
>

![image](https://user-images.githubusercontent.com/113402301/201003042-14e0b145-8d55-439c-b724-d31bd3fb2803.png)
