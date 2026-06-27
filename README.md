# Alireza Barzin Zanganeh

**IAM Architect · AI/ML for Identity & Security** | Adaptive Auth · Risk Engines · Agentic AI | OAuth2/OIDC · MFA · LLMs & RAG

[Email](mailto:alireza@zanganehai.com) • [LinkedIn](https://www.linkedin.com/in/alireza-barzin-zanganeh-2a9909126) • [Portfolio](https://www.zanganehai.com)

---

## 🚀 About Me

I'm an **IAM architect and AI/ML engineer** with over a decade of experience building production identity and security software — SDKs, mobile apps, IdPs, APIs, and multi-tenant platforms — and integrating **machine learning into real authentication workflows**.

My career is rooted in **enterprise identity** (SecureAuth, Acceptto): OAuth2/OIDC/SAML, SSO, MFA, device trust, directory integration, session lifecycle, and risk-adaptive access. At SecureAuth, I automated and validated **ML-driven risk engines** in production adaptive authentication. Today I architect **integrated identity platforms** with **agentic AI assurance** — fail-closed step-up MFA, tenant isolation, and eval-gated releases.

I also build **production-ready AI systems** — LLMs, RAG, tool-calling agents, and classical ML — designed for deployment, testability, and maintenance, not notebook demos.

Earlier in my career, I led **strategic modeling and infrastructure planning** for multimillion-dollar initiatives in fintech and manufacturing — a quantitative foundation that supports risk modeling and ML system design today.

---

## 🧠 Core Skills & Tech Summary

**Identity & Security:** IAM, OAuth2/OIDC/SAML, SSO, MFA, device trust, risk-adaptive auth, JWT, WebAuthn/passkeys, RBAC, anomaly scoring, Azure AD/Entra & Okta integration patterns

**AI / ML:** Scikit-learn, PyTorch, XGBoost, LightGBM, CNNs, RNNs, LSTMs, Transformers, feature engineering, SHAP, Optuna, model evaluation in CI

**LLMs & RAG:** LangChain, FAISS, embeddings, OpenAI/Groq APIs, tool-calling agents, prompt engineering, semantic search

**Languages:** Python, Go, Java, JavaScript, TypeScript, SQL

**Data & Pipelines:** Pandas, NumPy, Spark/PySpark, time-series modeling

**Engineering & Infra:** CI/CD (GitHub Actions, Jenkins), Docker, Kubernetes, test automation, eval harnesses, FastAPI, Flask, microservices, REST/OpenAPI

---

## 📚 Current Focus & Recent Work

Completed **Interview Kickstart's AI/ML Software Engineering Program** (2025–2026) — end-to-end ML systems, system design, and agentic AI.

### Identity + AI *(primary)*

- Integrated identity platforms: IdP protocols, directory sync, MFA, device trust, mobile authenticator
- Agentic AI for identity and admin workflows — RBAC-scoped tools, fail-closed gates, step-up auth
- ML in authentication: adaptive risk, anomaly scoring, validation through CI release gates
- OAuth2/OIDC/SAML, passkeys, conditional access, audit trails

### AI / ML Engineering *(ongoing)*

- LLM applications: fine-tuning, embeddings, retrieval-augmented generation
- NLP pipelines: tokenization, vectorization, semantic search
- Agentic patterns: tool-calling, multi-step reasoning, autonomous workflows
- Classical & deep learning: regression, classification, clustering, CNNs/RNNs/Transformers
- End-to-end ML: evaluation, deployment, monitoring, and LLM integration

---

# 🌟 Featured Projects

## 🔐 ASAR — Device Identity, Fingerprinting & Risk Engine *(Private)*

A multi-service platform for **device identity**, **browser fingerprinting**, **risk scoring**, and **MFA orchestration** for enterprise authentication flows.

**Engineering Highlights**

- Go-based identity service with OIDC discovery, JWKS, and secure internal token issuance
- Cryptographic keystore abstraction with ES384 and hardened defaults
- Browser SDK (TypeScript) for fingerprint capture and device binding
- Microservices for fingerprint collection, matching, anomaly detection, and MFA routing
- Argon2id password storage, account lockout, and hardened login flows
- Multi-phase architecture: IdP foundation → anomaly engine → event bus + MFA feedback

**Tech Stack:** Go, TypeScript, Node, microservices, OAuth/OIDC, JWT, Argon2id, RBAC

---

## 🤖 Rai — Agentic AI Layer for Identity & Admin Workflows *(Private)*

A production-oriented **agentic AI service** designed for identity, assurance, and admin operations.

**Engineering Highlights**

- FastAPI backend with domain-specialist agents
- RBAC-scoped tools and fail-closed safety gates
- Retrieval-augmented generation with structured action flows
- Step-up authentication, citation enforcement, and versioned prompts
- 570+ golden eval cases with CI-gated releases
- Designed to augment identity platforms via HTTP adapters

**Tech Stack:** Python, FastAPI, LangChain, FAISS, OpenAI/Groq APIs, Kubernetes

---

## 📝 Smart Resume Agent

An AI-powered resume-tailoring platform that rewrites resumes using **exact JD phrasing**, **ATS-optimized keywords**, and **non-fabricated metrics**, powered by a multi-phase LLM pipeline.

**Engineering Highlights**

- Four-phase agent pipeline: JD keyword extraction → gap analysis → rewrite → QA & ATS scoring
- LLM abstraction layer: Gemini, Claude, OpenAI, and BYOK support
- Embedding-backed master resume (pgvector) for grounded rewrites
- Inline editing, section-level regeneration, version history, and patch-based chat edits
- ATS scoring engine with keyword deltas, ceilings, quick wins, and blocking issues
- Secure OAuth (Google) + session-scoped BYOK keys
- Scalable architecture: Next.js frontend, FastAPI backend, Redis sessions, Postgres + pgvector

**Tech Stack:** Python, FastAPI, Next.js 15, Tailwind, Redis, Postgres (pgvector), Docker Compose
**Repo:** https://github.com/abzanganeh/smart-resume-agent

---

## 🎬 Movie Agent Service & Demo

A production-style **agentic AI system** for movie discovery using a **tool-calling agent architecture**.

**Key Engineering Decisions**

- Architecture: Service (rules + state) → Agent (reasoning) → Tools (execution) → Service (validation)
- OOP & Design: SRP, Separation of Decision/Action, Dependency Inversion, Factory & Strategy patterns
- Stateless service with session-scoped context
- FAISS-backed retrieval; multi-tool orchestration (search, statistics, quiz generation, vision analysis)
- Validation layers, structured error responses, graceful degradation
- Flask as a pure presentation/API layer

**Tech Stack:** Python, LangChain, FAISS, OpenAI/Groq APIs, Flask, JavaScript
**Repos:**

- Service: https://github.com/abzanganeh/movie-agent-service
- Demo: https://github.com/abzanganeh/movie-agent-demo

---

## 📉 Churn Risk Intelligence

Predictive modeling for telecom churn with **business-aligned evaluation**.

**Tech Stack:** Python, Pandas, Scikit-learn, XGBoost, Optuna, SHAP
**Repo:** https://github.com/abzanganeh/churn_risk_intelligence

---

## 💰 Bank Term Deposit Prediction

Binary classification on imbalanced financial data with a focus on **interpretability and risk tradeoffs**.

**Tech Stack:** Python, Scikit-learn, Imbalanced-learn, Seaborn
**Repo:** https://github.com/abzanganeh/bank-term-deposit-prediction

---

## 🌐 Flask ML Website

A full-stack ML application exposing a trained model via a **Flask-based web interface**.

**Tech Stack:** Python, Flask, HTML/CSS/JavaScript, Scikit-learn
**Repo:** https://github.com/abzanganeh/flask_ml_website

---

## 📡 Signal Strength Classification

Supervised learning on environmental signal data with emphasis on **data quality and evaluation**.

**Tech Stack:** Python, Scikit-learn, Pandas, NumPy
**Repo:** https://github.com/abzanganeh/signal_strength

---

## 🧩 Professional Background

**SecureAuth** · Senior Software QA Engineer · Enterprise IAM & ML Risk Engines
Automated and validated CI regression for a multi-product IAM suite (IdP, Connect, CIAM). Validated ML-driven risk engines (location, browser, time-anomaly) in adaptive authentication through E2E and API automation.

**Acceptto** · Software Engineer · Identity, Security & ML Validation
Built backend services and Android SDK modules for cognitive authentication. Automated and validated ML-integrated authentication pipelines; contributed to end-to-end identity architecture across mobile, Java backend, and React web.

**Current** · IAM Architect · AI/ML for Identity
Lead IAM architect on a confidential, pre-launch identity platform — IdP, directory sync, MFA, device trust, mobile authenticator, and agentic AI with fail-closed assurance.

Earlier in my career, I led **strategic modeling and infrastructure planning** for multimillion-dollar initiatives in fintech and manufacturing.
