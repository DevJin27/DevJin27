# DevJin27

<div align="right">
  <a href="https://github.com/DevJin27">
    <img src="https://gifdb.com/images/high/coding-animated-laptop-flow-stream-ja04010rm5o68zfk.gif" alt="DevJin27" width="320"/>
  </a>
</div>

Hi — I'm Dev Jindal (DevJin27).  
I'm passionate about building intelligent, reliable systems and learning continuously — from algorithms and systems to ML and full‑stack apps.

- 💻 Focus: Back-end & full-stack development, APIs, systems design  
- 🤖 Interests: AI, fine-tuning models, applied ML, developer tooling  
- 🌱 Always learning: system design, React/Next.js, model fine-tuning  
- 📫 Reach me: devjindal2317@gmail.com | https://github.com/DevJin27

---

## ⚙️ Core Tech & Tools

I work across the full stack and with ML tooling:

- Languages: Python, JavaScript (ES6+), SQL  
- Back-end: FastAPI, Flask, REST, WebSocket, Docker  
- Front-end: React, Next.js, HTML/CSS  
- ML & AI: Model fine-tuning, prompt engineering, evaluation pipelines  
- Datastores: MySQL, PostgreSQL, Redis  
- Dev & Deploy: Git, GitHub, Docker, CI/CD

---

## 🔭 Currently Learning & Working On

- Deepening knowledge of model fine-tuning and evaluation pipelines.  
- Building RISE — a DSA Mentor AI app (see project details below).  
- Improving React/Next.js front-end patterns and full-stack integration.

---

## Projects

### 1) Shelf Stack
- Tech: Python, MySQL, HTML/CSS, JS
- Status: Completed — production-ready MVP
- Overview: Shelf Stack is an inventory and retail management system tailored for small bookstores and shops. It combines staff management, role-based access control, inventory tracking, and sales analytics into one lightweight system.
- Key features:
  - User authentication and role-based access (Admin, Manager, Cashier)
  - Inventory management: add/edit books, categories, stock counts
  - Sales & POS: create sales, discounts, returns, and generate receipts
  - Sales tracking & reports: daily/monthly sales summaries, bestsellers, low-stock alerts
  - Reporting: exportable CSV reports, simple dashboard metrics
- Architecture:
  - Flask (or FastAPI) backend with REST APIs
  - MySQL for persistent storage
  - Modular service structure for inventory, sales, and users
- Deployment & run notes:
  - Designed to run in a container or small VM; easy to deploy with Docker
  - Can integrate barcode scanners and receipt printers for POS use

---

### 2) Project_map
- Tech: FastAPI, React (WebSockets), map visualization libraries, PostgreSQL/MySQL
- Status: Completed — realtime telemetry tracking system
- Overview: Project_map captures, processes, and visualizes real‑time telemetry from drones (or similar devices). It’s built to ingest frequent telemetry, provide live location & status updates on a map, and store historical telemetry for replay and analytics.
- Key features:
  - Real-time ingestion via REST + WebSocket streaming for low-latency updates
  - Interactive frontend map showing live locations, flight paths, telemetry overlays
  - Telemetry pipeline with storage for historical playback and diagnostics
  - Alerts for geofence breaches, low battery, or anomalous telemetry
  - Authentication for device operators and admin dashboards
- Architecture:
  - FastAPI handles telemetry ingestion, WebSocket streams, and REST endpoints
  - Front-end (React) subscribes to telemetry channels for live map updates
  - Optional message broker (Redis/Redis Pub/Sub or lightweight queue) for scaling real-time events
- How to run (example)
  ```bash
  # backend
  uvicorn app.main:app --reload

  # frontend
  cd web && npm install && npm run dev
  ```
- Notes: Built with extensibility in mind — can add ML-based anomaly detection, geospatial indexing, or integrate with cloud streaming services.

---

### 3) RISE — DSA Mentor (in development)
- Tech stack: FastAPI, model fine-tuning (transformer-based), React, Next.js, Python
- Status: Active development (I'm currently working on this)
- Vision: RISE is a DSA-focused AI mentor that helps learners prepare for algorithmic interviews and improves problem-solving skills using personalized coaching and automated feedback.
- Core capabilities:
  - Personalized learning paths and problem recommendations based on skill gaps
  - Problem explanation generation and step-by-step hints
  - Automated code evaluation and constructive feedback (style, complexity, correctness)
  - Adaptive difficulty and progress tracking
  - Conversational mentor UI powered by a fine-tuned model (for DSA pedagogy and scaffolding)
- Technical details:
  - FastAPI provides the API backend, evaluation sandbox, and model serving endpoints
  - Model fine-tuning pipeline for specialized DSA tutoring responses and scoring
  - React + Next.js for an interactive UI (SSR for landing and SEO; CSR for the mentor/chat experience)
  - Secure code execution sandbox for running user solutions (isolated, resource-limited)
  - Analytics and telemetry to track learning progress and model performance
- Current focus:
  - Building a robust evaluation and sandboxing system for running submissions safely
  - Fine-tuning model(s) with curated DSA dialogues and high-quality feedback examples
  - Implementing the mentor chat experience and personalized plan generator
- Example dev steps
  ```bash
  # backend dev
  uvicorn rise_api.main:app --reload

  # frontend dev
  cd client && npm install && npm run dev
  ```
- Goal: early private alpha → public beta with instructor/dev tools and integrations (GitHub, LeetCode-style problem import, etc.)

---

## How to collaborate / contribute
- Want to try RISE or contribute to Project_map/Shelf Stack? Reach out at devjindal2317@gmail.com with a short note about how you'd like to help.
- If you find issues or want features, open an issue or PR in the repo (linked project repos will have contributing guidelines).

---

## Contact & Social
- GitHub: https://github.com/DevJin27  
- Email: devjindal2317@gmail.com  
- LinkedIn: https://www.linkedin.com/in/dev-jindal-/

---

Thank you for stopping by — I enjoy working on systems that combine solid engineering with intelligent behavior. If you'd like to see code, demos, or discuss collaboration, drop me a message!