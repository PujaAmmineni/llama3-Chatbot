# Llama3 Chatbot with Ollama Integration

This project implements a chatbot using the **Llama3** language model integrated with **Ollama**. Built with Python, Flask, and LangChain, it delivers AI-powered conversational capabilities with a user-friendly interface.

![image alt](https://raw.githubusercontent.com/PujaAmmineni/llama3-Chatbot/64bed0e2d727b05ec86613badac04b3e206a12d6/Screenshot%20(1289).png)

---

## Features

- **Llama3 Integration**: Utilizes Llama3 for advanced natural language processing.
- **Flask Framework**: Lightweight web server for chatbot hosting.
- **Markdown-to-HTML Formatting**: Converts Markdown bold syntax to HTML for enhanced visual appeal.
- **Interactive Chat UI**: Simple, responsive interface for user interaction.
- **Error Logging**: Built-in error logging to ensure robust operation.

---

## Prerequisites

Before starting, ensure the following are installed:

1. Python 3.8 or higher.
2. Pip (Python package manager).
3. [Ollama CLI](https://ollama.ai/) installed and configured.
4. Required Python libraries:
   - `langchain_community`
   - `langchain_core`
   - `flask`
   - `logging`

---

## Installation

### Step 1: Clone the Repository
```bash
git clone https://github.com/PujaAmmineni/llama3-Chatbot.git

---
## Set Up a Virtual Environment
python -m venv venv
source venv/bin/activate    # On macOS/Linux
venv\Scripts\activate       # On Windows
---
ollama pull llama3
---

##  Running the Application
python app.py

!



