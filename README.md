# Hi, I'm Yash Dafade 👋

**Backend Developer · DevOps Practitioner · AI/ML Integration Engineer**

I build production-grade backend systems — from REST APIs and microservices to AI-powered automation. My focus is on clean architecture, real deployments, and integrating ML models into systems that actually run in production.

---

## ⚡ Tech Stack

**Backend:** Node.js · Express.js · Python (FastAPI) · REST APIs · Microservices · JWT Auth  
**Databases:** PostgreSQL · MySQL · MongoDB · Supabase  
**AI/ML:** InsightFace · OpenCV · Gemini API · Face Recognition · NL2SQL  
**DevOps & Cloud:** Docker · GitHub Actions · CI/CD · Linux (Ubuntu) · Caddy · VPS · AWS  
**Frontend:** React.js · JavaScript · HTML5 · CSS3  
**Tools:** Git · Postman · Power BI · n8n

---

## 🚀 Projects

### Schoolix — AI-Powered School Management Platform
**Stack:** Node.js · Express · React · PostgreSQL · Docker · GitHub Actions · Ubuntu VPS · Caddy

A production school ERP built as a freelance engagement. Handles student enrollment, billing, library, inventory, certificate generation, and reporting — deployed on a Hostinger VPS with Docker and Caddy reverse proxy.

- Modular backend with JWT auth and role-based access control across admin, teacher, and staff roles
- PostgreSQL database (Hostinger-managed) with optimized schema for multi-entity school data
- CI/CD pipeline via GitHub Actions — push to main triggers a Docker build and zero-downtime deploy
- **Impact:** Reduced administrative workload by 50%, improved data accuracy across departments

---

### AI Attendance System — Face Recognition Microservice
**Stack:** Python · FastAPI · InsightFace · OpenCV

A standalone microservice that handles face embedding generation and real-time identity matching. Integrated into Schoolix via REST — the Node.js backend delegates all biometric operations to this service.

- Generates and stores facial embeddings on enrollment; matches against stored vectors at attendance time
- Sub-second response times with 96% recognition accuracy in production conditions
- Fully decoupled — can be swapped or updated without touching the core ERP backend
- **Impact:** Replaced manual roll calls; increased attendance accuracy by 70%

---

### Intelligent Chatbot — NL2SQL Query Engine
**Stack:** Node.js · Gemini API (gemini-2.0-flash-lite) · PostgreSQL · REST

A natural language interface layered over the Schoolix PostgreSQL database. Converts plain-text admin queries into valid SQL using Gemini with table relationship lineage rules and keyword-based intent resolution — no vector embeddings required.

- Schema-aware prompt construction with explicit table relationship rules passed as context
- Keyword routing determines query intent before hitting the LLM — reduces hallucination on structured data
- Role-aware: responses are scoped to what the authenticated user's role can access
- **Impact:** Automates 80% of repetitive admin queries without any SQL knowledge required

---

### BillDoc — Clinic Billing System
**Stack:** React · Supabase · PostgreSQL · TipTap

A billing and patient management system built for Resonique Homeopathic Care. Handles the full billing lifecycle from patient registration to payment tracking.

- Custom charge line items with flexible billing form supporting variable pricing
- Rich-text patient notes via TipTap editor — persisted per consultation record
- Installment payment flows with partial payment tracking and outstanding balance views
- Multi-doctor auth with role separation — each doctor sees only their patient records
- **Impact:** Replaced manual paper-based billing; full clinic workflow now runs through BillDoc

---

## 🎯 Career Snapshot

Backend-focused engineer with hands-on DevOps and AI integration experience. I've deployed containerized applications on Linux VPS (Docker + Caddy), built ML microservices in production, and integrated LLMs into real-world data workflows. Currently targeting backend and AI integration roles at 6+ LPA.

---

## 📫 Connect

- 🌐 Portfolio: https://portfolio-v5-vs.vercel.app/
- 💼 LinkedIn: https://www.linkedin.com/in/yash-dafade-992ab2209/
- 📧 Email: yashdafade93@gmail.com

---

**Open to Backend, DevOps, and AI-Integrated Engineering roles.**
