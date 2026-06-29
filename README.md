<h1 align="center">Hi there, I'm sbkim 👋</h1>

<p align="center">
  <a href="https://github.com/starlawzz">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=36BCF7&center=true&vCenter=true&width=480&lines=Backend+Engineer;NestJS+%2F+TypeScript+%2F+Spring;Building+monitoring+%26+IoT+systems;Always+learning+something+new" alt="Typing SVG" />
  </a>
</p>

---

### 🧑‍💻 About Me

- 🔭 **모니터링·실시간 데이터 처리 백엔드** 시스템을 개발하고 있습니다.
- 🌱 **NestJS · TypeScript**를 주력으로 사용합니다.
- ⚙️ gRPC · WebSocket · MQTT 기반의 **실시간 데이터 파이프라인**에 관심이 많습니다.
- 📊 시계열 데이터(InfluxDB)와 멀티 DB 아키텍처를 다룹니다.
- 💬 백엔드 아키텍처, DDD, 분산 시스템 이야기를 좋아합니다.

---

### 🛠️ Tech Stack

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

**Backend**

![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socketdotio&logoColor=white)

**Database & Infra**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![InfluxDB](https://img.shields.io/badge/InfluxDB-22ADF6?style=for-the-badge&logo=influxdb&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)

---

### 📈 GitHub Stats

<p align="center">
  <img width="48%" src="https://github-readme-stats.vercel.app/api?username=starlawzz&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub Stats" />
  <img width="48%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=starlawzz&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top Languages" />
</p>

<p align="center">
  <img width="58%" src="https://streak-stats.demolab.com?user=starlawzz&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</p>

---

### 🚀 Projects

> 공개 저장소 외에 비공개·사내 프로젝트에서 진행한 작업을 익명화하여 정리했습니다.

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>🛰️ 실시간 모니터링 백엔드 플랫폼</h4>
      <p><sub><b>NestJS · TypeScript · gRPC · WebSocket · MQTT</b></sub></p>
      <ul>
        <li>NestJS 모노레포 기반 마이크로서비스 아키텍처 설계</li>
        <li>gRPC · WebSocket · MQTT로 센서 데이터 <b>실시간 수집·전파</b></li>
        <li>PostgreSQL · MongoDB · InfluxDB · Redis <b>멀티 DB</b> 운용</li>
        <li>레거시(Go) 서버의 NestJS 점진적 <b>마이그레이션</b> 주도</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>🔔 알림·이벤트 처리 시스템</h4>
      <p><sub><b>BullMQ · Outbox Pattern · FCM · Event-Driven</b></sub></p>
      <ul>
        <li>도메인 이벤트 기반 알림 fan-out 파이프라인 구축</li>
        <li><b>Outbox 패턴</b> + Consumer Group으로 전송 신뢰성 확보</li>
        <li>FCM data-only 푸시 / 다국어 스냅샷 메시지 처리</li>
        <li>BullMQ 큐로 비동기 작업·재시도 처리</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>🏢 멀티테넌시 아키텍처</h4>
      <p><sub><b>PostgreSQL search_path · TenantContext · TypeORM</b></sub></p>
      <ul>
        <li>스키마 분리(search_path) 기반 <b>멀티테넌트</b> 전환 설계</li>
        <li>요청 단위 TenantContext 전파(미들웨어·Bull·Cron)</li>
        <li>JWT · 서브도메인 · 헤더 3-tier 테넌트 식별 전략</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>🤖 객체 탐지 · 데이터 분석</h4>
      <p><sub><b>Python · YOLOv5 · Jupyter</b></sub></p>
      <ul>
        <li>YOLOv5 기반 객체 탐지 모델 실험</li>
        <li>빅데이터 전처리·분석 (Jupyter / Pandas)</li>
      </ul>
    </td>
  </tr>
</table>

---

### 📫 Contact

[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:seongbeop0@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/starlawzz)

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=starlawzz&style=flat-square&color=36BCF7" alt="Profile views" />
</p>
