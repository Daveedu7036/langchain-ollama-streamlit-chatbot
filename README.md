# LangChain Ollama Streamlit Chatbot

This project is a local LLM-powered chatbot built using LangChain, Ollama (Gemma 2B model), and Streamlit.  
It demonstrates prompt chaining, output parsing, and LangSmith tracking integration.

## 🚀 Features
- Local LLM execution using Ollama
- Gemma 2B model integration
- Streamlit interactive UI
- Prompt templating with LangChain
- LangSmith tracing enabled
- Clean and minimal architecture

## 🛠 Tech Stack
- Python
- LangChain
- Ollama
- Streamlit
- Dotenv
  

## 📂 Project Structure

```
langchain-ollama-streamlit-chatbot/
│
├── app.py              # Main Streamlit application
├── req.txt             # Project dependencies
├── .env                # Environment variables (API keys, project config) (not pushed to GitHub)
├── .venv/              # Virtual environment (not pushed to GitHub)
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```
git clone https://github.com/your-username/langchain-ollama-streamlit-chatbot.git
cd langchain-ollama-streamlit-chatbot
```

### 2️⃣ Create Virtual Environment

```
python -m venv .venv
```

Activate it:

**Windows:**
```
.venv\Scripts\activate
```

**Mac/Linux:**
```
source .venv/bin/activate
```

### 3️⃣ Install Dependencies

```
pip install -r req.txt
```

### 4️⃣ Setup Environment Variables

Create a `.env` file and add:

```
LANGCHAIN_API_KEY=your_key_here
LANGCHAIN_PROJECT=your_project_name
```

---

## ▶️ Run the Application

Make sure Ollama is running locally.

```
streamlit run app.py
```

---



## 👨‍💻 Author

Sangati Daveedu

---
