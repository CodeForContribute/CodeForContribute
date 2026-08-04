<h1 align="center">Hi, I'm Raushan 👋</h1>

<p align="center">
  <b>Senior Software Engineer · Real-Time Distributed Systems &amp; Applied AI</b><br>
  <sub>📍 Bengaluru, India &nbsp;·&nbsp; 🎓 IIIT Una &nbsp;·&nbsp; ⚡ 8 years shipping production systems</sub>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/raushrak"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://codeforcontribute.github.io/"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=About.me&logoColor=white" alt="Portfolio"></a>
  <a href="mailto:ping.raushan@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

> I build **low-latency, high-throughput distributed systems** — real-time messaging infrastructure,
> event-driven microservices, and the platform plumbing underneath them. Eight years across
> **Oracle**, **PayPal**, and **Otis**, most recently architecting notification microservices serving
> **400K+ daily requests** under strict SLAs. Lately: agentic AI tooling — RAG, vector DBs, and MCP
> pointed at real operational problems.

<p align="center"><b><i>"Learn fast &amp;&amp; Build fast !!"</i></b></p>

---

## 📌 By the Numbers

<table>
<tr>
<td align="center"><b>400K+</b><br><sub>daily requests served</sub></td>
<td align="center"><b>40%</b><br><sub>p99 latency reduced</sub></td>
<td align="center"><b>45% → 85%</b><br><sub>test coverage driven</sub></td>
<td align="center"><b>200+</b><br><sub>PRs reviewed</sub></td>
<td align="center"><b>500+</b><br><sub>LeetCode solved</sub></td>
</tr>
</table>

---

## 🌍 Open Source

**[cline/cline](https://github.com/cline/cline)** — the leading open-source AI coding agent (**59K+ ⭐ · 6K+ forks**)
Active contributor since Feb 2026 with **12 merged pull requests**: prompt history navigation, Gemini 3.1 Pro model support, i18n fixes for non-Latin filenames, CLI formatting, and cross-platform notification fixes.

---

## 💼 Experience

### 🔴 Oracle — Senior Software Engineer · Bengaluru
`May 2024 – Apr 2026`

- **AI on-call resolution agent** — multi-stage retrieval over Slack history (vector DB + RAG) → Jira/Confluence runbooks (MCP) → Grafana metrics → code search; ranks answers, replies in-thread, escalates to maintainers when confidence is low. Cut on-call toil and MTTR. *(Open-source reference implementation of the architecture: **[oncall-agent](https://github.com/CodeForContribute/oncall-agent)**.)*
- **Notification platform at scale** — Java/Helidon microservices handling **400K+ daily requests**; **40% p99 latency reduction** via HttpClient 5.x migration, connection-pool tuning, buffering, and dynamic rate limiting. **140+ PRs across 4 repos in 22 months.**
- **Payload transformation sidecar** — event-driven (Redis queue + Node.js sidecar, Java orchestration) for safe execution of untrusted user transformation logic at **99.9% uptime**; owned design doc → Helm → API schema → client.
- **Real-time delivery** — WebSocket/SSE in-app messaging with connection lifecycle management, half-closed session GC, and session-duration histograms → **60% faster delivery**. Built the email channel end-to-end, taking the platform to **5 channels**.
- **Caching backbone** — Redis/Valkey end-to-end: key prefixing, invalidation strategy, sidecar metrics, health probes, Valkey migration.
- **Security & observability** — OAuth private scopes, IDCS integration, K8s security contexts, secret-expiry alerting; OpenTelemetry tracing, zone-level Prometheus metrics, on-call Grafana dashboards, zero-downtime releases across 5+ branches.

### 💳 PayPal — Software Development Engineer II · Chennai
`Jun 2021 – May 2024`

- Built the **Data Lineage Orchestration Platform** (Java/Spring Boot + Spark) — **500+ ETL pipelines** serving **400M+ users**, with custom SQL parsers and graph traversal for dependency tracking.
- ETL metadata extraction Oracle DB → Elasticsearch: **10K+ daily events, 70% throughput gain** via pooling, batching, async.
- Lineage REST APIs with **sub-100ms** responses and multi-layer caching, serving **100+ downstream consumers**.
- SQL query parser at **99.5% accuracy** on nested queries, powering automated impact analysis and compliance reporting.
- Monitoring on GCP Stackdriver with automated anomaly detection — **MTTR down 45%**.

### 🛗 Otis Elevator (United Technologies) — Software Development Engineer I · Hyderabad
`Jul 2018 – Jun 2021`

- Real-time video streaming system (Python + Twilio SDK) across **500+ buildings** → **40% faster emergency response**.
- Secure microservices over TLS/ZMQ and an Azure IoT Hub pipeline handling **100K+ daily device messages at 99.8% delivery**.

---

## 🛠 Tech Stack

<p>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go">
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++">
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" alt="Spring Boot">
  <img src="https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white" alt="Kafka">
</p>
<p>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="Kubernetes">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white" alt="Helm">
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis">
  <img src="https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white" alt="Elasticsearch">
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" alt="Prometheus">
  <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white" alt="Grafana">
  <img src="https://img.shields.io/badge/Oracle_Cloud-F80000?style=flat-square&logo=oracle&logoColor=white" alt="OCI">
</p>

| Area | What I work with |
| :--- | :--- |
| **Languages** | Java, Python, TypeScript/JavaScript, Go, SQL, Bash, C++ |
| **Backend** | Spring Boot, Spring Security, Helidon, JAX-RS, Hibernate/JPA, REST, gRPC, WebSocket/SSE, OAuth 2.0/JWT, JUnit/Mockito |
| **Concurrency & Perf** | Java concurrency (ExecutorService, CompletableFuture), JVM tuning, connection pooling, low-latency architecture, thread safety |
| **Messaging & Streaming** | Apache Kafka, Redis Pub/Sub, Server-Sent Events, WebSocket, MQTT, ZeroMQ, Spark, Airflow |
| **Cloud & DevOps** | OCI, GCP, Azure, AWS, Kubernetes, Docker, Helm, Jenkins CI/CD, Linux, Maven/Gradle |
| **Observability** | OpenTelemetry, Prometheus, Grafana, Splunk/ELK, distributed tracing |
| **Data & Caching** | Oracle DB, PostgreSQL, MongoDB, Elasticsearch, BigQuery, Redis/Valkey, Qdrant |
| **AI / ML** | RAG pipelines, vector databases, Model Context Protocol (MCP), LangGraph, LLM agents, GNNs, Tensor Networks |

---

## 🚀 What I'm Building

| Project | What it does | Stack |
| :--- | :--- | :--- |
| **[oncall-agent](https://github.com/CodeForContribute/oncall-agent)** | Agentic on-call resolution — Slack bot with a ReAct tool loop over RAG, MCP (Jira/Confluence, Grafana) and code search, with confidence-gated escalation | Python · LangGraph · Qdrant |
| **[flowforge](https://github.com/CodeForContribute/flowforge)** | Automates the SDLC with AI agents — creates branches, writes code, raises PRs, handles review comments, auto-merges | TypeScript |
| **[pr-review-agentic-workflow](https://github.com/CodeForContribute/pr-review-agentic-workflow)** | Autonomous multi-agent code review system | Python · LangGraph |
| **[bitcoin_fraud_detection](https://github.com/CodeForContribute/bitcoin_fraud_detection)** | Graph Neural Networks + ensembles detecting illicit Bitcoin transactions on the Elliptic dataset | Python · PyTorch Geometric |
| **[hld-handbook](https://github.com/CodeForContribute/hld-handbook)** | A blueprint for designing systems at scale — 19 concepts, 15 case studies, interactive diagrams | Next.js · Excalidraw |
| **[tinyurl](https://github.com/CodeForContribute/tinyurl)** | URL shortener running in production on DigitalOcean App Platform | FastAPI · Postgres |
| **[poultry-platform](https://github.com/CodeForContribute/poultry-platform)** | B2B marketplace — orders, payments, settlements, delivery tracking | Java |
| **[flowly](https://github.com/CodeForContribute/flowly)** | Productivity app: tasks, attendance, trip planning | React · Firebase |

📚 Open study notes: **[java-revision](https://github.com/CodeForContribute/java-revision)** · **[springboot-revision](https://github.com/CodeForContribute/springboot-revision)** · **[go-learning](https://github.com/CodeForContribute/go-learning)** · **[LLD-Preparations](https://github.com/CodeForContribute/LLD-Preparations)** · **[Algos-DataStructures](https://github.com/CodeForContribute/Algos-DataStructures)**

---

## 🔭 Current Focus

- **Agentic systems** — task orchestration, multi-agent workflows, MCP-based tooling
- **Quantum-inspired finance** — tensor networks and Matrix Product States for portfolio optimisation and fraud detection
- **Distributed systems at scale** — high-throughput notification fan-out, event-driven architecture
- **Rapid prototyping** — full applications in days, not months

---

## 🏆 Beyond the Code

- **Awards** — Spot Award, PayPal (2023) · TITAN Award, Otis (2020) · POB Award, Otis (2019)
- **Competitive programming** — 500+ LeetCode problems · HackerRank 5★ in Java &amp; Python
- **Mentoring** — junior SDEs and interns on TDD, coding standards, and architectural patterns; primary reviewer on 200+ PRs
- **Education** — B.Tech, Electronics &amp; Communication Engineering, **IIIT Una** (2014–2018)
- **Certifications** — Spring Data JPA with Hibernate · Apache Kafka Connect · TensorFlow for AI/ML (Coursera) · Structuring ML Projects (deeplearning.ai)

---

## 📊 GitHub Activity

<p align="center">
  <img src="https://ghchart.rshah.org/409ba5/CodeForContribute" alt="GitHub Contribution Calendar" width="100%">
</p>

---

<details>
<summary><b>► Random facts</b></summary>

<br>

- 🔬 Fascinated by AI agents and how they reshape software workflows
- 📈 167+ public repos — I build to learn, and learn by building
- 🇮🇳 Building for India first: payments, verification, and marketplace infrastructure
- ☕ Powered by mass amounts of chai and curiosity
- 🌏 Based in Bengaluru, building for the world

</details>

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=CodeForContribute&color=blue&style=flat-square" alt="Profile views">
  &nbsp;
  <img src="https://img.shields.io/github/followers/CodeForContribute?style=flat-square&color=blue" alt="Followers">
  &nbsp;
  <img src="https://img.shields.io/github/stars/CodeForContribute?style=flat-square&color=blue" alt="Stars">
</p>
