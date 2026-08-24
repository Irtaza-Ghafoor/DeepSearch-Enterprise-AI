# ⚡ DeepSearch Enterprise — Autonomous AI Research Engine

> An elite, multi-agent autonomous intelligence system designed to execute deep web research, real-time multi-angle scraping, automated fact-checking, and comprehensive report synthesis.

![Python](https://img.shields.io/badge/Python-3.11+-blue.svg)
![Streamlit](https://img.shields.io/badge/Streamlit-UI-red.svg)
![Groq](https://img.shields.io/badge/Groq-Llama3.3-orange.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

---

## 🌟 Overview

**DeepSearch Enterprise** is a next-generation research assistant inspired by advanced agentic workflows. Instead of relying purely on static LLM memory, it deploys a **Multi-Agent Swarm** that plans search strategies, crawls live web sources asynchronously, filters temporal noise, and synthesizes exhaustive, publication-grade intelligence briefings in seconds.

---

## 🤖 The Multi-Agent Swarm Architecture

1. **🧠 Planner Agent:** Deconstructs user research hypotheses or queries into targeted, multi-angle sub-queries.
2. **🌐 Scraper Agent:** Dynamically harvests live web data and references across global search engines via DuckDuckGo.
3. **🛡️ Fact-Checker & Critic Agent:** Cross-references data, prunes outdated information, and ensures strict temporal and factual accuracy.
4. **✍️ Synthesis Agent:** Compiles structured, professional Markdown intelligence reports complete with metrics and citations.

---

## ✨ Key Features

* **🚀 Real-Time Autonomous Research:** Generates structured reports with executive summaries, technical analysis, and strategic recommendations.
* **💬 Contextual Q&A Thread:** Interactive chat assistant built into each session to drill down deeper into the generated report.
* **📊 Live Telemetry & Metrics:** Tracks word count, verified sources, and real-time agent execution traces.
* **📥 Export Capabilities:** Download full intelligence dossiers instantly as Markdown (`.md`) files.
* **🎨 Modern SaaS UI:** Built with Streamlit, featuring custom glassmorphism dark-mode aesthetics inspired by modern developer tools.

---

## 🛠️ Tech Stack

* **Frontend:** Streamlit (Custom CSS UI/UX)
* **LLM Orchestration:** Groq API & LangChain (`ChatGroq`)
* **Search Engine:** `duckduckgo_search` for zero-key live web retrieval
* **Language:** Python 3.11+

---

## ⚙️ Installation & Local Setup



### 1. Clone the Repository

```bash
git clone [https://github.com/Irtaza-Ghafoor/DeepSearch-Enterprise-AI.git](https://github.com/Irtaza-Ghafoor/DeepSearch-Enterprise-AI.git)
cd DeepSearch-Enterprise-AI 
```

### 2. Install Dependencies
 * Make sure you have Python installed, then run:
  * pip install streamlit groq langchain-groq duckduckgo_search python-dotenv

### 3. Configure Environment Variables
 * Create a .env file in the root directory of your project and add your Groq API key:
  * GROQ_API_KEY=your_groq_api_key_here

### 4. Run the Application
 * streamlit run app.py