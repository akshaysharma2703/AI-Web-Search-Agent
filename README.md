# 🔍 AI Web Search Agent

An AI-powered web search assistant built with **Python, Streamlit, LangChain, LangGraph, Groq, and Google Serper API**. The application performs real-time Google searches and generates accurate, context-aware responses through an interactive chat interface.

## 🚀 Features

- 🤖 AI-powered conversational assistant
- 🌐 Real-time web search using Google Serper API
- 💬 Context-aware conversations with LangGraph memory
- ⚡ Fast response generation using Groq LLM
- 🎨 Interactive Streamlit chat interface
- 🔒 Secure API key management using `.env`

## 🛠️ Tech Stack

- Python
- Streamlit
- LangChain
- LangGraph
- Groq API
- Google Serper API
- python-dotenv

## 📂 Project Structure

```
AI-Web-Search-Agent/
│── 1_qna_groq.py
│── .env
│── requirements.txt
└── README.md
```

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/AI-Web-Search-Agent.git
cd AI-Web-Search-Agent
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Create a `.env` file

```env
GROQ_API_KEY=your_groq_api_key
SERPER_API_KEY=your_serper_api_key
```

### 4. Run the application

```bash
streamlit run 1_qna_groq.py
```

## 📸 Demo

<img width="900" alt="Demo" src="https://via.placeholder.com/900x450?text=Add+Project+Screenshot+Here">

> Replace the image above with a screenshot of your application.

## 📖 How It Works

1. User enters a question.
2. The AI agent searches the web using Google Serper API.
3. Relevant search results are provided to the Groq LLM.
4. The model generates an accurate, context-aware response.
5. Conversation history is maintained using LangGraph memory.

## 📌 Future Improvements

- Multiple search providers
- PDF and document Q&A
- Voice input support
- Conversation export
- Multi-agent workflow
- Source citations
