## 👋 Hi, I'm Tanmay Rathi
💻 **Backend & AI Engineer specializing in Distributed Systems, Serverless ETL, & Agentic Workflows** 

🎓 B.Tech CSE Graduate | Poornima College of Engineering, Jaipur  

I build high-performance, secure, and production-ready backend systems. My core expertise lies in designing multi-tenant architectures, optimizing serverless data processing pipelines, and building protocol-driven intelligent agents using the Model Context Protocol (MCP).

---

### 🚀 Production-Proven Engineering Capabilities
* **Distributed Tracing & Observability:** Experienced in implementing `ContextVars` to inject correlation IDs into log lifecycles, propagating them across decoupled architectures via **SQS/SNS** payloads for end-to-end tracing.
* **Serverless ETL & Data Pipelines:** Onboarded to live AWS pipelines managing high-volume data ingestion via **Lambda, S3, Glue**, and auto-scaling EC2 groups.
* **Performance Optimization:** Proven track record of reducing execution times by **50%** on heavy dataset validations by eliminating nested DataFrame lookups in favor of batched lookups using **Pandas**.
* **Enterprise Security & Multi-Tenancy:** Hands-on experience developing 100+ secure endpoints using **FastAPI** and **Django REST Framework**, enforcing JWT revocation, MFA, and strict Role-Based Access Control (RBAC).
* **Asynchronous Task Management:** Deep familiarity with decoupling bottlenecks using **Celery & Redis** for background routines and distributed caching.

---

### 🧠 Current Focus Areas & R&D
* 🤖 **Agentic Frameworks:** Designing custom Model Context Protocol (MCP) servers and tools to connect LLMs securely to local/private data schemas.
* ⚡ **Event-Driven Architectures:** Transitioning traditional web backends into stateless cloud functions.
* 🏗️ **System Resilience:** Practicing Test-Driven Development (TDD) alongside load-testing workflows using **Locust** to catch scaling limits early.

---

### 🛠️ Tech Stack & Ecosystem

| Layer | Technologies |
| :--- | :--- |
| **Languages & Frameworks** | Python, FastAPI, Django, Django REST Framework (DRF) |
| **Databases, Cache & Queues** | PostgreSQL, Redis, MySQL, SQLAlchemy, Django ORM, Celery, AWS SQS/SNS |
| **Cloud & DevOps** | AWS (Lambda, S3, EC2, Glue), Serverless Framework, Docker, Nginx, GitHub Actions (CI/CD) |
| **Libraries & Tools** | Pandas, Pydantic, Pytest, Alembic, New Relic, Locust, Postman, WebSockets |

---

### 📌 Featured Architectural Projects

#### 🤖 [Expense-Agent Ecosystem](https://github.com/rathitanmay10/learn-mcps) — Agentic Financial Orchestration
An intelligent, closed-loop financial assistant utilizing tool-calling agent mechanics to automate transaction logging, semantic auditing, and personal accounting.
* **Architecture:** Composed of an autonomous agent orchestrator (`expense-agent`) coupled with a protocol abstraction layer (`mcp-expense-tracker`).
* **Protocol-Driven:** Implemented custom Model Context Protocol (MCP) servers to expose secure database schemas, tracking operations, and filtering rules directly to an LLM's runtime environment.
* **Semantic Analysis:** Designed the system to parse unstructured natural language input, extract entities (Amount, Currency, Category), and map them to precise backend database execution functions.
* **Strict Schema Type-Safety:** Authored rigid JSON schema definitions for the agent's tool declaration block, guaranteeing type-safe arguments and robust error handling during autonomous database mutation loops.

#### 🏠 [RentBnB — Multi-Tenant Property Rental Engine](https://github.com/rathitanmay10/rentbnb)
A high-concurrency async backend system managing real-world transactional complexities and rental flows.
* Optimized PostgreSQL database schemas with advanced indexing and query tuning to maximize data throughput.
* Streamlined payments and email notification lifecycles using Celery and Redis for background worker routines.
* Built a real-time WebSocket messaging layer for instant communication between tenants and properties.
* Integrated Razorpay payment systems with secure webhook handling for real-time transaction verification.

#### 🎮 [GamerHouse — Multi-Tenant Gaming Platform](https://github.com/rathitanmay10/gamerhouse)
An enterprise-style multi-tenant portal prioritizing bulletproof security layers and deep system monitoring.
* Achieved full tenant data isolation, multi-factor authentication (MFA), and strict RBAC setups.
* Containerized the application using Docker and deployed it on AWS EC2 using Nginx as a reverse proxy via GitHub Actions.
* Ensured high-traffic stability by utilizing Locust for targeted load-testing and New Relic for APM infrastructure monitoring.

---

### 📫 Let's Connect
* 💼 **LinkedIn:** [tanmay-rathi](https://linkedin.com/in/tanmay-rathi-567a6a257)
* ✉️ **Email:** [rathitanmay10@gmail.com](mailto:rathitanmay10@gmail.com)
* 🧑‍💻 **GitHub:** [rathitanmay10](https://github.com/rathitanmay10)
