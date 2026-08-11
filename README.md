# Привет, я Николай!

**ML Developer** 📍 Москва

**Московский авиационный институт**

*Бакалавриат — Прикладная математика и информатика (ПМИ)*


---

## Стек технологий

### Языки программирования
* **Go** — Standard Library, Gin, Chi, Sqlx, slog, zap, Concurrency, Performance optimization
* **Python** — FastAPI, Django, Asyncio, Pytest, Pydantic v2, Playwright, HTTPX, Tenacity
* **C/C++** — C++20, Алгоритмы и структуры данных, системное программирование

### Backend & API
* **Frameworks:** FastAPI, Django, Gin
* **Tools:** Pydantic v2, SQLAlchemy, Alembic, JWT, (Swagger/ReDoc), structlog
* **Architecture:** Clean Architecture, Event-Driven, Microservices, Mesh Networking
* **AI & Automation:** LLM integration (OpenRouter), Browser Automation (Playwright), Autonomous Agents

### Базы данных & Брокеры
* **SQL:** PostgreSQL, ClickHouse, SQLite (asyncpg, sqlx)
* **NoSQL:** Redis, MongoDB
* **Message Brokers:** RabbitMQ, Apache Kafka (aiokafka)

### DevOps & Мониторинг
* **Containerization:** Docker, Docker Compose, Kubernetes, Kustomize
* **CI/CD:** GitHub Actions, Makefile, golangci-lint, Trivy
* **Monitoring:** Prometheus, Grafana
* **OS:** Linux (Ubuntu/Debian), Bash

---

## Проекты и опыт

### 🔹 [CogniWeb Agent](https://github.com/loks1k192/CogniWeb_Agent)
* **Описание:** Автономный браузерный агент на базе LLM, способный выполнять задачи на естественном языке.
* **Архитектура:** Реализовал трехзвенный конвейер **Plan → Execute → Verify** с использованием системы подагентов (Planner, Executor, Verifier).
* **Особенности:** Внедрил **Security Gateway** для подтверждения критических действий (оплаты, удаления), систему аудита (JSONL) и механизмы детекции зацикливаний.
* **Стек:** Python 3.10+, Playwright, OpenRouter API, Pydantic v2, Asyncio, Tenacity.

### 🔹 [Geobustards Messenger](https://github.com/loks1k192/geobustards-messenger)
* **Событие:** Участие в хакатоне **Nuclear IT Hack 2026 (МИФИ)**, кейс от **Hex.Team**.
* **Описание:** Децентрализованная система связи (mesh-сеть), работающая полностью без интернета и центральных серверов.
* **Реализация:** Разработал с нуля за 30 часов асинхронный TCP-транспорт, flooding-маршрутизацию с дедупликацией и протокол передачи файлов чанками с проверкой SHA-256.
* **Функционал:** Поддержка голосовых звонков (UDP, Jitter buffer), E2E-шифрование (Fernet/AES-128) и мониторинг RTT пиров в реальном времени.
* **Стек:** Python, FastAPI, Asyncio, SQLite, React + Vite, WebRTC (signaling).

### 🔹 [Production-ready Go Backend API](https://github.com/loks1k192/production-ready-backend--API)
* Создал production-ready REST API на Go с JWT-аутентификацией, метриками Prometheus и health checks.
* Реализовал чистую архитектуру (handlers / services / repository).
* **Стек:** Go, PostgreSQL, SQLx, JWT, Prometheus, Docker, GitHub Actions.

### 🔹 [Distributed Event-Driven Analytics Engine](https://github.com/loks1k192/Distributed-Event-Driven-Analytics-Engine)
* Event-driven система аналитики: Ingestor → Kafka → Workers → ClickHouse.
* Мониторинг и визуализация высоконагруженных потоков данных в Grafana.
* **Стек:** Python, FastAPI, Kafka, ClickHouse, Redis.


---

## Образование и развитие

### Высшее образование

**МАИ, Прикладная математика и информатика** — *Бакалавриат*

---

### Профессиональная подготовка

**Яндекс Лицей** — *Веб-разработка на Go (Специализация)*

* **Фокус:** Проектирование архитектуры (common-lib, шаблоны сервисов), декомпозиция задач, работа с транспортным уровнем (Graceful shutdown) и масштабирование.
* **Результат:** Опыт работы с SQL-билдерами, контейнеризацией через Docker, настройкой Nginx и переходом к микросервисной архитектуре.
* **Стек:** `Go` • `PostgreSQL` • `Docker` • `Nginx` • `CI/CD`

**Яндекс Практикум** — *Backend-разработчик (Python)*

* **Фокус:** Построение отказоустойчивых систем, Django-экосистема и Production-ready API.
* **Результат:** Проектирование сервисов с нуля, работа в команде и прохождение жестких код-ревью.
* **Стек:** `Django` • `DRF` • `PostgreSQL` • `Docker` • `CI/CD`
* **Сертификат:** 📜 [Диплом об окончании курса «Python-разработчик»](https://drive.google.com/file/d/12_CyFhs734DL4SruGY4wQmvduXFQvp2O/view?usp=drive_link)

---

## Достижения и практика

### Хакатоны и соревнования

* **Nuclear IT Hack 2026 (НИЯУ МИФИ)** | *Участник*
    * **Сертификат:** 📜 [Подтверждающий сертификат](https://drive.google.com/file/d/1rf5fX7VX6D6DnOFtBvcnUi_k9c_nkFrf/view?usp=sharing)
    * **Проект:** [Geobustards Messenger](https://github.com/loks1k192/geobustards-messenger)
    * **Кейс:** Система децентрализованной связи (Mesh-сеть) от **Hex.Team**.
    * **Результат:** Разработал протокол связи, работающий без интернета, внедрив Flooding-маршрутизацию и асинхронный транспорт на Python.

* **AI Wellness Quest 2026 (СБЕР)** | *Участник*
    * **Сертификат:** 📜 [Подтверждающий сертификат (7-е место)](https://drive.google.com/file/d/1hbXmsN0A6cPP8TlfsFUXI1HLiXzGYMso/view?usp=drive_link)
    * **Проект:** [SBER_HACK_SPRING_2026](https://github.com/loks1k192/SBER_HACK_SPRING_2026)
    * **Кейс:** Придумать гипотезу, собрать по ней работающий прототип и представить результат жюри.
    * **Прототип:** [Худеем на здоровье БЕТА](https://testflight.apple.com/join/jdz6hgS1)
    * **Результат:** Реализовал end-to-end прототип сервиса персонального питания: пользователь получает рацион на день с учётом съеденного, КБЖУ и ограничений (аллергии). Интегрировал генерацию меню через GigaChat и связал её с пользовательским сценарием "от рекомендации → к покупке", включая формирование продуктовой корзины. Продемонстрирована работоспособность гипотезы сокращения friction до одного действия пользователя.

* **Авиахакатон 2025 (МАИ)** | *Финалист*
    * **Трек:** «Системный взлёт» от холдинга **Т1**.
    * **Результат:** Спроектировал отказоустойчивую backend-архитектуру для высоконагруженного сервиса, обеспечив обработку запросов в условиях жестких временных рамок хакатона.

* **RosEltorg 2026** | *Участник*
    * **Сертификат:** 📜 [Подтверждающий сертификат (RLT.Hack)](https://drive.google.com/file/d/15x2J9IqNm7ajWTF5MOARSI1bCjAMDtXk/view?usp=sharing)
    * **Проект:** [RosEltorg](https://github.com/loks1k192/RosEltorg)
    * **Кейс:** Интеллектуальный поиск закупок (RAG-based) для автоматизации подбора тендеров под сложную номенклатурную матрицу поставщика.
    * **RAG Architecture:** Реализовал Offline RAG пайплайн без использования внешних облачных API для безопасности данных.
    * **Задачи:** Внедрил векторный поиск через pgvector для быстрого отбора релевантных документов из БД. Настроил двухэтапную схему (Bi-Encoder для поиска + Cross-Encoder rubert-tiny2 для финального ранжирования), что значительно повысило точность выдачи.
    * **Результат:** Прототип обрабатывает тысячи позиций номенклатуры, сопоставляя их с тендерами по семантическому смыслу, а не просто по ключевым словам.

#### 🏆 [LeetCode Solutions](https://github.com/loks1k192/neetcode-submission)
*Автоматизированный архив решений алгоритмических задач.*
* **Статус:** Ежедневная практика алгоритмов и структур данных.
* **Стек:** C++, Go, Python.
* **Автоматизация:** Интеграция с NeetCode для синхронизации Accepted-решений.

### 🧩 Алгоритмическая подготовка

<p align="left">
  <a href="https://github.com/loks1k192/neetcode-submission">
    <img src="https://img.shields.io/badge/NeetCode-Roadmap_Progress-00C853?style=for-the-badge&logo=leetcode&logoColor=white" />
  </a>
  <img src="https://img.shields.io/badge/LeetCode-Solutions-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" />
  <img src="https://img.shields.io/badge/Stack-C%2B%2B%20%7C%20Go%20%7C%20Python-26A5E4?style=for-the-badge" />
</p>

![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=loks1k192&repo=neetcode-submission&theme=dracula&bg_color=0d1117&hide_border=true&color=00C853)

* **Платформа:** [NeetCode.io](https://neetcode.io/)
* **Репозиторий с решениями:** [neetcode-submission](https://github.com/loks1k192/neetcode-submission) — *обновляется автоматически после сабмитов.*
* **Фокус:** Blind 75 / NeetCode roadmap

---

## Связь со мной

* **Telegram:** [@nknyazkov16](https://t.me/nknyazkov16)
* **Email:** n.knyazkov16@gmail.com
