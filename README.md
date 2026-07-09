# ExoRAG-Bot

ExoRAG-Bot is a local Retrieval-Augmented Generation (RAG) pipeline designed to act as an offline conversational assistant for analyzing clinical literature. While originally configured to parse and synthesize complex data regarding **exosomes**, the architecture is entirely modular—allowing users to swap out the document directory to analyze any scientific or technical field.

"Local AI chatbot that lets you chat with your own scientific PDFs. Built with LangChain, Chroma DB, and Ollama to run completely offline (making it ideal for proprietary or pre-publication research.)".

## 📦 How to Install
1. **Set Up a Virtual Environment & Dependencies:**
   Activate the environment
      - pip install langchain-core langchain-community langchain-ollama chromadb pypdf

3. **Install & run Ollama:**
      - ollama pull llama3.2:3b
      - ollama pull nomic-embed-text

5. **How to run:**
      - python Test_AI.py
      - "Chat with your data"
   





