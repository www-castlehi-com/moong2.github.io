---
layout: post
permalink: /medicmagic/
title: "MedicMagic"
image: ../img/portfolio/medicmagic_home.jpg
description: "가임기 여성을 대상으로 한 건강 추적 어플리케이션"
position: "BACK-END Developer"
project-date: "2021.05 ~ "
---

_**[프로젝트 소개 문서 >](https://www.notion.so/Project-3-ideas-df56c48e56604be7a1973a6ce49a5af2){: target="\_blank"}**_

_**[BACK-END Github >](https://github.com/moong2/MedicMagic-BACKEND){: target="\_blank"}**_

_**[FRONT-END Github >](https://github.com/moong2/MedicMagic-FRONTEND){: target="\_blank"}**_

## About

Spring을 이용해서 게시판을 제작하고 소셜로그인 접속이나 aws를 이용한 배포를 한 후 Nginx와 CI/CD를 이용해서 무중단배포를 공부한 프로젝트입니다.

### Main features

- MedicMagic은 여성을 대상으로 건강을 추적하고 관리할 수 있도록 도와주는 안드로이드 기반 어플리케이션입니다.
- 캘린더를 기반으로 한 생리주기와 수면시간, 운동시간 등을 기록할 수 있는 달력 통합 서비스입니다.
- 해당 Repository는 BACKEND 코드를 포함하고 있습니다.
- 사용한 오픈소스의 라이선스의 경우 NOTICE.txt와 http://3.36.134.232:8080/MedicMagic_SPRING 에서 명시하고 있습니다.

### Stack

- Spring Framework / MariaDB / AWS(EC2, RDS) / Apache Tomcat / Linux

---

## Works

1. 개발 환경

- Intellij의 Spring MVC 모듈 사용
- Web 모듈 사용
- 자바 1.8 버전 사용
- TDD를 위한 junit, mock, assertj dependency 사용
- Android Studio와의 로컬 테스트를 위한 tomcat dependency 사용
- 로컬 테스트(mysql)를 위한 mysql-connector와 jdbc dependency 사용
- getEntity의 transaction annotation을 적용하기 위한 tx dependency 사용
- mariaDB 연결을 위한 mariadb.jdbc, mybatis dependency 사용

2. 배포 환경

- 호스팅을 위한 AWS EC2(+탄력적 ip)사용
- 클라우드 데이터베이스를 위한 AWS RDS사용
- EC2에 접근하기 위해 PUTTY사용
- EC2에 TOMCAT 설치 후(sudo yum install tomcat), 프로젝트 BUILD시 생성되는 WAR을 TOMCAT이 배포(FileZilla이용)

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
