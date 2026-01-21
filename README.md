# Chat with arXiv Research Papers

## Overview

**Chat with arXiv Research Papers** is a Streamlit-based Retrieval-Augmented Generation (RAG) application developed to enable conversational interaction with academic research papers from **arXiv**. The application leverages **OpenAI GPT-4o** to generate intelligent, context-aware responses grounded directly in scholarly content.

This project aims to simplify the exploration and understanding of complex research papers by allowing users to query academic literature using natural language.

---

## Features

- Conversational interface for querying arXiv research papers  
- Retrieval-Augmented Generation (RAG) for accurate and source-aware responses  
- Integration with OpenAI GPT-4o  
- Interactive and user-friendly Streamlit interface  
- Access to a vast collection of scholarly articles  

---

## Tech Stack

- Python  
- Streamlit  
- OpenAI GPT-4o  
- arXiv API  
- Retrieval-Augmented Generation (RAG)

---

## Getting Started

### Prerequisites

- Python 3.8 or higher  
- OpenAI API key  

---

### Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/chat-with-arxiv.git
cd chat-with-arxiv


Install the required dependencies using the command below:

```bash
pip install -r requirements.txt
OpenAI API Configuration
To use this application, you must configure your OpenAI API key.

Create an account at OpenAI

Generate an API key from the dashboard

Set the API key as an environment variable

macOS / Linux
bash
Copy code
export OPENAI_API_KEY="your_api_key_here"
Windows (PowerShell)
powershell
Copy code
setx OPENAI_API_KEY "your_api_key_here"
Running the Application
Start the Streamlit application using the following command:

bash
Copy code
streamlit run chat_arxiv.py
Once the application is running, open the local URL provided by Streamlit in your browser to begin interacting with arXiv research papers.

Use Cases
Academic research and literature review

Rapid understanding of complex research papers

Exploration of topics in artificial intelligence and machine learning

Educational and learning assistance

Future Enhancements
Support for multiple LLM providers

Automated research paper summarization

Citation and reference export

Category-based paper filtering

Chat history persistence and bookmarking

