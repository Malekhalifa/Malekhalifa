# 👋 Hi, I'm Malek Khalifa

IT student and self-taught developer based in Rades, Tunisia. I started in web development (Angular, Vue.js, Symfony) and now build data-driven and AI-assisted tools: multi-agent data-quality validation, and research pipelines that test ideas before believing them.

## 💡 About Me

- 🎓 Bachelor's degree in Computer Science (in progress), ISET Rades
- 🔬 Final year project: **QualityLab**, an AI-powered data-quality platform built on a multi-agent pipeline
- 📊 Recently shipped **Sift**, a pre-registered research pipeline for testing trading strategies on free data
- 💻 Former freelance web developer (Angular and Vue.js)
- 🔄 Moving from full-stack web development toward data analytics, data engineering and applied AI

## 🛠 Tech Stack

**Languages:** Python, TypeScript, JavaScript, PHP, SQL, Java, C  
**Frontend:** Angular, Vue 3, Tailwind CSS, Chart.js  
**Backend:** Django REST Framework, Celery, Redis, Symfony  
**Databases:** PostgreSQL, MySQL, SQLite, MongoDB, SQL Server, Oracle DB  
**AI & Data:** Agno (multi-agent framework), Google Gemini API, pandas, Parquet, pytest  
**Tools:** uv, Git, LaTeX, Mermaid, UML, SSIS, SSMS, REST APIs  
**Other:** OOP, UI/UX, Data Visualization, i18n, Statistics and backtesting

## 🔨 Featured Projects

### 🔹 [Sift](https://github.com/Malekhalifa/sift): Honest testing for trading ideas
A pre-registered research pipeline that tests short-term US stock strategies on free data and catches the ideas that only look like they work.

- Tested **12 trading ideas** (breakouts, mean reversion, earnings drift, insider buying, political-news event studies and more). None passed, and a clear "no" is the result.
- Built to catch the two traps that make most ideas look good: **selection luck** and **the market's own rise**.
- Protocol, parameter grid and pass criteria are committed *before* every run. Walk-forward testing, a log of every configuration tried (298), a Deflated Sharpe check, a market-adjusted check, and replication on unseen stocks.
- 2025+ data is a locked holdout, refused by the code unless explicitly unlocked. Real money traded: **$0**.
- Findings published as a [whitepaper (PDF)](https://github.com/Malekhalifa/sift/blob/main/docs/Trading-Research-Findings.pdf) with plain-language write-ups per idea.
- Stack: **Python 3.12+, uv, pandas, Parquet, SQLite trial registry, pytest, Alpaca free data tier, SEC EDGAR, USAspending.gov, LaTeX, Mermaid**. 208 tests.

### 🔹 QualityLab: AI-Powered Data Quality Platform *(Final Year Project)*
A full-stack platform that connects to a PostgreSQL database, finds data-quality issues with a **multi-agent AI pipeline**, and proposes SQL fixes that a human reviews before anything runs.

- **Multi-agent pipeline** orchestrated with **Agno** and **Google Gemini**: schema check and profiling, then Statistical, Structural and Relational validators in parallel; a reducer deduplicates and ranks findings, a Data Fix Planner turns them into SQL fix cards, and a verifier checks them.
- Human-in-the-loop fixes: each proposed SQL fix is reviewed with a pre-flight dry run, then approved or rejected before execution.
- Async pipeline runs on **Celery + Redis**, with job status, results review, conversational AI chat over findings, history, domain rules, report export and an admin dashboard (stats, users, pipeline performance, audit log).
- Angular 21 front end with standalone components, signals, Tailwind CSS, dark/light themes and **English / French / Arabic** i18n.
- Generated **2 million rows** of synthetic training data (70% valid, 30% intentionally corrupt, across 33 business tables) with topological FK resolution.
- Stack: **Angular 21, Django 5 + DRF, PostgreSQL, Celery, Redis, Agno, Gemini**.
- GitHub: [Backend (Django)](https://github.com/Malekhalifa/PFE-Project-Backend-Django) · [Frontend (Angular)](https://github.com/Malekhalifa/PFE-Project-Frontend-Angular)

## 🧱 Other Projects

### 🔹 [Dynamic Data Visualization Platform](https://github.com/Malekhalifa/dynamic-data-visualization-platform)
- Web app to run user queries and render the results as zoomable pie, bar and line charts, with query history, favourites and CSV export.
- Stack: Angular, TypeScript, Chart.js, Tailwind CSS. · [Live demo](https://dynamic-data-visualization-platform.vercel.app)

### 🔹 [E-commerce (Symfony)](https://github.com/Malekhalifa/e-commerce-symfony)
- Symfony 7.2 shop with authentication, product catalog and categories, cart, order management, admin-only catalog and order pages, and pagination.
- Stack: PHP 8.2, Symfony, Twig, MySQL.

### 🔹 [Training Platform](https://github.com/Tayss1r/Training_Platform) *(Team Project)*
- Course and training management platform built with 3 classmates: course browsing, enrollment, and roles (admin, trainer, learner).
- Stack: PHP 8.2, Symfony 7.2, Twig.

### 🔹 Freelance work
- **Spotify Clone:** music streaming web app with Angular and Angular Material, playlist management, playback and REST API integration.
- **Book Collection Manager:** Vue 3 (Composition API, Pinia), Google Books API search and pagination, local-storage collection tracking.

## 📈 Certifications

- 🐍 Python Essentials 1, Cisco Academy
- 🗃️ Database Programming with SQL, Oracle Academy

## 📫 Let's Connect

- 📧 Email: [malek.khalifa321@gmail.com](mailto:malek.khalifa321@gmail.com)
- 💼 LinkedIn: [linkedin.com/in/khalifa-malek](https://www.linkedin.com/in/khalifa-malek)
- 💻 GitHub: [github.com/Malekhalifa](https://github.com/Malekhalifa)

---

Thanks for visiting! I'm open to collaboration and learning opportunities, especially in data analysis, data engineering and applied AI.
