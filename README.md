<div align="center">

![header](https://capsule-render.vercel.app/api?type=rect&color=0:0B1220,50:132238,100:1E3A5F&height=220&section=header&text=Jinhyeok%20Kim&fontSize=52&fontColor=F8FAFC&fontAlignY=42&desc=Java%20%7C%20Spring%20Backend%20Developer&descSize=20&descAlignY=62)

### `Concurrency` · `Realtime` · `Reliability` · `Transaction`

문제를 재현하고 원인을 분석한 뒤, 테스트와 수치로 개선합니다.

<br/>

[![GitHub](https://img.shields.io/badge/GitHub-kimjinhyeok--1-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/kimjinhyeok-1)
[![Blog](https://img.shields.io/badge/Tech%20Blog-Tistory-FF5A4A?style=flat-square&logo=tistory&logoColor=white)](https://developkjh.tistory.com/)
[![Portfolio](https://img.shields.io/badge/Portfolio-Google%20Docs-34A853?style=flat-square&logo=googledocs&logoColor=white)](https://docs.google.com/document/d/13r75qhWY9OhmL4ohsbN09TKPG2AmYU8jbIZe_1XFbJM/edit)

</div>

---

## 👋 About Me

- 🧑‍💻 Java & Spring 기반 백엔드 개발자 김진혁입니다.
- ⚙️ 동시성, 실시간 처리, 데이터 정합성, 장애 복구 문제 해결에 관심이 있습니다.
- 🔍 문제를 재현하고 원인을 분석한 뒤, 테스트와 수치로 개선 결과를 검증하는 과정을 중요하게 생각합니다.
- 🌱 카카오테크 부트캠프 4기 Backend 과정에 참여하고 있습니다.
- 🤝 팀 프로젝트 **Meety**에서 회의·녹음·실시간 전사·알림 API와 AI 요청 신뢰성 개선을 담당하고 있습니다.
- 💼 Bosch Korea 제조혁신팀 인턴으로 업무 자동화를 구현했습니다.

---

## 💻 Tech Stack

### 🚀 Languages
![Java](https://img.shields.io/badge/JAVA-007396?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/PYTHON-3776AB?style=for-the-badge&logo=python&logoColor=white)

### 🌐 Backend
![Spring Boot](https://img.shields.io/badge/SPRING%20BOOT-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Data JPA](https://img.shields.io/badge/SPRING%20DATA%20JPA-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Spring Security](https://img.shields.io/badge/SPRING%20SECURITY-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![Spring Batch](https://img.shields.io/badge/SPRING%20BATCH-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![WebSocket](https://img.shields.io/badge/WEBSOCKET-010101?style=for-the-badge&logo=socketdotio&logoColor=white)
![SSE](https://img.shields.io/badge/SSE-5A29E4?style=for-the-badge)

### 🗃 Databases / Cache
![MySQL](https://img.shields.io/badge/MYSQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/REDIS-DC382D?style=for-the-badge&logo=redis&logoColor=white)

### 🧪 Test / Monitoring
![JUnit5](https://img.shields.io/badge/JUNIT5-25A162?style=for-the-badge&logo=junit5&logoColor=white)
![Mockito](https://img.shields.io/badge/MOCKITO-78A641?style=for-the-badge)
![JaCoCo](https://img.shields.io/badge/JACOCO-CB2C34?style=for-the-badge)
![Spring Actuator](https://img.shields.io/badge/SPRING%20ACTUATOR-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Prometheus](https://img.shields.io/badge/PROMETHEUS-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)

### 🛠 DevOps / Tools
![Docker](https://img.shields.io/badge/DOCKER-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GITHUB%20ACTIONS-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![AWS EC2](https://img.shields.io/badge/AWS%20EC2-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Git](https://img.shields.io/badge/GIT-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GITHUB-181717?style=for-the-badge&logo=github&logoColor=white)

---

## 🚀 Projects

### [Meety | AI 기반 실시간 회의 관리 서비스](https://github.com/100-hours-a-week/KTB4-6th-BE)

- 회의·녹음·실시간 전사·알림 API와 실시간 통신 구조를 설계·개발했습니다.
- 알림 처리를 비동기화해 DB Connection Pool 10개 조건에서 동시 녹음 시작 성공을 **10/50 → 50/50**으로 개선했습니다.
- Redis Pub/Sub과 SSE를 활용해 멀티 인스턴스 환경의 실시간 이벤트 전달 구조를 구현했습니다.
- 회의별 순서 보장 Queue를 적용해 느린 SSE 연결의 지연이 다른 회의로 전파되는 문제를 격리했습니다.
- AI 요청에 조건부 UPDATE와 processingToken 검증을 적용해 중복 실행과 늦은 응답의 잘못된 반영을 방지했습니다.

[Backend Repository](https://github.com/100-hours-a-week/KTB4-6th-BE) · [Team Wiki](https://github.com/100-hours-a-week/KTB4-6th-wiki)

### [Bamboo | 커뮤니티 서비스](https://github.com/100-hours-a-week/KTB4_Jay_Personal_Project_BE)

- Spring Boot·JPA·MySQL 기반으로 게시글·댓글·좋아요·신고·실시간 채팅 기능을 구현했습니다.
- JWT와 Redis를 활용해 인증·Refresh Token 관리 및 WebSocket/STOMP 채팅 구조를 구성했습니다.
- Spring Batch와 ShedLock을 활용해 DAILY / WEEKLY 인기글 랭킹을 주기적으로 집계했습니다.
- 집계 쿼리를 `EXPLAIN ANALYZE`와 인덱스 기반으로 개선해 **328ms → 266ms** 수준으로 최적화했습니다.
- Docker와 GitHub Actions를 활용해 테스트·이미지 빌드·EC2 배포 과정을 자동화했습니다.

[Backend Repository](https://github.com/100-hours-a-week/KTB4_Jay_Personal_Project_BE)

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=kimjinhyeok-1&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="165" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=kimjinhyeok-1&layout=compact&theme=tokyonight&hide_border=true" height="165" />

<br/>

<img src="https://streak-stats.demolab.com?user=kimjinhyeok-1&theme=tokyonight&hide_border=true" />

</div>
