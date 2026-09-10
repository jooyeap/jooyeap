<h1 align="center">김주엽 · Backend Developer</h1>
<p align="center"><em>시스템의 작은 허점까지 파고들어 서비스의 근본적인 안정성을 확보합니다.</em></p>

<p align="center">
  <a href="mailto:eyoung071212@gmail.com"><img src="https://img.shields.io/badge/Email-eyoung071212%40gmail.com-informational?style=flat"/></a>
  <a href="https://github.com/jooyeap"><img src="https://img.shields.io/badge/GitHub-jooyeap-181717?style=flat&logo=github&logoColor=white"/></a>
</p>

<br>

## Tech Stack

| 구분 | 기술 |
|---|---|
| Backend | ![Java](https://img.shields.io/badge/Java-007396?style=flat&logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat&logo=springboot&logoColor=white) ![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?style=flat&logo=springsecurity&logoColor=white) ![JWT](https://img.shields.io/badge/JWT-000000?style=flat&logo=jsonwebtokens&logoColor=white) ![JPA](https://img.shields.io/badge/JPA-59666C?style=flat&logo=hibernate&logoColor=white) ![MyBatis](https://img.shields.io/badge/MyBatis-000000?style=flat) |
| Database | ![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat&logo=oracle&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white) |
| Frontend | ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black) ![Redux Toolkit](https://img.shields.io/badge/Redux%20Toolkit-764ABC?style=flat&logo=redux&logoColor=white) ![Ant Design](https://img.shields.io/badge/Ant%20Design-0170FE?style=flat&logo=antdesign&logoColor=white) ![Thymeleaf](https://img.shields.io/badge/Thymeleaf-005F0F?style=flat&logo=thymeleaf&logoColor=white) |
| Infra | ![AWS EC2](https://img.shields.io/badge/AWS%20EC2-FF9900?style=flat&logo=amazonaws&logoColor=white) ![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white) |
| AI 연동 | ![OpenAI](https://img.shields.io/badge/OpenAI%20API-412991?style=flat&logo=openai&logoColor=white) |

<br>

## Project — Spring-Breeze-ERP

4인 팀 ERP 시스템 · **전자결재 모듈**(ApprForm/ApprDoc/ApprLine) 단독 개발

| 버전 | 스택 | 링크 |
|---|---|---|
| v3 | Spring Boot 3 + Next.js + JWT + AI | [GitHub](https://github.com/jooyeap/SBErp_v3) · [영상](https://www.youtube.com/watch?v=do1A-hIby4U) |
| v2 | Spring Boot + Thymeleaf | [GitHub](https://github.com/yoonguri988/spring-breeze-erp/tree/main/spring-breeze-erp-v2) |
| v1 | Spring + MyBatis | [GitHub](https://github.com/yoonguri988/spring-breeze-erp/tree/main/spring-breeze-erp-v1) · [영상](https://youtu.be/JktFg-zR71I) |

**핵심 성과**

| 항목 | 내용 |
|---|---|
| 🔐 보안 | 회사 ID 검증 누락(IDOR)을 자체 발굴 → Controller-Service-Mapper 전 계층 comId 검증 구축 |
| 🐞 트러블슈팅 | 결재선 미활성화 버그를 로그 분석으로 추적, `activateNextLine` 분리로 결함률 0% |
| 🤖 AI 연동 | OpenAI API로 자연어 → 결재 양식 JSON 자동 생성, Schema Validation으로 오류 방어 |
| ⚖️ 의사결정 | 마감 임박 시 위임전결 자동화를 리스크 기준으로 스코프 제외, 코드는 주석 보존 |

<!-- TODO: v3 시연 영상 녹화 후 추가 -->
