

Readme · MD
<h1 align="center">안녕하세요, 백엔드 개발자 김주엽입니다 👋</h1> <p align="center"> <em>시스템의 작은 허점까지 파고들어 서비스의 근본적인 안정성을 확보하는 개발자입니다.</em> </p> <br>
🙋 About Me
4인 팀 프로젝트에서 전자결재 모듈을 단독 담당하며, Spring MVC + Thymeleaf 구조를 Spring Boot 3 + Next.js 기반 RESTful API로 리팩토링했습니다. 이 과정에서 회사 ID 검증 누락으로 인한 IDOR 취약점을 스스로 발굴하고, Controller-Service-Mapper 전 계층에 걸쳐 방어 로직을 구축했습니다.

🔐 인가·보안 취약점을 선제적으로 찾아 고치는 것에 관심이 많습니다
🏗️ 백엔드(Spring Boot, JPA/MyBatis)와 프론트엔드(Next.js, Redux-Saga)를 함께 다룹니다
🧭 마감 압박 속에서도 리스크와 우선순위를 냉정하게 판단해 스코프를 조정한 경험이 있습니다
🎓 더조은 컴퓨터아카데미 AI 활용 풀스택 부트캠프 수료 (2026.03 ~ 2026.10)
📫 eyoung071212@gmail.com
🔗 github.com/jooyeap
<br>
🛠️ Tech Stack
Backend

<p> <img src="https://img.shields.io/badge/Java-007396?style=flat&logo=openjdk&logoColor=white"/> <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat&logo=springboot&logoColor=white"/> <img src="https://img.shields.io/badge/Spring%20Security-6DB33F?style=flat&logo=springsecurity&logoColor=white"/> <img src="https://img.shields.io/badge/JWT-000000?style=flat&logo=jsonwebtokens&logoColor=white"/> <img src="https://img.shields.io/badge/JPA-59666C?style=flat&logo=hibernate&logoColor=white"/> <img src="https://img.shields.io/badge/MyBatis-000000?style=flat"/> <img src="https://img.shields.io/badge/Oracle-F80000?style=flat&logo=oracle&logoColor=white"/> <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white"/> <img src="https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white"/> </p>
Frontend

<p> <img src="https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white"/> <img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black"/> <img src="https://img.shields.io/badge/Redux%20Toolkit-764ABC?style=flat&logo=redux&logoColor=white"/> <img src="https://img.shields.io/badge/Ant%20Design-0170FE?style=flat&logo=antdesign&logoColor=white"/> <img src="https://img.shields.io/badge/Thymeleaf-005F0F?style=flat&logo=thymeleaf&logoColor=white"/> </p>
Infra & Tools

<p> <img src="https://img.shields.io/badge/AWS%20EC2-FF9900?style=flat&logo=amazonaws&logoColor=white"/> <img src="https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white"/> <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white"/> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white"/> <img src="https://img.shields.io/badge/OpenAI%20API-412991?style=flat&logo=openai&logoColor=white"/> </p> <br>
🚀 대표 프로젝트
Spring-Breeze-ERP — 4인 팀 ERP 시스템 (전자결재 모듈 단독 개발)
ApprForm(양식) · ApprDoc(결재 문서) · ApprLine(결재선) 3개 도메인을 v1부터 v3까지 반복 개선했습니다.

버전	스택	내용	링크
v3	Spring Boot 3 + Next.js + JWT + AI	Thymeleaf → REST API 전면 전환, IDOR 자체 감사 및 방어 체계 구축	GitHub
v2	Spring Boot + Thymeleaf	결재 양식 버전 관리, 낙관적 락 동시성 제어, AI 양식 자동 생성 최초 구현	GitHub
v1	Spring + MyBatis	전자결재 시스템 기반 구축	GitHub · 시연 영상
핵심 성과

🔐 IDOR 보안 취약점 자체 발굴·방어: getForm, selectDocDetail 등에서 회사 ID 검증 누락 발견 → Controller-Service-Mapper 전 계층에 comId 검증 로직 구축, 권한 체계를 회사 단위 ADMIN/USER로 세분화
🐞 결재 워크플로우 정합성 버그 수정: 다음 결재선이 활성화되지 않는 현상을 로그 분석으로 추적 → 대기(WAI)/미활성(NOT) 상태 처리 메서드가 뒤섞여 있던 것을 activateNextLine으로 분리해 결함률 0%
🤖 AI 연동 결재 양식 자동 생성: OpenAI API(response_format: json_object)로 자연어 입력을 정형 JSON 스키마로 변환, JSON Schema Validation으로 파싱 오류 사전 방어
⚖️ 마감 임박 스코프 조정: 위임전결 자동화 요구사항을 IDOR 리스크와 일정을 근거로 스코프 제외, 코드는 주석 처리로 보존하는 대안 제시
<!-- TODO: v3 시연 영상 녹화 후 링크 추가 --> <br>
📊 GitHub Stats
<p align="center"> <img src="https://github-readme-stats.vercel.app/api?username=jooyeap&show_icons=true&theme=default" /> </p>







