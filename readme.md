# 💬 LangChain + Ollama + Streamlit Demo

This is a simple demo application that uses **LangChain**, **Ollama**, and **Streamlit** to build a local AI chatbot powered by the **Gemma** LLM. The app allows users to ask questions and receive responses from a locally running model through a web interface.

---

## 📦 Tech Stack

- [LangChain](https://www.langchain.com/)
- [Ollama](https://ollama.com/) (for running LLMs locally like `gemma3`)
- [Streamlit](https://streamlit.io/) (for the UI)
- [Python-dotenv](https://pypi.org/project/python-dotenv/) (for managing environment variables)

---

## 🚀 Getting Started

### 1. ✅ Prerequisites

- Python 3.8+
- [Ollama installed](https://ollama.com/download) and running
- `gemma3` model pulled via Ollama:
  ```bash
  ollama pull gemma3


### 2. 🛠️ Installation
Clone the repo and install the required dependencies:

git clone https://github.com/your-username/langchain-ollama-demo.git
cd langchain-ollama-demo

# Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install packages
pip install -r requirements.txt


### 3. 🔐 Environment Variables
Create a .env file in the project root and add:

LANGCHAIN_PROJECT=your_langchain_project_name
LANGCHAIN_API_KEY=your_langchain_api_key


### 4. ▶️ Run the App

streamlit run app.py
