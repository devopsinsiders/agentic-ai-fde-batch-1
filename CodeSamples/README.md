# 💻 Code Samples & Starter Kits ⚡

Welcome to the **Code Samples** repository for **Agentic AI & Forward Deployed Engineering (Batch 1)**! 🚀🤖

This folder contains verified, production-grade starter kits 📦, reference implementations 🧪, and utility scripts 🔧 used across our cohort sessions.

---

## 📂 Directory Structure 🗂️

```text
CodeSamples/
├── 📁 01-python-foundations/    # 🐍 AsyncIO patterns, typing, Pydantic models & high-performance APIs
├── 📁 02-rag-pipelines/         # 🔍 Chunking strategies, pgvector integrations & embedding pipelines
├── 📁 03-mcp-servers/           # 🔌 Model Context Protocol server templates (stdio & SSE)
├── 📁 04-langgraph-agents/      # 🕸️ Stateful multi-agent graphs, checkpoints & human-in-the-loop loops
└── 📁 05-gateways-governance/   # ⛩️ LiteLLM configurations, cost tracking & Langfuse observability
```

---

## 🚀 Getting Started 🛠️

### 1. Environment Setup 🐍
We recommend using Python 3.11+ with a virtual environment:

```bash
# Create virtual environment 📦
python -m venv .venv

# Activate on Windows PowerShell 💻
.venv\Scripts\Activate.ps1

# Activate on Linux/macOS 🐧
source .venv/bin/activate
```

### 2. Install Common Dependencies 📥
```bash
pip install --upgrade pip
pip install pydantic fastapi uvicorn httpx langchain langgraph mcp litellm
```

### 3. Environment Variables 🔒
Always copy `.env.example` to `.env` before running samples:
```bash
cp .env.example .env
```

---

> [!TIP]
> 💡 *All code samples in this folder are designed to be self-contained, typed, and enterprise ready!* 🌟
