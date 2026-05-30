# 🤖 Chatbot Projects

A collection of chatbot implementations built using **LangChain** and **LangGraph**, demonstrating different approaches to managing conversation history, memory, and agent workflows.

## 📂 Project Structure

### 1. Conversation History Chatbot

**Folder:** `1_CBwithConversationHistory`

A chatbot that maintains conversation context by passing previous interactions to the model, enabling more natural and coherent conversations.

### 2. Message History Chatbot

**Folder:** `2_CBwithmessageHistory`

A chatbot implementation that stores and retrieves chat message history, allowing persistent conversations across multiple user interactions.

### 3. LangGraph Chatbot with Tools

**Folder:** `3_CBLanngGraph`

A chatbot built using LangGraph that can interact with external tools and follow graph-based workflows for more advanced reasoning and task execution.

---

## 🚀 Technologies Used

* Python
* LangChain
* LangGraph
* OpenAI / Groq LLMs
* Jupyter Notebook

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/chatbot-projects.git
cd chatbot-projects
```

Create and activate a virtual environment:

```bash
python -m venv venv

# Windows
venv\Scripts\activate

# Linux / Mac
source venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Create a `.env` file and add your API keys:

```env
GROQ_API_KEY=your_key
OPENAI_API_KEY=your_key
LANGCHAIN_API_KEY=your_key
```

---

## 📚 Learning Objectives

This repository explores:

* Chat history management
* Conversation memory
* Context-aware chatbots
* LangChain integrations
* LangGraph workflows
* Tool calling with LLMs

---

## 🔒 Security

API keys and environment variables are stored in a `.env` file and are excluded from version control using `.gitignore`.

---

## 👨‍💻 Author

**Siddhant Jain**

Exploring Generative AI, LangChain, LangGraph, RAG Systems, and AI Agents.
