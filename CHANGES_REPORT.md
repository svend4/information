# Отчёт об объёме репозиториев и статистике изменений (`+добавлено / -удалено`)

Детальная ведомость по **93 открытым (Public) техническим репозиториям** профиля [`svend4`](https://github.com/svend4?tab=repositories) за сессию `2026-11-18` (все данные сняты напрямую через GitHub API `search_repositories` и `get_commit` с `detail: "stats"`).

> [!NOTE]
> Важное разграничение: крупные массивы исходного кода и автотестов в проектах (`info70` — 3 393 теста, `robot` — 2 446 тестов, `daten2` — 47 сервисов, `ail-runtime` — 55 тестов v2) были созданы ранее в неслитых ветках. В таблице изменений ниже учтены **строго новые коммиты текущей ревизии (`2026-11-18`)**: документация `README.md` на русском языке, сохранённые оригинальные описания `docs/BRANCH_README_ORIG.md`, синхронизированные лицензии `GNU AGPL v3.0` (`661` строка) в ветках `consolidate/ready-for-main`, а также файлы центрального каталога и аудита веток.

---

## 1. Общая сводка по открытому техническому контуру (`93` репозитория)

- **Всего открытых технических репозиториев проверено (read-only аудит веток и каталогизация):** **93**
- **Репозиториев, в которых сегодня созданы/обновлены ветки и коммиты:** **39**
  - Прямое обновление в `main`: **1** (`cardix`)
  - Открыты Pull Request с новым `README.md`: **3** (`game-apps` #3, `new-project-ai-colab` #2, `gameco` #1)
  - Ветки `docs/add-readme-ru` (готовы к открытию PR): **30** *(18 заготовок + 12 расширенных кратких описаний)*
  - Бесконфликтные ветки консолидации кода `consolidate/ready-for-main`: **14** *(для `pro2` зафиксирован безопасный план cherry-pick 4 коммитов поверх PR #86)*
  - Центральный каталог и отчёт по веткам (`docs/catalog`): **1** (`information`)
- **Репозиториев без изменений (проверены в режиме read-only):** **54** *(51 проект уже имел развёрнутый `README.md` на `main`, включая `pro2`, плюс 3 пустые заготовки `4p`, `infod20`, `infod30` — `+0 / -0` строк)*
- **Суммарно по всем `92` коммитам ревизии в 39 открытых технических репозиториях (до записи этого отчёта):** **+11385 добавленных строк / -2071 удалённых строк** *(чистый прирост: **+9314** строк; удаления в ветках `consolidate/ready-for-main` в основном связаны с переносом прежнего `README.md` в `docs/BRANCH_README_ORIG.md` и заменой MIT на `AGPL-3.0`)*.

---

## 2. Топ-20 крупнейших открытых технических репозиториев по размеру GitHub (`size`)

| # | Репозиторий | Размер GitHub (`КБ`) | Размер (`МБ`) | Основной язык | Статус правок `2026-11-18` |
| ---: | :--- | ---: | ---: | :--- | :--- |
| 1 | [pro2](https://github.com/svend4/pro2) | 231068 | 225.65 | Python | +0 / -0 (аудит + план cherry-pick 4 коммитов) |
| 2 | [meta](https://github.com/svend4/meta) | 218118 | 213.01 | Python | +0 / -0 (read-only аудит) |
| 3 | [lorenzo](https://github.com/svend4/lorenzo) | 131717 | 128.63 | Python | +0 / -0 (read-only аудит) |
| 4 | [daten3](https://github.com/svend4/daten3) | 31759 | 31.01 | TypeScript | +93 / -3 (1 комм.) |
| 5 | [data70](https://github.com/svend4/data70) | 22862 | 22.33 | Python | +0 / -0 (read-only аудит) |
| 6 | [gameco](https://github.com/svend4/gameco) | 13944 | 13.62 | TypeScript | +58 / -0 (1 комм.) |
| 7 | [infod10](https://github.com/svend4/infod10) | 13159 | 12.85 | Jupyter Notebook | +0 / -0 (read-only аудит) |
| 8 | [data2](https://github.com/svend4/data2) | 12814 | 12.51 | Python | +81 / -6 (2 комм.) |
| 9 | [AI2DTab](https://github.com/svend4/AI2DTab) | 11322 | 11.06 | TypeScript | +80 / -1 (1 комм.) |
| 10 | [info70](https://github.com/svend4/info70) | 9217 | 9 | Markdown / Mixed | +94 / -2 (1 комм.) |
| 11 | [daten](https://github.com/svend4/daten) | 8295 | 8.1 | Python | +0 / -0 (read-only аудит) |
| 12 | [daten20](https://github.com/svend4/daten20) | 8142 | 7.95 | Python | +0 / -0 (read-only аудит) |
| 13 | [info4project](https://github.com/svend4/info4project) | 7320 | 7.15 | JavaScript | +90 / -2 (1 комм.) |
| 14 | [infon](https://github.com/svend4/infon) | 7191 | 7.02 | Go | +0 / -0 (read-only аудит) |
| 15 | [runway](https://github.com/svend4/runway) | 5940 | 5.8 | JavaScript | +0 / -0 (read-only аудит) |
| 16 | [meta2](https://github.com/svend4/meta2) | 5931 | 5.79 | Python | +0 / -0 (read-only аудит) |
| 17 | [x-index](https://github.com/svend4/x-index) | 5837 | 5.7 | Markdown / Mixed | +250 / -72 (11 комм.) |
| 18 | [ai-colab](https://github.com/svend4/ai-colab) | 5384 | 5.26 | Python | +0 / -0 (read-only аудит) |
| 19 | [flower-shop-online](https://github.com/svend4/flower-shop-online) | 4711 | 4.6 | TypeScript | +57 / -1 (1 комм.) |
| 20 | [info7](https://github.com/svend4/info7) | 4173 | 4.08 | TypeScript | +0 / -0 (read-only аудит) |

---

## 3. Построчная статистика по каждому из 39 изменённых открытых репозиториев

| # | Репозиторий | Размер репо (`КБ`) | Коммитов | Добавлено (`+`) | Удалено (`-`) | Чистая дельта | Детализация по веткам и файлам |
| ---: | :--- | ---: | ---: | ---: | ---: | ---: | :--- |
| 1 | [data10](https://github.com/svend4/data10) | 342 | 4 | **+1361** | **-502** | +859 | `docs/add-readme-ru` (`5a14a2ed`): +121/-3 — README.md (+121/-3)<br>`consolidate/ready-for-main` (`a025efe9`): +1240/-499 — README.md (+61/-478), docs/BRANCH_README_ORIG.md (+518/-0), LICENSE AGPL-3.0 (+661/-21) |
| 2 | [robot](https://github.com/svend4/robot) | 2416 | 4 | **+1203** | **-437** | +766 | `docs/add-readme-ru` (`0166fe37`): +56/-2 — README.md (+56/-2)<br>`consolidate/ready-for-main` (`786fc314`): +1147/-435 — README.md (+39/-432), docs/BRANCH_README_ORIG.md (+449/-0), LICENSE AGPL-3.0 (+659/-3) |
| 3 | [daten9](https://github.com/svend4/daten9) | 56 | 6 | **+1119** | **-296** | +823 | `docs/add-readme-ru` (`0e0fccf3`): +82/-2 — README.md (+82/-2)<br>`consolidate/ready-for-main` (`c5d67686`): +1037/-294 — LICENSE (+661), docs/BRANCH_README_ORIG.md (+311), README.md (+58/-287) + выравнивание байтов |
| 4 | [data4](https://github.com/svend4/data4) | 60 | 7 | **+1036** | **-259** | +777 | `docs/add-readme-ru` (`edfb178e`): +59/-2 — README.md (+59/-2)<br>`consolidate/ready-for-main` (`c48aab2e`): +977/-257 — LICENSE (+660 + выравнивание), docs/BRANCH_README_ORIG.md (+248), README.md (+36/-225) |
| 5 | [daten8](https://github.com/svend4/daten8) | 58 | 7 | **+1013** | **-184** | +829 | `docs/add-readme-ru` (`718ddfb9`): +85/-2 — README.md (+85/-2)<br>`consolidate/ready-for-main` (`253d28c8`): +928/-182 — LICENSE (+661 + выравнивание), docs/BRANCH_README_ORIG.md (+190), README.md (+62/-167) |
| 6 | [info200](https://github.com/svend4/info200) | 2295 | 2 | **+784** | **-26** | +758 | `docs/add-readme-ru` (`7338d245`): +68/-2 — README.md (+68/-2)<br>`consolidate/ready-for-main` (`e68333a6`): +716/-24 — LICENSE (+661/-0), README.md (+55/-24) |
| 7 | [in4n](https://github.com/svend4/in4n) | 105 | 2 | **+696** | **-25** | +671 | `consolidate/ready-for-main` (`5e0fa086`): +696/-25 — README.md (+35/-25), LICENSE (+661/-0) |
| 8 | [ail-runtime](https://github.com/svend4/ail-runtime) | 200 | 2 | **+681** | **-10** | +671 | `consolidate/ready-for-main` (`d74254ca`): +681/-10 — README.md (+20/-10), LICENSE (+661/-0) |
| 9 | [daten2](https://github.com/svend4/daten2) | 1705 | 2 | **+667** | **-0** | +667 | `consolidate/ready-for-main` (`7e1f3d37`): +667/-0 — README.md (+6/-0), LICENSE (+661/-0) |
| 10 | [information](https://github.com/svend4/information) | 36 | 2 | **+325** | **-50** | +275 | `docs/catalog` (`cfbd9871`): +325/-50 — Центральный каталог README.md и BRANCH_AUDIT.md (2 коммита: +271/-2 и +54/-48) |
| 11 | [x-index](https://github.com/svend4/x-index) | 5837 | 11 | **+250** | **-72** | +178 | `docs/add-readme-ru` (`321ed836`): +90/-2 — README.md (+90/-2)<br>`consolidate/ready-for-main` (`e9c2ca6e`): +160/-70 — README.md (+74/-45), docs/BRANCH_README_ORIG.md (+61/-0), выравнивание LICENSE |
| 12 | [cardix](https://github.com/svend4/cardix) | 37 | 8 | **+165** | **-55** | +110 | `main` (`e646be3e`): +57/-2 — README.md обновлён напрямую в main (+57/-2)<br>`consolidate/ready-for-main` (`d978ba2d`): +108/-53 — README.md (+57/-2) и побайтовое выравнивание LICENSE с main |
| 13 | [an-info](https://github.com/svend4/an-info) | 412 | 7 | **+133** | **-40** | +93 | `docs/add-readme-ru` (`a4327612`): +61/-2 — README.md (+61/-2)<br>`consolidate/ready-for-main` (`466d8be3`): +72/-38 — README.md (+58/-24) и побайтовое выравнивание LICENSE с main |
| 14 | [data3](https://github.com/svend4/data3) | 25 | 1 | **+121** | **-2** | +119 | `docs/add-readme-ru` (`a711b487`): +121/-2 — README.md (+121/-2) |
| 15 | [daten4](https://github.com/svend4/daten4) | 620 | 1 | **+115** | **-3** | +112 | `docs/add-readme-ru` (`ea530190`): +115/-3 — README.md (+115/-3) |
| 16 | [meta0](https://github.com/svend4/meta0) | 199 | 1 | **+106** | **-5** | +101 | `docs/add-readme-ru` (`b81b6089`): +106/-5 — README.md (+106/-5) |
| 17 | [info140](https://github.com/svend4/info140) | 2104 | 1 | **+99** | **-45** | +54 | `consolidate/ready-for-main` (`10679484`): +99/-45 — README.md (+30/-45), docs/BRANCH_README_ORIG.md (+69/-0) |
| 18 | [info4](https://github.com/svend4/info4) | 2723 | 1 | **+99** | **-3** | +96 | `docs/add-readme-ru` (`66ba39be`): +99/-3 — README.md (+99/-3) |
| 19 | [daten23](https://github.com/svend4/daten23) | 24 | 1 | **+96** | **-2** | +94 | `docs/add-readme-ru` (`da3c272c`): +96/-2 — README.md (+96/-2) |
| 20 | [daten5](https://github.com/svend4/daten5) | 115 | 1 | **+96** | **-2** | +94 | `docs/add-readme-ru` (`4f0b6b13`): +96/-2 — README.md (+96/-2) |
| 21 | [info70](https://github.com/svend4/info70) | 9217 | 1 | **+94** | **-2** | +92 | `docs/add-readme-ru` (`b0a3fae5`): +94/-2 — README.md (+94/-2) |
| 22 | [daten3](https://github.com/svend4/daten3) | 31759 | 1 | **+93** | **-3** | +90 | `docs/add-readme-ru` (`e4581150`): +93/-3 — README.md (+93/-3) |
| 23 | [info4project](https://github.com/svend4/info4project) | 7320 | 1 | **+90** | **-2** | +88 | `docs/add-readme-ru` (`109d913d`): +90/-2 — README.md (+90/-2) |
| 24 | [info3](https://github.com/svend4/info3) | 1956 | 1 | **+89** | **-3** | +86 | `docs/add-readme-ru` (`7eb62d87`): +89/-3 — README.md (+89/-3) |
| 25 | [data2](https://github.com/svend4/data2) | 12814 | 2 | **+81** | **-6** | +75 | `docs/add-readme-ru` (`3b510287`): +81/-6 — README.md (2 коммита: +80/-3 и +1/-3) |
| 26 | [AI2DTab](https://github.com/svend4/AI2DTab) | 11322 | 1 | **+80** | **-1** | +79 | `docs/add-readme-ru` (`15925631`): +80/-1 — README.md (+80/-1) |
| 27 | [info10](https://github.com/svend4/info10) | 80 | 1 | **+66** | **-2** | +64 | `docs/add-readme-ru` (`d945aaa1`): +66/-2 — README.md (+66/-2) |
| 28 | [startups-bizwiki](https://github.com/svend4/startups-bizwiki) | 318 | 2 | **+63** | **-17** | +46 | `docs/add-readme-ru` (`0929072d`): +38/-1 — README.md (+38/-1)<br>`consolidate/ready-for-main` (`2742ed60`): +25/-16 — README.md (+25/-16) |
| 29 | [daten1](https://github.com/svend4/daten1) | 630 | 1 | **+62** | **-2** | +60 | `docs/add-readme-ru` (`d639eea1`): +62/-2 — README.md (+62/-2) |
| 30 | [info201](https://github.com/svend4/info201) | 420 | 1 | **+61** | **-2** | +59 | `docs/add-readme-ru` (`f0267a15`): +61/-2 — README.md (+61/-2) |
| 31 | [infom](https://github.com/svend4/infom) | 347 | 1 | **+61** | **-2** | +59 | `docs/add-readme-ru` (`2fc92209`): +61/-2 — README.md (+61/-2) |
| 32 | [meta10](https://github.com/svend4/meta10) | 61 | 1 | **+59** | **-3** | +56 | `docs/add-readme-ru` (`818ff928`): +59/-3 — README.md (+59/-3) |
| 33 | [gameco](https://github.com/svend4/gameco) | 13944 | 1 | **+58** | **-0** | +58 | `docs/add-readme-ru` (`077cfb5a`): +58/-0 — README.md добавлен (+58/-0, открыт PR #1) |
| 34 | [flower-shop-online](https://github.com/svend4/flower-shop-online) | 4711 | 1 | **+57** | **-1** | +56 | `docs/add-readme-ru` (`37a91379`): +57/-1 — README.md (+57/-1) |
| 35 | [info15](https://github.com/svend4/info15) | 131 | 1 | **+56** | **-2** | +54 | `docs/add-readme-ru` (`4f63e8d9`): +56/-2 — README.md (+56/-2) |
| 36 | [data50](https://github.com/svend4/data50) | 18 | 1 | **+48** | **-3** | +45 | `docs/add-readme-ru` (`b96a1dcc`): +48/-3 — README.md (+48/-3) |
| 37 | [game-apps](https://github.com/svend4/game-apps) | 113 | 1 | **+46** | **-0** | +46 | `docs/add-readme-ru` (`d5d11923`): +46/-0 — README.md добавлен (+46/-0, открыт PR #3) |
| 38 | [meta4](https://github.com/svend4/meta4) | 20 | 1 | **+32** | **-2** | +30 | `docs/add-readme-ru` (`806ba88d`): +32/-2 — README.md (+32/-2) |
| 39 | [new-project-ai-colab](https://github.com/svend4/new-project-ai-colab) | 16 | 1 | **+24** | **-0** | +24 | `docs/add-readme-ru` (`b7dbd2ea`): +24/-0 — README.md добавлен (+24/-0, открыт PR #2) |
| — | **ИТОГО (39 репо)** | — | **92** | **+11385** | **-2071** | **+9314** | По данным GitHub get_commit (stats, вкл. 14 пустых коммитов выравнивания в истории) |

> Остальные **54** открытых технических репозитория профиля прошли полный read-only аудит веток и включены в [README.md](./README.md) и [BRANCH_AUDIT.md](./BRANCH_AUDIT.md) со статистикой изменений **`+0 / -0` строк**.
