## Konstantin Konuhov
**Product Analytics | PostgreSQL · Python · BI · A/B testing**

I analyse funnels, cohort retention and user behaviour to help teams prioritise product changes. My commercial experience combines hands-on analytics with product and project management in digital products and EdTech.

[LinkedIn](https://www.linkedin.com/in/konstantin-konuhov-4a4a23352/) · Moscow, Russia · Open to product and data analytics roles

### Featured Analytics Projects

| Project | Question and methods | Evidence |
|---|---|---|
| [**Cookie Cats A/B test** (real data)](https://github.com/kkchillbro/cookie-cats-ab-test) | Should a mobile game move its first paywall gate from level 30 to 40? 90k real players: SRM check, outliers, z-test + bootstrap, power. Moving the gate cut 7-day retention by 0.82 pp (p = 0.0016). | [Kaggle notebook](https://www.kaggle.com/code/kkchillbro/cookie-cats-a-b-test-gate-30-vs-40) with outputs, README with decision and limitations. |
| [Retention drop root cause](https://github.com/kkchillbro/retention-drop-investigation) | Why did D7 retention fall by 7 pp? Hypothesis tree, segment and funnel drill-down, counterfactual, Kitagawa mix/rate decomposition: release bug 41%, channel mix 55%. | PostgreSQL + pandas pipeline, 4 charts, auto-generated findings, 3 tests. |
| [A/B testing toolkit](https://github.com/kkchillbro/ab-testing-toolkit) | How much do common experiment mistakes cost? Power analysis, SRM, delta method, CUPED, Holm; simulations show peeking raises false positives from 5% to 25%. | Python package, Monte-Carlo simulations, experiment readout, 9 tests. |
| [SQL product metrics cookbook](https://github.com/kkchillbro/sql-product-metrics) | How to compute DAU/MAU, funnels, cohorts, churn, LTV, CAC/ROMI/payback, RFM, sessions without the usual pitfalls? | 10 PostgreSQL queries, SQL-only seed, Docker, saved outputs. |
| [EdTech purchase funnel](https://github.com/kkchillbro/edtech-funnel-analysis) | Where does the ordered purchase journey lose users? Python, mobile / desktop segments, seven-day follow-up and event quality checks. | Reproducible pipeline, chart, user-level audit and 5 tests. |
| [Marketing unit economics](https://github.com/kkchillbro/marketing-unit-economics) | Which acquisition channels cover their costs? Mature 30-day cohorts, CAC, refund-adjusted revenue and contribution ROMI. | BI-ready exports, chart, metric specification and 9 tests. |

The Cookie Cats project uses a public real-world dataset. The other demonstrations were created in October 2026 with AI assistance on fully synthetic data; they contain no employer or personal data and do not represent commercial results. Each repository includes reproduction steps, tests and explicit limitations.

### Analytical Work

| Product question | My work |
|---|---|
| Where do users leave the purchase journey? | Analysed course discovery and payment funnels; worked with designers and developers on UX improvements. |
| Which users return after communications? | Built first-visit cohorts, measured D1 / D3 / D7 retention by channel and excluded technical anomalies. |
| What was a user's first communication touchpoint? | Ranked interactions with `ROW_NUMBER() OVER (PARTITION BY user_id ORDER BY hit_time)`. |
| Which users need different messages? | Segmented users to support targeted communications and more focused advertising. |
| What should the product team prioritise? | Combined dashboards, survey analysis, customer interviews and usability findings into product tasks. |

### Toolkit

| Area | Tools and methods |
|---|---|
| SQL | PostgreSQL, JOIN, GROUP BY, aggregations, CASE WHEN, COUNT(DISTINCT), window functions, subqueries and CTEs |
| Python | pandas, NumPy, SciPy, Jupyter Notebook |
| Experimentation | sample size and power, SRM, z / t-tests, bootstrap, delta method, CUPED, multiple testing |
| BI & web analytics | Power BI, Yandex DataLens, Google Analytics, Yandex Metrica |
| Product metrics | Funnels, conversion, cohort analysis, retention, churn, segmentation, LTV, CAC, ROI/ROMI |

### Experience

**LAUNCH-BOX** · December 2023 – present
Project / Product Manager with product and business analytics responsibilities.

Digital products and an EdTech platform: funnel analysis, cohort retention, survey processing, dashboards and collaboration with design / development teams. Investigated payment logs jointly with developers and translated findings into product and technical tasks.

### Education & Development

**State University of Management**
Economics and Finance / Financial Management · 2025 – 2029, in progress.

Courses: VK Education – Product Management; Netology – Project Management.

Finalist: TechnoCup 2025 · T1.GenAI 2025 · HSE Case 2024.

Open to remote or hybrid work and relocation to Europe with visa sponsorship.
