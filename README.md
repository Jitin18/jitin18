# Hi, I'm Jitin Pranav Kolathur 👋

### Data & AI Engineer | Agentic AI | Forward Deployed & Solutions Engineering

📍 Seattle, WA | 🎓 MS Business Analytics @ University of Washington Foster

I build **data and AI systems that solve real business problems**.

My background started in enterprise data engineering, where I built and supported multi-terabyte data platforms at Capgemini. Since then, I've expanded into **RAG, agentic AI, multi-agent systems, LLM evaluation, and customer-facing technical solutions**.

I enjoy working where **engineering meets the customer**: understanding an ambiguous problem, designing the architecture, building the solution, evaluating whether it actually works, and explaining the tradeoffs.

---

## 🚀 What I've Been Building

### 🎙️ Cadence — Real-Time Voice AI Agent

A real-time voice AI system that turns structured contact-center workflows into natural conversations.

**Architecture:**  
`Silero VAD → Whisper STT → LLM Coordinator → Orpheus TTS`

Built with specialist workflows for identity verification, rewards, orders, refunds, knowledge retrieval, and escalation.

The key design principle:

> **The AI understands and speaks. Deterministic code decides.**

Business actions are controlled through a deterministic Journey Manager, least-privilege MCP tools, and input/output guardrails.

**Tech:** Python · Groq · Whisper · Orpheus TTS · Silero VAD · MCP · Voice AI

---

### 🛡️ Sentinel — Agentic Multimodal AI System

A multi-agent system that analyzes video and audio, retrieves relevant policies, reasons over evidence, and determines the appropriate action.

The system orchestrates specialized:

- 👁️ **Perception Agent** — analyzes video frames and transcribes speech
- 📚 **Policy Agent** — retrieves relevant policies using RAG
- ⚙️ **Action Agent** — determines whether to allow, blur, mute, or escalate

Ambiguous cases automatically loop back for additional analysis before a decision is made.

Includes **human-in-the-loop escalation, audit logging, RAG-based policy retrieval, and conditional agent routing**.

**Tech:** Python · LangGraph · Groq · RAG · ChromaDB · Whisper · Multimodal AI

---

## 🧠 Enterprise AI

### ☁️ Salesforce — Agentforce Industry Capstone

Architected and built an enterprise RAG system using **Salesforce Agentforce + Data Cloud**, owning the end-to-end technical build.

Worked across:

`Enterprise Data → Search Index → Retriever → Query Optimization → Agentforce → Grounded Response`

- Designed retrieval workflows using search indexing, metadata, hybrid search, and query rewriting
- Built a repeatable evaluation framework using **LLM-as-a-Judge + FLEX**
- Evaluated the system across **200+ structured test scenarios**
- Achieved **80.6% Hit@K** on an adversarial retrieval evaluation set
- Reduced hallucination rates by approximately **30%** through iterative retrieval and prompt optimization
- Presented architecture decisions, results, and technical tradeoffs to Salesforce stakeholders

🏆 Salesforce Certified Agentforce Specialist

---

## 🏗️ Enterprise Data Engineering

### Capgemini — Senior Analyst | Data & Consulting

Before building AI systems, I spent 3+ years building the data infrastructure underneath them.

I worked across enterprise **Supply Chain and Finance** data platforms using Azure and Databricks.

Some scale:

- ⚡ Processed approximately **3–5 TB of enterprise data daily**
- 🔧 Improved pipeline efficiency by approximately **15%**
- 🔍 Built validation and reconciliation workflows across **50M+ records**
- 📉 Contributed to a **40% reduction in production incidents**
- ✅ Maintained **99%+ SLA adherence**
- 🏆 Received the **Shining Star Award**

**Tech:** Python · SQL · PySpark · Scala · Databricks · Spark · Azure Data Factory · Delta Lake

---

## 💼 What I'm Doing Now

### HireCrit — Technical Product Manager

I'm currently working at the intersection of **AI, product, engineering, and customers**.

My work includes:

- Understanding customer problems and technical requirements
- Translating ambiguous needs into AI workflows and implementation approaches
- Building and demonstrating technical prototypes
- Defining success criteria across accuracy, latency, reliability, and business outcomes
- Working with Product and Engineering to turn customer feedback into product improvements

This has pushed me further toward the kind of work I enjoy most:

**Build the technology → understand the user → solve the problem → prove that it works.**

---

## 🧪 More Projects

### 📈 ExperimentLab

LLM experimentation and evaluation platform for systematically testing AI features instead of relying on subjective prompt testing.

Evaluates thousands of interactions using **RAGAS and LLM-as-a-Judge** workflows.

**Tech:** Python · RAGAS · LLM Evaluation · Experimentation

### 💬 ConvoAI

Stateful multi-turn conversational AI application built using **Gemini 2.5 Flash, Python, SQL, and Streamlit**.

Designed to maintain coherent context across long conversations with persistent conversation history and application state.

**Tech:** Python · Gemini · SQL · Streamlit · LLM APIs

---

## 🛠️ Tech Stack

**Agentic AI & LLMs**  
LangChain · LangGraph · RAG · Multi-Agent Systems · Agentforce · MCP · Prompt Engineering · Tool Calling

**LLM Evaluation**  
RAGAS · LLM-as-a-Judge · FLEX · LangSmith

**Data Engineering**  
Databricks · Apache Spark · PySpark · Delta Lake · Azure Data Factory · ADLS · ETL/ELT · Data Modeling

**Programming**  
Python · SQL · Scala

**AI / ML**  
Embeddings · Vector Search · Hybrid Search · ChromaDB · XGBoost · Forecasting · Multimodal AI · Voice AI

**Analytics**  
Power BI · Tableau · A/B Testing · Statistical Analysis

---

## 🎯 What I'm Interested In

I'm particularly interested in roles where I can combine **building + problem solving + working directly with users or customers**, including:

**Forward Deployed Engineering · Solutions Engineering · AI Engineering · Data & AI Engineering · Technical Product**

---

## 📫 Let's Connect

📧 **Email:** jitin2300@gmail.com  
💼 **LinkedIn:** www.linkedin.com/in/jitin-pranav-kolathur  
🌐 **Portfolio:** https://jitinpranavkolathur.lovable.app

If you're building something interesting around **Agentic AI, enterprise data, or applied AI systems**, I'd love to connect.
