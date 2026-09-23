

#### Hi, I'm Harikrishnan 👋

Data Engineer at **Kpler** (Singapore). 
- 🔭 Currently building: agentic RAG and multi-agent support systems
- 🌱 Learning: [e.g. evals for LLM agents, LangGraph deployment]
- 💬 Ask me about: LangGraph, RAG, Airflow, Debezium / CDC, ArgoCD, Spark
- 📫 Reach me: [https://www.linkedin.com/in/harikrishnan-rajkumar/] · [email]


## 🛠️ Tech stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Scala](https://img.shields.io/badge/Scala-DC322F?logo=scala&logoColor=white)

**AI / LLM**

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?logo=langchain&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?logo=streamlit&logoColor=white)

**Data engineering**

![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?logo=apachespark&logoColor=white)
![Apache Iceberg](https://img.shields.io/badge/Apache%20Iceberg-2D7FF9)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?logo=apacheairflow&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)

**Infra / DevOps**

![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white)
![ArgoCD](https://img.shields.io/badge/Argo%20CD-EF7B4D?logo=argo&logoColor=white)

## 📊 GitHub stats

![Profile details](https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=harikrishnan-dev&theme=github)


![Streak](https://streak-stats.demolab.com?user=harikrishnan-dev&hide_border=true)


## 🚀 Featured projects

### 🤖 [CORA](https://github.com/harikrishnan-dev/cora): Customer Operations & Resolution Agent
Multi-agent customer support system for e-commerce. A triage agent reads the customer's
message and routes it to specialist agents for **refunds, warranty/service and shipping**,
resolving tickets end to end with minimal human intervention.
- Multi-agent orchestration with **LangGraph** and **Claude**, traced in **LangSmith**
- **FastAPI** backend + **Streamlit** chat UI, **PostgreSQL** for customers/orders
- Dockerized and deployable to **Render**

`LangGraph` `Anthropic Claude` `FastAPI` `Streamlit` `PostgreSQL` `Docker`

### 🏦 [issue-classifier](https://github.com/harikrishnan-dev/issue-classifier): Secure support-ticket routing for a digital bank
Takes free-text customer issues ("my card was declined", "block my lost card") and routes
each one to the owning internal team, with guardrails built in.
- **PII redaction** with Microsoft Presidio before any text reaches the LLM
- **Prompt-injection screening**; fails safe to human review instead of guessing
- Team taxonomy derived by clustering the 77 intents of the **banking77** dataset into 6 teams
- Tested with pytest, pre-commit and CI

`LangGraph` `Presidio` `LLM guardrails` `FastAPI` `pytest`

### 📚 [newbie](https://github.com/harikrishnan-dev/newbie): Agentic RAG onboarding assistant
A chatbot that helps new employees get answers from the company handbook
(demoed on the public GitLab handbook).
- **Hybrid search** (BM25 + vector) over a **Weaviate** vector store
- CLI to backfill and query documents; graph debuggable in LangGraph Studio
- **FastAPI** backend + **Streamlit** chat UI

`LangGraph` `RAG` `Weaviate` `FastAPI` `Streamlit`

<!--
**harikrishnan-dev/harikrishnan-dev** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
