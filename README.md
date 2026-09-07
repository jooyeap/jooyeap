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
| Backend | Java · Spring Boot 3 · Spring Security · JWT · JPA · MyBatis |
| Database | Oracle · MySQL · Redis |
| Frontend | Next.js · React · Redux Toolkit / Saga · Ant Design · Thymeleaf |
| Infra | AWS EC2 · Nginx · GitHub Actions · Docker |
| AI 연동 | OpenAI API (JSON Schema 기반 구조화 응답) |

<br>

## Project — Spring-Breeze-ERP

4인 팀 ERP 시스템 · **전자결재 모듈**(ApprForm/ApprDoc/ApprLine) 단독 개발

| 버전 | 스택 | 링크 |
|---|---|---|
| v3 | Spring Boot 3 + Next.js + JWT + AI | [GitHub](https://github.com/yoonguri988/spring-breeze-erp/tree/main/spring-breeze-erp-v3) |
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

<br>

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=jooyeap&show_icons=true&theme=default" />
</p>
