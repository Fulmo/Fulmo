<img src="avatar.png" alt="Мария Протас" align="right" width="150">

<!-- lang-switch -->
[![Русский](https://img.shields.io/badge/%F0%9F%87%B7%F0%9F%87%BA_Русский-a8481c?style=flat)](README.md) [![English](https://img.shields.io/badge/%F0%9F%87%AC%F0%9F%87%A7_English-8a8580?style=flat)](README.en.md) [![Сайт](https://img.shields.io/badge/%F0%9F%8C%90_Сайт-2f4858?style=flat)](https://fulmo.github.io/Fulmo/)

# Мария Протас

## Lead Developer / Senior FullStack Developer (Python, Go) / ML

[![Telegram](https://img.shields.io/badge/Telegram-@vkusniypirogok-2CA5E0?style=flat&logo=telegram)](https://t.me/vkusniypirogok)
[![GitHub](https://img.shields.io/badge/GitHub-Fulmo-181717?style=flat&logo=github)](https://github.com/Fulmo)
[![Email](https://img.shields.io/badge/Email-i@mprotas.ru-D14836?style=flat&logo=gmail)](mailto:i@mprotas.ru)
[![Location](https://img.shields.io/badge/Location-Нижний%20Новгород-4285F4?style=flat&logo=google-maps)](https://maps.google.com/?q=Нижний+Новгород)
[![Remote](https://img.shields.io/badge/Формат-Remote%20%2F%20Hybrid-34D399?style=flat)](/)

---

## 📊 Статистика

| 🏆 Опыт | 🏢 Компании | 👥 Команда | 💎 Уровень | 💰 Ожидания |
|:---:|:---:|:---:|:---:|:---:|
| **7+ лет** | Intel · YADRO · Транснефть | **11 человек** | **Senior / Lead** | **400 000 ₽/мес** |

---

## 👩‍💻 Профессиональный профиль

**Разработчик** с 7+ годами коммерческого опыта, веду команду из 11 инженеров. Пишу код каждый день — лидерство не заменило инженерную работу, а добавилось к ней.

**Backend** — основная специализация: Python (Senior) и Go (Middle+). Микросервисы, gRPC-контракты, асинхронное взаимодействие через Kafka и RabbitMQ, оптимизация PostgreSQL под нагрузкой. Проектирую системы целиком: границы сервисов, схема данных, отказоустойчивость, деплой, мониторинг.

**FullStack** — React и TypeScript в проде: SPA поверх собственных API, Next.js для SSR, Vue 3 там, где так сложилось исторически.

**Инженерная культура**: тесты как часть определения готовности (покрытие 20% → 75%+ на текущем проекте), обязательное code review, статическая проверка типов в CI.

**SDET-часть работы**: тестовую инфраструктуру строю сама и как код — фикстуры и фабрики данных, интеграционные тесты на testcontainers, стабы внешних API, контрактные проверки по OpenAPI, UI-автотесты на Playwright, параллельный прогон и отчёты в CI. Качество для меня — не отдельная роль рядом с разработкой, а свойство пайплайна: пока автотесты не гоняются на каждый мерж, «готово» не наступает.

**ML и глубокое обучение** — второе направление: в Intel и YADRO обучала и дообучала модели (TensorFlow / Keras, PyTorch, Scikit-learn), подбирала гиперпараметры, решала задачи регрессии и классификации — от подготовки датасета до инференса в проде.

Открыта к позициям: **Lead Developer · Team Lead · Senior Backend (Python / Go) · Senior FullStack · SDET / Test Automation · ML Engineer**

---

## 🛠 Технический стек

### Backend

```
Python (Senior)   ●●●●●  FastAPI 0.115+ · Django 4.2–6.1 / DRF 3.15+ · asyncio · Celery · SQLAlchemy async · Pydantic 2
HTTP-клиенты      ●●●●●  httpx 0.28 (async, таймауты, ретраи, пулы) · requests · aiohttp
Авторизация       ●●●●○  Keycloak 26 (OIDC / SSO) · OAuth2 · JWT · роли и права
Go (Middle+)      ●●●●○  Gin · Echo · goroutines · channels · context · sync · gRPC · статические бинари
gRPC / protobuf   ●●●●○  контракты между сервисами · streaming · генерация клиентов
Микросервисы      ●●●●○  границы сервисов · API Gateway · идемпотентность · graceful degradation
Очереди           ●●●○○  Kafka (топики, партиции, consumer groups) · RabbitMQ (exchange, DLQ, retry)
REST API          ●●●●○  OpenAPI · Swagger · WebSocket · версионирование
Node.js           ●●●○○  Express · Nest.js — сервисы и BFF под фронтенд
Rust              ●●○○○  пет-проекты и CLI-утилиты (~2 года): ownership, tokio, serde, cargo
```

### Frontend

```
React             ●●●●○  React 18+ · hooks · контекст · Redux/Zustand · React Query
TypeScript        ●●●●○  strict · дженерики · типизация API-контрактов · ES2022+
Next.js           ●●●●○  SSR/SSG · App Router · оптимизация загрузки
Vue.js / Nuxt     ●●●●○  Vue 3 · Composition API · Pinia · Nuxt 3
HTML5 / CSS3      ●●●●●  Tailwind CSS · адаптивная вёрстка · доступность
React Native      ●●○○○  Expo · мобильные экраны поверх общего API (пет-проекты)
```

### Базы данных

```
PostgreSQL        ●●●●●  планы запросов · индексы · партиционирование · транзакции и блокировки
MongoDB           ●●●●○  motor (async) · агрегации · схемы и индексы
Redis             ●●●●○  кэш · pub/sub · очереди задач · распределённые блокировки
```

### Системный дизайн

```
Проектирование    ●●●●○  декомпозиция монолита · выбор синхрон/асинхрон · схема данных
Надёжность        ●●●●○  таймауты · ретраи с backoff · circuit breaker · идемпотентность
Нагрузка          ●●●○○  кэширование · пулы соединений · профилирование узких мест
```

### QA / SDET и качество кода

```
pytest            ●●●●●  юнит · параметризация · фикстуры · моки · покрытие (pytest-cov)
Экосистема pytest ●●●●○  pytest-asyncio · pytest-mock · pytest-xdist (параллельный прогон) · Allure-отчёты
Интеграционные    ●●●●○  testcontainers · тестовая БД · WireMock и стабы внешних API
API-контракты     ●●●●○  контрактные тесты по OpenAPI · schemathesis · Postman / Newman
UI-автотесты      ●●●●○  Playwright · Jest / Vitest
Тестовые данные   ●●●○○  Faker · factory-boy · hypothesis (property-based)
Нагрузка          ●●●○○  Locust · k6 — профили нагрузки, поиск узких мест
Процесс           ●●●●●  code review · quality gate в CI · Ruff · MyPy · basedpyright (strict) · pre-commit
```

### DevOps и инфраструктура

```
Docker / K8s      ●●●●○  многостадийные сборки · Docker Compose · Helm · Kubernetes
CI/CD             ●●●●○  GitLab CI · GitHub Actions · автотесты и линтеры на каждый PR
Linux / Bash      ●●●●●  автоматизация · скрипты · администрирование серверов
Observability     ●●●●○  Grafana · Prometheus · ELK · структурные логи
```

### SRE / DevOps

```
Kubernetes       ●●●●○  1.30+ · Helm · выкаты, ресурсные лимиты, health-пробы
CI/CD            ●●●●○  GitLab CI · GitHub Actions · quality gate, автотесты на каждый мерж
Наблюдаемость    ●●●●○  Grafana · Prometheus — дашборды, алерты, метрики сервисов
SRE-практики     ●●●●○  SLA/SLO · дежурства по графику · разбор инцидентов и постмортемы
```

### AI / ML

```
LLM / RAG         ●●●●○  OpenAI · Anthropic (Claude) API · RAG · function calling · LangChain
Глубокое обучение ●●●●○  PyTorch · TensorFlow · Keras — CNN/RNN, обучение и дообучение моделей
Классический ML   ●●●●○  Scikit-learn — регрессия, классификация, кросс-валидация, метрики
Обучение моделей  ●●●●○  подготовка датасетов · подбор гиперпараметров · регуляризация · инференс в проде
MLOps             ●●●○○  версионирование моделей · регулярный ретрейн · выкат весов · контроль качества после релиза
```

`Git` `Nginx` `Jira` `Confluence` `Agile` `Scrum` `System Design` `Code Review`

---

## 💼 Опыт работы

### 🔴 Транснефть-Технологии — Tech Lead / Lead Fullstack Developer

**Июнь 2025 — настоящее время** · *Нефть & Газ / Enterprise IT*

- 🏗 **Спроектировала архитектуру платформы**: разделила монолит на микросервисы, определила границы и контракты, под каждую задачу выбрала синхронное (gRPC) или асинхронное (очереди) взаимодействие
- 👥 **Веду команду из 11 разработчиков**: декомпозирую задачи, ревьюю код, менторю, провожу 1-on-1 и собеседования — не переставая писать код сама
- ✅ **Подняла покрытие тестами с 20% до 75%+**: ввела pytest и интеграционные тесты на testcontainers, quality gate в CI и обязательное ревью перед мержем
- 🧪 **Построила тестовую инфраструктуру платформы (SDET)**: слой фикстур и фабрик данных (Faker, factory-boy), поднятие зависимостей в testcontainers, стабы внешних API, контрактные проверки по OpenAPI (schemathesis), параллельный прогон (pytest-xdist) и Allure-отчёты в GitLab CI; нагрузочные профили критичных ручек на Locust перед выкатом
- 📈 **Ускорила критичные API на 40%**: переписала планы запросов и добавила покрывающие индексы в PostgreSQL
- 🐍 **Написала основные бизнес-сервисы на Python 3.12–3.14**: FastAPI 0.115+, asyncio, SQLAlchemy async, Celery
- 🐹 **Вынесла интеграции и фоновую обработку в сервисы на Go 1.22–1.24** (Gin) — там, где важны latency и параллелизм: goroutines, channels, context с отменой, статические бинари без рантайма на целевой машине
- 🔄 **Развела сервисы через Kafka и RabbitMQ**: идемпотентные обработчики, DLQ, политики повторов
- 🚀 **Собрала фронтенд поверх собственных API**: React SPA на TypeScript — формы, таблицы с серверной пагинацией, разграничение прав
- 🛡 **Отвечаю за эксплуатацию**: SLA/SLO на критичные сервисы, алерты в Grafana/Prometheus, разбор инцидентов и постмортемы, дежурства по графику; Kubernetes 1.30+, GitLab CI
- 🧠 **Вывела ML в прод на данных платформы**: модели прогнозирования и классификации (PyTorch 2.x, Scikit-learn 1.5+), подбор гиперпараметров, версионирование, сервис инференса, контроль качества после каждого выката
- 🤖 **Встроила LLM во внутренние сервисы**: OpenAI и Anthropic Claude API, RAG, function calling
- 🔗 **Закрыла интеграции и единый вход**: httpx (async, таймауты, ретраи, пулы соединений), Keycloak 26 (OIDC/SSO, JWT, роли)

`Python` `FastAPI` `httpx` `Keycloak` `Go` `gRPC` `Kafka` `RabbitMQ` `React` `TypeScript` `PostgreSQL` `Redis` `Docker` `K8s` `GitLab CI` `LLM` `PyTorch` `Scikit-learn`

### 🟣 YADRO — Senior FullStack Developer

**Февраль 2023 — Июнь 2025** · *Software / Hardware R&D*

- 🌐 **Построила веб-платформу мониторинга производительности железа и ПО**: Django 4.2–5.1 / DRF 3.14+, Vue 3 (Composition API), TypeScript 5
- 🔌 **Отдала метрики в реальном времени**: REST API и WebSocket; собирала и агрегировала телеметрию с оборудования на httpx (async, таймауты, ретраи)
- 🧠 **Обучала и дообучала модели на телеметрии** (PyTorch 2.0–2.5, TensorFlow / Keras 2.12+, Scikit-learn 1.3+): подбор гиперпараметров, регрессия и классификация, оценка на отложенной выборке
- 🛠 **Эксплуатировала платформу**: сборки и выкаты через GitLab CI, дашборды и алерты в Grafana / Prometheus, дежурства и разбор инцидентов
- 🔐 **Внедрила единый вход** и разграничение прав через Keycloak (OIDC/SSO)
- 🐹 **Написала утилиты сбора метрик на Go 1.20–1.23** — там, где нужен один статический бинарь без рантайма на целевой машине
- 🧩 **Поддерживала компонентную библиотеку** Vue 3 (Pinia) и контракты OpenAPI/Swagger
- ✅ **Автоматизировала регресс на всём стеке**: pytest на бэкенде и Jest на фронтенде, UI-сценарии на Playwright, прогон на каждый мерж в GitLab CI; code review, Scrum

`Python` `Django 4–5` `DRF` `httpx` `Keycloak` `Go` `Vue 3` `TypeScript` `PostgreSQL` `MongoDB` `Docker` `pytest` `Jest` `PyTorch` `TensorFlow` `Scikit-learn`

### 🟢 Intel Corporation — AI Systems Engineer / FullStack Developer

**Февраль 2018 — Февраль 2022** · *Semiconductor / AI & ML*

- 🧠 **Обучала и дообучала модели глубокого обучения** на TensorFlow 1.15–2.8 / Keras и PyTorch 1.x, классические алгоритмы — на Scikit-learn 0.20–1.0
- 🎛 **Вела модель полного цикла**: подготовка и разметка датасетов, выбор архитектуры, подбор гиперпараметров, регуляризация, метрики регрессии и классификации, инференс в проде
- ♻️ **Автоматизировала обучение и переобучение**: подготовка данных, регулярный ретрейн, выкат весов в сервисы — MLOps до того, как это так назвали
- ⚡ **Подняла сервисы инференса и внутренние API на FastAPI** (с 2019): асинхронная выдача предсказаний, валидация запросов на Pydantic, интеграция с пайплайнами обучения
- 🔬 **Построила веб-инструменты анализа производительности ПО и железа**: Python 3.6–3.9 (Django 2.0–4.0, FastAPI 0.4x–0.7x), React 16, D3.js
- 🗃 **Отдала данные через REST API**: PostgreSQL 9.6–13 и MongoDB 4.x, дашборды на больших выборках
- 🧪 **Автоматизировала тестирование инструментов анализа** (pytest, unittest): регрессионные наборы на реальных датасетах, проверка стабильности метрик модели между прогонами; мониторинг в Grafana / Prometheus

`Python` `Django 2–4` `FastAPI` `React` `TypeScript` `D3.js` `PostgreSQL` `MongoDB` `Docker` `Grafana` `TensorFlow` `Keras` `PyTorch` `Scikit-learn` `Deep Learning`

---

## 🚀 Собственные проекты

Пет-проекты в production — там я отвечаю за систему целиком: схему данных, архитектуру, деплой, мониторинг и восстановление после сбоев.

### 📚 Interviews — офлайн-платформа подготовки · `production`

*Python · TypeScript · WebAssembly · Android · CI/CD*

- **94 материала и 258 задач** с исполнением кода прямо в браузере: **Pyodide** (Python в WASM) и **sql.js** — без сервера и без интернета
- **Один источник — три продукта**: Markdown + Jupyter собираются в веб-версию, Telegram Mini App и Android-APK; сборка и релиз APK автоматизированы в CI
- Системная задача: офлайн-first — весь рантайм, поиск и подсветка кода упакованы в статику; прогресс хранится локально

`Python` `TypeScript` `WebAssembly` `Pyodide` `Android` `GitHub Actions`

### 💰 Финансовый дашборд по данным 1С · `production`

*Python · FastAPI · React · Plotly · pandas*

- Веб-аналитика поверх бухгалтерии 1С: прямое чтение `.1CD` через onec_dtools (без COM, не блокирует боевую базу), in-memory кэш **~1,3 млн проводок**
- Backend FastAPI + REST API: обороты по счетам, корреспонденция, топ-контрагенты, **ABC-анализ** (80/15/5), YoY-динамика
- **Прогноз кассовых разрывов** (сценарный, 30/60/90 дней); health-check данных (дубли, отсутствующие реквизиты)
- Frontend: React SPA (Vite + TypeScript) + Plotly; Ruff + MyPy + basedpyright (strict), pre-commit, GitHub Actions CI

`Python` `FastAPI` `React` `TypeScript` `Plotly` `pandas` `GitHub Actions`

### 🎂 Very Match — приём заказов и аналитика · `production`

*Python · aiogram 3 · FastAPI · MongoDB · Docker*

- Бот полного цикла приёма заказов: **4 сценария на FSM**, каталог с модификаторами через внешний API, синхронизация каждые 6 часов
- **Async-бэкенд** FastAPI + MongoDB (motor), слой репозиториев и сервисов, Pydantic 2; реле «клиент ↔ менеджер» в форум-темах супергруппы
- **APScheduler**: эскалации, напоминания об оплате, отложенные отзывы, авто-бэкап БД
- **Веб-дашборд** (FastAPI + Chart.js): KPI, конверсия, сегментация клиентов; экспорт в CSV/XLSX
- Надёжность: анти-спам middleware, healthcheck, авто-рестарт polling, ротация логов
- **285 юнит-тестов** · Ruff + MyPy + basedpyright · многостадийный Docker (non-root) · CI

`Python 3.14` `aiogram 3` `FastAPI` `MongoDB` `Pydantic 2` `APScheduler` `Docker` `pytest`

### 🥗 HProject — health-бот с распознаванием еды · `production`

*Python · FastAPI · PostgreSQL · LLM*

- Расчёт КБЖУ по фотографии блюда: пайплайн **«фото → LLM-распознавание → нормализация к справочнику → дневник питания»**
- Проектирование под ненадёжную внешнюю модель: таймауты, ретраи, деградация до ручного ввода при отказе LLM
- Дневник питания и статистика: агрегации по периодам, цели по калориям

`Python` `FastAPI` `PostgreSQL` `LLM` `aiogram`

### 🛡️ VPNTunnel — VPN-роутер на sing-box · `self-hosted`

*Python (stdlib) · asyncio · sing-box · launchd*

- Парсинг подписок (VLESS/VMess/Trojan/Shadowsocks), async TCP-пинг пула серверов, выбор лучшего по доступности → стабильности → скорости
- **Двухфазная оценка**: gate и стабильность для всех, реальный throughput — только для топ-3; sticky-логика и авто-откат конфига при провале
- Системная часть: генерация конфигов sing-box (TUN + typed DNS), автозапуск через launchd, Telegram-уведомления
- Чистый stdlib, **69 тестов**, ruff/mypy/basedpyright (strict) — 0 ошибок

`Python` `asyncio` `sing-box` `launchd` `pytest`

### 🤖 zentist-rpa — RPA-платформа для внешних порталов · `production`

*Python · Playwright · PostgreSQL · Docker*

- Автоматизация работы с порталами без публичного API: браузерные сценарии на Playwright
- Устойчивость к сменам вёрстки: несколько стратегий поиска элементов, ретраи, журналирование каждого шага для разбора падений
- Очередь заданий и отчёты о выполнении

`Python` `Playwright` `PostgreSQL` `Docker`

---

## 🎓 Образование

| Степень | Год | Учебное заведение | Специальность |
|---------|-----|-------------------|---------------|
| 🎓 **Магистр** | 2021 | ННГУ им. Лобачевского (ИИТММ) | Фундаментальная информатика и информационные технологии |
| 📚 **Бакалавр** | 2019 | ННГУ им. Лобачевского (ИИТММ) | Прикладная математика и информатика |

---

## 🌍 Языки

🇷🇺 **Русский** — родной  ·  🇬🇧 **English** — C1 (документация, переговоры, деловая переписка)  ·  🇮🇹 **Italiano** — A2

---

## 🔎 Дополнительно

**Изучаю сейчас:** Kubernetes (CKA), Apache Kafka, Rust (пет-проекты и CLI-утилиты, ~2 года), React Native

**Форматы работы:** Remote · Hybrid (Нижний Новгород) · командировки · проектная / частичная занятость

**Открыта к ролям:** Lead Developer / Team Lead · Senior Backend (Python / Go) · Senior FullStack · SDET / Senior QA Automation · Senior Frontend (React / Vue)

---

## 📞 Контакты

| | |
|---|---|
| **Телефон** | +7 (910) 791-30-18 |
| **Email** | <i@mprotas.ru> |
| **Telegram** | [@vkusniypirogok](https://t.me/vkusniypirogok) |
| **GitHub** | [github.com/Fulmo](https://github.com/Fulmo) |
| **Локация** | Нижний Новгород |

---

*Резюме обновлено: Август 2026*
