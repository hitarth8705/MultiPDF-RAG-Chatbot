 Overview

This project is an AI-powered PDF Q&A application built with Streamlit and LangChain.
It allows users to upload PDF files and then ask natural language questions about their content. The app uses Google Generative AI (Gemini) for embeddings and conversational responses, storing vector data in a FAISS index for efficient retrieval.

 Tech Stack

Frontend: Streamlit

Backend: Python

Libraries:

PyPDF2
 – Extract text from PDF documents

LangChain
 – Text splitting, embeddings, and QA chains

FAISS
 – Vector database for semantic search

Google Generative AI (Gemini)
 – Embeddings + conversational model


 Features

 Upload multiple PDF files

 Extract text from PDFs

 Split text into chunks for processing

 Generate vector embeddings using Google’s Generative AI

 Semantic search powered by FAISS

💬 Ask questions in natural language and get context-aware answers

🖥️ Simple Streamlit UI with sidebar for file uploads
