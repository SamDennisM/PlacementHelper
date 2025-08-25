<h1 align="center">🚀 Integrated Career Platform</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Made%20with-Streamlit-FF4B4B?logo=streamlit&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3.9%2B-blue?logo=python&logoColor=yellow" />
  <img src="https://img.shields.io/badge/Powered%20by-LangChain-1E90FF?logo=chainlink&logoColor=white" />
  <img src="https://img.shields.io/badge/Agentic-AI%20Framework-purple" />
  <img src="https://img.shields.io/badge/License-MIT-green" />
</p>

<p align="center">
  One platform for <b>Resume Optimization</b>, <b>RAG Chat</b>,  
  <b>Interview Practice</b>, and <b>Career Analytics</b>.  
</p>
---

## 📹 Demo  

Check out the walkthrough video of the platform here:  

[![Watch the Demo](https://img.shields.io/badge/▶️%20Watch-Demo-red?style=for-the-badge)](https://drive.google.com/file/d/1G0AIWdeEvlrFFnaopj7z5lCUTRZG9yIS/view?usp=sharing)

---

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
