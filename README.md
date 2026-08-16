HR Resume Screening + RAG Chatbot

An AI-powered HR Resume Screening application that uses **Retrieval-Augmented Generation (RAG)** to analyze resumes and answer recruiter questions based on the uploaded resume data.

The application converts resumes into text, creates embeddings using Sentence Transformers, stores them in a FAISS vector database, retrieves the most relevant information, and uses an LLM to generate contextual answers.

## Features

- Upload and process candidate resumes in PDF format
- Extract text from resumes
- Split resume text into smaller chunks
- Generate vector embeddings using Sentence Transformers
- Store and search embeddings using FAISS
- Retrieve relevant resume information based on a query
- Generate answers using Groq LLM
- Streamlit-based user interface
- Ask recruiter-style questions about candidate resumes
