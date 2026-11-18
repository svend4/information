# Ревизия неслитых веток по публичным техническим репозиториям `svend4` (93 проекта)

Отчёт охватывает **93 публичных технических репозитория** профиля `svend4`. Проверка выполнена в режиме **read-only** без изменения, слияния или удаления веток.

---

## Категория А — Основной код проекта находится в неслитой ветке (`main` пустая / заглушка)

Эти репозитории являются главными кандидатами на перенос кода в `main` через Pull Request (с сохранением `LICENSE` и актуального `README.md` из `main`):

| Репозиторий | Что на `main` | Приоритетная ветка к слиянию | Что принесёт в `main` | Ссылка на сравнение |
| :--- | :--- | :--- | :--- | :--- |
| **cardix** | `LICENSE` + новый `README.md` | `karten-projekt` | Полный монорепозиторий `karten-projekt/` (спека ядра, HTML-прототип, Python HTTP-сервер заказов, симулятор v0.2) | [ready-for-main](https://github.com/svend4/cardix/compare/main...consolidate/ready-for-main?expand=1) · [исходная](https://github.com/svend4/cardix/compare/main...karten-projekt) |
| **data4** | `LICENSE` + заглушка `README.md` | `claude/budget-app-accessibility-HisIP` | Полноценное веб-приложение бюджета (React/TS, Node/Express, `docker-compose.yml`, `docs/`) + `BRANCH_README_ORIG.md` | [ready-for-main](https://github.com/svend4/data4/compare/main...consolidate/ready-for-main?expand=1) · [исходная](https://github.com/svend4/data4/compare/main...claude/budget-app-accessibility-HisIP) |
| **data10** | Методика `.md` + `LICENSE` | `claude/review-repository-DMl4A` | Полная 4-фазная реализация системы на FastAPI, PyTorch/BERTopic, Neo4j, Docker и Kubernetes; `AGPL-3.0` + `BRANCH_README_ORIG.md` перенесены в `consolidate/ready-for-main` | [ready-for-main](https://github.com/svend4/data10/compare/main...consolidate/ready-for-main?expand=1) · [исходная](https://github.com/svend4/data10/compare/main...claude/review-repository-DMl4A) |
| **daten8** | `LICENSE` + заглушка `README.md` | `claude/classified-ads-indexer-egVtD` | Полная система индексации и классификации объявлений на Python + SQLite + RSS/Email + `docs/` + `BRANCH_README_ORIG.md` | [ready-for-main](https://github.com/svend4/daten8/compare/main...consolidate/ready-for-main?expand=1) · [исходная](https://github.com/svend4/daten8/compare/main...claude/classified-ads-indexer-egVtD) |
| **daten9** | `LICENSE` + заглушка `README.md` | `claude/universal-widget-templates-5DOXm` | Модульная система 7 веб-виджетов и 3 тем на HTML/CSS/Vanilla JS + `docs/API.md`, `docs/USAGE.md` + `BRANCH_README_ORIG.md` | [ready-for-main](https://github.com/svend4/daten9/compare/main...consolidate/ready-for-main?expand=1) · [исходная](https://github.com/svend4/daten9/compare/main...claude/universal-widget-templates-5DOXm) |
| **daten23** | `LICENSE` + `README.md` | `claude/flower-shop-website-T3FN3` | Готовый статический сайт магазина цветов (`index.html`, `catalog.html`, `contact.html`, `script.js`, `style.css`) | [compare](https://github.com/svend4/daten23/compare/main...claude/flower-shop-website-T3FN3) |
| **info200** | `LICENSE` + заглушка `README.md` | `claude/agent-swarms-audit-wiki-266bh9` | Вики-энциклопедия аудита 61 публичного репозитория (305 страниц в 14 темах, `PROFILE.md`, `ROADMAP.md`, `_data/`) | [ready-for-main](https://github.com/svend4/info200/compare/main...consolidate/ready-for-main?expand=1) · [исходная](https://github.com/svend4/info200/compare/main...claude/agent-swarms-audit-wiki-266bh9) |
| **info201** | `LICENSE` + заглушка `README.md` | `codex` (открыт **PR #1**) | Скрипты аудита профиля (`scripts/*.py`), отчёты и 62 файла `wiki/` | [PR #1](https://github.com/svend4/info201/pull/1) |
| **an-info** | `LICENSE` + заглушка `README.md` | `claude/anthropic-public-benefit-fund-urtjcw` | `CLAUDE.md`, `raw/`, Python-линтер `tools/lint_wiki.py` и 12 файлов `wiki/` | [ready-for-main](https://github.com/svend4/an-info/compare/main...consolidate/ready-for-main?expand=1) · [исходная](https://github.com/svend4/an-info/compare/main...claude/anthropic-public-benefit-fund-urtjcw) |
| **x-index** | `LICENSE` + заглушка `README.md` | `claude/clever-bohr-5h86es` | Python CLI `tools/wiki.py`, `tools/workflows/`, `docs/ANALYSIS.md`, `docs/PIPELINE.md`, `wiki/` + `BRANCH_README_ORIG.md` | [ready-for-main](https://github.com/svend4/x-index/compare/main...consolidate/ready-for-main?expand=1) · [исходная](https://github.com/svend4/x-index/compare/main...claude/clever-bohr-5h86es) |
| **startups-bizwiki** | `LICENSE` + заглушка `README.md` | `claude/startup-wiki-hacker-news-qa7p7s` | 30 карточек компаний в `wiki/companies/`, выгрузки HN CSV и Python-инструменты анализа | [ready-for-main](https://github.com/svend4/startups-bizwiki/compare/main...consolidate/ready-for-main?expand=1) · [исходная](https://github.com/svend4/startups-bizwiki/compare/main...claude/startup-wiki-hacker-news-qa7p7s) |
| **meta4** | `LICENSE` + заглушка `README.md` | `copilot/flower-shop-setup` (PR #2) | Прототип `main.py` для магазина цветов *(если нужен как прототип в `main`)* | [compare](https://github.com/svend4/meta4/compare/main...copilot/flower-shop-setup) |

---

## Категория Б — Активные проекты с неслитыми доработками, фичами или открытыми PR

| Репозиторий | Невлитые ветки / PR | Что содержат и рекомендация |
| :--- | :--- | :--- |
| **robot** | `consolidate/ready-for-main`, `claude/add-hyundai-robot-docs-kvCBq`, `claude/determined-hawking-q8xvi0` | **`kvCBq` содержит весь Python-код** (FastAPI, `etd_cli.py`, валидатор, 2 446 тестов). Собрана [consolidate/ready-for-main](https://github.com/svend4/robot/compare/main...consolidate/ready-for-main?expand=1) с `LICENSE` и русским `README.md` (+ `docs/BRANCH_README_ORIG.md`); затем влить `AUDIT.md` из `q8xvi0`. |
| **ail-runtime** | `consolidate/ready-for-main`, `claude/busy-pasteur-xxbvai` | Критические фиксы сборки `v1`, спека и реализация `v2` (`mvp/src/v2/`, 55 тестов, clippy-clean), `Cargo.lock` и CI. Собрана [consolidate/ready-for-main](https://github.com/svend4/ail-runtime/compare/main...consolidate/ready-for-main?expand=1) с `LICENSE` и `README.md`. |
| **daten2** | `consolidate/ready-for-main` + **43** неслитые ветки (PR #11, #12 устарели) | На `main` только старый Уровень 5. На базе `claude/main-candidate-GBpVR` (47 сервисов + `docker-compose.yml`) собрана [consolidate/ready-for-main](https://github.com/svend4/daten2/compare/main...consolidate/ready-for-main?expand=1) с `LICENSE` (`AGPL-3.0`); в `1vrefm` остаётся **NPP-Act 1.0** (`act/`). **Важно:** ветки `claude/*-GBpVR` не удалять, на них ссылается `docker-compose.yml`. |
| **info70** | `claude/children-network-programs-germany-hr0jh9`, `codex/-ein-netz-fur-kinder-nv0cw8` (PR #4), `codex/-ein-netz-fur-kinder` (Draft PR #1) | Ветка `hr0jh9` — наиболее полный монорепо (232 каталога, 3 393 теста) на материалах `Ein Netz für Kinder` и `PRALESKA.pdf`; закрыть устаревшие PR #1 и #4 после ревью `hr0jh9`. |
| **data15** | `feature/v6-improvements` (**PR #5**) | Существенное обновление до **v6** (SQLite WAL + FTS5, ChromaDB, PBKDF2/JWT, Streamlit WebUI, 10 критических багфиксов). Проверить и влить PR #5. |
| **ai-colab** | **11** неслитых веток (**8** открытых PR: #1, #3, #4, #7–#11) + `claude/youthful-ramanujan-m7gyjy` | Приоритет: влить готовые PR **#3** (fail-closed `*_BASE`), **#4** (approval через Environment) и **#7** (`D-041` Jules); затем security/validation PR **#8, #10, #11, #9** и аудит от 2026-11-06 из `m7gyjy`. Устаревшие `d040` и `mtooxx` закрыть. |
| **daten20** | **38** неслитых веток (**18** открытых PR: #89–#97, #107, #117–#127) + `claude/document-management-app-7INVu` | Приоритет: влить **PR #127** (`docs/align-licence-agpl`), перенести 78 тестов из `7INVu`, CodeQL/`CODEOWNERS` из Draft PR #107 и обработать свежие Dependabot PR. Старые январские аудит-ветки и закрытые Dependabot-ветки не вливать. |
| **data30** | **27** открытых PR (#45–#118, поверх баз PR #10, #30, #106) | Вливать только ветки, построенные поверх PR #106 (серия **PR #107–#118**, плюс прототип #95 после перебазирования); ранние PR от баз #10/#30 закрыть как конфликтующие дубли. |
| **lorenzo** | **10** неслитых веток (**4** открытых PR: #32, #33, #35, #36) | Влить свежий **PR #36**, перенести `claude/full-audit-y488cv`, `claude/current-dev-stage-dJtu0` и CI-фиксы (`5cdc90ce`, PR #32); дубли PR #33/#35 и старые `auto/*` закрыть. |
| **pro2** | `audit/code-review`, `claude/current-dev-stage-ulcwt`, `claude/disable-cron-testing-daF7A` | ⚠️ Прямое слияние `ulcwt` затрёт **PR #86** (`nautilus/*`) и `CURRENT-STAGE.md` на `main`. Проверка показала 0 пересечений по файлам, поэтому в ветке [audit/code-review](https://github.com/svend4/pro2/compare/main...audit/code-review?expand=1) на базу `main` чисто перенесены все 10 файлов из `ulcwt` (`+1608/-28`) + добавлен `docs/AUDIT_REPORT.md` (отмечены XSS в `nautilus/portal.py`, 209 МБ `.pt`-чекпоинты и расхождение MIT/AGPL-3.0). |
| **infon** | `claude/infon-audit`, `feat/ai-next`, `claude/epic-sagan-EWTTr` | В `infon-audit` 15 коммитов исправлений по всему стеку (2026-10-23); в `EWTTr` адаптивный `pkg/framecodec`; в `feat/ai-next` (`worldwalk`, `TVCP Craft`). Ветка `assets` — отдельная медиа-ветка превью. |
| **meta** | `claude/review-pdf-document-qvUbL` (**PR #11**) | Полезные тесты (`hexcore`) и фикс бага в `hexdim.gray_code_step()`; требуется rebase на `main`. |
| **AI2DTab** | `ccr-16458c8b-rhgxsh`, `claude/pensive-tesla-qb0rt4-site-engine` (PR #3), `claude/pensive-tesla-qb0rt4` (PR #2, «do not merge»), `neq-candidates-pass9` | PR #3 вносит важные AUD-15 транзакции/блокировки в `engine/pm.py` и снапшот; `ccr-16458c8b-rhgxsh` — альтернативная крупная переработка v2.1 (1.7с загрузка); `neq-candidates-pass9` — 1 009 raw-кандидатов. Требуют осознанного выбора/слияния без затирания PR #3. |
| **info140** | `consolidate/ready-for-main`, `ccr-850e4012-jnffea` | +2 коммита чисто поверх `main`: собрана [consolidate/ready-for-main](https://github.com/svend4/info140/compare/main...consolidate/ready-for-main?expand=1) с русским `README.md`, `docs/BRANCH_README_ORIG.md` и сохранённой `LICENSE`. |
| **in4n** | `consolidate/ready-for-main`, `claude/dynamic-graph-visualization-OLZGo` | +2 коммита после PR #2: иерархия архетипов и адаптер InfoM (`Q6Overlay.jsx`, `useInfoM.js`). Собрана [consolidate/ready-for-main](https://github.com/svend4/in4n/compare/main...consolidate/ready-for-main?expand=1) с `LICENSE` и обновлённым `README.md`. |
| **info3** | `docs/align-licence-agpl` (**PR #9**) | Приводит упоминания лицензии в документации к `AGPL-3.0-only`. |
| **info70net** | `codex/policy-safety-foundation` (**Draft PR #2**) | Добавляет `policy/`, `SECURITY.md`, `CONTRIBUTING.md`, `safety.{html,css,js}`. |
| **data70** | `claude/restructure-monorepo-folders-zUtMN`, `claude/trusting-allen-XHaaw` | В `zUtMN` добавлены `kbtool/` (14 CLI-команд), `textkit` и аудит; в `XHaaw` — `.mcp.json` и `MCP-SETUP.md`. *(Ветку `NdKxk` не вливать — см. Категорию В!)* |
| **data20** | `claude/fix-apk-builds-fdMiG` | +3 коммита с крупными документами `METHODOLOGY_LOCAL_AI_INFERENCE.md` и `PHILOSOPHY_OF_MODULARITY.md`. |
| **daten** | `claude/program-question-xKtF5` | Последний коммит `39db03f` добавляет конфиги для Render (`render.yaml`, `docker-compose.yml`). *(Остальные ветки — см. Категорию В!)* |
| **daten4** | `claude/claude-md-mkux32w1dijtop14-tcSow` (**PR #2**) | Добавляет `CLAUDE.md`, но ответвлена до мержа `ai-planner/` — нужно обновить перед слиянием. |
| **info30** | `claude/claude-md-mlp1jt922ntuvnzf-JCl6O` | Добавляет `CLAUDE.md` (1 495 байт). |
| **infom** | `claude/wasm-performance-optimization-u8svc` | 1 неслитый коммит регенерации `infom_graph.html` после PR #2. |
| **claudeai-test-project-k** | `claude/test-new-features-Jcxgd` | Добавляет подробный отчёт `CLAUDE_CODE_REPORT.txt` (~39 КБ). |
| **info4project** | `claude/kind-wozniak-qgqi2t`, `feature/testing-ci` | Ранние/дублирующие коммиты Nginx и тестов, в целом перекрытые влитыми `feature/*` ветками. |
| **data3** | `codex/develop-budget-management-application` (**PR #1**) | Прототип `budget-assist-de` (Python CLI + Docker); стоит актуализировать с `LICENSE`/`README.md` и влить. *(Ветку `grokbot-test-files` не вливать!)* |

> [!CAUTION]
> **Прочие проверки безопасности и устаревшие PR:**
> - **open-cycle-jepa:** ветка `main` сейчас не защищена (`protected: false`) — рекомендуется включить защиту ветки и добавить `requirements.txt` + `LICENSE`.
> - **data15 (`svend4-patch-1`):** хотя ветка уже влита, в её старом снимке дерева остался файл `package.zip`, ранее удалённый из `main` из-за утекшего ключа MiniMax. Рекомендуется удалить ветку `svend4-patch-1` и убедиться в ротации ключа.
> - **meta2 (`PR #6`)**, **data7 (`Draft PR #1`)**, **daten3 (`svend4-patch-1`, `copilot/update-ci-workflow-variables`)**: устарели и уже перекрыты изменениями в `main`; можно закрыть без слияния.

---

## Категория В — ВНИМАНИЕ: в ветках лежат посторонние проекты или тестовый мусор (НЕ сливать в `main` вслепую!)

В этих репозиториях под одной историей веток хранятся **совершенно другие проекты**, экспериментальные песочницы или тестовые артефакты ботов. Прямое слияние затрёт корневые файлы основного проекта:

| Репозиторий | Посторонняя / смешанная ветка | Что находится внутри (причина блокировки слияния) |
| :--- | :--- | :--- |
| **daten1** | `claude/extract-archive-TDUEs`, `claude/level1-TDUEs` .. `claude/level7-TDUEs` (8 веток) | Все 8 веток содержат **7 уровней магазина цветов (`flower-shop`)**, вынесенных в корень вместо HTML-блокнотов и игр с `main`! *(Только `VBcEn` с Fuse.js/темами и `u0n4p` со Space Defender относятся к играм/блокнотам.)* |
| **info10** | `claude/react-todo-task-plan-Nfh4B` | Полный **React + TypeScript + Vite магазин цветов** (основной проект на `main` — Python-шлюз `daf-gateway`). |
| **infod10** | `archive/session-001` | Самостоятельный прототип **`agentwiki/`** (55 КБ `AGENTS.md`, 96 КБ `README.md`, SQLite-журнал) вместо Google Colab блокнотов. |
| **data70** | `claude/review-repository-NdKxk` | Статический веб-сайт цветочного магазина **`FloraShop`** (`index.html`, `css/`, `js/`). |
| **daten** | `codex/add-action-and-method-to-cta__form`, `codex/update-.cta__form-in-index.html`, `svend4-patch-1`, `svend4-patch-2` | Две `codex/*`-ветки содержат статический лендинг магазина цветов **«Bloomery»**; две `svend4-patch-*` — сырые дампы чатов. |
| **games-monorepo** | `codex/-ein-netz-fur-kinder`, `feature/nexus-loop-gates` | В `codex/-ein-netz-fur-kinder` лежит посторонний пакет **`kindergeldaiinfo/`** (детская интернет-безопасность); в `feature/nexus-loop-gates` полезный фикс ссылок `c5437d5` смешан с копией **`mirendil-wiki/`** (переносить только cherry-pick `c5437d5`, а из `mfqjv4` брать документы по доступности). |
| **info7** | `claude/setup-orchestrator-kit-n1kNz` | Тестовая песочница с приложениями Todo API, Task Manager Pro, Flower Shop и коротким `README.md` (13 Б) — при слиянии в корень затрёт монорепо. |
| **data3** | `grokbot-test-files` | Тестовые файлы коннектора (`GROKBOT_TEST_NOTE.md`, `grokbot-test-page.html`) — удалить. |
| **universal-file-storage-mcp** | `grokbot-test-files` | Тестовые файлы коннектора (`GROKBOT_TEST_NOTE.md`, `grokbot-test-page.html`) — удалить. |

---

## Категория Г — Документационные ветки (`docs/add-readme-ru` и черновики `codex`)

1. **Открытые PR с русским `README.md` (3):**
   - [game-apps PR #3](https://github.com/svend4/game-apps/pull/3)
   - [new-project-ai-colab PR #2](https://github.com/svend4/new-project-ai-colab/pull/2)
   - [gameco PR #1](https://github.com/svend4/gameco/pull/1)
2. **Ветки `docs/add-readme-ru` с готовым русским `README.md` (30 публичных технических проектов — ждут открытия PR):**
   - Исходные **18**: `AI2DTab`, `data4`, `robot`, `infom`, `meta4`, `info15`, `info10`, `info201`, `an-info`, `info200`, `daten9`, `daten8`, `daten5`, `daten1`, `x-index`, `info4project`, `startups-bizwiki`, `flower-shop-online`. *(А `cardix` уже обновлён напрямую в `main`.)*
   - Дополнительно расширены **12** (вместо прежних кратких описаний): `daten23`, `data3`, `info70`, `meta0`, `daten4`, `data2`, `meta10`, `data10`, `data50`, `info4`, `info3`, `daten3`.
   - Прямые ссылки для открытия PR: `https://github.com/svend4/<repo>/compare/main...docs/add-readme-ru?expand=1`
3. **Бесконфликтные ветки консолидации кода `consolidate/ready-for-main` (14 публичных технических проектов — ждут открытия PR в `main`):**
   - **8 с заглушкой `main`:** `cardix`, `data4`, `daten8`, `daten9`, `x-index`, `an-info`, `startups-bizwiki`, `info200`.
   - **6 активных проектов:** `robot`, `ail-runtime`, `in4n`, `data10`, `daten2`, `info140`.
   - Прямые ссылки для открытия PR: `https://github.com/svend4/<repo>/compare/main...consolidate/ready-for-main?expand=1`
4. **Ветки прицельного технического аудита и исправлений `audit/code-review` (6 приоритетных проектов волны 2):**
   - `pro2` (на базе `main`: перенесены 10 файлов из `ulcwt` поверх PR #86 + `docs/AUDIT_REPORT.md`), `robot` (`.gitignore`, `pyproject.toml`, `docs/AUDIT_REPORT.md`), `ail-runtime` (`mvp/src/lib.rs`, `docs/AUDIT_REPORT.md`), `data10` (фиксы `jwt.PyJWTError` и `JWT_SECRET_KEY` в `security.py`, `.env.example`, `docs/AUDIT_REPORT.md`), `info70` (`tools/serve.mjs`, `.gitignore`, `docs/AUDIT_REPORT.md`), `daten3` (`.gitignore`, `.env.example`, `docker-compose.dev.yml`, `docs/AUDIT_REPORT.md`).
   - Прямые ссылки на сравнение с `main`: `https://github.com/svend4/<repo>/compare/main...audit/code-review?expand=1`
5. **Существующие черновые Draft PR от `codex` (`codex/readme-overview-20261118` / `readme-overview-20261118`):** присутствуют в `game-apps` (#2), `new-project-ai-colab` (#1), `AI2DTab` (#4), `data4` (#1), `robot` (#2), `infom` (#5), `meta4` (#3), `info15` (#6), `info10` (#2), `info201` (#2), `an-info` (#1), `info200` (#8), `daten9` (#3), `daten8` (#1), `daten5` (#2), `daten1` (#12), `info4project` (#2), а также в пустых `infod20` (#1), `infod30` (#1), `information` (#4). При слиянии более полных `docs/add-readme-ru` эти черновики можно закрыть.

---

## Категория Д — Полностью влитые ветки (безопасны для удаления при уборке)

Следующие репозитории не содержат невлитого кода, а их старые побочные ветки уже полностью входят в `main` (подробнее с точными названиями веток см. отдельные группы):
- **Только `main` (14 проектов, плюс `meta0` с новой документационной веткой `docs/add-readme-ru`):** `4p`, `alice-snov`, `flower-shop-online`, `game-one`, `gameco`, `geoweave`, `info80`, `info90`, `info100`, `meta0` *(+`docs/add-readme-ru`)*, `milogic-jev`, `mirendil-ai-careers-wiki`, `mirendil-wiki`, `open-cycle-jepa`, `runway`.
- **Все побочные ветки уже влиты (24 проекта, 37 влитых веток к очистке):** `data2` (3), `data40` (1), `data50` (1), `daten6` (2), `daten7` (1), `daten11` (1), `daten12` (1), `daten14` (1), `daten22` (2), `daten30` (1), `daten40` (2), `in4` (2), `info` (2, включая `audit-wave1`), `info1` (1), `info2` (1), `info4` (3), `info5` (1), `info15` (3 влитых + `codex` черновик), `info20dd` (1), `info40` (1), `info150` (1), `meta1` (1), `meta10` (1), `nautilus` (3).
- **Крупные архивы уже влитых веток в многоветочных репо:** `data30` (**90** веток с `2026-01-09`), `daten3` (**13** веток), `lorenzo` (**9** веток), `pro2` (**8** веток), `daten20` (**8** веток), `meta` (**7** веток), `games-monorepo` (**4** ветки), `info4project` (**4** ветки), `universal-file-storage-mcp` (**3** ветки), `ai-colab` (**2** ветки), `infod10` (**2** ветки), `infon` (**5** веток), `daten4` (**1** ветка), `data7` (**1** ветка), `info3` (**1** ветка), `daten5` (**1** ветка), `info30` (**1** ветка), `info7` (**1** ветка), `data20` (**8** веток).
