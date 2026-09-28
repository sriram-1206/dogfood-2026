# DOGFOOD 2026 — Architecture

## 1. Project Overview

This project is an open-source, self-hostable hackathon submission and judging platform.

The platform will support:

- User authentication and sessions
- Multiple user roles
- Hackathon event management
- Tracks and prizes
- Team formation
- Project submissions
- Public project gallery
- Judge assignment
- Configurable weighted judging
- Judge score isolation
- Organizer judging progress
- Score normalization
- CSV export

The initial implementation will focus on Tier 1 (T1) and Tier 2 (T2).

---

## 2. Development Model

This project is being developed by one person.

All frontend, backend, database, judging, testing, DevOps, and documentation work will be maintained in the same repository.

The application must use one shared architecture and one consistent database/API design.

---

## 3. Main Technology Stack

The planned stack is:

- Frontend: React
- Backend: Node.js + Express
- Database: PostgreSQL
- Containerization: Docker Compose

The exact implementation may change if required, but the application must remain self-hostable and runnable locally.

---

## 4. Deployment Requirement

The complete application must run locally using:

```bash
docker compose up
