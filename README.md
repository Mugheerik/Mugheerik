# Mugheer Islam Khattak

**Software Engineer | Backend & Full-Stack Development**
Abbottabad, Pakistan · [LinkedIn](https://www.linkedin.com/in/mugheer-islam-khattak-7a1ab831b/) · [Portfolio](https://mugheer-site.vercel.app/) · mugheer.ik1@gmail.com

I'm a Software Engineering graduate (COMSATS University Islamabad, 2025) who builds backend services and full-stack applications. My work centers on the parts of a system that have to be right: authentication and authorization, relational data models, migrations, automated tests, and reproducible environments.

I build projects end to end: schema design, API, tests, containerized setup, CI, and documentation. Each repository below explains what the application does and how to run and test it.

## What I Work On

- **Backend services:** REST APIs with FastAPI, SQLAlchemy, Pydantic, and Alembic
- **Access control:** JWT authentication, role-based authorization, resource ownership, and multi-tenant data isolation
- **Data:** PostgreSQL schema design, constraints, indexes, migrations, and Redis caching and rate limiting
- **Frontend and integration:** React, TypeScript, and Next.js applications connected to backend APIs and external services
- **Quality:** pytest and HTTPX test suites, Ruff, pre-commit, and GitHub Actions CI
- **Environments:** Docker and Docker Compose for reproducible local setup

## Tech Stack

| Area | Tools |
| --- | --- |
| Languages | Python, TypeScript, JavaScript, SQL |
| Backend | FastAPI, SQLAlchemy, Pydantic, Alembic |
| Frontend | React, Next.js |
| Databases | PostgreSQL, Redis |
| Testing and quality | pytest, HTTPX, Ruff, pre-commit |
| Infrastructure | Docker, Docker Compose, GitHub Actions, Linux |

## Featured Projects

### [Customer360](https://github.com/Mugheerik/customer360-platform): full-stack customer management platform
A React/TypeScript frontend, FastAPI backend, and PostgreSQL database for managing customers, notes, tasks, and an activity timeline.
- Modular monolith with service and repository layers and explicit transaction boundaries
- JWT authentication, role-based authorization, Alembic migrations
- pytest tests, Ruff, pre-commit, and GitHub Actions CI

`Python` `FastAPI` `React` `TypeScript` `PostgreSQL` `SQLAlchemy` `Alembic` `Docker`

### [TeamFlow](https://github.com/Mugheerik/TeamFlow): multi-tenant task management API
A backend for organizations, memberships, projects, and tasks, where access depends on the user's role in each organization.
- Owner/Admin/Member permissions enforced server-side
- Tenant-isolated data access, with constraints and indexes in the PostgreSQL schema
- Automated RBAC and cross-tenant access tests, Docker, and GitHub Actions CI

`Python` `FastAPI` `PostgreSQL` `SQLAlchemy` `Alembic` `pytest` `Docker`

### [Doc Service](https://github.com/Mugheerik/doc-service): AI-assisted document processing
An application for authenticated PDF, DOCX, and TXT uploads, with asynchronous analysis using the Gemini API.
- Asynchronous text extraction with processing status tracking
- PostgreSQL persistence of results, with user-level resource ownership
- Docker Compose setup, migrations, health checks, automated tests, and CI

`Python` `FastAPI` `Next.js` `PostgreSQL` `Gemini API` `Docker Compose`

### [LinkVault](https://github.com/Mugheerik/LinkVault): URL shortening and analytics API
A URL-shortening service with authenticated link management, expiration, redirects, and click analytics.
- Redis caching with PostgreSQL as the source of truth, and fallback when the cache is unavailable
- Redis-backed rate limiting
- Tests for authentication, ownership, rate limiting, and cache-failure fallback

`Python` `FastAPI` `PostgreSQL` `Redis` `Docker` `GitHub Actions`

### [News Broadcast Updates](https://github.com/Mugheerik/newsbroadcast): final-year mobile application
A team-of-3 React Native/Firebase app for community-submitted local news, with admin moderation and AI-assisted video summarization (Python/Flask). I developed the code.

## Engineering Practices

How I approach the work in these repositories:

1. **Design the data first.** Entities, relationships, and constraints come before endpoints.
2. **Enforce access on the server.** Authorization is tested explicitly, including cross-tenant access attempts.
3. **Change schemas through migrations**, never by hand.
4. **Test behavior, not just coverage.** That includes failure cases such as invalid input and an unavailable cache.
5. **Make setup reproducible.** Docker and documented commands let someone else run the project.
6. **Let CI run the checks** I claim in the README.

## More Work: Data and Analytics

SQL, dbt, and Power BI projects: [Healthcare Analytics Platform](https://github.com/Mugheerik/healthcare-analytics-platform) · [Stock Market Analytics Pipeline](https://github.com/Mugheerik/stock-market-analytics-pipeline) · [SaaS Funnel Analytics](https://github.com/Mugheerik/saas-funnel-analytics) · [Reliable Notes API](https://github.com/Mugheerik/reliable-notes-api)

## Education and Certifications

- B.S. Software Engineering, COMSATS University Islamabad, Abbottabad Campus (2021–2025)
- IBM DevOps & Software Engineering · Google Advanced Data Analytics · Google IT Automation with Python · Microsoft Power BI Data Analyst · AWS Cloud Practitioner Essentials (course completion)

## Open To

Junior and associate software engineering, backend development, and full-stack development roles. Remote, hybrid, and on-site opportunities.
