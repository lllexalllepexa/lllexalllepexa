<div align="center">

<h2>Алексей</h2>

**Аналитик данных · BI · C++ / Qt**

Аналитические пайплайны, SQL-витрины и дашборды; сетевые приложения на C++.

<img src="https://img.shields.io/badge/Python-3d444d?style=flat-square&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/SQL-3d444d?style=flat-square&logo=postgresql&logoColor=white" alt="SQL" />
<img src="https://img.shields.io/badge/DuckDB-3d444d?style=flat-square&logo=duckdb&logoColor=white" alt="DuckDB" />
<img src="https://img.shields.io/badge/Airflow-3d444d?style=flat-square&logo=apacheairflow&logoColor=white" alt="Airflow" />
<img src="https://img.shields.io/badge/Streamlit-3d444d?style=flat-square&logo=streamlit&logoColor=white" alt="Streamlit" />
<img src="https://img.shields.io/badge/C++20-3d444d?style=flat-square&logo=cplusplus&logoColor=white" alt="C++20" />
<img src="https://img.shields.io/badge/Qt_6-3d444d?style=flat-square&logo=qt&logoColor=white" alt="Qt 6" />
<img src="https://img.shields.io/badge/Docker-3d444d?style=flat-square&logo=docker&logoColor=white" alt="Docker" />

</div>

<br/>

### Аналитика данных

<table>
<tr>
<td width="50%" valign="top">

**[Retail Metrics & Cohort Analytics](https://github.com/lllexalllepexa/portfolio-retailmetrics)**

Метрики e-commerce и когортное удержание: 5 SQL-витрин на DuckDB (выручка с учётом возвратов, AOV, удержание с доверительными интервалами), 22 проверки качества данных, 54 теста на эталонных данных, дашборд на Streamlit. Данные синтетические, и README разбирает, какие тренды порождает сам генератор.

<sub>Python · DuckDB · SQL · Streamlit · pytest</sub><br/>
<sub>[Демо →](https://lllexalllepexa-test1.streamlit.app/)</sub>

</td>
<td width="50%" valign="top">

**[Global Superstore: скидки и прибыль](https://github.com/lllexalllepexa/testsomeshi)**

Где скидки съедают прибыль: 51 290 строк заказов за 2011–2014. Строки со скидкой больше 20% дают 15% выручки и −$815 тыс. прибыли. SQL-витрины в DuckDB и PostgreSQL, регрессия с робастными ошибками, Airflow DAG, дашборд на Streamlit, 53 теста.

<sub>Python · DuckDB · PostgreSQL · statsmodels · Airflow · Streamlit</sub>

</td>
</tr>
</table>

### Разработка

<table>
<tr>
<td width="50%" valign="top">

**[Throne Dual Proxy](https://github.com/lllexalllepexa/Throne-DualProxy-win)**

Форк GUI для sing-box: два независимых прокси на разных портах, раздельное определение IP и изолированный DNS.

<sub>C++20 · Qt 6 · sing-box · Go</sub><br/>
<sub>[Релизы →](https://github.com/lllexalllepexa/Throne-DualProxy-win/releases/latest)</sub>

</td>
<td width="50%" valign="top">

**[Sora V2 Battery Tray](https://github.com/lllexalllepexa/ninjutso-sora-v2-battery-tray)**

Заряд мыши Ninjutso Sora V2 в трее Windows. HID-протокол восстановлен по веб-драйверу производителя, драйвер не нужен.

<sub>Python · hidapi · pystray</sub>

</td>
</tr>
</table>

### Небольшие утилиты

- **[Twitch Local SOCKS5 Proxy](https://github.com/lllexalllepexa/twitch-local-socks5-proxy)** — расширение для Chrome и Firefox, ускоряющее запуск стримов через локальный SOCKS5.
- **[Deadlock Build Randomizer](https://github.com/lllexalllepexa/randomizer777)** — генератор случайных сборок для игры Deadlock · [демо](https://lllexalllepexa.github.io/randomizer777/)

<br/>

### Компетенции

| Область | Инструменты и методы |
|---|---|
| **BI и визуализация** | Streamlit, Plotly, Matplotlib, Seaborn |
| **Бизнес-метрики** | выручка и маржа с учётом возвратов, AOV, когортное удержание, анализ скидок |
| **SQL** | оконные функции, CTE, агрегаты с `FILTER`, витрины в DuckDB и PostgreSQL |
| **Статистика** | доверительные интервалы, t-тест Уэлча, регрессия (OLS, робастные ошибки HC3) |
| **ETL и Data Quality** | Pandas, DuckDB, Apache Airflow, проверки качества данных, pytest |
| **Разработка** | C++20 / Qt 6, JavaScript, Docker, Aiogram 3, SQLAlchemy |
