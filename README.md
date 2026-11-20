<div align="center">

![header](https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,100:2F81F7&height=190&section=header&text=Song%20Jihan&fontSize=48&fontColor=FFFFFF&fontAlignY=38&desc=Backend%20Developer%20%7C%20AI%20Service%20Integration&descAlignY=60&descSize=18)

## 안녕하세요, 백엔드 개발 지망생 송지한입니다.

**AI 서비스를 안정적으로 연결하는 백엔드 시스템**에 관심이 있습니다.

단순히 API를 구현하는 것을 넘어  
도메인 상태, 트랜잭션 경계, 비동기 작업, 실패 복구를 함께 고민합니다.

[![Github Badge](http://img.shields.io/badge/-Github-black?style=flat-square&logo=github&link=https://github.com/Song-Jihan)](https://github.com/Song-Jihan)
[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/%EC%A7%80%ED%95%9C-%EC%86%A1-b01334308/)]([https://www.linkedin.com/in/seong-yun-byeon-8183a8113/](https://www.linkedin.com/in/%EC%A7%80%ED%95%9C-%EC%86%A1-b01334308/))

![Velog GitHub stats](https://velog-github-badge.vercel.app/badge/songjihan)

</div>

---

## About Me

컴퓨터공학을 전공하며 **Java와 Spring Boot 기반 백엔드 개발**을 공부하고 있습니다.

현재는 웹사이트 데이터를 수집하고 AI 서버의 평가 결과를 제공하는  
**GEO·JSON-LD 기반 AI 검색 최적화 SaaS**를 개발하고 있습니다.

특히 다음과 같은 문제에 관심이 있습니다.

- 서비스의 책임을 명확하게 분리하는 도메인 설계
- 작업 상태와 재시도 횟수를 관리하는 비동기 처리 구조
- 외부 AI 서버의 지연과 실패를 고려한 안정적인 연동
- PostgreSQL과 JPA를 활용한 데이터 무결성 관리
- 로그와 테스트를 기반으로 한 장애 원인 분석
- 실제 배포 환경을 고려한 인증·보안·인프라 설계

---

## Tech Stack

### Backend

<p>
  <img src="https://img.shields.io/badge/Java%2021-007396?style=flat-square&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring%20Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring%20Data%20JPA-6DB33F?style=flat-square&logo=spring&logoColor=white"/>
  <img src="https://img.shields.io/badge/Hibernate-59666C?style=flat-square&logo=hibernate&logoColor=white"/>
  <img src="https://img.shields.io/badge/Gradle-02303A?style=flat-square&logo=gradle&logoColor=white"/>
</p>

### Database

<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/H2%20Database-09476B?style=flat-square"/>
</p>

### Authentication & Integration

<p>
  <img src="https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white"/>
  <img src="https://img.shields.io/badge/OAuth%202.0-4285F4?style=flat-square&logo=google&logoColor=white"/>
  <img src="https://img.shields.io/badge/REST%20API-005571?style=flat-square"/>
  <img src="https://img.shields.io/badge/JSON--LD-0C479D?style=flat-square&logo=json&logoColor=white"/>
</p>

### Crawling & Data

<p>
  <img src="https://img.shields.io/badge/Jsoup-4B5563?style=flat-square"/>
  <img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=flat-square"/>
</p>

### Infrastructure & Tools

<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white"/>
  <img src="https://img.shields.io/badge/Tailscale-242424?style=flat-square&logo=tailscale&logoColor=white"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white"/>
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white"/>
</p>

---

## 📚 Projects

### GEOmini — AI 검색 최적화 SaaS

> **2026.03 ~ 현재 | 캡스톤디자인·SW상상기업 | 팀 대표·백엔드**

URL에서 본문·메타데이터·JSON-LD를 수집하고, AI 진단 결과와 구조화 데이터 개선안을 제공하는 서비스입니다.

- **담당:** API·DB 설계, Google OAuth2·JWT 인증, 웹페이지 수집과 AI 서버 연동
- **주요 구현:** DB 작업 큐 기반 비동기 분석·재시도, 비관적 잠금과 트랜잭션을 통한 이용권 차감, 개선 전후 재평가

`Java 21` `Spring Boot` `JPA` `PostgreSQL` `Flyway` `Jsoup` `Playwright`

[GitHub](https://github.com/Virtual-Company-Mal-Geum/backend) · [서비스](https://virtual-company-mal-geum.github.io/frontend/) · [시연 영상](https://www.youtube.com/watch?v=Nuw_cNghpzQ)

### FolioLens — 근거를 제시하는 공시 질의응답 Agent

> **2026.07 ~ 2026.09 | 미래에셋증권 AI Festival | 백엔드·AI Agent 오케스트레이션**

공시에서 질문에 필요한 사실을 검색·비교·계산하고, 원문 근거와 정보의 한계를 함께 제시하는 AI Agent입니다.

- **담당:** Spring 기반 Agent 오케스트레이션, 평가 API, 답변 검증 및 제출 서버 배포
- **주요 구현:** LLM 실행 계획 검증, 답변의 수치·근거 대조, 전체 처리 시간 제한과 재시도 제어

`Java 21` `Spring Boot` `PostgreSQL` `HyperCLOVA X` `Docker`

[GitHub](https://github.com/portfolio-disclosure-guardian/foliolens-server) · [역할·설계](https://github.com/portfolio-disclosure-guardian/foliolens-server/blob/develop/docs/role-a/ROLE_A_SPEC.md) · [검증 구현 기록](https://github.com/portfolio-disclosure-guardian/foliolens-server/blob/develop/docs/role-a/A7_COMPLETION_REPORT.md)

### BudgEats SG — 싱가포르 예산 기반 식당 추천

> **2026.08 | 싱가포르 보안 연수·4인·5일 스프린트 | 백엔드**

싱가포르를 방문한 한국 학생을 위해 가격대별 식당 지도와 예산에 맞춘 식사 일정을 제공하는 웹서비스입니다.

- **담당:** Google 로그인·Places API 연동, 사용자·리뷰 모델, 가격 집계와 예산 일정 API
- **주요 구현:** 실제 지출액을 활용한 가격 등급 산정, HttpOnly 서명 쿠키 세션과 리뷰 작성자 검증

`Java 21` `Spring Boot` `JPA` `H2` `Google Places API`

[GitHub](https://github.com/Ctrl-Alt-Defend-KR/budgeats-sg/tree/develop) · [요구사항 명세](https://github.com/Ctrl-Alt-Defend-KR/budgeats-sg/blob/develop/docs/SRS.md)

---

## 🏆 Awards & Research

| 날짜 | 대회 | 수상 |
| --- | --- | --- |
| 2026.10.02 | 2026 AI-Powered SW상상기업 경진대회 · 경기대학교 SW중심대학사업단 | **장려상** · Mal-Geum팀(GEOmini) |
| 2026.06.10 | 한국정보기술학회 2026 하계종합학술대회 및 대학생논문경진대회 | **🥇금상** · [수상 안내](https://ki-it.or.kr/board/maininfo/article/277150) |

**논문:** [LLM의 인용 가능성을 높이는 콘텐츠 구조화 기법: GEO 전략의 실험적 검증](https://www.dbpia.co.kr/journal/articleDetail?nodeId=NODE12901308)

## 🌍 Experience

### 2026 시큐어코딩 해외연수 — 싱가포르

> **2026.08.11 ~ 2026.08.21 | 경기대학교 SW중심대학사업단 주관**

- 위협 모델링, 인증·인가, 클라우드·소프트웨어 공급망 보안 교육과 Burp Suite 웹 보안 실습
- AWS·현대자동차 싱가포르 글로벌 혁신센터(HMGICS) 방문 및 현직자 간담회
- 팀 프로젝트 BudgEats SG 개발 및 성과 발표

[연수 소개](https://www.etnews.com/20260825000344)
· [교내 인터뷰](https://swuniv.kyonggi.ac.kr/community/boardDetail?seq=1734&nowPage=1&searchType=title&searchText=%EC%86%A1%EC%A7%80%ED%95%9C#none)

---

## 🧠 Algorithm Study

자료구조와 알고리즘 문제 풀이를 기록하고 있습니다.

[GitHub](https://github.com/Song-Jihan/Algorithm-Study) · [solved.ac / Baekjoon](https://solved.ac/profile/withsjh0417)
---

</div>
