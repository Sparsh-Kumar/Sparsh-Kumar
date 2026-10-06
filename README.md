<div align="center">

# Sparsh Kumar

### Backend Engineering · Data Platforms · Distributed Systems · Generative AI

Software Engineer with 7+ years of experience building scalable applications,
data-intensive systems, and production-minded AI workflows.

<p>
  <a href="https://github.com/Sparsh-Kumar">
    <img src="https://img.shields.io/badge/GitHub-Sparsh--Kumar-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub profile" />
  </a>
  <a href="https://www.linkedin.com/in/sparsh-kumar-b868b4180">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn profile" />
  </a>
</p>

</div>

---

## Engineering Profile

I work on systems where reliability, throughput, and maintainability matter: backend services, real-time ingestion, distributed messaging, data platforms, and retrieval-augmented AI applications.

My approach is to make complexity explicit—clear service boundaries, reusable infrastructure, validated data contracts, failure-aware processing, and automation that supports repeatable delivery.

## Selected Engineering Work

### [Low-Latency Data as a Service](https://github.com/Sparsh-Kumar/Low-Latency-DAAS)

**Status:** In progress &nbsp;·&nbsp; **Python · WebSockets · Docker · PostgreSQL · MongoDB · Terraform**

Building a reusable market-data platform around independently deployable ingestion jobs for live tickers, trades, and order books. Each Python 3.12 job owns its dependencies, linting, tests, and container build; shared libraries provide database, logging, and exception abstractions across the platform.

**Technical depth:** Separate local and production Compose configurations, tested MongoDB/PostgreSQL adapters, environment-specific Terraform scaffolding, and an architecture designed to extend beyond cryptocurrency feeds to protocols such as ITCH and FIX.

---

### [News Investing Advisor](https://github.com/Sparsh-Kumar/Live-News-Evaluation-Implementation)

**Status:** In progress &nbsp;·&nbsp; **Python · Flask · MongoDB · OpenAI · RSS · Groww API**

An automated research workflow that combines market and political news with portfolio context to produce structured, confidence-scored investment suggestions. The scheduler deduplicates RSS items, selects the correct analysis mode, validates model output, and persists auditable results in MongoDB.

**Technical depth:** Independent real-time and weekly rebalancing paths, guarded handling of unavailable live-price data, versioned database migrations, a REST API, a responsive dashboard, and unit/integration/end-to-end test layers.

---

### [Finsight](https://github.com/Sparsh-Kumar/Finsight)

**Type:** Developer library &nbsp;·&nbsp; **TypeScript · Node.js · Web Data Extraction**

A typed library for retrieving structured company information where a conventional API may not exist. Its source-oriented design exposes asynchronous methods for financial statements, shareholding patterns, credit ratings, announcements, annual reports, conference calls, and sentiment data.

**Technical depth:** A unified public interface separates consumers from source-specific extraction logic; Screener.in is currently supported, with the codebase structured for additional providers.

---

### [Redis Streams Message Queue](https://github.com/Sparsh-Kumar/Redis-Streams-Message-Queue)

**Type:** Distributed systems project &nbsp;·&nbsp; **TypeScript · Node.js · Redis Streams**

A message-queue implementation built from first principles on Redis Streams. It provides producer and blocking-consumer abstractions while exploring the mechanics behind durable messaging rather than treating the broker as a black box.

**Technical depth:** Consumer-group primitives, explicit acknowledgement, pending-message handling, delivery guarantees, persistence trade-offs, and horizontal consumer scaling.

---

### [RAG Stock Concall Evaluation](https://github.com/Sparsh-Kumar/Quarterly-Concall-Evaluation-Implementation)

**Type:** Applied RAG research &nbsp;·&nbsp; **Python · Haystack · OpenAI · PDF Processing**

A research pipeline for turning company conference-call PDFs into clean, queryable transcript context. It supports cross-quarter analysis of management commentary, commitments, positive and negative developments, and potential investment signals.

**Technical depth:** Automated PDF-to-text preparation followed by a Haystack and GPT-4o-mini retrieval workflow, with notebook-based analysis over processed transcript collections.

## Technical Toolkit

| Area | Technologies |
| --- | --- |
| **Languages** | Python, TypeScript, JavaScript, SQL |
| **Backend & APIs** | Node.js, Flask, NestJS, REST, WebSockets, asynchronous processing |
| **Data & Messaging** | Kafka, Redis Streams, PySpark, Parquet, Apache Iceberg, Trino |
| **Databases** | PostgreSQL, MongoDB, Redis |
| **Cloud & Infrastructure** | AWS, GCP, Docker, Kubernetes, Terraform |
| **AI Engineering** | OpenAI APIs, RAG, Haystack, LangChain, LangGraph, AI agents |
| **Engineering Practice** | pytest, Ruff, GitHub Actions, CircleCI, system design |

## Current Focus

- Designing independent, observable ingestion workloads for real-time data systems
- Building reliable data-lake foundations for analytical and AI workloads
- Applying LLMs through validated schemas, retrieval, and auditable workflows
- Deepening distributed-systems design, failure handling, and performance engineering

---

<div align="center">

Interested in backend systems, data infrastructure, distributed architectures, and practical AI engineering.

[GitHub](https://github.com/Sparsh-Kumar) · [LinkedIn](https://www.linkedin.com/in/sparsh-kumar-b868b4180)

</div>
