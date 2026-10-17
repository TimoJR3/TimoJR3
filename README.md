# Тимур Гасанов — Data / Product Analyst · Системный аналитик

Аналитик данных, 1 год 3 месяца коммерческого опыта. Москва · Telegram [@TimoJR07](https://t.me/TimoJR07)

**Данные:** SQL · PostgreSQL · DuckDB · dbt · Airflow · Python (pandas, SciPy, scikit-learn) · A/B-тесты · Power BI · Yandex DataLens<br>
**Системный анализ:** user stories и критерии приёмки · use case · BPMN · ER · UML sequence · C4 · REST / OpenAPI · AsyncAPI · RabbitMQ / Kafka<br>
**Инженерия:** FastAPI · Docker · Git · pytest · GitHub Actions

---

## Опыт

**MeshGroup — аналитик данных** · январь 2025 — март 2026
- Повысил **конверсию в оплату с 13,4% до 21,0% (+7,6 п.п.)**: разложил путь от выбора лицензии до оплаты на этапы на данных **150 тыс. пользователей** (SQL, PostgreSQL, Python) и нашёл этап с наибольшим оттоком — платёжный сценарий.
- Вместе с продакт-менеджером и дизайнером оформил изменения формы оплаты в Jira как user stories с критериями приёмки, описал требования к событиям аналитики и довёл изменения до релиза.
- Подтвердил эффект A/B-тестом (сплит 70/30, месяц); после раскатки на всех пользователей эффект сохранился.
- Сократил ручную подготовку отчётности **на 80%**: запустил 5 автоматизированных дашбордов Power BI для руководства.
- Собирал и обрабатывал данные для отчётности: события сайта и данные CRM через Apache Airflow и Apache NiFi, предобработка в SQL.

---

## Data / Product Analytics

| Проект | Результат | Стек |
|---|---|---|
| [**E-commerce Product Analytics**](https://github.com/TimoJR3/ecommerce-product-analytics-ru) | 20,7 млн событий: воронка сессий просмотр → корзина 16,9%, корзина → покупка 13,9%; 86% корзин не доходят до покупки — первая гипотеза для A/B-теста. Витрины в dbt (12 моделей, 37 тестов данных), пайплайн в Airflow | SQL (DuckDB), dbt, Airflow, Python, Power BI / DataLens |
| [**Experiment Lab**](https://github.com/TimoJR3/Experiment-Lab) | A/B-тест от дизайна до вывода: размер выборки и MDE (для +5% к конверсии 13,4% нужно 41 430 пользователей на группу), SRM, CUPED, поправка Холма, z- и t-тесты | Python, SciPy, statsmodels, PostgreSQL, FastAPI |
| [**Retail Demand & Inventory**](https://github.com/TimoJR3/retail-demand-inventory-analytics) | Прогноз спроса товар × страна: LightGBM точнее лучшего baseline (WMAPE 0,80 против 0,86, RMSE −27%); 10% позиций дают 71% ошибки — их стоит отдать на ручную проверку закупщику | SQL (DuckDB), pandas, LightGBM, Power BI |
| [**Sales Analytics (Power BI)**](https://github.com/TimoJR3/sales-analytics-powerbi) | Тестовое задание (принято): 6 KPI на DAX, ABC 70/90%, модель «звезда» из 6 таблиц; 279 убыточных заказов съедают 20% прибыли. Все метрики сверены независимым расчётом на Python до копейки | Power BI (DAX, Power Query, PBIP), Python, pytest |

## Системный анализ

| Проект | Результат | Стек |
|---|---|---|
| [**IT Skills Radar**](https://github.com/TimoJR3/IT_Skills_Radar) | Пайплайн по junior-вакансиям (валидация → нормализация навыков → PostgreSQL → API → дашборд) и [комплект аналитической документации](https://github.com/TimoJR3/IT_Skills_Radar/tree/main/docs/system-analysis): 8 user stories с критериями приёмки, BPMN AS-IS / TO-BE, ER, OpenAPI, sequence, спецификация интеграции с DLQ, C4 | PostgreSQL, FastAPI, Streamlit, OpenAPI, BPMN |
| [**CloudRM** — прототип для ВКР](https://github.com/TimoJR3/cloud_multi_agent-manager) | 7 агентов управляют очередями и ресурсами ЦОД через события; контракт 16 событий описан в [AsyncAPI 3.0](https://github.com/TimoJR3/cloud_multi_agent-manager/blob/main/docs/asyncapi.yaml) с повторной доставкой и DLQ, тест сверяет спецификацию с кодом | Python, FastAPI, RabbitMQ, Kafka, PostgreSQL, Redis, Prometheus |

**Хакатон AI Journey Contest 2026 — Coordination Referee** (октябрь 2026, в процессе): классификация логов мультиагентных систем по 7 типам сбоев координации, успеху и шагу сбоя; ансамбль градиентного бустинга и BiGRU, локальная кросс-валидация совпадает с лидербордом до 0,001; метрика 0,919, 40-е место из 128 (на 17.10).

Также: [Churn Risk & Model Monitoring](https://github.com/TimoJR3/Churn-Risk-Model-Monitoring-Lab) — модель оттока на синтетических данных (ROC-AUC 0,84 на отложенной выборке), API скоринга и мониторинг дрейфа PSI.

---

## Образование и обучение
- **РТУ МИРЭА**, «Управление данными» — выпуск 2028 (учёбу совмещаю с работой)
- **Karpov.courses** — «Аналитик данных» (в процессе): Python, Git, SQL, теория вероятностей, статистика, продуктовая аналитика и A/B-тесты
- Английский — B1

Открыт к позициям **Junior / Junior+ Data Analyst, Product Analyst, Системный аналитик** в Москве: офис, гибрид или удалёнка, полный рабочий день.
