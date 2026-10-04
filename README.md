<div align="center">

# Thierry Kwizera

**Backend & QA Engineer** · Python · FastAPI · AWS · Kigali, Rwanda 🇷🇼

[![Email](https://img.shields.io/badge/Email-thkwzr%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:thkwzr@gmail.com)
[![AWS Certified](https://img.shields.io/badge/AWS-Certified%20Cloud%20Practitioner-FF9900?style=flat&logo=amazon-aws&logoColor=white)](https://github.com/thierry0011)

</div>

---

I build backend systems in Python, integrate LLMs into production-style services, and test software the way it should be tested — from API contracts down to edge cases. Currently deepening my cloud and QA automation skills through AmaliTech's apprenticeship programme.

### 🧰 Core stack

| Area | Tools |
|---|---|
| **Backend** | Python, FastAPI, Django / DRF, REST & GraphQL APIs |
| **AI engineering** | RAG pipelines, ChromaDB (vector search), multi-provider LLM integration (OpenAI, Anthropic), prompt engineering |
| **Cloud & DevOps** | AWS (ECS/Fargate, CloudFormation, IAM), Docker, CI/CD (GitHub Actions) |
| **QA & Testing** | Test case design, boundary value analysis, Postman (API testing), Jira/Xray, `unittest`/mocking |
| **Databases** | PostgreSQL, MySQL |

---

### 🚀 Featured project

#### [LibraryMind](https://github.com/thierry0011/LibraryMind) — AI-powered library assistant

A FastAPI backend with a clean, layered architecture (API → services → AI providers → infrastructure) built as a capstone project.

- **RAG pipeline** — semantic search over a ChromaDB vector store, relevance filtering, and cited sources in every answer
- **Multi-provider AI layer** — OpenAI and Anthropic behind one interface, with retry/backoff and automatic failover so the service never depends on a single vendor
- **Conversational memory** — multi-turn chatbot with context-window-aware history truncation
- **Structured outputs** — prompt-engineered ticket classification and review summarisation, with markdown-fence stripping and JSON validation
- **Production concerns** — Redis caching, a thread-safe token-bucket rate limiter, and per-call token/cost tracking
- **330+ automated tests** — mocking, module stubbing, and deterministic time control, no live API calls required

`Python` `FastAPI` `ChromaDB` `Redis` `OpenAI` `Anthropic API` `unittest`

---

### 📂 Other projects

| Repo | What it covers |
|---|---|
| [applied-ai-prompt-engineering-capstone-project](https://github.com/thierry0011/applied-ai-prompt-engineering-capstone-project) | Prompt engineering capstone — structured prompting techniques for reliable LLM outputs |
| [Agile_devops_practices](https://github.com/thierry0011/Agile_devops_practices) | Agile and DevOps workflow practice |
| [iam-automation-lab](https://github.com/thierry0011/iam-automation-lab) | AWS IAM automation |
| [iam-permission-testing](https://github.com/thierry0011/iam-permission-testing) | AWS IAM permission testing and validation |
| [amalitech-data-governance](https://github.com/thierry0011/amalitech-data-governance) | Data governance concepts and practice |

*(Add a one-line description to each repo's "About" box on GitHub — it's what shows up here and in search results.)*

---

### 💼 Professional experience

**Backend Developer / Systems Administrator** — Origin Group Ltd ([Orinestbooking.com](https://orinestbooking.com))
Built a multi-tenant backend serving multiple client organisations from one codebase, integrated third-party payment gateways (transaction flows, webhooks, reconciliation), and administered the production server and deployments.

**Software Development Apprentice — Backend & QA** — AmaliTech
Built Python microservices and deployed them on AWS ECS/Fargate with CloudFormation. Worked as QA engineer on **RMS**, an HR/payroll platform — designed test cases for loan disbursement and payroll deduction logic, tested GraphQL APIs in Postman, applied boundary value analysis, and traced a proof-of-payment bug end to end.

---

### 🎓 Certifications

- AWS Certified Cloud Practitioner
- Google Cybersecurity Professional Certificate
- Python Programming Specialization (Coursera)

---

### 📫 Let's connect

- 📧 **thkwzr@gmail.com**
- 💼 Open to backend, QA, and cloud-focused roles — remote or Kigali-based
