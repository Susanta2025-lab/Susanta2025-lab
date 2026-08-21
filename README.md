<p align="center">
  <img
    src="./assets/github-profile-banner-dark.svg"
    alt="Susanta Hazra — AI Engineer building production-oriented AI systems"
    width="100%"
  >
</p>

# Hi, I'm Susanta Hazra 👋

### AI Engineer | LLMs • RAG • AI Agents | Cloud AI • AI Solution Architecture | Full-Stack AI Systems

I design and build production-oriented AI systems combining LLMs, Retrieval-Augmented Generation, agentic workflows, machine learning, APIs, cloud AI platforms, and modern web interfaces.

My focus is modular architecture: maintainable services, clear provider boundaries, secure integrations, observable workflows, and deployable applications that solve real business problems—from backend APIs and inference layers to full-stack AI products.

---

# 🚀 Featured Projects

## 🏢 Enterprise Communication Intelligence

**Enterprise Communication Intelligence Platform**

[Repository](https://github.com/Susanta2025-lab/enterprise-communication-intelligence)

![Python](https://img.shields.io/badge/Python-FastAPI-009688?logo=python&logoColor=white)
![Architecture](https://img.shields.io/badge/Clean_Architecture-Provider_Abstraction-0EA5E9)
![Testing](https://img.shields.io/badge/Pytest-Automated-green)
![Status](https://img.shields.io/badge/Status-Multi--Cloud_Enterprise_AI-blue)

Provider-independent enterprise AI platform for transforming business communications into structured, actionable intelligence, built with Clean Architecture, FastAPI, multi-cloud AI providers, identity-aware persistence, communication connectors, and approval-gated workflow automation.

### Highlights

- Clean Architecture with provider-independent AI, persistence, connector, and workflow boundaries
- Microsoft Foundry and Amazon Bedrock provider implementations with structured model outputs
- Same Dockerized application deployed across Azure Container Apps and AWS ECS Fargate
- OIDC/JWT authentication, permission-based authorization, and Microsoft Entra ID integration
- PostgreSQL user-scoped persistence plus Gmail and Microsoft Graph read-only connector adapters
- GitHub Actions CI/CD, cloud-native observability, and approval-gated workflow actions with a deterministic execution boundary

**Tech:** Python • FastAPI • Pydantic • PostgreSQL • Docker • Microsoft Foundry • Amazon Bedrock • Azure Container Apps • AWS ECS Fargate • GitHub Actions

---

## 🧠 Estudio PolyMind — Multi-LLM RAG & Agent Orchestration

[Repository](https://github.com/Susanta2025-lab/estudio-polymind-llm-orchestration)

![Python](https://img.shields.io/badge/Python-3.12-blue?logo=python&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-Agentic-purple)
![RAG](https://img.shields.io/badge/RAG-Hybrid_Retrieval-0EA5E9)
![Docker](https://img.shields.io/badge/Docker-Containerized-2496ED?logo=docker&logoColor=white)
![CI](https://github.com/Susanta2025-lab/estudio-polymind-llm-orchestration/actions/workflows/ci.yml/badge.svg)

Local-first multi-LLM RAG and agent orchestration platform demonstrating semantic routing, hybrid retrieval, reranking, conversational memory, tool use, model routing, FastAPI services, Docker, and CI.

### Highlights

- Multi-LLM orchestration with Ollama using Mistral, Qwen 2.5, Gemma 2, and Phi-3 Mini
- LangGraph workflows with tool calling, semantic routing, and persistent session memory
- Hybrid dense + BM25 retrieval fused with Reciprocal Rank Fusion
- Cross-encoder reranking for improved context relevance and reduced retrieval noise
- ChromaDB vector search, document ingestion, Streamlit UI, and evaluation workflows
- Dockerized services with GitHub Actions CI and local-first inference

**Tech:** Python • FastAPI • LangGraph • ChromaDB • Ollama • Sentence Transformers • BM25 • Streamlit • Docker • GitHub Actions

---

## 📰 FatoCheck — Fake News Detection API

Deployed NLP classification system using a tuned **TF-IDF + XGBoost** pipeline, with local fine-tuned **BERT** inference, a FastAPI backend, Streamlit frontend, Docker, and automated CI.

<p>
  <img src="https://img.shields.io/badge/FastAPI-REST%20API-009688?logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/XGBoost-Production%20Model-337AB7" alt="XGBoost">
  <img src="https://img.shields.io/badge/BERT-Local%20Inference-FFD21E?logo=huggingface&logoColor=black" alt="BERT">
  <img src="https://img.shields.io/badge/Streamlit-Live%20Demo-FF4B4B?logo=streamlit&logoColor=white" alt="Streamlit">
  <img src="https://img.shields.io/badge/Docker-Containerized-2496ED?logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Render-Live%20API-46E3B7?logo=render&logoColor=black" alt="Render">
  <img src="https://github.com/Susanta2025-lab/Fatocheck/actions/workflows/ci.yml/badge.svg" alt="CI">
</p>

**[Live Demo](https://fatocheck-ai.streamlit.app/)** · **[Live API](https://fatocheck.onrender.com/docs)** · **[Repository](https://github.com/Susanta2025-lab/Fatocheck)**

**Highlights**

* Tuned TF-IDF + XGBoost pipeline achieving approximately **97.08% test accuracy**
* Public FastAPI deployment using **XGBoost as the production inference model**
* Fine-tuned `bert-base-uncased` supported and verified for **local inference**
* Unified inference layer with confidence scoring and lazy BERT model loading
* Streamlit frontend, Dockerized backend, GitHub Actions CI, and health/readiness endpoints

**Tech:** Python · FastAPI · Scikit-learn · XGBoost · Transformers · BERT · Streamlit · Docker · Render


---

## 🩺 MediChrono Insight — AI-Powered Medical Chronology Platform

[Repository](https://github.com/Susanta2025-lab/medichrono-insight) · [Live Demo](https://medichrono-insight.vercel.app/)

![React](https://img.shields.io/badge/React-TypeScript-61DAFB?logo=react&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-OpenRouter-009688?logo=fastapi&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_2.5_Flash-LLM-8B5CF6)
![Deploy](https://img.shields.io/badge/Vercel_%2B_Render-Live-black)
![Status](https://img.shields.io/badge/Status-Portfolio_Demo-blue)

Live full-stack AI portfolio application, evolved from a SWANS Applied AI Hackathon prototype, for interactive medical chronology visualization and grounded AI-assisted case summarization.

### Highlights

- React/TypeScript frontend with interactive medical timeline, search, filtering, and case inspection
- Client-side Excel chronology parsing so the raw workbook is not uploaded to the backend
- FastAPI backend for chronology condensation, prompt construction, AI orchestration, and response validation
- OpenRouter integration with Google Gemini 2.5 Flash for on-demand executive case summaries
- Live Vercel frontend and Render backend demonstrating a legal-tech AI workflow
- Portfolio-oriented architecture with explicit no-hallucination prompting and known persistence/testing limitations

**Tech:** React • TypeScript • FastAPI • OpenRouter • Gemini • Vite • Tailwind CSS • Vercel • Render

---

## Selected Collaboration

### ⚡ Grid Intelligence — Energy Price Forecasting

[Repository](https://github.com/xucenying/grid-intelligence)

Collaborative ML/MLOps project for day-ahead electricity-price forecasting in the Germany–Luxembourg (DE-LU) bidding zone. My contribution focused on deep-learning development using Transformer and LSTM models; the team platform combined these models with a broader data, API, and cloud deployment stack.

**Tech:** PyTorch • Transformer • LSTM (my contribution) • XGBoost • FastAPI • Docker • BigQuery • Cloud Run • GCP

---

# 🛠 Core Engineering Stack

| Area | Capabilities |
|------|----------------|
| **AI / GenAI** | LLMs, RAG, AI Agents, LangGraph, LangChain, Microsoft Foundry, Amazon Bedrock, OpenRouter, Ollama, Prompt Engineering, Tool Calling, Hybrid Retrieval, Reranking, Vector Search |
| **Backend / Architecture** | Python, FastAPI, REST APIs, Pydantic, Clean Architecture, Dependency Injection, Async APIs, OIDC/JWT, PostgreSQL |
| **ML / NLP** | Scikit-learn, XGBoost, Transformers, BERT, PyTorch, TensorFlow/Keras, Model Evaluation, Time-Series Forecasting |
| **Frontend** | React, TypeScript, Vite, Tailwind CSS, Streamlit |
| **Infrastructure / MLOps** | Docker, GitHub Actions, CI/CD, Azure Container Apps, AWS ECS Fargate, Azure, AWS, GCP, Render, Vercel, Cloud Observability |

---

# 🎯 Current Engineering Focus

- AI Solution Architecture
- Enterprise LLM applications
- Retrieval-Augmented Generation
- Agentic workflows and approval-gated automation
- Provider-independent and multi-cloud AI architectures
- Full-stack AI applications
- Cloud AI integration, observability, and MLOps

---

# 📫 Connect

- [LinkedIn](https://www.linkedin.com/in/susantahazra)
- [GitHub](https://github.com/Susanta2025-lab)
