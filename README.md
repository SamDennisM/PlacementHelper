# 🚀 Integrated Career Platform  

![Streamlit](https://img.shields.io/badge/Made%20with-Streamlit-FF4B4B?logo=streamlit&logoColor=white)  
![Python](https://img.shields.io/badge/Python-3.9%2B-blue?logo=python&logoColor=yellow)  
![LangChain](https://img.shields.io/badge/Powered%20by-LangChain-1E90FF?logo=chainlink&logoColor=white)  
![Agno](https://img.shields.io/badge/Agentic-AI%20Framework-purple)  
![License](https://img.shields.io/badge/License-MIT-green)  

> An **AI-powered career development suite** that integrates **Streamlit apps**,  
> **LangChain tools**, and the **Agno Agentic AI framework** for:  
> ✅ Resume optimization, ✅ Retrieval-based chat, ✅ Placement dashboards,  
> ✅ Interview simulations, and ✅ LLM evaluation metrics.  

---

## ✨ Features  

<details>
<summary><b>🤖 Agentic Resume Optimizer</b></summary>  

- ATS-powered resume analysis using **Groq LLMs (Gemma, LLaMA, Mixtral)**.  
- Upload **PDF/DOCX resumes** → Get compatibility score & improvement suggestions.  
- Keyword & missing skill analysis (tech skills, tools, soft skills).  
- **Offline fallback mode** when API unavailable.  

</details>

<details>
<summary><b>🐋 DeepSeek RAG Chatbot</b></summary>  

- Local **RAG agent** using **DeepSeek reasoning models**.  
- Embeddings: **Google Generative AI Embeddings**.  
- Vector DB: **ChromaDB**.  
- Web fallback: **DuckDuckGo search via Agno Tools**.  
- Interactive Streamlit **chat UI with history**.  

</details>

<details>
<summary><b>🎓 Placement Dashboard</b></summary>  

- Role-based login: **Admin | Placement Officer | Student**.  
- KPIs: Placement rate, avg package, total students, placed students.  
- **Interactive analytics** with Plotly charts & timelines.  
- Scrolling **news ticker** for live placement updates.  

</details>

<details>
<summary><b>💬 AI Interview Assistant</b></summary>  

- Resume + Job Role → Generates **custom interview questions**.  
- AI evaluates answers with: **scores, strengths, missed points, suggestions**.  
- Powered by **Google Gemini API**.  
- Modern chat-style UI with real-time feedback.  

</details>

<details>
<summary><b>📊 Evaluation Dashboard</b></summary>  

- Unified LLM evaluation across modules.  
- Metrics: **Exact Match, F1, ROUGE-1, ROUGE-L, Semantic Similarity**.  
- Visualization: **Bar charts & Radar plots**.  
- Logs results in `evaluation_log.csv`.  

</details>

---

## 🏠 Unified Navigation  

Launch `home.py` → Choose between all apps in one place:  

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
