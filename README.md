<div align="center">

# Sparsh Kumar

### Senior Software Engineer · Backend Systems · Distributed Platforms · Data & AI Infrastructure

Software Engineer with 7+ years of experience designing backend services, data platforms,
distributed workflows, and production-ready AI applications.

<p>
  <img src="https://img.shields.io/badge/-Backend_Architecture-2563EB?style=flat-square" alt="Backend Architecture" />
  <img src="https://img.shields.io/badge/-Data_Platforms-0891B2?style=flat-square" alt="Data Platforms" />
  <img src="https://img.shields.io/badge/-Distributed_Systems-0F766E?style=flat-square" alt="Distributed Systems" />
  <img src="https://img.shields.io/badge/-Applied_AI-7C3AED?style=flat-square" alt="Applied AI" />
</p>

<p>
  <a href="https://github.com/Sparsh-Kumar">
    <img src="https://img.shields.io/badge/GitHub-Sparsh--Kumar-334155?style=flat-square&logo=github&logoColor=white" alt="GitHub profile" />
  </a>
  <a href="https://www.linkedin.com/in/sparsh-kumar-b868b4180">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn profile" />
  </a>
  <a href="mailto:sparshkumar14998@gmail.com">
    <img src="https://img.shields.io/badge/Email-sparshkumar14998%40gmail.com-B91C1C?style=flat-square&logo=gmail&logoColor=white" alt="Email Sparsh Kumar" />
  </a>
  <a href="tel:+917300159158">
    <img src="https://img.shields.io/badge/Phone-%2B91_7300159158-047857?style=flat-square" alt="Call Sparsh Kumar" />
  </a>
</p>

</div>

---

## Engineering Profile

I design backend systems from service boundaries and data contracts through deployment and operation. My work spans asynchronous services, APIs, ingestion pipelines, messaging infrastructure, storage abstractions, and LLM-backed workflows.

I focus on the tradeoffs that keep systems useful as they grow. Reliability, scalability, maintainability, delivery speed, and operational clarity are treated as design inputs rather than cleanup work.

| Focus | Applied work |
| --- | --- |
| **System architecture** | Independently deployable services, reusable libraries, stable APIs, and explicit ownership boundaries |
| **Reliability** | Acknowledgements, recovery paths, deduplication, schema validation, migrations, and layered tests |
| **Data platforms** | Real-time ingestion, relational and document storage, columnar data, and analytical query engines |
| **Delivery** | Locked dependencies, container builds, infrastructure as code, CI/CD, and environment separation |

## Selected Engineering Work

### [Low-Latency Data as a Service](https://github.com/Sparsh-Kumar/Low-Latency-DAAS)

<img src="https://img.shields.io/badge/-IN_PROGRESS-B45309?style=flat-square" alt="In progress" />
<img src="https://img.shields.io/badge/-DISTRIBUTED_DATA_PLATFORM-1D4ED8?style=flat-square" alt="Distributed data platform" />

**Python · WebSockets · Docker · PostgreSQL · MongoDB · Terraform**

Building a data platform that isolates ticker, trade, and order book ingestion into independently deployable Python services. Each service owns its dependencies, lint checks, tests, and container build. Shared libraries provide consistent logging, exception handling, and MongoDB or PostgreSQL access. Separate Compose stacks and Terraform environments keep local and production concerns explicit while allowing new ingestion protocols to follow the same operating model.

---

### [News Investing Advisor](https://github.com/Sparsh-Kumar/Live-News-Evaluation-Implementation)

<img src="https://img.shields.io/badge/-COMPLETE-15803D?style=flat-square" alt="Complete" />
<img src="https://img.shields.io/badge/-BACKEND_AI_SYSTEM-6D28D9?style=flat-square" alt="Backend AI system" />

**Python · Flask · MongoDB · OpenAI · RSS · Groww API**

A scheduled backend system that combines external news feeds with portfolio data and structured model output. The pipeline deduplicates inputs, chooses the correct processing mode, validates responses before persistence, and preserves an auditable decision history in MongoDB. Versioned migrations, guarded behavior when live data is unavailable, Flask APIs, a responsive dashboard, and layered tests support the complete workflow from ingestion to presentation.

---

### [Redis Streams Message Queue](https://github.com/Sparsh-Kumar/Redis-Streams-Message-Queue)

<img src="https://img.shields.io/badge/-MESSAGING_INFRASTRUCTURE-0F766E?style=flat-square" alt="Messaging infrastructure" />

**TypeScript · Node.js · Redis Streams**

A message queue built directly on Redis Streams to make asynchronous delivery behavior explicit. Producer and blocking consumer APIs use consumer groups, acknowledgements, and pending-message recovery. The implementation exposes work distribution, redelivery, persistence choices, and horizontal scaling without hiding the underlying broker semantics behind a framework.

---

### [Finsight](https://github.com/Sparsh-Kumar/Finsight)

<img src="https://img.shields.io/badge/-EXTENSIBLE_DATA_LIBRARY-0E7490?style=flat-square" alt="Extensible data library" />

**TypeScript · Node.js · Web Data Extraction**

A TypeScript library that turns multiple categories of financial information into a consistent programmatic interface. Its asynchronous API covers company statements, ratios, ownership data, ratings, announcements, and reports. Source-specific extraction remains behind adapters, which isolates provider behavior and keeps the public contract stable as integrations are added.

---

### [RAG Stock Concall Evaluation](https://github.com/Sparsh-Kumar/Quarterly-Concall-Evaluation-Implementation)

<img src="https://img.shields.io/badge/-RAG_DATA_PIPELINE-4338CA?style=flat-square" alt="RAG data pipeline" />

**Python · Haystack · OpenAI · PDF Processing**

A Python pipeline that converts unstructured PDFs into cleaned transcript collections and retrieves relevant passages for downstream analysis. Document preparation remains separate from Haystack and GPT-4o-mini retrieval, which allows the corpus to be rebuilt independently and keeps ingestion concerns outside the model-facing workflow.

## Technical Toolkit

| Area | Technologies |
| --- | --- |
| **Languages** | Python, TypeScript, JavaScript, SQL |
| **Backend & APIs** | Node.js, Flask, NestJS, REST, WebSockets |
| **Distributed Systems** | Kafka, Redis Streams, consumer groups, asynchronous processing |
| **Data Platforms** | PySpark, Parquet, Apache Iceberg, Trino, real-time ingestion |
| **Databases** | PostgreSQL, MongoDB, Redis |
| **Cloud & Infrastructure** | AWS, GCP, Docker, Kubernetes, Terraform |
| **Applied AI** | OpenAI APIs, RAG, Haystack, LangChain, LangGraph |
| **Engineering Practice** | System design, pytest, Ruff, GitHub Actions, CircleCI |

## Current Focus

- Designing reliable distributed services with clear ownership boundaries
- Building data and AI platforms from ingestion through APIs and user-facing workflows
- Evaluating tradeoffs across consistency, availability, latency, complexity, and cost
- Improving operational readiness through tests, automation, observability, and failure recovery

---

<div align="center">

Interested in senior backend, platform, distributed systems, and data infrastructure roles.

[GitHub](https://github.com/Sparsh-Kumar) · [LinkedIn](https://www.linkedin.com/in/sparsh-kumar-b868b4180) · [Email](mailto:sparshkumar14998@gmail.com) · [Phone](tel:+917300159158)

</div>
