# Shivam Nayak

**AI Engineer | LLM Applications | Agentic AI Systems**

Building reliable AI systems — LLM applications, RAG pipelines, multi-agent workflows, and production-grade automation solutions.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shivam-nayakk)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/shivamnayakk)
[![X](https://img.shields.io/badge/X-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/shivmnyk)

---

## About

I design and build end-to-end AI systems that combine modern Generative AI with strong software engineering practices.

My focus is on systems that are reliable in production — not just functional in notebooks. That means evaluation-driven development, clean architecture, and deployment pipelines that actually hold up.

Current areas of work:
- Agentic systems and multi-agent orchestration
- RAG pipelines with evaluation and hybrid retrieval
- Voice AI and real-time conversational backends
- LLM fine-tuning and domain adaptation
- Production MLOps and experiment tracking

---

## Core Focus Areas

**Agentic AI**
Multi-agent orchestration, stateful workflows, tool calling, LangGraph, MCP, Agent-to-Agent communication, memory systems.

**RAG Engineering**
Retrieval pipeline design, vector databases, hybrid search, embedding strategies, generation control, evaluation with Ragas / DeepEval.

**Production AI**
FastAPI backends, Docker, cloud deployment, CI/CD, experiment tracking with MLflow, observability with LangSmith.

**LLM Adaptation**
Parameter-efficient fine-tuning (LoRA / QLoRA), quantization, domain-specific adaptation, Hugging Face ecosystem.

---

## Featured Projects

### [Asha AI – Healthcare Voice Agent](https://github.com/shivamnayakk/ai-hospital-voice-agent)

End-to-end conversational voice agent for clinical triage and hospital workflow automation.

**Problem:** Hospital intake workflows are slow, error-prone, and human-bottlenecked. Real-time voice AI can automate triage and scheduling while maintaining reliability under live conversational conditions.

**Architecture:** Streaming voice pipeline → STT → Reasoning Layer (LangGraph) → Intent Router → TTS → Async response delivery

**Engineering highlights:**
- Low-latency streaming pipeline with concurrent request handling
- Stateful agent workflow for multi-turn clinical conversations
- Reliable intent routing under noisy, real-world speech conditions
- Async FastAPI backend with structured session management

**Stack:** Python · FastAPI · LangGraph · STT/TTS · Async streaming

---

### [AI Workforce Automation Platform](https://github.com/shivamnayakk/AI-Workforce-Automation-Platform-)

Multi-agent platform for automating business workflows through specialized AI agents.

**Problem:** Business operations — research, outreach, scheduling, support — require coordinated effort across functions. A multi-agent system can automate these workflows with controllable, auditable agent behavior.

**Architecture:** Supervisor agent → Specialist agents (research, outreach, scheduling, support) → Structured tool calling → State management layer

**Engineering highlights:**
- Supervisor-worker pattern for controllable task delegation
- Persistent state management across agent turns
- Extensible agent design — new agents added without redesigning orchestration
- Tool-calling contracts with structured input/output validation

**Stack:** Python · LangGraph · Multi-agent systems · Tool calling · FastAPI

---

### [Agent Runtime OS – MCP, A2A, Memory](https://github.com/shivamnayakk/Agent-Runtime-OS-MCP-A2A-Memory-)

Agentic execution runtime implementing Model Context Protocol, Agent-to-Agent communication, and persistent memory stores.

**Problem:** Production agentic systems need more than a single LLM call chain — they need a runtime that handles tool registration, inter-agent messaging, and memory that persists across sessions.

**Architecture:** MCP tool registry → A2A message bus → Persistent memory layer → Agent execution engine

**Engineering highlights:**
- MCP-compliant tool registration and invocation
- Agent-to-Agent communication with structured messaging protocol
- Persistent memory with retrieval-aware storage
- Runtime designed for extensibility and composability

**Stack:** Python · MCP · LangGraph · Vector DB · Memory systems

---

### [LLM Evaluation & Observability Platform](https://github.com/shivamnayakk/LLM-Evaluation-Observability-Platform)

Production observability and evaluation platform for LLM applications.

**Problem:** Deploying LLMs without systematic evaluation leads to silent quality degradation. Teams need visibility into model behavior, retrieval quality, and generation accuracy across production traffic.

**Architecture:** Trace collection → Evaluation pipeline (Ragas / DeepEval) → Metrics aggregation → Dashboard

**Engineering highlights:**
- Automated evaluation runs on production traces
- RAG-specific metrics: faithfulness, context precision, answer relevance
- LangSmith integration for trace observability
- Modular evaluator design — swap frameworks without pipeline changes

**Stack:** Python · Ragas · DeepEval · LangSmith · FastAPI

---

### [CogniFlow AI – Autonomous Business Intelligence](https://github.com/shivamnayakk/CogniFlow-AI)

Autonomous AI platform that helps founders make decisions by analyzing competitors, markets, and investors through multi-agent workflows and RAG.

**Problem:** Early-stage founders spend significant time on manual competitive research and market analysis. An agentic system can automate intelligence gathering and synthesis at scale.

**Architecture:** Query decomposition → Specialized research agents (competitor, market, investor) → RAG synthesis → Structured report generation

**Engineering highlights:**
- Multi-agent research orchestration with LangGraph
- RAG pipeline with hybrid retrieval over curated business data
- Structured output generation with source attribution
- Modular agent design — each domain agent independently testable

**Stack:** Python · LangGraph · RAG · Vector DB · FastAPI

---

### [Deep Research Agent](https://github.com/shivamnayakk/Deep-Research-Agent-)

Autonomous multi-step web research agent with context synthesis and automated report generation.

**Architecture:** Query planning → Parallel web exploration → Context synthesis → Iterative refinement → Report generation

**Engineering highlights:**
- Multi-step reasoning with dynamic query expansion
- Parallel web retrieval with deduplication and relevance filtering
- Iterative synthesis across multiple sources
- Structured Markdown report output

**Stack:** Python · LangGraph · Web retrieval · LLM synthesis

---

### [SyllAIq – RAG System for Academic Content](https://github.com/shivamnayakk/syllaiq)

Intelligent RAG system over CS syllabi, textbooks, and past year questions.

**Architecture:** Document ingestion → Chunking strategy → Embedding → Vector DB → Hybrid retrieval → Controlled generation

**Engineering highlights:**
- Domain-specific chunking for academic content structure
- Hybrid search combining semantic and keyword retrieval
- Query-aware context assembly for precise answer generation
- Evaluation against ground-truth Q&A pairs

**Stack:** Python · RAG · Vector DB · Hybrid search · LLMs

---

### [RetailOps – Production ML Pipeline](https://github.com/shivamnayakk/Retail-Ops-End-to-End-Sales-Forecasting-Pipeline)

End-to-end MLOps system for sales forecasting and inventory optimization.

**Architecture:** Modular ETL → Feature engineering → Training → Validation → Experiment tracking → Containerized deployment

**Engineering highlights:**
- Reproducible pipelines with DVC for data versioning
- MLflow for experiment tracking and model registry
- Docker-based consistent environments across dev and production
- Automated validation gates before model promotion

**Stack:** Python · MLflow · DVC · Docker · CI/CD

---

### [Llama-3 Fine-Tuning Pipeline](https://github.com/shivamnayakk/Llama3-Domain-Specific-FineTuning)

Parameter-efficient fine-tuning system for domain adaptation of Llama-3 models.

**Architecture:** Dataset preparation → Quantization → LoRA/QLoRA adaptation → Evaluation → Adapter export

**Engineering highlights:**
- Memory-efficient training with 4-bit quantization and QLoRA
- Systematic evaluation before and after fine-tuning
- Adapter-based design — base model unchanged, domain adapters composable
- Reproducible training configs with documented hyperparameters

**Stack:** Python · PyTorch · Hugging Face · LoRA / QLoRA · PEFT

---

## Technical Stack

**Programming**
Python · SQL · JavaScript

**Backend**
FastAPI · PostgreSQL · Redis · REST APIs

**AI / ML**
PyTorch · Scikit-learn · Deep Learning · Transformers

**Generative AI**
LLMs · RAG · Vector Databases · Embeddings · LoRA · QLoRA · Fine-tuning

**Agentic Systems**
LangGraph · LangChain · MCP · Tool Calling · Multi-agent Orchestration · A2A

**Production & MLOps**
Docker · AWS · Linux · CI/CD · MLflow · DVC · Git

**Evaluation & Observability**
Ragas · DeepEval · LangSmith · Tracing · Metrics pipelines

---

## Engineering Principles

> **I build systems, not demos.**

- **Reliability first.** Systems that work under real conditions, not just controlled inputs.
- **Evaluation-driven.** Every LLM component has measurable quality criteria and regression tests.
- **Clean architecture.** Modular, testable components with clear interfaces.
- **Deployment mindset.** Nothing is done until it runs in a container with a health check.
- **Scalability by design.** Async where it matters, stateless where possible, observable always.

---

## GitHub Stats

![Shivam's GitHub Stats](https://github-readme-stats.vercel.app/api?username=shivamnayakk&show_icons=true&theme=default&hide_border=true&count_private=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=shivamnayakk&layout=compact&theme=default&hide_border=true)

---

*Building in public. Focused on shipping.*

