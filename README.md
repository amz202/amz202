## About Me:
Backend-focused software engineer with a relentless drive to build resilient systems.

# Tech Stack:

## Core Backend Infrastructure

**Frameworks**<br>
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-000000?style=for-the-badge&logo=node.js&logoColor=339933)
![Kotlin](https://img.shields.io/badge/kotlin-%237F52FF.svg?style=for-the-badge&logo=kotlin&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-2E7D32?style=for-the-badge&logo=springboot&logoColor=white)
![Ktor](https://img.shields.io/badge/Ktor-BF360C?style=for-the-badge&logo=kotlin&logoColor=white)

**Data Layer**<br>
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Drizzle ORM](https://img.shields.io/badge/Drizzle%20ORM-212121?style=for-the-badge&logo=drizzle&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

**Infrastructure**<br>
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![BullMQ](https://img.shields.io/badge/BullMQ-FF4081?style=for-the-badge)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=for-the-badge&logo=socketdotio&logoColor=white)

## Mobile Frontend

![Android](https://img.shields.io/badge/Android-2DBF6C?style=for-the-badge&logo=Android&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white)
![Room DB](https://img.shields.io/badge/Room%20DB-73398D?style=for-the-badge&logo=android&logoColor=white)

# GitHub Stats:
<div style="display: flex; justify-content: center; gap: 20px;">
  <img src="https://streak-stats.demolab.com/?user=amz202&theme=blue_navy&hide_border=true" height="150" />  
  <img src="https://github-readme-stats-six-lime-fr2el28qhs.vercel.app/api/top-langs?username=amz202&locale=en&hide_title=false&layout=compact&card_width=320&langs_count=4&theme=blue_navy&hide_border=true&count_private=true&order=4" height="150" />
</div>

---
# Engineering Portfolio

### [ExploitGrid](https://exploitgrid.net/)
![Role](https://img.shields.io/badge/Role-Full_Stack_Architect-0038A8?style=flat-square) [![Client](https://img.shields.io/badge/Client-Nebulark-1E293B?style=flat-square)](https://www.nebulark.net/) ![Domain](https://img.shields.io/badge/Domain-Cybersecurity-006994?style=flat-square)
> **A cybersecurity threat intelligence platform** that aggregates vulnerability data (CVEs) and exploit proofs-of-concept, tracking them against specific software inventories to provide real-time alerting and cybersecurity risk profiles.

*   **Data Ingestion:** Architected diverse ingestion pipelines (API polling, web scraping, and Git diffing) to continuously synchronize and normalize distributed threat intelligence feeds via transaction-safe `PostgreSQL` batch processing.
*   **Threat Indexing:** Engineered a proprietary composite risk metric for vulnerabilities that evaluates real-world exploitability by blending foundational CVSS scores, predictive EPSS probabilities, and time-decayed exploit evidence with immediate federal catalog overrides.
*   **Event-Driven Alerting:** Built asynchronous, idempotent notification pipelines (Email, Telegram, Discord, WhatsApp) utilizing `BullMQ` and `Redis` pub/sub.
*   **Infrastructure:** Configured `Nginx` reverse proxy for real-time Server-Sent Events (SSE) stream delivery and SSR micro-caching.

<br>

### NUST E-Support System
![Role](https://img.shields.io/badge/Role-Backend_Lead-0038A8?style=flat-square) ![Client](https://img.shields.io/badge/Client-ICT_Dte._NUST-1E293B?style=flat-square) ![Domain](https://img.shields.io/badge/Domain-Enterprise_IT-006994?style=flat-square) ![Status](https://img.shields.io/badge/Status-Pre__Release-D40000?style=flat-square)
> **An enterprise IT support ticketing platform** engineered for the ICT Dte., National University of Sciences and Technology (NUST), managing the complete complaint lifecycle with strict role-based access control (RBAC) for university staff and technicians.

*   **State Machine Logic:** Designed role-based ticket lifecycle transitions enforcing conditional status updates across multiple roles.
*   **Real-Time Events:** Integrated `Socket.IO` for instant, room-based event broadcasting to keep distributed teams synchronized.
*   **Security & Compliance:** Append-only audit logging written in-transaction with every mutating operation, and refresh-token rotation on each use with an absolute expiry to cap refresh chains.

---
