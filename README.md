## About the project

This project demonstrates a RAG (Retrieval-Augmented Generation) pipeline using PDF documents, OpenAI embeddings, and Chroma vector store. Users can upload PDFs, which are split into chunks and embedded, then queried through a Streamlit interface. The app retrieves relevant text from the documents and provides answers using an LLM.

Key features:

- Load and split PDF documents into chunks
- Generate embeddings using OpenAI
- Store and query embeddings with Chroma
- Interactive query interface using Streamlit

## Technologies

[![LangChain](https://img.shields.io/badge/LangChain-angchain-blue?style=for-the-badge)](https://github.com/hwchase17/langchain)
[![ChromaDB](https://img.shields.io/badge/ChromaDB-orange?style=for-the-badge)](https://github.com/chroma-core/chroma)
[![PyPDF](https://img.shields.io/badge/PyPDF-red?style=for-the-badge)](https://github.com/py-pdf/PyPDF2)
[![Pandas](https://img.shields.io/badge/Pandas-lightgrey?style=for-the-badge)](https://pandas.pydata.org/)
[![Streamlit](https://img.shields.io/badge/Streamlit-orange?style=for-the-badge)](https://streamlit.io/)
[![Python-dotenv](https://img.shields.io/badge/Python--dotenv-green?style=for-the-badge)](https://pypi.org/project/python-dotenv/)

## How to use it?

1. Clone the repository:
```
git clone https://github.com/szidzse/langchain-pdf-rag.git
```

2. Open the project, then go to the 'app' folder:
```
cd app/
```

3. Make an image using Dockerfile:
```
docker build -t streamlit-app .
```

4. Run the application:
```
docker run -p 8501:8501 streamlit-app
```

5. Copy your OpenAI API key key and browse to a .pdf file then on the 'Generate' button.

---

<img width="2738" height="1398" alt="Screenshot From 2025-09-21 20-56-27" src="https://github.com/user-attachments/assets/cf4042c2-193a-4d76-b034-102c508ba52e" />
