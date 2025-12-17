# 원데이 클래스 플랫폼 (JSP · Servlet 기반)

![Java](https://img.shields.io/badge/Java-21-007396?style=flat-square&logo=java)
![JSP](https://img.shields.io/badge/JSP-Servlet-orange?style=flat-square)
![MariaDB](https://img.shields.io/badge/MariaDB-10.x-003545?style=flat-square&logo=mariadb)
![Redis](https://img.shields.io/badge/Redis-Cache-DC382D?style=flat-square&logo=redis)
![Selenium](https://img.shields.io/badge/Selenium-Dynamic%20Crawling-43B02A?style=flat-square&logo=selenium)
![Apache Tomcat](https://img.shields.io/badge/Tomcat-9-F8DC75?style=flat-square&logo=apachetomcat)

---

## 프로젝트 소개

JSP와 Servlet 기반으로 구현한 원데이 클래스 웹 플랫폼입니다.  
웹 개발 학습 초기에 진행했던 프로젝트로,  
기능과 구조 측면에서 부족한 부분이 있지만 **전체 서비스 흐름을 직접 구현해보는 데 목적**을 두었습니다.

클래스 데이터 수집부터 저장, 화면 출력, 신청 처리까지  
하나의 웹 서비스가 동작하는 전 과정을 경험하는 데 초점을 맞췄습니다.

---

## 주요 구현 및 경험

- JSP / Servlet 기반 서버 사이드 렌더링 구조 구현
- MariaDB를 사용한 관계형 데이터 관리
- Redis를 활용한 세션 처리 및 캐싱 경험
- 클래스 등록, 조회, 검색, 신청 흐름 구현
- 카테고리 기반 필터 및 페이징 처리
- Selenium을 활용한 **동적 웹 크롤링 구현**
- 크롤링한 데이터를 DB에 저장하여 서비스 데이터로 활용

---

## 동적 크롤링

- Selenium을 사용해 자바스크립트로 렌더링되는 페이지 크롤링
- 클래스 제목, 설명, 가격, 일정, 강사 정보, 이미지 등 데이터 수집
- 클래스별 이미지 파일을 로컬에 저장하고 DB와 연동
- 깨진 이미지 URL 및 예외 상황 처리 경험

정적 크롤링과 달리,  
실제 서비스 환경에서 동적으로 로드되는 데이터를 수집하는 과정을 직접 구현했습니다. 

---

## 기술 스택

### Backend
- Java 21
- JSP / Servlet
- Apache Tomcat
- MyBatis
- MariaDB
- Redis

### Crawling
- Selenium (Dynamic Crawling)

### Frontend
- HTML / CSS
- Bootstrap
- JavaScript
---

## 프로젝트 목적

- Java 기반 웹 애플리케이션의 동작 원리 이해
- 요청/응답 흐름 및 서버 사이드 렌더링 경험
- 동적 크롤링을 통한 데이터 수집과 활용
- 데이터베이스, 서버, 화면을 연결하는 전체 흐름 학습


