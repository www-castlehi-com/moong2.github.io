---
layout: post
permalink: /board/
title: "board"
image: ../img/portfolio/board_home.jpg
description: "Spring을 이용해서 게시판을 제작하고 소셜로그인 접속이나 aws를 이용한 배포를 한 후 Nginx와 CI/CD를 이용해서 무중단배포를 공부한 프로젝트"
position: "full-stack Developer"
project-date: "2021.02 ~ 2021.04"
---

_**[프로젝트 소개 문서 >](https://www.notion.so/Project-3-ideas-df56c48e56604be7a1973a6ce49a5af2){: target="\_blank"}**_

_**[Github >](https://github.com/moong2/freelec-springboot2-webservice){: target="\_blank"}**_

---

## About

Spring을 이용해서 게시판을 제작하고 소셜로그인 접속이나 aws를 이용한 배포를 한 후 Nginx와 CI/CD를 이용해서 무중단배포를 공부한 프로젝트입니다.

### Main features

- 사용자들은 질문을 올리고, 답변을 달 수 있습니다.
- 사용자들은 마음에 드는 답변을 추천할 수 있습니다.
- 질문자는 받은 답변 중 베스트 3 답변을 선택합니다.
- 답변 선택이 마감된 질문을 확인하면 베스트 3 답변만 표시됩니다.
- 베스트 3 답변 외에도 추천 수가 많은 순서대로 답변을 확인할 수 있습니다.

### Stack

- JavaScript / Node.js / Express.js / Sequelize / Mysql / JWT / AWS(S3, EC2, RDS)

---

## Works

JWT와 Token을 이용한 자동 로그인을 구현하여 잦은 로그아웃으로 인한 불편함 최소화.

로그아웃 시 Blacklist 테이블에 토큰을 저장하여 해당 토큰을 가진 유저는 유효하지 않은 토큰을 가진 것으로 판단하는 로직 추가. 만료되지 않은 토큰으로도 로그아웃을 할 수 있게 구현.

ORM인 Sequelize의 OR과 LIKE 기능을 사용해 등록된 질문 글, 답변 글 검색 기능 구현.

클라이언트가 보낼 수 있는 다양한 입력값에 대한 테스트를 바탕으로 예외처리 및 에러를 검토하여 상황에 따른 response 및 state 전송. 그를 통해 예상치 못한 서버 에러 발생을 최소화함.

AWS의 S3 버킷의 정적 웹 사이트 호스팅 기능을 활용하여 클라이언트를 배포하고, EC2 인스턴스를 생성을 통해 서버를 배포. RDS로 MySQL 데이터베이스 생성 후 EC2와 연결해 EC2의 용량부담을 줄임.

---

## Service GIF

<br/>

_- login_
![Login](/assets/3ideas/01_Login.gif){: width="100%" height="100%"}

_- write question_
![Write_question](/assets/3ideas/02_Write_question.gif){: width="100%" height="100%"}

_- write answer_
![Write_answer](/assets/3ideas/03_Write_answer.gif){: width="100%" height="100%"}

<br>

_- select answer_
![Select_answer](/assets/3ideas/04_Select_answer.gif){: width="100%" height="100%"}

<br>

_- show answers_
![Show_answers](/assets/3ideas/05_Show_answers.gif){: width="100%" height="100%"}

<br>

_- search_
![Search](/assets/3ideas/06_Search.gif){: width="100%" height="100%"}
