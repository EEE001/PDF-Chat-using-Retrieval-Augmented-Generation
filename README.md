# 📄 PDF Chat using Retrieval-Augmented Generation (RAG)

## 🔍 Overview
This project implements a **PDF-based question answering system** using **Retrieval-Augmented Generation (RAG)**.  
It enables users to ask questions over document content by retrieving relevant text passages and generating **context-aware answers** using a large language model.

The project demonstrates an **end-to-end RAG pipeline** for document understanding and knowledge-grounded question answering.

---

## ⚙️ Key Features
- Supports PDF and DOCX document ingestion
- Text extraction and chunking
- Semantic embeddings using transformer-based models
- Vector similarity search for relevant context retrieval
- Retrieval-Augmented Generation for grounded answers
- Jupyter Notebook–based implementation for easy experimentation

---

## 🧠 RAG Workflow
1. Load and parse documents from the dataset folder  
2. Split documents into text chunks  
3. Generate embeddings for each chunk  
4. Retrieve the most relevant chunks for a user query  
5. Augment the query with retrieved context  
6. Generate a final answer using an LLM  

---

## 🗂️ Repository Structure
pdf-chat-rag/
├── PDF_Chat_using_Retrieval_Augmented_Generation.ipynb
├── dataset/
│ ├── README.md
│ ├── Company_GreenFields BioTech.docx
│ ├── Company_QuantumNext Systems.docx
│ ├── Company_TechWave Innovations.docx
│ ├── GreenGrow Innovations_Company History.docx
│ └── GreenGrow's EcoHarvest System_A Revolution in Farming.pdf
├── requirements.txt
└── README.md
