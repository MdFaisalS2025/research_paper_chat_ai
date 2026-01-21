Chat with arXiv Research Papers
Overview

Chat with arXiv Research Papers is a Streamlit-based Retrieval-Augmented Generation (RAG) application that enables conversational interaction with academic research papers from arXiv. The application leverages OpenAI GPT-4o to generate intelligent, context-aware responses grounded in scholarly content.

This project simplifies the process of exploring and understanding complex research papers using natural language queries.

Features

Conversational interface for querying arXiv research papers

Retrieval-Augmented Generation (RAG) for accurate, source-aware responses

Integration with OpenAI GPT-4o

Interactive and lightweight Streamlit UI

Access to a vast collection of scholarly articles

Installation

Install the required dependencies:

pip install -r requirements.txt

OpenAI API Configuration

To use this application, you must configure your OpenAI API key.

Create an account at OpenAI

Generate an API key

Set the API key as an environment variable

macOS / Linux
export OPENAI_API_KEY="your_api_key_here"

Windows (PowerShell)
setx OPENAI_API_KEY "your_api_key_here"

Running the Application

Run the Streamlit application using the following command:

streamlit run chat_arxiv.py


Once the application is running, open the local URL provided by Streamlit in your browser to start interacting with arXiv research papers.

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
