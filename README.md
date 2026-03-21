# Prakhar Dwivedi

**Full-Stack · Backend · DevOps · Applied AI**
ECE @ IIIT Bhopal (2027) · Open to internships

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/prakhar-dwivedi-a05611292/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/prakharDvedi)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/prakhar_the_vedi/)
[![CodeChef](https://img.shields.io/badge/CodeChef-5B4638?style=for-the-badge&logo=codechef&logoColor=white)](https://www.codechef.com/users/prakhar_d_vedi)
[![Resume](https://img.shields.io/badge/Resume-PDF-blue?style=for-the-badge&logo=adobeacrobat)](https://drive.google.com/file/d/1G8ENhRTMof0kX5iWo7nZd_wGCwkcvGnW/view)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://prakhardwivedi.vercel.app)

---

## About

I build and ship full-stack systems with a focus on backend reliability, measurable performance, and clean deployment. Currently interning at **Brinavv Technologies** (production MERN stack) and serving as an **LFX Mentee at the Linux Foundation** working on Magma Core's distributed C++ packet-core infrastructure.

What I actually care about:
- Backend systems that don't break in production
- CI/CD pipelines that catch failures before users do
- AI integrations that are reliable, not just impressive in a demo
- Performance you can measure — latency numbers, not vibes

---

## Tech Stack

### Languages
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-003B57?style=for-the-badge&logo=postgresql&logoColor=white)

### Frontend
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/TailwindCSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

### Backend & Databases
![Node.js](https://img.shields.io/badge/Node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

### DevOps & Infrastructure
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white)

### AI & Testing
![LangChain](https://img.shields.io/badge/LangChain-000000?style=for-the-badge)
![Jest](https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white)
![Supertest](https://img.shields.io/badge/Supertest-000000?style=for-the-badge)

---

## Projects

### [PanditAI](https://github.com/prakharDvedi/PanditAI)
**FastAPI · Next.js · Neo4j · Docker**

Neuro-symbolic Vedic astrology application combining Swiss Ephemeris astronomical calculations, a Neo4j knowledge graph of classical astrological rules, and AI inference for natural language readings.

- Reduced median API latency from ~5.4s (cold) to ~2.2s (warm) via `lru_cache` on computation-heavy functions
- Cut backend Docker image size by ~700MB by enforcing CPU-only PyTorch build
- Enforced strict API contracts between FastAPI (Pydantic) and Next.js (TypeScript) to eliminate runtime schema drift

---

### [eVakeel](https://evakeel.vercel.app)
**FastAPI · React · Node.js · WebSockets · Redis · Docker**

Full-stack legal tech application for document-centric workflows and semantic search over legal texts using InLegalBERT.

- Built legal document QA over ~63 high-density chunks, achieving ~50ms warm-start query latency
- Reduced document embedding time from 12s to 1.2s and median API latency from 340ms to 190ms via Redis caching
- WebSocket sessions for real-time low-latency query interactions
- Top 5 finish at HackX 3.0, Manipal University Jaipur

---

### [Chatify](https://github.com/prakharDvedi/Chatify)
**Node.js · Socket.IO · Redis · MongoDB · Docker Compose**

Real-time messaging service with presence tracking, rate limiting, and reliable message persistence across Dockerized services.

---

### [Automated Test Infrastructure for Microservices](https://github.com/prakharDvedi)
**Node.js · Jest · Supertest · Docker · GitHub Actions**

Containerized microservice backend (auth, user, task services) with a comprehensive automated test suite.

- Unit, integration, and API test suites with ~92% branch coverage across 45+ tests
- GitHub Actions CI pipeline — runs tests, lints, and builds Docker images on every PR; blocks merges on failure; completes in ~45s
- Multi-stage Alpine Docker builds reduced container size by ~70%

---

## Experience

**Software Development Intern** · Brinavv Technologies · Jan–Mar 2026
> Production MERN stack — resolved 21 critical bugs in live HR workflows, refactored a backend monolith to CSR pattern, built a full Payroll/Payslip system with MongoDB aggregation pipelines

**LFX Mentee** · The Linux Foundation (Magma Core) · Jan 2026–Present
> Onboarding into Magma Core's distributed C++ packet-core architecture; contributing to Docker migration workflows targeting Ubuntu 24.04 compatibility

**Teaching Assistant** · Digital Logic Design · IIIT Bhopal
> Mentoring 60+ students, assisting with evaluation and problem-solving sessions

---

## Achievements

- 🏆 Top 12K of 262K participants — Adobe India Hackathon 2025 (top 5%)
- 🥇 Ranked 1st in ECE department — Semester 3 (SGPA: 9.32)
- 🏅 Top 5 & Top 20 at inter-college hackathons (CodeUtsav – NIT Raipur; HackX 3.0 – MUJ)
- 💻 LeetCode: 1799 rating · CodeChef: 1614 (3★) · 400+ problems solved

---

## Engineering Principles

- **Measure before optimizing** — latency numbers, not intuition
- **Contracts first** — Pydantic + TypeScript types prevent runtime surprises
- **Deployable by default** — every project ships with a Dockerfile
- **Tests that block bad merges** — CI pipelines that actually enforce quality

---

*If you're building backend systems, DevOps infrastructure, or AI integrations — reach out.*

📧 prakhar.dwivedi.3782@gmail.com
