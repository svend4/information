# Каталог публичных технических репозиториев `svend4`

Единый реестр-навигатор **93 открытых (Public) технических и исследовательских проектов** аккаунта [`svend4`](https://github.com/svend4?tab=repositories).

> [!NOTE]
> В данном открытом каталоге собраны исключительно **публичные технические и общие проекты** (`93` репозитория). Социальные и закрытые репозитории в этом публичном реестре не перечисляются и ведутся отдельно в приватном репозитории.

---

## Сводка по открытой части профиля

- **Всего публичных технических репозиториев:** **93**
- **Состояние документации (`README.md`):**
  - **Подробный `README.md` на `main`:** 55 (плюс `cardix` обновлён напрямую в `main` — итого **56**)
  - **Краткий `README.md` (169–385 симв.):** 12
  - **Новые русские `README.md` в ветке `docs/add-readme-ru` (готовы к открытию PR):** 18
  - **Открыты PR с русским `README.md` (`docs/add-readme-ru`):** 3 (`game-apps` #3, `new-project-ai-colab` #2, `gameco` #1)
  - **Пустые заготовки без кода (кандидаты на архивацию/очистку):** 3 (`4p`, `infod20`, `infod30`), плюс [information](https://github.com/svend4/information) выбран в качестве центрального каталога (ветка `docs/catalog`)
- **Многоветочные проекты:** детальная ревизия всех веток и рекомендации по слиянию приведены в [BRANCH_AUDIT.md](./BRANCH_AUDIT.md).

---

## 1. Базы знаний, вики-системы, RAG и оркестрация ИИ-агентов (22)

| Репозиторий | Стек | Описание | README / Ветки |
| :--- | :--- | :--- | :--- |
| [info](https://github.com/svend4/info) | Markdown | Энциклопедическая база знаний по концепциям, числам, природе, истории, науке, медицине и ИТ (39 документов в 10 категориях) | Подробный `README.md` · 3 ветки (2 влиты) |
| [info1](https://github.com/svend4/info1) | Python, HTML/JS SPA, Docker, Markdown | Информационно-операционная система для дома на карточной методологии (`⇑⇓↔`) с CLI/Web UI и AI-генератором | Подробный `README.md` · 2 ветки (1 влита) |
| [info2](https://github.com/svend4/info2) | Node.js, Express, React/Next.js, PG/Redis/ES, K8s | Архитектура и прототип T-Hub — платформы content-addressed дедупликации и реестра компонентов | Подробный `README.md` · 2 ветки (1 влита) |
| [info3](https://github.com/svend4/info3) | Python (FastAPI, FAISS, Neo4j), React, Chart.js | Четырёхчастная система представления знаний (формулы, архетипы, алгоритмы, теоремы) и прототипы RAG | Краткий `README.md` · 3 ветки, открыт PR #9 |
| [info4](https://github.com/svend4/info4) | Markdown, YAML, Python, Bash | Коллекция из 100+ `.skill`-пакетов Claude Skills, чекпоинтов и методических руководств | Краткий `README.md` · 4 ветки (3 влиты) |
| [info5](https://github.com/svend4/info5) | Markdown | Методология 4-уровневой пирамиды автоматизации офисных процессов (от приложений к агентам) | Подробный `README.md` · 2 ветки (1 влита) |
| [info7](https://github.com/svend4/info7) | TypeScript (`pnpm` workspaces), Markdown | Монорепозиторий AI-платформы из 4 пакетов (`openclaw-meta-agents`, `info7`, `leonardo-ai`, `orchestrator-kit-enterprise`) | Подробный `README.md` · 3 ветки (`n1kNz` неслитая) |
| [info10](https://github.com/svend4/info10) | Python, Docker; на `Nfh4B` — React/TS/Vite | Web/MCP-шлюз `daf-gateway` (3 варианта запуска); в ветке `Nfh4B` лежит отдельный прототип магазина | `docs/add-readme-ru` · 3 ветки (1 посторонняя) |
| [info15](https://github.com/svend4/info15) | Markdown | Структурированная LLM-вики по каналу `@yersham` об ИИ-инновациях, контекст-инжиниринге и SDD (`yersham_wiki/`) | `docs/add-readme-ru` · 5 веток (3 влиты) |
| [info30](https://github.com/svend4/info30) | Markdown, YAML, JSON, MCP | RAG-ориентированная база знаний для Claude Code (агенты, скиллы, шаблоны, MCP-руководства) | Подробный `README.md` · 3 ветки (`JCl6O` неслитая) |
| [info40](https://github.com/svend4/info40) | Python (FastAPI, Typer), PG/Redis/RabbitMQ, K8s/Helm | Платформа оркестрации, аренды и маркетплейса AI-агентов с CLI, SDK и Prometheus/Grafana-мониторингом | Подробный `README.md` · 2 ветки (1 влита) |
| [info70](https://github.com/svend4/info70) | Документы; в ветках Node.js ESM, HTML/JS | Материалы по детской интернет-безопасности («Ein Netz für Kinder»); масштабный монорепо (3 393 теста) в ветке `hr0jh9` | Краткий `README.md` · 6 веток, PR #1, #4 |
| [info70net](https://github.com/svend4/info70net) | Vanilla JS (ESM), HTML5/CSS3, Node.js | Портал 4 веб-прототипов цифровой безопасности для детей и семей (поиск, медиаплан, маршруты помощи, проверка ИИ) | Подробный `README.md` · 3 ветки, Draft PR #2 |
| [info80](https://github.com/svend4/info80) | Python, LangGraph, Graphiti/Neo4j, FastAPI, Streamlit | Мультиагентная система с графовой памятью, реактивными Data Cards, Docker-песочницей и Marketplace | Подробный `README.md` · только `main` |
| [info90](https://github.com/svend4/info90) | Python 3 (stdlib, Ed25519, ActivityPub), HTML/YAML | Исследование форм организации информации и прототип федеративной базы знаний «Живая Библиотека» | Подробный `README.md` · только `main` |
| [info100](https://github.com/svend4/info100) | Python (`networkx`, `pyyaml`), GitHub Actions | Монорепозиторий и CI-конвейер эволюционного синтеза и дистилляции методологий ИИ-агентов и скиллов | Подробный `README.md` · только `main` |
| [info140](https://github.com/svend4/info140) | HTML5/JS, Node.js (`cjs`), Python, Markdown | Экспериментальный браузерный проект MERIDIAN (P78 Living Ring и архив P1–P80) для семантического анализа фраз | Подробный `README.md` · 2 ветки (`ccr-850e4012-jnffea` неслитая) |
| [info150](https://github.com/svend4/info150) | Python (FastAPI, OpenCV), React/TS/Vite, Docker | Монорепозиторий из 17 пакетов вокруг системы поддержки решений DARPA Triage Challenge (`triage4`) и `portal` | Подробный `README.md` · 2 ветки (1 влита) |
| [info200](https://github.com/svend4/info200) | Markdown, JSON, Node.js (`audit-swarm-workflow.js`) | Двухфазная вики-энциклопедия аудита 61 публичного репозитория по 14 темам (контент в неслитой ветке `266bh9`) | `docs/add-readme-ru` · 4 ветки (1 основная неслитая) |
| [info201](https://github.com/svend4/info201) | Python (`scripts/*.py`), JSON, Markdown | Вики-навигатор и генератор аудита публичных репозиториев профиля (основной код и `wiki/` в ветке `codex`, PR #1) | `docs/add-readme-ru` · 4 ветки, PR #1 |
| [infom](https://github.com/svend4/infom) | Python, FastAPI, MCP (stdio), D3.js, Docker | Геометрическая GraphRAG-система и MCP-сервер (Q6 LSH, HNSW, архетипы, HTML-граф) с REST API | `docs/add-readme-ru` · 4 ветки (1 неслитая) |
| [infon](https://github.com/svend4/infon) | Go 1.24 (Yggdrasil P2P, `.babe`), Python (`ai/adapters/`) | Терминальная платформа P2P-видеосвязи TVCP с открытым AI-слоем `tvcp-ai/1` и 3D/игровыми прототипами | Подробный `README.md` · 10 веток (3 неслитых) |

---

## 2. Пространства ИИ-разработки, MCP и межагентная инфраструктура (10)

| Репозиторий | Стек | Описание | README / Ветки |
| :--- | :--- | :--- | :--- |
| [ai-colab](https://github.com/svend4/ai-colab) | Python CLI, MCP-драйверы, SQLite FTS5, Markdown | Рабочее пространство мультиагентного взаимодействия на базе версионируемого Markdown-канона и защитных гейтов | Подробный `README.md` · 14 веток, 8 открытых PR |
| [new-project-ai-colab](https://github.com/svend4/new-project-ai-colab) | Markdown (`LICENSE`) | Заготовка рабочего пространства для совместной работы ИИ-агентов (на `main` пока только `LICENSE`) | Открыт PR #2 (`docs/add-readme-ru`), Draft PR #1 |
| [universal-file-storage-mcp](https://github.com/svend4/universal-file-storage-mcp) | TypeScript, Node.js, MCP (HTTP/SSE), Shell | Универсальный MCP-сервер для доступа и OCR-поиска по файлам на десктопе, Android (ADB), NAS и в облаке | Подробный `README.md` · 5 веток (3 влиты, 1 тест) |
| [claudeai-test-project-k](https://github.com/svend4/claudeai-test-project-k) | Python 3 (stdlib), Markdown | Тестовый проект проверки Claude Code, Desktop Commander и кодировок (ветка по умолчанию — `master`) | Подробный `README.md` · 2 ветки (`Jcxgd` с отчётом) |
| [x-index](https://github.com/svend4/x-index) | Python (`tools/wiki.py`), Markdown | Анализатор и CLI-инструмент структурирования базы знаний (основные файлы в неслитой ветке `claude/clever-bohr-5h86es`) | `docs/add-readme-ru` · 2 ветки (основная неслитая) |
| [an-info](https://github.com/svend4/an-info) | Python (`tools/lint_wiki.py`), Markdown | Исследовательская вики и линтер материалов об Anthropic Public Benefit Fund (в ветке `urtjcw`) | `docs/add-readme-ru` · 3 ветки (основная неслитая) |
| [in4](https://github.com/svend4/in4) | Статический HTML, Markdown | Серия из 15 HTML-исследований и калькуляторов по сборке домашних AI-кластеров (`prima.cpp`, `llama.cpp`, Vulkan) | Подробный `README.md` · 3 ветки (2 влиты) |
| [in4n](https://github.com/svend4/in4n) | HTML/Canvas2D, React/Three.js, TypeScript/Obsidian | Динамический граф знаний InfoAquarium в трёх клиентах с физикой, триангуляцией Делоне и связкой с InfoM в `OLZGo` | Подробный `README.md` · 2 ветки (`OLZGo` неслитая) |
| [info4project](https://github.com/svend4/info4project) | Node.js, Express, React, Docker/Nginx, Playwright | Демонстрационная система управления задачами, собранная иерархической бригадой агентов | `docs/add-readme-ru` · 7 веток (4 влиты) |
| [info20dd](https://github.com/svend4/info20dd) | Markdown | Методическое руководство на русском языке по расширению Claude Code (Skills, MCP, `CLAUDE.md`, оркестраторы) | Подробный `README.md` · 2 ветки (1 влита) |

---

## 3. Веб-платформы, каталоги, планировщики и e-commerce (27)

| Репозиторий | Стек | Описание | README / Ветки |
| :--- | :--- | :--- | :--- |
| [AI2DTab](https://github.com/svend4/AI2DTab) | React 19, TanStack, Vite 8, PGlite, Python/SQLite | Веб-интерфейс («живой стол» L1–L4) и движок `engine/pm.py` для структурирования диалогов и утверждений | `docs/add-readme-ru` · 7 веток (4 неслитых, Draft PR #2, #3) |
| [cardix](https://github.com/svend4/cardix) | Python (stdlib HTTP-сервер и симулятор), HTML/JS | Offline-first карточные каталоги *Karten-Projekt* (спецификация ядра, сервер, симулятор в ветке `karten-projekt`) | Обновлён в `main` · 2 ветки (код на `karten-projekt`) |
| [daten](https://github.com/svend4/daten) | FastAPI, React/TS/Vite, Redis/Celery, Docker | Fullstack-платформа «Информационная ОС» (`ios-system`) из экспорта ChatGPT (в `codex/*` лежит отдельный лендинг) | Подробный `README.md` · 6 веток (5 неслитых) |
| [daten1](https://github.com/svend4/daten1) | HTML5, Three.js, sql.js (SQLite WASM), PWA | Автономные HTML-блокноты на SQLite (PWA) и игры Space Shooter; 8 веток с отдельными уровнями `flower-shop` | `docs/add-readme-ru` · 12 веток (8 посторонних) |
| [daten2](https://github.com/svend4/daten2) | PHP, Flask, Django, Express, Next.js, Docker, Python | Полиглот-стенд магазина цветов в 7 уровнях + 33 AI/инфра-микросервиса и NPP-Act `act/` (**43** неслитые ветки) | Подробный `README.md` · 44 ветки, 2 открытых PR |
| [daten3](https://github.com/svend4/daten3) | TypeScript/Express/Prisma/React 18 + legacy PHP | Туристическая платформа TravelHub (поиск туров/отелей и партнёрка): архивы PHP и монорепо `travelhub-ultimate/` | Краткий `README.md` · 16 веток (13 влиты) |
| [daten4](https://github.com/svend4/daten4) | HTML + React/Vite/Tailwind + Express + ChromaDB | Динамический планировщик: однофайловые HTML-демо и AI/RAG-версия `ai-planner/` | Краткий `README.md` · 3 ветки, PR #2 |
| [daten5](https://github.com/svend4/daten5) | Node.js/Microservices, Frontend, Docker Compose | Платформа рационализации программных решений (`rationalization-platform/` с 7 backend-сервисами) | `docs/add-readme-ru` · 3 ветки (1 влита) |
| [daten6](https://github.com/svend4/daten6) | HTML5, CSS3, Vanilla JS, Markdown | Прототип и архитектура модульного динамического каталога коллекций с мозаичным UI | Подробный `README.md` · 3 ветки (2 влиты) |
| [daten7](https://github.com/svend4/daten7) | Markdown | Спецификации модульной системы обработки данных с интерфейсом «вертикальный аккордеон» (7/20/52 модуля) | Подробный `README.md` · 2 ветки (1 влита) |
| [daten8](https://github.com/svend4/daten8) | Python (`src/`), SQLite, YAML, RSS | Индексатор и классификатор объявлений с RSS/Email-уведомлениями (реализация в ветке `egVtD`, `main` пустая) | `docs/add-readme-ru` · 3 ветки (основная неслитая) |
| [daten9](https://github.com/svend4/daten9) | HTML5, CSS3, Vanilla JS, JSON | Модульная система универсальных веб-виджетов и HTML/JS-шаблонов без зависимостей (код в ветке `5DOXm`) | `docs/add-readme-ru` · 3 ветки (основная неслитая) |
| [daten11](https://github.com/svend4/daten11) | Python (Flask, CLI), JSON Schema, HTML/JS | 4-уровневая информационная ОС для файлов с JSON-метаданными, краулером и фасетным веб-поиском | Подробный `README.md` · 2 ветки (1 влита) |
| [daten12](https://github.com/svend4/daten12) | Markdown | Пошаговая методология и концепт-план системной рационализации существующего ПО в единую B2B-OS | Подробный `README.md` · 2 ветки (1 влита) |
| [daten14](https://github.com/svend4/daten14) | Markdown | Проектная документация BIOS-I по систематизации, совместимости и автоматизации программных экосистем | Подробный `README.md` · 2 ветки (1 влита) |
| [daten20](https://github.com/svend4/daten20) | Python (Flask/FastAPI, PyTorch, Ray, Tesseract), K8s | Платформа управления документами (DMS) с 16+ CLI-утилитами, BI-аналитикой, OCR и AI-модулями | Подробный `README.md` · 47 веток, 18 открытых PR |
| [daten22](https://github.com/svend4/daten22) | Markdown, Python (LangChain/ChromaDB), Kotlin/FTS4 | Энциклопедия 16 типов личности MBTI с семантическим поиском RAG/PseudoRAG и Android-приложением | Подробный `README.md` · 3 ветки (2 влиты) |
| [daten23](https://github.com/svend4/daten23) | на `T3FN3` — HTML5, CSS3, Vanilla JS (`localStorage`) | Заготовка интернет-магазина; готовый статический сайт цветочного магазина расположен в ветке `T3FN3` | Краткий `README.md` · 2 ветки (`T3FN3` неслитая) |
| [daten30](https://github.com/svend4/daten30) | Python (Flask/FastAPI, SQLite), Flutter/Dart, Termux | Динамический хаб-портал микросервисных приложений (Service Registry, Message Bus, Flutter UI) | Подробный `README.md` · 2 ветки (1 влита) |
| [daten40](https://github.com/svend4/daten40) | Markdown, JSON Schema, OpenAPI YAML, Python, HTML | Append-only реестр и конвейер генерации интернет-функций IFOS (блоки 14241–88800 и OpenAPI-спеки) | Подробный `README.md` · 3 ветки (2 влиты) |
| [flower-shop-online](https://github.com/svend4/flower-shop-online) | TypeScript, React, TanStack, SQLite/сервер | Интернет-магазин цветов *Flora* (каталог букетов, корзина, оформление и история заказов) | `docs/add-readme-ru` · 1 ветка |
| [meta4](https://github.com/svend4/meta4) | Python (`main.py` в ветке `copilot/flower-shop-setup`) | Заготовка с прототипом приложения цветочного магазина на ветке `copilot/flower-shop-setup` (PR #2) | `docs/add-readme-ru` · 4 ветки |
| [startups-bizwiki](https://github.com/svend4/startups-bizwiki) | Python (`tools/*.py`), CSV, Markdown (`wiki/`) | Бизнес-вики по стартапам из выгрузок Hacker News Hiring (контент и 30 карточек компаний в ветке `qa7p7s`) | `docs/add-readme-ru` · 2 ветки (основная неслитая) |
| [runway](https://github.com/svend4/runway) | Node.js (zero deps), Vanilla JS ESM, Markdown | Исследовательская LLM-вики и исполняемый движок прогнозирования личного денежного потока | Подробный `README.md` · только `main` |
| [ingit](https://github.com/svend4/ingit) | Python (FastAPI, SQLAlchemy), React/TS/Vite, Docker | Offline-first платформа InGit, объединяющая Git, управление задачами, вики и учёт через YAML и SQL | Подробный `README.md` · 2 ветки (1 влита) |
| [nautilus](https://github.com/svend4/nautilus) | Python 3, SQLite, OpenAPI, D3.js, Docker | Мета-портал совместимости репозиториев (NPP v1.2): 14 адаптеров, 33 моста, Q6-гиперкуб и TF-IDF поиск | Подробный `README.md` · 4 ветки (3 влиты) |
| [geoweave](https://github.com/svend4/geoweave) | Python (FastAPI, Uvicorn), JSON Schema, HTML/JS/SVG | MVP для сборки фрагментов карт в версионируемый атлас доказательств с хэш-проверяемыми дельтами | Подробный `README.md` · только `main` |

---

## 4. Данные, API, аналитика и оптимизация (12)

| Репозиторий | Стек | Описание | README / Ветки |
| :--- | :--- | :--- | :--- |
| [data2](https://github.com/svend4/data2) | Markdown (310 томов), Python (`scarab_algorithm.py`) | Многотомный корпус по «единой теории движения» и архетипам движения с Python-реализацией алгоритма Scarab | Краткий `README.md` · 4 ветки (3 влиты) |
| [data3](https://github.com/svend4/data3) | в PR #1 — Python CLI (`budget-assist-de`), Docker | Заготовка бюджетного приложения с Python/Docker-прототипом в PR #1 и тестовой веткой `grokbot-test-files` | Краткий `README.md` · 3 ветки, PR #1 |
| [data4](https://github.com/svend4/data4) | на `HisIP` — React/TS, Node/Express, Docker Compose | Веб-приложение управления бюджетом (исходный код, фронтенд, бэкенд и доки в неслитой ветке `HisIP`) | `docs/add-readme-ru` · 3 ветки (основная неслитая) |
| [data7](https://github.com/svend4/data7) | Python (FastAPI, TSP/NSGA-II), React/TS/Three.js, Docker | Многокомпонентный проект оптимизации на базе TSP: Meta-Orchestrator, симулятор профессий и MMO AI Bridge | Подробный `README.md` · 3 ветки, устаревший Draft PR #1 |
| [data10](https://github.com/svend4/data10) | на `DMl4A` — Python (FastAPI, PyTorch, Neo4j), Docker/K8s | Методика динамических блоков для правовых текстов; полная 4-фазная NLP/K8s-система в неслитой ветке `DMl4A` | Краткий `README.md` · 2 ветки (основная неслитая) |
| [data15](https://github.com/svend4/data15) | Python 3 (SQLite FTS5, Streamlit), Bash, Docker | Многоагентный гибридный оркестратор (v5 на `main`, v6 в PR #5) с 33+ модулями и REST API | Подробный `README.md` · 6 веток, PR #5 *(требуется очистка `svend4-patch-1`)* |
| [data20](https://github.com/svend4/data20) | Python (FastAPI, Pyodide), React, Electron, Flutter | Оффлайн-платформа управления знаниями и обработки данных (57 инструментов) под десктоп, веб и Android | Подробный `README.md` · 10 веток (8 влиты) |
| [data30](https://github.com/svend4/data30) | Python, HTML/CSS, Shell, JSON Schema, Markdown | Платформа и каталог функций, приложений и макросов с системой рейтингов и веб-прототипом поиска | Подробный `README.md` · 118 веток, 27 открытых PR |
| [data40](https://github.com/svend4/data40) | HTML/CSS/JS PWA, Node.js, Express, SQLite3 | Интернет-магазин цветов «Цветочный Рай» с PWA, конструктором букетов и Node/SQLite бэкендом | Подробный `README.md` · 2 ветки (1 влита) |
| [data50](https://github.com/svend4/data50) | Markdown | Исследовательская заметка и разбор статьи об ИИ-клоне технического директора для рутинных ревью | Краткий `README.md` · 2 ветки (1 влита) |
| [data70](https://github.com/svend4/data70) | Markdown (220+ карточек), Python (`kbtool/` в ветке) | Архив 1105+ диалогов ChatGPT (~83 МБ) и монорепо знаний из 10 кластеров (в `NdKxk` отдельный сайт `FloraShop`) | Подробный `README.md` · 5 веток (1 посторонняя) |
| [infod10](https://github.com/svend4/infod10) | Jupyter Notebook (pandas, sklearn, plotly) | Два Colab-блокнота для анализа данных и ML (в `archive/session-001` отдельный прототип `agentwiki/`) | Подробный `README.md` · 4 веток (1 посторонняя) |

---

## 5. Языки ИИ (AIL), математические модели, нейросети и мета-системы (12)

| Репозиторий | Стек | Описание | README / Ветки |
| :--- | :--- | :--- | :--- |
| [meta](https://github.com/svend4/meta) | Python stdlib (`libs/hexcore/`), `pytest`, PDF/ODT | Монорепозиторий 24 Python-проектов и библиотеки `hexcore` на 6-мерном гиперкубе `Q6` + исследовательский архив | Подробный `README.md` · 9 веток, PR #11 |
| [meta0](https://github.com/svend4/meta0) | Rust (`ail_runtime`), Python (Z3), HTML/JS | Сквозной прототип ИИ-ориентированной среды разработки AIL с бинарным AST, акторами на Rust и верификацией | Краткий `README.md` · только `main` |
| [meta1](https://github.com/svend4/meta1) | TypeScript, Node.js >=20, Vitest, Docker | Детерминированный рантайм Continuum для AI-кода с кэшем планов, песочницей и каскадным самовосстановлением | Подробный `README.md` · 2 ветки (1 влита) |
| [meta2](https://github.com/svend4/meta2) | Python 3 (OpenCV, NumPy, sklearn, Flask, pytest), Docker | Система автоматической сборки и верификации разорванных документов из сканов фрагментов (305+ модулей) | Подробный `README.md` · 6 веток, устаревший PR #6 |
| [meta10](https://github.com/svend4/meta10) | Markdown | Аналитический разбор двухстадийного AST-пайплайна (`grep-ast → ast-grep`) для извлечения REST и Kafka из кода | Краткий `README.md` · 2 ветки (1 влита) |
| [ail-runtime](https://github.com/svend4/ail-runtime) | Rust (`Cargo`), Markdown, Shell/JS | Семантический рантайм AIL на Rust (Binary AST, Ownership, Hot-Swap, Star Gate); v2 и фиксы сборки в `xxbvai` | Подробный `README.md` · 2 ветки (`xxbvai` неслитая) |
| [pro2](https://github.com/svend4/pro2) | Python, PyTorch 2.0+, BPE, Shell | Фреймворк языковых моделей (`YiJingGPT`, `NautilusMoME`, `HMoE`) с геометрией на 6-мерном гиперкубе `Q6` | Подробный `README.md` · 11 веток (2 неслитых) |
| [open-cycle-jepa](https://github.com/svend4/open-cycle-jepa) | Python, PyTorch, YAML | Исследовательский PyTorch-прототип теории раскрытых циклов поверх JEPA / H-JEPA и Latent LCI *(ветка `main` не защищена)* | Подробный `README.md` · только `main` |
| [milogic-jev](https://github.com/svend4/milogic-jev) | Python >=3.9 (`pyproject.toml`, pytest) | Библиотека и CLI для иерархических систем принятия решений на основе Jev, милогии Беляева и структур Крюкова | Подробный `README.md` · только `main` |
| [lorenzo](https://github.com/svend4/lorenzo) | Python (`docs-toolkit`), pnpm, Docker/Helm, Obsidian | Монорепозиторий ~2815 `.md` заметок (Svyazi 2.0, Nautilus/NPP) и Python-фреймворка `docs-toolkit` | Подробный `README.md` · 20 веток, 4 открытых PR |
| [mirendil-wiki](https://github.com/svend4/mirendil-wiki) | Docsify v4, Markdown | Статическая Docsify-вики на русском языке с аналитическим обзором Mirendil и разбором 14 позиций (71 задача) | Подробный `README.md` · только `main` |
| [mirendil-ai-careers-wiki](https://github.com/svend4/mirendil-ai-careers-wiki) | Markdown, PowerShell (`tools/*.ps1`) | Русскоязычный монорепозиторий и PowerShell-генератор вики по профессиям, задачам и рискам AI R&D | Подробный `README.md` · только `main` |

---

## 6. Игры и интерактивные медиа (5)

| Репозиторий | Стек | Описание | README / Ветки |
| :--- | :--- | :--- | :--- |
| [game-apps](https://github.com/svend4/game-apps) | Kotlin 2.2, Jetpack Compose, Room, Android | Ненасильственная медитативная 3D Android-аркада *Сюрреалистический Цирк Снов (Surreal Circus)* | Открыт PR #3 (`docs/add-readme-ru`), Draft PR #2 |
| [gameco](https://github.com/svend4/gameco) | React 19, TypeScript, Vite 8, Three.js, Tailwind, Express | Веб-игра и RPG-студия *Emoji Universe: Maze & RPG Studio* с 3D-лабиринтом и `@google/genai` | Открыт PR #1 (`docs/add-readme-ru`) · 1 ветка |
| [game-one](https://github.com/svend4/game-one) | Kotlin, Jetpack Compose, Material 3, Android TTS | Семейная словесная Android-игра *TetriCross*, объединяющая тетрис, кроссворд, озвучку и конструктор загадок | Подробный `README.md` · только `main` |
| [games-monorepo](https://github.com/svend4/games-monorepo) | HTML5/JS, Three.js, TypeScript/Vite/Phaser/Capacitor, PHP | Монорепозиторий игр (*NEXUS* v1–v3, *Crystal Collector*, *Ad-concepts*) и лендинга услуг | Подробный `README.md` · 8 веток (3 неслитых) |
| [alice-snov](https://github.com/svend4/alice-snov) | Markdown (GDD), YAML (`schema/*.yaml`) | Геймдизайн-документация («Physics of Carriers») и YAML-схемы для серьёзной 3D-игры-капчи «Алиса: Машина снов» | Подробный `README.md` · только `main` |

---

## 7. Робототехника (1)

| Репозиторий | Стек | Описание | README / Ветки |
| :--- | :--- | :--- | :--- |
| [robot](https://github.com/svend4/robot) | Markdown/JSON/ZIP; на `kvCBq` — Python, FastAPI, pytest | Фреймворк, валидатор и маркетплейс skill-пакетов ETD для роботов (2 446 тестов и код лежат в ветке `kvCBq`) | `docs/add-readme-ru` · 5 веток (2 неслитых, Draft PR #2) |

---

## 8. Центральный каталог (1) и пустые публичные заготовки (3)

| Репозиторий | Содержимое на ветках | Примечание |
| :--- | :--- | :--- |
| [information](https://github.com/svend4/information) | **Центральный открытый каталог** 93 технических проектов (ветка `docs/catalog`: `README.md` и `BRANCH_AUDIT.md`) | В `main` `LICENSE` (AGPL-3.0); также есть Draft PR #4 (`codex/readme-overview-20261118`) |
| [4p](https://github.com/svend4/4p) | Только `# 4p` (4 Б) и `LICENSE` (AGPL-3.0) | 1 коммит, других веток и PR нет |
| [infod20](https://github.com/svend4/infod20) | Только `# infod20 / info` и `LICENSE` | Есть только пустой Draft PR #1 (`codex/readme-overview-20261118`) |
| [infod30](https://github.com/svend4/infod30) | Только `# infod30 / info` и `LICENSE` | Есть только пустой Draft PR #1 (`codex/readme-overview-20261118`) |
