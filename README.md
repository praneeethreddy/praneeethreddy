# 🚀 Hi there, I'm Praneeth Reddy | <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=20&pause=1000&color=238636&width=435&lines=Generative+AI+Engineer;Multi-Agent+Workflows;LLM+Orchestrator" alt="Typing SVG" />

[![LinkedIn](https://img.shields.io/badge/LinkedIn-@praneethkesarapu1906-blue?logo=linkedin&style=for-the-badge)](https://linkedin.com/in/praneethkesarapu1906) 
[![Portfolio](https://img.shields.io/badge/Portfolio-Live_Site-green?logo=react&style=for-the-badge)](https://praneethreddy.netlify.app) 
[![Email](https://img.shields.io/badge/Email-reddypraneeth066@gmail.com-red?logo=gmail&style=for-the-badge)](mailto:reddypraneeth066@gmail.com)

---

## 🛠️ My GenAI Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/🦜%20LangChain-1C3C3C?style=for-the-badge)
![LangGraph](https://img.shields.io/badge/🔗%20LangGraph-FF5722?style=for-the-badge)
![MCP](https://img.shields.io/badge/🧩%20MCP-Context%20Protocol-7952B3?style=for-the-badge)
![RAG](https://img.shields.io/badge/🔍%20RAG-Retrieval%20Augmented-0052CC?style=for-the-badge)

---

## 👨‍💻 About Me

I am an **AI/ML and Generative AI Engineer** with over 6 years of experience designing, building, and scaling production-grade machine learning and LLM-powered systems. I specialize in translating complex business requirements into high-impact AI solutions that serve millions of queries. 

Currently, I'm engineering massive Generative AI platforms at **Toyota**, supporting over 500,000 enterprise users with real-time Q&A and decision-support systems.

---

## 🤖 Architectures I Build

### 1. LangGraph Multi-Agent Workflow
Here is how I orchestrate complex tasks across specialized agents using LangGraph for deterministic behavior:

```mermaid
graph TD
    User([User Prompt]) --> Router{Router Agent}
    Router -->|Retrieval Task| Retriever[Retriever Agent]
    Router -->|Coding Task| Coder[Code Agent]
    
    Retriever --> Aggregator[Aggregator Agent]
    Coder --> Aggregator
    
    Aggregator --> Validator{Validator Agent}
    Validator -->|Fails Check| Router
    Validator -->|Passes Check| Output([Final Guardrailed Answer])
    
    style Router fill:#f9f,stroke:#333,stroke-width:2px
    style Validator fill:#bbf,stroke:#333,stroke-width:2px
2. ReAct (Reasoning + Acting) Small Flow

For dynamic problem solving, I implement the ReAct paradigm to let LLMs use external tools iteratively:

Plaintext
 ┌─────────────┐       ┌──────────────┐       ┌───────────────┐
 │             │       │              │       │               │
 │   THOUGHT   ├──────►│    ACTION    ├──────►│  OBSERVATION  │
 │             │       │              │       │               │
 │ (Reasoning) │       │(Call Tool/APIs)      │ (Read Result) │
 └──────▲──────┘       └──────────────┘       └──────┬────────┘
        │                                            │
        └────────────────────────────────────────────┘
                (Loop until final answer is reached)
📈 Featured Professional Impact
🏎️ Toyota | Generative AI Engineer

Massive Scale: Architected production GenAI platforms serving 500,000+ enterprise users.

Big Data RAG: Built end-to-end Retrieval-Augmented Generation pipelines over 10M+ documents.

Advanced Orchestration: Standardized context exchange with Model Context Protocol (MCP) for multi-agent workflows.

🏥 Omnicell | AI/ML Engineer

High Throughput: Deployed pipelines serving 100K+ monthly predictions with sub-200ms P99 latency.

Vision & OCR: Developed computer vision solutions processing 100K+ images monthly at 92%+ accuracy.

🎓 Education
Master's Degree | University of Central Missouri, United States

🤝 Let's Build the Future of AI Together!

📫 Email: reddypraneeth066@gmail.com

💼 LinkedIn: @praneethkesarapu1906

🌐 Portfolio: praneethreddy.netlify.app


***

### Key Upgrades Included:
1. **The Typing Effect:** I used a dynamic SVG link at the very top. When a recruiter opens your GitHub profile, your titles will literally type out on the screen one letter at a time, just as you requested!
2. **For-The-Badge Icons:** I added the exact style of thick, solid badges you linked to for Python, Hugging Face, LangChain, LangGraph, MCP, and RAG. 
3. **Diagrams:** I included a native GitHub `mermaid` graph for the LangGraph agents and a clean ASCII block diagram for the ReAct flow. Recruiters *love* seeing visual representations of technical systems because it proves you actually know how to map out complex architecture.

Would you like me to help you set up or optimize your actual GitHub repository pins or a custom "About Me" description to go with this?
