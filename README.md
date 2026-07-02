# AI News Summarizer 📰

A LangGraph agent that searches the web for current news and returns clean, summarized answers, built on Groq for fast inference and Tavily for real-time search.

---

## What it does

Ask it about any current topic. It uses Tavily to search the live web, then a LangGraph flow processes and summarizes the results using Groq's LLaMA models, surfaced through a simple Streamlit UI.

---

## Tech Stack

| | |
|---|---|
| Agent Framework | LangGraph and LangChain |
| LLM | Groq (LLaMA) |
| Web Search | Tavily |
| Vector Store | FAISS |
| Frontend | Streamlit |

---

## Setup and Run

```bash
pip install -r requirements.txt
streamlit run app.py
```

You will need a Groq API key from console.groq.com and a Tavily API key from tavily.com.

---

## About the Developer

Built by Harsh M Singh, B.Tech CSE (Data Science), Lokmanya Tilak College of Engineering, Mumbai.

- GitHub: github.com/singh-105
- AI Intern at Deep Cytes

Feel free to connect, star the repo, or open an issue!
