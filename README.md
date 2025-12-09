### 👨‍💻 Experience

**Founder & CEO**  
*CapySchool* | Oct 2024 – Present | Chile  

**CapySchool** — *Multilingual EdTech platform for language learning and pronunciation practice*.

- Achieved #2 global ranking on Google Search for “IPA Reader,” driving up to 50% organic traffic growth per keyword by implementing targeted SEO and performance optimizations.
- Built and optimized a high-performance language platform using Astro Islands, Tailwind CSS, and Preact (with SSR), resulting in a perfect 100 Lighthouse Core Web Vitals score.
- Designed complex data models for tracking user progress and vocabulary retention using Drizzle ORM and LibSQL/Turso, enabling personalized study sessions and spaced repetition features.
- Developed a robust i18n and accessibility system, supporting dynamic routing for 40+ languages and ensuring 100% WAI-ARIA compliance across all interactive Tailwind v4 components.
- Integrated precise audio synthesis using AWS Polly and Google Cloud TTS with SSML, creating a "Phonetic Reader" that enables users to practice pronunciation with near-native accuracy.
- Engineered high-performance particle effects, including a dynamic rain animation, leveraging Framer Motion to create a visually arresting user interface.

**CMS AI** — *Headless Content Management System with versioning*.

- Architected a serverless, multi-tenant Headless CMS on Cloudflare Workers and Hono, utilizing a DB-per-tenant strategy that guarantees data isolation and unlimited horizontal scalability.
- Engineered AI Agents with tools, enabling users to bootstrap content, field sets, and locale configurations via natural language.
- Implemented version-controlled AI content generation, automating drafting and translation while maintaining granular history for safe rollbacks.
- Built a RAG architecture (Turso Vector) with automated ingestion (chunking, embedding), enabling real-time semantic search and linking related articles to improve discoverability.
- Built comprehensive usage monitoring and cost control tools, optimizing LLM spending by identifying and routing requests to lower-cost models, reducing monthly expenses x10.
- Optimized read performance by refactoring the database schema (Vertical Partitioning), splitting heavy content fields from metadata queries to reduce list-view latency by ~40%.
- Built a rule engine for strict validation of unstructured data, preventing malformed content from breaking frontend consumers.

**Auth** — *Centralized Identity & Access Gateway*.

- Architected a centralized Auth Gateway serving a multi-product ecosystem (CapySchool, CMS-AI), reducing authentication integration time for new microservices by 90%.
- Designed a multi-tenant database schema supporting organizations, RBAC (owner/admin), and invitations.
- Implemented seamless Single Sign-On (SSO) across subdomains using advanced CORS and shared cookie logic, improving cross-product user retention and session continuity.
- Unified 6+ OAuth providers (Google, GitHub, etc.) under a single standardized proxy layer, increasing developer velocity by eliminating custom authentication code for new services.
- Implemented defense-in-depth security, including WebAuthn/Passkeys and TOTP 2FA, resulting in zero user-reported account compromise incidents.
- Created a scoped API Key management system with rate-limiting, protecting downstream services from abuse, and ensuring 99.9% uptime during high-traffic spikes.

**Backend & Infrastructure Lead**  
*4Geeks* | Oct 2020 – May 2025 | Miami, United States  4Geeks

**4Geeks** — *Coding education REST API with bootcamps and self-paced courses*.

- Architected a modular ERP & LMS using Django and PostgreSQL, scaling the platform to support 1,000+ concurrent users across multiple academies with 99.99% service availability.
- Engineered a secure API access layer (Django REST Framework) with granular RBAC and custom OAuth strategies, enforcing strict data protection for thousands of students.
- Enabled instant cloud development by engineering an ephemeral environment system (Codespaces/Gitpod) that automatically provisions resources, reducing developer onboarding time.
- Orchestrated high-volume background processing using Celery and RabbitMQ, handling asynchronous tasks (CRM sync, media processing) to ensure a responsive UI under heavy load.
- Decoupled analytics from transactions using PostgreSQL and BigQuery, processing millions of event logs with zero impact on core latency.
- Developed a Student Engagement Engine that calculates Frustration Scores based on tutorial interaction patterns, triggering automated mentor interventions that improved student retention.
- Engineered a multi-currency billing engine on top of Stripe, supporting complex consumption-based financing models and subscriptions while automating tax compliance and invoicing.
- Built Supervisor, a custom self-healing system that runs periodic integrity checks in production, automatically detecting and patching data inconsistencies without human intervention.
- Conducted load, stress, and endurance testing using ab and wrk for applications serving 1,000+ concurrent users.
- Established a robust CI/CD pipeline (GitHub Actions/Heroku CI) with 5,500+ automated regression scripts, achieving 80% code coverage for critical user journeys.

**Linked Services** — *Secure Microservice Communication Library*.

- Implemented high-performance API proxying with streaming response support, enabling memory-efficient data piping between services without buffering large payloads.
- Architected linked-services, a Python library for secure microservice communication, enforcing HMAC-SHA256/ED25519 request, implementing a zero-trust authentication.
- Designed a granular OAuth-like permission system with versioned user consent flows, enabling services to request scoped access (e.g., read:users) while enforcing Principle of Least Privilege.
- Optimized authentication latency by ~90% during high-traffic spikes by implementing aggressive LRU caching for key lookups, bypassing database hits for hot paths.

**Celery Task Manager** — *Distributed Task Orchestration Engine*.

- Designed an optimized auditing schema (Django ORM) to index task lifecycles and exceptions, enabling instant root-cause analysis for millions of executed background jobs.
- Developed a robust Django-Celery extension that standardized asynchronous task management, providing observability and eliminating "blind spots" in background job execution.
- Implemented transactional task workflows across 4+ distributed services, enabling atomic multi-system operations with rollback and compensatory logic.

---

### 🛠️ Technical Expertise

**Frontend & UI**  
- Next.js
- Astro
- React
- Svelte
- Tailwind CSS
- Shaden/UI
- Framer Motion

**Backend & APIs**  
- Hono
- FastAPI
- Django REST Framework
- Express
- Zod
- RESTful APIs

**Databases & Storage**  
- PostgreSQL
- Redis
- Turso
- MongoDB
- GCP (Cloud Storage, BigQuery, Firestore)

**Cloud & Infrastructure**  
- Vercel
- Heroku
- Google Cloud Platform (GCP)
- Cloudflare
- Amazon Web Services (AWS)
- Serverless

**Architecture & Patterns**  
- Modular Monolith
- Self-Contained Systems
- Event-Driven Design
- Domain-Driven Design
- Blackboard Pattern

**Tools & Methodologies**  
- Agile
- Scrum
- RabbitMQ
- Celery
- BullMQ
- Git
- CI/CD

**Message Queueing & Event-Driven Architecture**
- Redis
- RabbitMQ
- QStash
- Celery
- BullMQ

**Web Rendering Strategies**
- Single-Page Application
- Server-Side Rendering
- Incremental Static Regeneration
- Server Islands
- Edge Rendering

---

### 🚀 Projects

**CMS AI (Proprietary)**  
Headless CMS with AI and automations
- Integrated AI content generation pipeline for automated article creation
- Built content moderation and validation workflows with AI-assisted quality control

---

### 🎓 Education

**Computer Engineering**  
Universidad Nacional Experimental Rómulo Gallegos | 2012 – 2017 | Venezuela

---

### 📞 Contact
- **Email:** jdefreitaspinto@gmail.com  
- **Phone:** +56951451665  
- **Location:** Santiago, Chile
