# Привет, я Николай!

**Developer** 📍 Москва

**Московский авиационный институт**

*Бакалавриат — Прикладная математика и информатика (ПМИ)*

---

## Стек технологий

### Языки программирования

* **Python** — FastAPI, Django, Asyncio, Pytest, Pydantic v2, Playwright, HTTPX, Tenacity
* **C/C++** — C++20, Алгоритмы и структуры данных, системное программирование

### Machine Learning & AI

* **Frameworks & Data Science:** PyTorch, Scikit-learn, NumPy, Pandas, Polars, Transformers
* **ML & Models:** LLM architecture, Transformer / SSM hybrids, summarization
* **Engineering, MLOps & Inference:** Production ML, inference optimization, vLLM, SGLang, TensorRT-LLM
* **AI Agents & Tools:** AI agents (фреймворки с ИИ-агентами), LLM integration (OpenRouter), Browser Automation (Playwright), Autonomous Agents

### Backend & API

* **Frameworks:** FastAPI, Django
* **Tools:** Pydantic v2, SQLAlchemy, Alembic, JWT, (Swagger/ReDoc), structlog
* **Architecture:** Clean Architecture, Event-Driven, Microservices, Mesh Networking

### Базы данных & Брокеры

* **SQL:** PostgreSQL, ClickHouse, SQLite (asyncpg)
* **NoSQL:** Redis, MongoDB
* **Message Brokers:** RabbitMQ, Apache Kafka (aiokafka)

### DevOps & Мониторинг

* **Containerization:** Docker, Docker Compose, Kubernetes, Kustomize
* **CI/CD:** GitHub Actions, Makefile, Trivy
* **Monitoring:** Prometheus, Grafana
* **OS:** Linux (Ubuntu/Debian), Bash

---

## Проекты и опыт

### 🔹 [CogniWeb Agent](https://github.com/loks1k192/CogniWeb_Agent?utm_source=gemini)

* **Описание:** Автономный браузерный агент на базе LLM, способный выполнять задачи на естественном языке.
* **Архитектура:** Реализовал трехзвенный конвейер **Plan → Execute → Verify** с использованием системы подагентов (Planner, Executor, Verifier).
* **Особенности:** Внедрил **Security Gateway** для подтверждения критических действий (оплаты, удаления), систему аудита (JSONL) и механизмы детекции зацикливаний.
* **Стек:** Python 3.10+, Playwright, OpenRouter API, Pydantic v2, Asyncio, Tenacity.

### 🔹 [Geobustards Messenger](https://github.com/loks1k192/geobustards-messenger?utm_source=gemini)

* **Событие:** Участие в хакатоне **Nuclear IT Hack 2026 (МИФИ)**, кейс от **Hex.Team**.
* **Описание:** Децентрализованная система связи (mesh-сеть), работающая полностью без интернета и центральных серверов.
* **Реализация:** Разработал с нуля за 30 часов асинхронный TCP-транспорт, flooding-маршрутизацию с дедупликацией и протокол передачи файлов чанками с проверкой SHA-256.
* **Функционал:** Поддержка голосовых звонков (UDP, Jitter buffer), E2E-шифрование (Fernet/AES-128) и мониторинг RTT пиров в реальном времени.
* **Стек:** Python, FastAPI, Asyncio, SQLite, React + Vite, WebRTC (signaling).

### 🔹 [Distributed Event-Driven Analytics Engine](https://github.com/loks1k192/Distributed-Event-Driven-Analytics-Engine?utm_source=gemini)

* Event-driven система аналитики: Ingestor → Kafka → Workers → ClickHouse.
* Мониторинг и визуализация высоконагруженных потоков данных в Grafana.
* **Стек:** Python, FastAPI, Kafka, ClickHouse, Redis.

---

## Образование и развитие

### Высшее образование

**МАИ, Прикладная математика и информатика** — *Бакалавриат*

---

### Профессиональная подготовка

**Яндекс Практикум** — *Backend-разработчик (Python)*

* **Фокус:** Построение отказоустойчивых систем, Django-экосистема и Production-ready API.
* **Результат:** Проектирование сервисов с нуля, работа в команде и прохождение жестких код-ревью.
* **Стек:** `Django` • `DRF` • `PostgreSQL` • `Docker` • `CI/CD`
* **Сертификат:** [Диплом об окончании курса «Python-разработчик»](https://drive.google.com/file/d/12_CyFhs734DL4SruGY4wQmvduXFQvp2O/view?usp=drive_link&utm_source=gemini)

---

## Достижения и практика

### Хакатоны и соревнования

**Nuclear IT Hack 2026 (НИЯУ МИФИ)** | *Участник*

* **Сертификат:** [Подтверждающий сертификат](https://drive.google.com/file/d/1rf5fX7VX6D6DnOFtBvcnUi_k9c_nkFrf/view?usp=sharing&utm_source=gemini)
* **Проект:** [Geobustards Messenger](https://github.com/loks1k192/geobustards-messenger?utm_source=gemini)
* **Кейс:** Система децентрализованной связи (Mesh-сеть) от **Hex.Team**.
* **Результат:** Разработал протокол связи, работающий без интернета, внедрив Flooding-маршрутизацию и асинхронный транспорт на Python.

**AI Wellness Quest 2026 (СБЕР)** | *Участник*

* **Сертификат:** [Подтверждающий сертификат (7-е место)](https://drive.google.com/file/d/1hbXmsN0A6cPP8TlfsFUXI1HLiXzGYMso/view?usp=drive_link&utm_source=gemini)
* **Проект:** [SBER_HACK_SPRING_2026](https://github.com/loks1k192/SBER_HACK_SPRING_2026?utm_source=gemini)
* **Кейс:** Придумать гипотезу, собрать по ней работающий прототип и представить результат жюри.
* **Прототип:** [Худеем на здоровье БЕТА](https://testflight.apple.com/join/jdz6hgS1?utm_source=gemini)
* **Результат:** Реализовал end-to-end прототип сервиса персонального питания: пользователь получает рацион на день с учётом съеденного, КБЖУ и ограничений (аллергии). Интегрировал генерацию меню через GigaChat и связал её с пользовательским сценарием "от рекомендации → к покупке", включая формирование продуктовой корзины. Продемонстрирована работоспособность гипотезы сокращения friction до одного действия пользователя.

**Авиахакатон 2025 (МАИ)** | *Финалист*

* **Трек:** «Системный взлёт» от холдинга **Т1**.
* **Результат:** Спроектировал отказоустойчивую backend-архитектуру для высоконагруженного сервиса, обеспечив обработку запросов в условиях жестких временных рамок хакатона.

**RosEltorg 2026** | *Участник*

* **Сертификат:** [Подтверждающий сертификат (RLT.Hack)](https://drive.google.com/file/d/15x2J9IqNm7ajWTF5MOARSI1bCjAMDtXk/view?usp=sharing&utm_source=gemini)
* **Проект:** [RosEltorg](https://github.com/loks1k192/RosEltorg?utm_source=gemini)
* **Кейс:** Интеллектуальный поиск закупок (RAG-based) для автоматизации подбора тендеров под сложную номенклатурную матрицу поставщика.
* **RAG Architecture:** Реализовал Offline RAG пайплайн без использования внешних облачных API для безопасности данных.
* **Задачи:** Внедрил векторный поиск через pgvector для быстрого отбора релевантных документов из БД. Настроил двухэтапную схему (Bi-Encoder для поиска + Cross-Encoder rubert-tiny2 для финального ранжирования), что значительно повысило точность выдачи.
* **Результат:** Прототип обрабатывает тысячи позиций номенклатуры, сопоставляя их с тендерами по семантическому смыслу, а не просто по ключевым словам.

#### [LeetCode Solutions](https://github.com/loks1k192/neetcode-submission?utm_source=gemini)

*Автоматизированный архив решений алгоритмических задач.*

* **Статус:** Ежедневная практика алгоритмов и структур данных.
* **Стек:** C++, Python.
* **Автоматизация:** Интеграция с NeetCode для синхронизации Accepted-решений.

### Алгоритмическая подготовка

* **Платформа:** [NeetCode.io](https://neetcode.io/?utm_source=gemini)
* **Репозиторий с решениями:** [neetcode-submission](https://github.com/loks1k192/neetcode-submission?utm_source=gemini) — *обновляется автоматически после сабмитов.*
* **Фокус:** Blind 75 / NeetCode roadmap

---

## Связь со мной

* **Telegram:** [@nknyazkov16](https://t.me/nknyazkov16?utm_source=gemini)
* **Email:** n.knyazkov16@gmail.com
* **Hugging Face:** [loks1k](https://huggingface.co/loks1k?utm_source=gemini)
* **Kaggle** [nikolayknyazkov](https://www.kaggle.com/nikolayknyazkov)
