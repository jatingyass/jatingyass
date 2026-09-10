<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0d1117,100:1a1b27&height=140&section=header&text=Jatin%20Gyass&fontSize=42&fontColor=58a6ff&fontAlignY=45&desc=AI%2FML%20Engineer%20%7C%20Full-Stack%20Developer%20%7C%20IIIT%20Lucknow&descAlignY=68&descColor=8b949e&descSize=15#gh-dark-mode-only" />
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:ffffff,100:ffffff&height=140&section=header&text=Jatin%20Gyass&fontSize=42&fontColor=1f6feb&fontAlignY=45&desc=AI%2FML%20Engineer%20%7C%20Full-Stack%20Developer%20%7C%20IIIT%20Lucknow&descAlignY=68&descColor=57606a&descSize=15&stroke=d0d7de&strokeWidth=1#gh-light-mode-only" />

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jatingyass/)
[![Email](https://img.shields.io/badge/msa24010%40iiitl.ac.in-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:msa24010@iiitl.ac.in)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/jatingyass)

</div>

## About

M.Sc. Artificial Intelligence & Machine Learning student at **IIIT Lucknow**, building production-grade backend systems and LLM applications — a double-entry payments ledger, a load-tested flash-sale engine, multi-agent LLM systems, and fine-tuned open-source models. Currently a Full Stack Developer Intern at Excelerate. Competitive programmer — Codeforces Specialist (1404), 350+ LeetCode problems solved.

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
- Built production-grade REST APIs and UI components in Angular, TypeScript, Node.js, Express, and DynamoDB
- Led a class-based architecture migration across the existing codebase

---

## Featured Projects

**[PayFlow](https://github.com/jatingyass/payflow)** — Payment Transaction Processing Service
`Java 17 · Spring Boot · PostgreSQL · Flyway · Testcontainers`
Fintech-style REST service that authorizes, captures, and refunds payments on a double-entry ledger. Idempotent APIs (unique-indexed keys + a state machine) and optimistic locking keep balances correct under concurrent requests; the full authorize → capture → refund flow runs as a Testcontainers integration test in CI.

**[Flash Sale System](https://github.com/jatingyass/flash-sale-system)** — High-Concurrency Inventory Engine
`Node.js · Redis · BullMQ · MySQL · Docker · k6`
Prevents overselling under flash-sale traffic using an atomic Redis `DECR` gatekeeper in front of a BullMQ order pipeline, with two-layer idempotency. Load-tested with k6 at 200 concurrent users: **~2,020 req/sec, 86.6ms p90 latency, 0 units oversold**.

**[Multi-Agent AI System](https://github.com/jatingyass/multi-agent-system)** — Autonomous LangGraph Workflow
`LangGraph · FastAPI · Groq (Llama 3.3 70B) · SQLite/Redis`
Planner–Executor–Critic–Memory agents collaborate with explicit state routing; a dedicated critic scores each output and triggers replanning below a quality threshold. Streams progress live over SSE and runs on Hugging Face Spaces.

**[RAG Research Agent](https://github.com/jatingyass/rag-research-agent)** — Multi-Source Research Assistant
`LangChain · LangGraph · FastAPI · ChromaDB`
Ingests PDFs, web pages, and databases, then answers with cited sources using hybrid BM25 + semantic retrieval (RRF fusion) and Cohere re-ranking. Benchmarked with RAGAS: **0.87 faithfulness, 0.91 answer relevancy** on a 50-question eval set.

**[Legal LLM Fine-Tuning](https://github.com/jatingyass/legal-llm-qlora-mistral7b)** — QLoRA on Mistral-7B
`PyTorch · HuggingFace PEFT/TRL · QLoRA`
Fine-tuned Mistral-7B (4-bit NF4, rank-16 LoRA adapters, 0.086% trainable params) on legal QA data using a free Colab T4 GPU. **Perplexity 18.4 → 12.7 (-31%), legal-domain accuracy 62.5% → 87.5%.**

**[Group Chat App](https://github.com/jatingyass/group-chat-app)** — Sharded Real-Time Messaging
`Node.js · Express · Socket.IO · MySQL · Redis · Docker`
JWT-authenticated WebSocket chat with hash-sharded message tables (by `groupId`) and a cron-driven hot → warm → cold 3-tier archival pipeline. Horizontal-scale ready via a drop-in Socket.IO Redis adapter.

---

## Tech Stack

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)

**AI / LLM**
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-6E40C9?style=flat-square&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)

**Backend & APIs**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white)

**Data Stores**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square&logo=amazondynamodb&logoColor=white)

**Frontend**
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**DevOps & Cloud**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
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

Open to full-time AI/ML and software engineering roles — reach out via [LinkedIn](https://www.linkedin.com/in/jatingyass/) or [email](mailto:msa24010@iiitl.ac.in).

</div>
