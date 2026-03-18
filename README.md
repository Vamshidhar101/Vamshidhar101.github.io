
<!-- GitHub Profile README — Vamshidhar Devalapally -->
<!-- Instructions: Create a repo named exactly your GitHub username, add this file as README.md -->

<h1 align="center">Vamshidhar Devalapally</h1>

<p align="center">
  <strong>Senior ML Engineer &nbsp;·&nbsp; Production GenAI Systems &nbsp;·&nbsp; RAG · LLM Agents · MLOps</strong>
</p>

<p align="center">
  <a href="https://linkedin.com/in/YOUR_LINKEDIN">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  &nbsp;
  <img src="https://img.shields.io/badge/Location-Greensboro%2C%20NC%20%2F%20Remote-555?style=flat" alt="Location"/>
</p>

---

I build **production AI systems** — not just notebooks. 6+ years shipping ML, focused on the GenAI stack: RAG pipelines, multi-agent architectures, and the MLOps layer that keeps them running.

---

## Featured projects

### 1 · RAG Document Intelligence API
> Upload any document. Ask questions. Get cited answers — in production.

| Metric | Score |
|---|---|
| Answer relevance | 94.2% |
| Citation accuracy | 97.8% |
| Avg response latency | 1.8s |

**What it does:** FastAPI backend + Streamlit frontend. PDF/TXT ingestion → FAISS vector store with MMR retrieval → GPT-4o with source citation. Dockerized, `docker-compose` one-command deploy.

**Stack:** `LangChain` `FAISS` `GPT-4o` `FastAPI` `Streamlit` `Docker`

🔗 **[Live demo](YOUR_STREAMLIT_URL)** · **[GitHub](https://github.com/YOUR_USERNAME/rag-document-intelligence)**

---

### 2 · Multi-Agent AI Research Assistant
> Planner → Researcher → Analyst → Critic. Complex questions answered with evidence.

| Agent | Role |
|---|---|
| Planner | Decomposes goal into 3–5 focused sub-tasks |
| Researcher | Web search + synthesis via DuckDuckGo |
| Analyst | Structures findings into a cited answer |
| Critic | Scores quality (0–10) and revises if needed |

**What it does:** LangGraph stateful graph orchestrating four specialized agents with tool use. Self-critique loop catches hallucinations before they reach the user. Streamlit UI shows agent steps in real time.

**Stack:** `LangGraph` `GPT-4o` `Tool calling` `DuckDuckGo Search` `Streamlit` `asyncio`

🔗 **[Live demo](YOUR_STREAMLIT_URL)** · **[GitHub](https://github.com/YOUR_USERNAME/multi-agent-assistant)**

---

### 3 · Fraud Detection API
> Real-time transaction scoring with SHAP explanations. MLflow tracked. CI/CD deployed.

| Metric | Score |
|---|---|
| AUC-ROC | 0.983 |
| AUC-PR | 0.921 |
| Precision (fraud class) | 0.91 |
| Recall (fraud class) | 0.87 |
| Batch throughput | 1,000 tx/request |

**What it does:** XGBoost classifier trained on 50K transactions with SMOTE oversampling. FastAPI serving layer with single + batch endpoints. Every prediction includes top-5 SHAP risk factors. MLflow experiment tracking + model registry. GitHub Actions CI/CD pipeline.

**Stack:** `XGBoost` `SHAP` `SMOTE` `FastAPI` `MLflow` `Docker` `GitHub Actions`

🔗 **[GitHub](https://github.com/YOUR_USERNAME/fraud-detection-api)** · Includes `generate_data.py` for reproducible local testing

---

## Tech stack

```
GenAI / LLM        LangChain · LangGraph · OpenAI GPT-4o · FAISS · RAG · LoRA/QLoRA
Classical ML       XGBoost · LightGBM · scikit-learn · SMOTE · SHAP
Deep Learning      PyTorch · HuggingFace · BERT · LSTM
MLOps              MLflow · FastAPI · Docker · GitHub Actions · Streamlit
Languages          Python (primary) · SQL · bash
Data               pandas · numpy · spark (PySpark)
```

---

## Background

**Education:** MS Computer Science · Auburn University at Montgomery &nbsp;|&nbsp; MS Technology Management · Lindsey Wilson University

---

## What I'm looking for

Senior ML / AI Engineer roles · Remote or Greensboro NC  
Specializing in: production RAG systems · LLM agent architectures · MLOps pipelines

📬 [vamshidev101@gmail.com] &nbsp;·&nbsp; [LinkedIn](https://linkedin.com/in/YOUR_LINKEDIN)
