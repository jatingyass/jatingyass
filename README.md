<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0d1117,100:1a1b27&height=150&section=header&text=Jatin%20Gyass&fontSize=44&fontColor=58a6ff&fontAlignY=38&desc=Software%20Development%20Engineer%20%7C%20AI%2FGenAI%20Engineer&descAlignY=60&descColor=8b949e&descSize=16" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&pause=1500&color=58A6FF&background=00000000&center=true&vCenter=true&width=680&height=40&lines=Owns+features+end-to-end+%E2%80%94+DB+to+API+to+UI;Ships+production-grade+RAG+%26+agentic+LLM+systems;Fine-tunes+and+deploys+open-source+models" alt="Typing SVG" />

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jatingyass/)
[![Email](https://img.shields.io/badge/jatingyass9%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:jatingyass9@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/jatingyass)

</div>

## About

Software Development Engineer and AI Engineer who owns systems end-to-end — database design, API architecture, and production UI on one side; RAG pipelines, agentic workflows, and fine-tuned LLMs on the other. M.Sc. Artificial Intelligence & Machine Learning, IIIT Lucknow. Codeforces Specialist (1404) · 350+ LeetCode problems solved.

**At a glance**

| | |
|---|---|
| 🚀 | 131+ commits / ~21K LOC shipped in current internship |
| ⚡ | Flash-sale engine load-tested to **2,020 req/sec, 0 oversells** |
| 🧠 | Fine-tuned Mistral-7B — **31% perplexity reduction**, 25% accuracy gain |
| ✅ | 80%+ test coverage on a Java/Spring Boot payments service |

```ts
const jatin = {
  degree : "M.Sc. AI & ML — IIIT Lucknow",
  role   : "Full Stack + GenAI Engineer",
  focus  : ["Backend Systems", "LLM Fine-Tuning", "Agentic AI"],
};
```

---

## Experience

**Full Stack Developer Intern · Excelerate** (Remote) — Mar 2026 – Present
- Shipped 131+ commits (~21K LOC) across four repositories, including a config-driven Opportunity Card system and a full FAQ/Support Center redesign with RxJS caching that cut redundant API calls to zero
- Led a platform-wide migration to typed, class-based API models and optimized the moderator task pipeline with pagination and a reusable Joi utility for human-readable API errors

**Coordinator — Web & Coding Wing, AETHER, IIIT Lucknow** — Sep 2025 – May 2026
- Coordinated coding activities and peer-learning initiatives for M.Sc. AI & ML students; ran technical sessions on backend development, DSA, and AI/ML concepts

---

## Featured Projects

**[PayFlow](https://github.com/jatingyass/payflow)** — Payment Transaction Processing Service
`Java 17 · Spring Boot · PostgreSQL · JUnit/Mockito · Docker · GitHub Actions`
RESTful payment service supporting authorize, capture, and refund on a double-entry ledger for transaction consistency. Idempotent APIs (request keys + optimistic locking), **80%+ test coverage**, CI-automated via Docker + GitHub Actions.

**[Flash Sale System](https://github.com/jatingyass/flash-sale-system)** — High-Concurrency Inventory Management
`Node.js · Redis · BullMQ · MySQL · Docker · k6`
Atomic stock reservation via Redis `DECR` in front of an async BullMQ order pipeline, decoupling request latency from database writes. Validated under 200 VUs / 2,000 concurrent requests with k6: **~2,020 req/sec, zero inventory oversell**.

**[Multi-Agent AI System](https://github.com/jatingyass/multi-agent-system)** — Planner–Executor–Critic
`LangGraph · FastAPI · Groq (Llama 3.3 70B) · Redis/SQLite`
Multi-agent system with dynamic routing, tool calling, and failure recovery, backed by a two-tier Redis + SQLite memory architecture. A Critic reflection loop scores outputs 0–100 and triggers replanning for low-quality responses, exposed via concurrent FastAPI REST APIs.

**[RAG Research Agent](https://github.com/jatingyass/rag-research-agent)** — Multi-Source Research Assistant
`LangChain · LangGraph · FastAPI · React · ChromaDB · Cohere`
Hybrid retrieval combining semantic embeddings and BM25 with RRF fusion — **+30% retrieval accuracy over single-method baselines**. Agentic pipeline with tool calling, reflection, and real-time streaming, exposed via FastAPI + React with source citations.

**[Legal LLM Fine-Tuning](https://github.com/jatingyass/legal-llm-qlora-mistral7b)** — QLoRA on Mistral-7B
`PyTorch · HuggingFace PEFT/TRL · QLoRA`
Fine-tuned Mistral-7B on 4,000+ legal QA pairs using QLoRA (4-bit NF4), training only 0.086% of parameters. **31% perplexity reduction, 25% accuracy gain.** LoRA adapter published on Hugging Face Hub with an auto-generated model card.

**[Group Chat App](https://github.com/jatingyass/group-chat-app)** — Sharded Real-Time Messaging
`Node.js · Express · Socket.IO · MySQL · Redis · React · Docker`
Horizontal sharding of message storage across multiple MySQL databases with a three-tier (Hot–Warm–Cold) archival lifecycle. JWT-authenticated WebSocket communication via Socket.IO and Redis Pub/Sub for scalable multi-instance real-time messaging.

---

## Tech Stack

**Languages**
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**AI / ML**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-6E40C9?style=flat-square&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)

**Backend & APIs**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white)

**Data & Messaging**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square&logo=amazondynamodb&logoColor=white)

**Frontend**
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**DevOps & Cloud**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

## Competitive Programming

| Platform | Result |
|---|---|
| Codeforces | Specialist · Max rating **1404** |
| LeetCode | **350+** problems solved |

---

## Education

| Institution | Degree | Period |
|---|---|---|
| IIIT Lucknow | M.Sc. Artificial Intelligence & Machine Learning | 2024 – 2026 |
| Kurukshetra University | B.Sc. Computer Science | 2018 – 2021 |

**Coursework:** Deep Learning · NLP · Computer Vision · Reinforcement Learning · MLOps · Systems Programming

---

<div align="center">

Open to full-time SDE and AI/ML engineering roles — reach out via [LinkedIn](https://www.linkedin.com/in/jatingyass/) or [email](mailto:jatingyass9@gmail.com).

</div>
