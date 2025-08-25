# 🚀 Integrated Career Platform  

![Streamlit](https://img.shields.io/badge/Made%20with-Streamlit-FF4B4B?logo=streamlit&logoColor=white)  
![Python](https://img.shields.io/badge/Python-3.9%2B-blue?logo=python&logoColor=yellow)  
![LangChain](https://img.shields.io/badge/Powered%20by-LangChain-1E90FF?logo=chainlink&logoColor=white)  
![License](https://img.shields.io/badge/License-MIT-green)  

> An **AI-powered career development suite** that integrates resume optimization, retrieval-based chat, placement dashboards, interview simulations, and evaluation metrics — all in one **Streamlit application**.  

---

## ✨ Features  

<details>
<summary><b>🤖 Agentic Resume Optimizer</b></summary>  

- Upload **PDF/DOCX resumes** and compare against job descriptions.  
- AI-driven **ATS compatibility scoring** with keyword & skill analysis.  
- Offline fallback mode for basic keyword matching.  
- Resume optimization using **Groq LLMs (Gemma, LLaMA, Mixtral)**.  

</details>

<details>
<summary><b>🐋 DeepSeek RAG Chatbot</b></summary>  

- Local **RAG agent** powered by **DeepSeek** models.  
- Upload PDFs or enter URLs to build a **ChromaDB knowledge base**.  
- Uses **Google AI embeddings** & **DuckDuckGo web search**.  
- Toggleable RAG & Web Search modes with interactive chat.  

</details>

<details>
<summary><b>🎓 Placement Dashboard</b></summary>  

- Secure login with **role-based access** (admin, officer, student).  
- Real-time KPIs: placement rate, packages, student stats.  
- Visualizations with **Plotly**: department-wise, package distributions, company insights.  
- News ticker with placement highlights.  

</details>

<details>
<summary><b>💬 AI Interview Assistant</b></summary>  

- Upload/paste resume & specify job role.  
- Generates **resume-specific & job-role-specific questions**.  
- AI evaluates answers with scores, missed points, strengths, suggestions.  
- Interactive **chat-style interview simulation**.  

</details>

<details>
<summary><b>📊 Evaluation Dashboard</b></summary>  

- Unified **LLM evaluation framework**.  
- Metrics: **Exact Match, F1, ROUGE-1, ROUGE-L, Semantic Similarity**.  
- Logs results in `evaluation_log.csv`.  
- Visualizations: **Bar & Radar charts** for comparisons.  

</details>

---

## 🏠 Unified Navigation  

The `home.py` module provides a **central hub** to access all apps:  

- 🤖 Resume Optimizer  
- 🐋 DeepSeek RAG Chatbot  
- 🎓 Placement Dashboard  
- 💬 Interview Assistant  
- 📊 Evaluation Dashboard  

---

## ⚙️ Installation  

```bash
# Clone the repo
git clone https://github.com/your-username/integrated-career-platform.git
cd integrated-career-platform

# Create virtual environment
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
