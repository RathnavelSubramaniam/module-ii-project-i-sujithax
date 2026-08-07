[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/CtKjnZeu)
#  Medical Diagnosis Assistant using RAG

A Retrieval-Augmented Generation (RAG) based medical question-answering system built using **LLaMA-2**, **LangChain**, **Hugging Face Embeddings**, and **ChromaDB**. The system retrieves relevant information from the **Merck Manual of Diagnosis & Therapy** to generate accurate, context-aware medical responses.

##  Features
- Medical Question Answering using LLaMA-2
- Retrieval-Augmented Generation (RAG)
- Semantic Search with ChromaDB
- Hugging Face Embeddings
- Groundedness & Relevance Evaluation

##  Tech Stack
- Python
- LLaMA-2
- LangChain
- Hugging Face
- ChromaDB
- PyMuPDF
- Pandas

##  Dataset
- **Merck Manual of Diagnosis & Therapy** (Medical Diagnosis Manual)

##  Workflow
1. Load Medical PDF
2. Split into Chunks
3. Generate Embeddings
4. Store in ChromaDB
5. Retrieve Relevant Context
6. Generate Answers using LLaMA-2
7. Evaluate Responses

##  Sample Queries
- Sepsis management protocol
- Appendicitis symptoms and treatment
- Causes and treatment of patchy hair loss
- Traumatic brain injury treatment

---
