# AI-Powered-News-Fact-Checking-Misinformation-Detection

# 🧠 AI-Powered Fake News Detector

This project is a Retrieval-Augmented Generation (RAG) pipeline for fake news detection using Wikipedia, LangChain, FAISS, and GPT-4o. It evaluates political claims (from the LIAR dataset) and news articles (via URL) for credibility in real time.


## 📌 Features

- 🧾 Fact-checks political/news claims using Wikipedia and GPT-4o
- 🌐 Supports URL input with article text extraction (via newspaper3k)
- 🔍 Uses LangChain + FAISS for semantic search
- 📊 Evaluates using LIAR dataset with accuracy, precision, recall, F1-score


## 🛠️ Tech Stack

| Component     | Description |
|---------------|-------------|
| Python        | Programming language |
| LangChain     | RAG pipeline management |
| GPT-4o        | LLM for reasoning |
| FAISS         | Vector store for semantic retrieval |
| Wikipedia     | Source of verified knowledge |
| Newspaper3k   | URL content extraction |
| LIAR Dataset (Link [https://www.kaggle.com/datasets/doanquanvietnamca/liar-dataset]) | Real-world labeled claims for benchmarking | 


## 📈 Sample Evaluation (on LIAR Test Subset)
yaml
Copy
Edit
Accuracy: 0.72
Precision: 0.69
Recall: 0.85
F1 Score: 0.76

## 🔧 What This Tool Does
📰 User submits a news link
📄 AI extracts the main article content
🧠 GPT-4o + RAG pipeline analyzes the text
✅ System returns a verdict: Real, Fake, or Potentially Misleading
💬 Accompanied by a clear, concise explanation

