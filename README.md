# 👋 Hi, I'm Malek Khalifa

I'm a passionate IT student and self-taught developer based in Rades, Tunisia. With a strong foundation in web development and a growing interest in data analysis and engineering, I'm currently exploring ways to combine clean UI design with meaningful, data-driven functionality.

## 💡 About Me

- 🎓 Bachelor's degree in Computer Science (in progress) – ISET Rades
- 💻 Former freelance web developer (Angular & Vue.js)
- 🤝 Collaborating on a team project to create a training platform
- 🔄 Transitioning from full-stack web development to data analytics/engineering

## 🛠 Tech Stack

**Languages:** JavaScript, TypeScript, Python, PHP, SQL, Java, C  
**Frameworks & Libraries:** Angular, Vue.js, Django, Symfony, JavaFX  
**Databases:** PostgreSQL, MongoDB, MySQL, SQL Server, Oracle DB  
**AI & Data:** Agno (multi-agent framework), Google Gemini API, Celery, Pandas  
**Tools:** UML, SSIS, SSMS, REST APIs  
**Other:** OOP, UI/UX, Data Visualization, Real-time Streaming (SSE)

## 🔨 Projects

### 🔹 QualityLab — AI-Powered Data Quality Platform *(Final Year Project)*
- Built a full-stack platform that connects to a PostgreSQL database and automatically detects data quality issues using a **multi-agent AI pipeline**.
- Implemented **4 specialised AI agents** (Schema Integrity Validator, Cross-Row Validator, Row-Level Logic Validator, Fix Planner) orchestrated with the **Agno framework** and **Google Gemini**.
- Agents detect schema violations, referential integrity issues, and business rule breaches (invalid phone formats, date inversions, negative quotas, routing self-loops, etc.) and generate structured **human-reviewable fix cards**.
- Human-in-the-loop fix review system: users inspect, accept, or reject each proposed SQL fix before it is applied to a shadow `_clean` table — source data is never modified.
- Real-time agent progress streamed to the frontend via **Server-Sent Events (SSE)**.
- Generated **2 million rows** of realistic synthetic training data (70% valid / 30% intentionally corrupt across 33 business tables) using a custom data generator with topological FK resolution.
- Stack: **Angular, Django REST Framework, PostgreSQL, MongoDB, Celery, Agno, Google Gemini API**.
- GitHub: [Backend (Django)](https://github.com/Malekhalifa/PFE-Project-Backend-Django) · [Frontend (Angular)](https://github.com/Malekhalifa/PFE-Project-Frontend-Angular)

### 🔹 HubbleMind Visualization App
- Built a full-stack web application to execute user queries and render results using pie, bar, and line charts.
- Integrated role-based access (Admin, User, Guest) with a clean, intuitive UI.
- Stack: Angular, TypeScript, PHP (API), MySQL.

### 🔹 Training Platform (Team Project)
- Collaborating with 3 classmates to build a full-featured training and course management platform.
- Features include course browsing, enrollment, and user roles (admin, trainer, learner).
- Contributing to both front-end and back-end development using modern tools and clean architecture.
- GitHub: [Tayss1r/Training_Platform](https://github.com/Tayss1r/Training_Platform)

### 🔹 Spotify Clone (Freelance Project)
- Created a music streaming web app with Angular and Angular Material.
- Included playlist management, playback features, and RESTful API integration.

### 🔹 Book Collection Manager (Freelance Project)
- Built with Vue 3 using Composition API and Pinia for state management.
- Integrated Google Books API for search and pagination.
- Local storage for collection tracking and responsive design enhancements.

## 📈 Certifications

- 🐍 Python Essentials 1 – Cisco Academy  
- 🗃️ Database Programming with SQL – Oracle Academy  

## 📫 Let's Connect

- 📧 Email: [malek.khalifa321@gmail.com](mailto:malek.khalifa321@gmail.com)
- 💼 LinkedIn: [linkedin.com/in/khalifa-malek](https://www.linkedin.com/in/khalifa-malek)
- 💻 GitHub: [github.com/Malekhalifa](https://github.com/Malekhalifa)

---

Thanks for visiting my GitHub! I'm always open to collaboration and learning opportunities—especially in data analysis and engineering.
