# Hi, I'm Yash Dafade 👋

**Backend Developer · DevOps · AI/ML Integration**

I build backend systems and AI-integrated applications — REST APIs, microservices, containerized deployments, and LLM/computer-vision integrations. Most of my projects are self-driven builds where I take an idea to a deployed, production-grade system to deepen my engineering depth across the full stack.

---

## ⚡ Tech Stack

**Backend:** Node.js · Express.js · Python · FastAPI · REST APIs · Microservices · JWT · Role-Based Access Control
**Databases:** PostgreSQL · MySQL · Supabase · MongoDB
**AI/ML:** QLoRA Fine-Tuning · Hugging Face · InsightFace · OpenCV · Gemini API · NL2SQL · Embeddings
**DevOps & Cloud:** Docker · GitHub Actions · CI/CD · Linux (Ubuntu) · Caddy · Nginx · VPS · AWS
**Frontend:** React · TypeScript · Vite · Tailwind CSS

---

## 🚀 Projects

### TelcoBot-QLoRA — Fine-Tuned Customer Support LLM
**Stack:** Python · Qwen2.5-1.5B · QLoRA · Hugging Face · AMD MI300X (ROCm)

Fine-tuned Qwen2.5-1.5B-Instruct using QLoRA (4-bit NF4, LoRA r=16) on a 20k-example telecom support dataset, built during the TCS × AMD AI Hackathon 2026. Trained on an AMD MI300X GPU in under two hours.

- Worked through TRL/ROCm compatibility issues and switched to bfloat16 for stable inference
- Measurable ROUGE improvements over the base model on held-out support queries
- 🔗 [github.com/Yashdafade/TelcoBot-QLoRA](https://github.com/Yashdafade/TelcoBot-QLoRA)

---

### Face-Recognition-Microservice — Biometric Attendance Service
**Stack:** Python · FastAPI · InsightFace · OpenCV

A standalone face-recognition microservice built to practice computer-vision integration and clean service boundaries. Generates 512-d ArcFace embeddings on enrollment and cosine-matches them at scan time.

- ~96% match accuracy with sub-second latency on a 200-face test set
- Fully decoupled REST service — pluggable into any backend without code changes
- 🔗 [github.com/Yashdafade/Face-Recognition-Microservice](https://github.com/Yashdafade/Face-Recognition-Microservice)

---

### Schoolix — Full-Stack School Management Platform
**Stack:** Node.js · Express · React · PostgreSQL · Docker · GitHub Actions · Caddy

A full-stack ERP I designed end-to-end to learn production backend architecture and DevOps. Covers enrollment, billing, library, inventory, certificate generation, and reporting.

- JWT auth with role-based access control across admin, teacher, and staff roles
- Containerized with Docker + Caddy, CI/CD via GitHub Actions on a Linux VPS
- Private repo — architecture overview and walkthrough available on request

---

### Intelligent Chatbot — NL2SQL Query Engine (Schoolix module)
**Stack:** Node.js · Gemini API (gemini-3.1-flash-lite-preview) · PostgreSQL

A natural-language interface over the Schoolix database, built to explore LLM-to-SQL translation without vector embeddings.

- Schema-aware prompts with explicit table-relationship lineage rules passed as context
- Keyword-based intent routing before the LLM call — reduces hallucination on structured queries
- Role-aware: generated SQL is scoped to the authenticated user's access level

---

### MediBill — Clinic Billing App
**Stack:** React · TypeScript · Vite · Supabase

A billing and patient-management app I built to get hands-on with TypeScript, Supabase, and Postgres row-level security.

- Custom charge line items, rich-text patient notes (TipTap), installment payment tracking
- Row-level security isolating each user's records at the database layer
- Private repo — built as a TypeScript + Supabase learning project

---

## 🛠 Other Builds
- **caveman-antigravity** — a token-reduction skill for the Antigravity coding agent, cutting context usage on agentic coding tasks (inspired by the "caveman" skill pattern for Claude)
- **yash.dev** — a VS Code-themed developer portfolio (React + Three.js)

---

## 📫 Connect

- 🌐 Portfolio: https://portfolio-v5-vs.vercel.app/
- 💼 LinkedIn: https://www.linkedin.com/in/yash-dafade-992ab2209/
- 📧 Email: yashdafade93@gmail.com

---

**Open to Backend, DevOps, and AI-Integration Engineering roles.**
