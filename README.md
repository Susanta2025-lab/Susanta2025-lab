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

## 🏢 Enterprise Communication Intelligence (ECI)

**Production-oriented multi-cloud enterprise AI communication platform — Register. Connect. Analyze.**

**[Azure Frontend](https://witty-island-03f5de51e.7.azurestaticapps.net)** · **[AWS Frontend](https://d1ut7j94w7lt3b.cloudfront.net)** · **[Repository](https://github.com/Susanta2025-lab/enterprise-communication-intelligence)**

![Python](https://img.shields.io/badge/Python-FastAPI-009688?logo=python&logoColor=white)
![Architecture](https://img.shields.io/badge/Clean_Architecture-Provider_Abstraction-0EA5E9)
![Cloud](https://img.shields.io/badge/Cloud-Azure_%2B_AWS-2563EB)
![RBAC](https://img.shields.io/badge/RBAC-Platform_Owner-7C3AED)
![Status](https://img.shields.io/badge/Status-Phase_22_Validated-success)

Provider-independent platform for turning business communications into structured, actionable intelligence while keeping users in control of mailbox access, attachment retrieval, AI analysis, business context, tracked obligations, workflow approval, and external side effects.

### Highlights

- Implemented and validated through **Phase 22**, including Business Context & Matter Intelligence, XLSX / Tabular Intelligence, and Action, Deadline & Obligation Tracking
- Clean Architecture with provider-independent AI, persistence, connector, credential-store, workflow, business-context, and tracking boundaries
- Independent multi-cloud deployments: Azure Static Web Apps + Container Apps + PostgreSQL + Microsoft Foundry, and AWS CloudFront/S3 + ECS Fargate + RDS + Amazon Bedrock
- Cloud AI implementations validated with **GPT-5.4-mini** on Microsoft Foundry and **Claude Haiku 4.5** on Amazon Bedrock
- Microsoft Entra External ID application login, delegated `communications:*` permissions, and persisted application RBAC with server-side **Platform Owner** authorization
- Gmail and Microsoft Graph / Outlook mailbox connectors with mailbox OAuth kept separate from ECI application identity
- Secure Attachment Intelligence with explicit per-attachment analysis, ClamAV-before-parsing/AI, bounded PDF/DOCX/TXT/XLSX handling, and fail-closed controls
- Human-controlled Propose → Approve / Reject → Execute workflow; analysis, attachment intelligence, context suggestions, and tracking never send automatically
- Durable Work Items support lifecycle, archive/restore, verified provenance, event history, optional Business Context association, and explicit due-date/time semantics
- Technical deployment and scoped browser validation completed on both Azure and AWS; external business-user verification remains deferred

**Tech:** Python • FastAPI • React • TypeScript • PostgreSQL • Docker • Microsoft Entra External ID • Microsoft Foundry • Amazon Bedrock • Azure Container Apps • AWS ECS Fargate • RDS • CloudFront • GitHub Actions

---

## 🧠 Estudio PolyMind — Multi-LLM RAG & Agent Orchestration

[Repository](https://github.com/Susanta2025-lab/estudio-polymind-llm-orchestration)

![Python](https://img.shields.io/badge/Python-3.12-blue?logo=python&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-Agentic-purple)
![RAG](https://img.shields.io/badge/RAG-Hybrid_Retrieval-0EA5E9)
![Kubernetes](https://img.shields.io/badge/Kubernetes-Helm-326CE5?logo=kubernetes&logoColor=white)
![Observability](https://img.shields.io/badge/Observability-Prometheus-E6522C?logo=prometheus&logoColor=white)
![Autoscaling](https://img.shields.io/badge/HPA-Validated_in_Kind-22C55E)
![CI](https://github.com/Susanta2025-lab/estudio-polymind-llm-orchestration/actions/workflows/ci.yml/badge.svg)

Production-style multi-LLM RAG and agent orchestration platform with provider-neutral inference, externalized state boundaries, hardened Kubernetes deployment controls, production-oriented observability, and validated application autoscaling.

### Highlights

- Multi-LLM orchestration with logical model roles decoupled from provider-specific model identifiers
- Provider-neutral inference through local **Ollama** or an **OpenAI-compatible adapter** for a separately deployed vLLM-compatible service
- LangGraph workflows with semantic routing, tool calling, hybrid dense + BM25 retrieval, Reciprocal Rank Fusion, and cross-encoder reranking
- Shared-state boundaries using **Redis** for replica-safe conversation memory and external **Chroma HTTP** for horizontally scaled vector retrieval
- FastAPI query and NDJSON streaming APIs with bearer-token boundaries, readiness checks, sanitized failures, request IDs, and rollout-safe streaming behavior
- Helm-based Kubernetes deployment with NetworkPolicy, non-root/read-only containers, bounded writable `/tmp`, probes, and hardened operational defaults
- Prometheus-compatible metrics, scrape/ServiceMonitor contracts, recording rules, SLIs, and candidate alerts for multi-replica operation
- **Phase 15 PASS:** validated `autoscaling/v2` HPA control loop using per-pod active-query custom metrics through Prometheus and Prometheus Adapter
- Kind validation demonstrated scale **2 → 4 → 2** under bounded authenticated load with all **120 requests successful**; production enablement still requires target-cluster and dependency-capacity calibration
- Latest documented production enablement status: **READY WITH CONDITIONS**, with cloud-specific integration, dependency autoscaling, HA, and multi-node disruption work still deferred

**Tech:** Python • FastAPI • LangGraph • ChromaDB • Redis • Ollama • OpenAI-compatible APIs • Sentence Transformers • BM25 • Streamlit • Docker • Kubernetes • Helm • Prometheus • HPA • GitHub Actions

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
| **AI / GenAI** | LLMs, RAG, AI Agents, LangGraph, LangChain, Microsoft Foundry, Amazon Bedrock, OpenRouter, Ollama, vLLM/OpenAI-compatible APIs, Prompt Engineering, Tool Calling, Hybrid Retrieval, Reranking, Vector Search |
| **Backend / Architecture** | Python, FastAPI, REST APIs, Pydantic, Clean Architecture, Dependency Injection, Async APIs, OIDC/JWT, Microsoft Entra External ID, PostgreSQL, Redis |
| **ML / NLP** | Scikit-learn, XGBoost, Transformers, BERT, PyTorch, TensorFlow/Keras, Model Evaluation, Time-Series Forecasting |
| **Frontend** | React, TypeScript, Vite, Tailwind CSS, Streamlit |
| **Infrastructure / MLOps** | Docker, Kubernetes, Helm, Prometheus, GitHub Actions, CI/CD, Azure Container Apps, AWS ECS Fargate, CloudFront, RDS, Azure, AWS, GCP, Render, Vercel, Cloud Observability |

---

# 🎯 Current Engineering Focus

- AI Solution Architecture
- Enterprise LLM applications
- Retrieval-Augmented Generation
- Agentic workflows and approval-gated automation
- Provider-independent and multi-cloud AI architectures
- Secure identity, RBAC, and external-service integration
- Kubernetes deployment, observability, and capacity-aware scaling
- Full-stack AI applications
- Cloud AI integration and MLOps

---

# 📫 Connect

- [LinkedIn](https://www.linkedin.com/in/susantahazra)
- [GitHub](https://github.com/Susanta2025-lab)
