# Maria Protas

## Lead Developer · Senior Full-Stack Engineer (Python, Go) · SDET

<i@mprotas.ru> · [t.me/vkusniypirogok](https://t.me/vkusniypirogok) · [github.com/Fulmo](https://github.com/Fulmo) · [linkedin.com/in/maria-protas](https://www.linkedin.com/in/maria-protas-9a6168199/) · Nizhny Novgorod, Russia (UTC+3, 2–4h overlap with CET/EET) · English C1 · Remote or relocation

---

## Summary

Engineer with 7+ years of commercial experience, currently leading a team of 11 engineers and still writing production code daily. Core specialisation is backend — Python (advanced) and Go (working knowledge): microservices, gRPC contracts, Kafka and RabbitMQ messaging, PostgreSQL under load. Comfortable owning a system end to end: service boundaries, data model, fault tolerance, deployment and monitoring — including the test infrastructure, which I build as code (fixtures, testcontainers, contract checks, UI automation, load profiles). Second track is machine learning — trained and served models in production at Intel and YADRO, now including LLM integrations.

## Core skills

- **Backend** — Python (FastAPI, Django/DRF, asyncio, Celery, SQLAlchemy, Pydantic 2), Go (Gin, goroutines, gRPC), REST and WebSocket APIs, microservice architecture, Kafka, RabbitMQ, Keycloak (OIDC/SSO), httpx
- **Frontend** — React 18, TypeScript (strict), Next.js, Vue 3 / Nuxt, Tailwind CSS
- **Data** — PostgreSQL (query plans, indexing, partitioning), MongoDB, Redis
- **Infrastructure** — Docker, Kubernetes 1.30+, Helm, GitLab CI, GitHub Actions, Nginx, Linux, Grafana, Prometheus, ELK
- **ML / AI** — PyTorch, TensorFlow / Keras, scikit-learn, model training and serving, MLOps; OpenAI and Anthropic APIs, RAG, function calling
- **Test automation / SDET** — pytest (asyncio, mock, xdist, coverage), testcontainers, Playwright, Jest/Vitest, OpenAPI contract testing (schemathesis), WireMock stubs, Faker and factory-boy, hypothesis, Locust and k6, Allure reports
- **Practices** — system design, SLA/SLO and on-call, incident postmortems, code review, CI quality gates (Ruff, MyPy, basedpyright)

## Experience

### Tech Lead / Lead Full-Stack Developer — Transneft Technologies

*Jun 2025 — Present · IT arm of Transneft, the national oil & gas pipeline operator*

- Designed the platform architecture: decomposed a monolith into services, defined boundaries and contracts, and chose synchronous (gRPC) or asynchronous (Kafka, RabbitMQ) interaction per case
- Led a team of 11 engineers — task decomposition, code review, mentoring, 1-on-1s and hiring — while remaining a hands-on contributor
- Raised test coverage from 20% to 75%+ by building the platform's test infrastructure: fixtures and data factories, testcontainers-based integration tests, OpenAPI contract checks, parallel runs and Allure reports in a CI quality gate
- Cut response time of business-critical APIs by 40% through PostgreSQL query-plan rewrites and covering indexes
- Built core business services in Python 3.12–3.14 (FastAPI, asyncio, SQLAlchemy async, Celery) and latency-sensitive integration services in Go 1.22–1.24
- Owned the SRE side: SLA/SLO for critical services, Grafana and Prometheus alerting, incident postmortems, scheduled on-call, Kubernetes 1.30+ and GitLab CI
- Delivered ML in production — forecasting and classification models (PyTorch, scikit-learn) with versioning, serving and post-release quality monitoring — plus LLM integrations (RAG, function calling) in internal tools

### Senior Full-Stack Developer — YADRO

*Feb 2023 — Jun 2025 · Hardware R&D — servers, storage systems, telecom equipment*

- Built a hardware and software performance monitoring platform on Django 4.2–5.1 / DRF with Vue 3 and TypeScript, serving real-time metrics over REST and WebSocket
- Collected and aggregated device telemetry through async httpx clients with timeouts, retries and connection pooling
- Trained and fine-tuned models on that telemetry (PyTorch, TensorFlow / Keras, scikit-learn): hyperparameter search, regression and classification, evaluation on held-out data
- Operated the platform: GitLab CI releases, Grafana and Prometheus dashboards and alerts, on-call duty and incident analysis
- Implemented single sign-on and fine-grained permissions with Keycloak (OIDC/SSO); wrote metric collectors in Go where a single static binary was required

### AI Systems Engineer / Full-Stack Developer — Intel Corporation

*Feb 2018 — Feb 2022 · Semiconductor / AI & ML*

- Trained and fine-tuned deep learning models (TensorFlow / Keras, PyTorch) and classical models (scikit-learn), owning the full lifecycle from dataset preparation to production inference
- Automated training and retraining pipelines with scheduled retraining and weight rollout into services — MLOps before the term existed
- Built internal web tools and inference services for software and hardware performance analysis: Python (Django, FastAPI from 2019), React 16 and D3.js over PostgreSQL and MongoDB
- Automated QA with pytest and unittest; set up Grafana and Prometheus monitoring

## Selected projects

**Interviews** — offline-first interview-prep platform, in production. 94 study modules and 258 exercises executing code in the browser through Pyodide (Python on WebAssembly) and sql.js, with no server and no internet connection. One Markdown source builds into a web app, a Telegram Mini App and an Android APK, released through CI. *Python, TypeScript, WebAssembly, GitHub Actions*

**Financial dashboard** — analytics over a 1C accounting database, in production. Reads the database file directly without touching the live system, caches ~1.3M ledger entries in memory, and serves turnover, ABC analysis and scenario-based cash-gap forecasts. *Python, FastAPI, React, Plotly, pandas*

**Very Match** — order-intake and analytics bot, in production. Async FastAPI and MongoDB backend with repository and service layers, four FSM-driven scenarios, scheduled jobs for escalations and backups, an analytics dashboard, and 285 unit tests. *Python, aiogram 3, FastAPI, MongoDB, Docker*

## Education

- **M.Sc., Fundamental Informatics and Information Technology** — Lobachevsky State University of Nizhny Novgorod (UNN), 2021
- **B.Sc., Applied Mathematics and Computer Science** — Lobachevsky State University of Nizhny Novgorod (UNN), 2019

## Languages

Russian — native · English — C1 (documentation, negotiations, business correspondence) · Italian — A2
