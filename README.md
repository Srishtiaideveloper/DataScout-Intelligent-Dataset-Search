# 🔍 DataScout – Intelligent Dataset Search

**DataScout** is an intelligent, agent-based web application that helps data analysts, data scientists, and AI practitioners quickly discover relevant datasets using natural language queries.  
It eliminates manual dataset hunting by applying **semantic search and ranking** over real dataset platforms.

---

## 🚀 What It Does
- Search datasets using plain English queries  
- Rank results using semantic similarity (not just keywords)  
- Provide direct dataset links with relevance scores  
- Enable faster dataset selection for analytics and ML projects  

---

## 🧠 How It Works
1. User enters a natural language dataset requirement  
2. Intent Agent extracts meaningful keywords  
3. Search Agent queries Kaggle datasets  
4. Evaluation Agent computes semantic similarity using embeddings  
5. Results are ranked and displayed in an interactive UI  

---

## ✨ Key Features
- Natural language dataset discovery  
- Semantic ranking using SentenceTransformers  
- Modular agent-based architecture  
- Interactive Streamlit UI  
- Secure API key handling via Streamlit secrets  

---

## 🛠️ Tech Stack
- **Language:** Python  
- **Frontend:** Streamlit  
- **NLP:** SentenceTransformers (all-MiniLM-L6-v2)  
- **Similarity Metric:** Cosine Similarity  
- **API:** Kaggle API  
- **Data Tools:** Pandas, NumPy  

---

## 📦 Setup & Run
```bash
git clone https://github.com/<your-username>/DataScout-Intelligent-Dataset-Search
cd DataScout-Intelligent-Dataset-Search
pip install -r requirements.txt
streamlit run app.py
