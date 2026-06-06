# Llama 2 AI Toolkit

> Production-ready collection of Llama 2 powered AI applications — SQL generation, email automation, invoice extraction, and LLM deployment on Google Colab.

[![Python](https://img.shields.io/badge/Python-3.9+-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![LangChain](https://img.shields.io/badge/LangChain-Latest-1C3C3C?style=flat-square)](https://langchain.com)
[![Google Colab](https://img.shields.io/badge/Google_Colab-Ready-F9AB00?style=flat-square&logo=google-colab&logoColor=white)](https://colab.research.google.com)
[![Stars](https://img.shields.io/github/stars/SauravSrivastav/llama2-ai-toolkit?style=flat-square)](https://github.com/SauravSrivastav/llama2-ai-toolkit)

---

## Overview

This toolkit demonstrates practical **Llama 2 LLM deployments** for enterprise use cases — from natural language SQL queries to automated document processing. Built by a **Cloud & DevSecOps Engineer** with a focus on production-grade AI infrastructure on Azure.

---

## Projects

| # | Project | Description | Stack |
|---|---------|-------------|-------|
| 01 | **Llama 2 on Google Colab** | Deploy and run Llama 2 (7B/13B) on free GPU — complete setup guide | Python · Colab · HuggingFace |
| 02 | **SQLNinja** | Natural language → SQL query generator using Llama 2 | LangChain · SQLite · Streamlit |
| 03 | **Email Generator** | AI-powered professional email drafting assistant | Llama 2 · LangChain · Python |
| 04 | **Invoice Extraction Bot** | Automated invoice data extraction using LLM | Llama 2 · PDF · Python |
| 05 | **Text-to-SQL Helper** | Advanced SQL query builder from plain English | LangChain · Llama 2 · Gradio |

---

## Quick Start

### Prerequisites

```bash
pip install langchain transformers accelerate bitsandbytes
pip install streamlit gradio
```

### Run Llama 2 on Google Colab

1. Open the notebook in `01-Run Llama 2 on Google Colab/`
2. Select **GPU runtime** (T4 recommended)
3. Run all cells — model downloads automatically from HuggingFace

### Run SQLNinja locally

```bash
cd 02-SQLNinja
pip install -r requirements.txt
streamlit run app.py
```

---

## Architecture

```
llama2-ai-toolkit/
├── 01-Run Llama 2 on Google Colab/   # LLM deployment guide
├── 02-SQLNinja Tool/                  # NL → SQL with LangChain
├── 03-EmailGeneratorApp/              # Email automation
├── 04-InvoiceExtractionBot/           # Document processing
└── 05-Text_To_SQL_Query_Helper_Tool/  # Advanced SQL generation
```

---

## Use Cases

- **Enterprise SQL automation** — Let business users query databases in plain English
- **Document processing** — Extract structured data from invoices and PDFs automatically
- **Communication automation** — Generate professional emails at scale
- **LLM evaluation** — Test Llama 2 capabilities across different hardware configurations

---

## Built By

**Saurav Srivastav** — Cloud & DevSecOps Leader | Azure · AKS · MLOps · LLMOps | Dubai, UAE

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/sauravsrivastav2205/)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-0078D4?style=flat-square&logo=vercel)](https://saurav-srivastav-portfolio.vercel.app)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=flat-square&logo=github)](https://github.com/SauravSrivastav)

---

## Related Projects

- [ai-code-assistant](https://github.com/SauravSrivastav/ai-code-assistant) — Code Llama powered coding assistant
- [ultimate-mcp-setup-guide](https://github.com/SauravSrivastav/ultimate-mcp-setup-guide) — Best MCP servers for Claude Code
- [Azure-Managed-Prometheus-and-Grafana](https://github.com/SauravSrivastav/Azure-Managed-Prometheus-and-Grafana) — AKS monitoring stack

---

<sub>Llama 2 · LLM · MLOps · LLMOps · Generative AI · LangChain · Python · Google Colab · SQL · Azure AI · Dubai UAE</sub>
