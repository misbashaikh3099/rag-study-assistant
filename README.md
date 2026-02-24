# RAG Study Assistant — Operating Systems

This project implements a Retrieval-Augmented Generation (RAG) system for answering questions from Operating Systems course materials.

---

## Prerequisites

Before running the project, ensure you have:

* Python 3.10 or higher
* VS Code or Jupyter Notebook
* Internet connection (for first-time model download)

---

## Dependencies

The following Python libraries are required:

* langchain
* chromadb
* sentence-transformers
* pdfplumber
* transformers
* torch
* pandas
* matplotlib

---

## How to Install Packages

Open terminal in your project folder and run:

pip install langchain chromadb sentence-transformers pdfplumber transformers torch pandas matplotlib

---

## Dataset Setup

1. Create a folder named:

data

2. Place your Operating Systems PDF files inside the data folder.

---

## API Keys

This project runs completely locally and does **NOT require any API keys**.

---

## How to Run the Notebook

1. Open the project folder in VS Code.
2. Open the notebook:

rag_project.ipynb

3. Run cells sequentially from:

   * Part 1 → Data Loading
   * Part 2 → Baseline System
   * Part 3 → Experiments
   * Part 4 → Challenges
   * Part 5 → Final Results

---

## Expected Output

When the notebook runs successfully, it will:

* Extract text from PDFs
* Create embeddings
* Store data in ChromaDB
* Retrieve relevant document chunks
* Generate answers to user questions
* Display experiment comparison graphs

---

## Project Goal

The objective of this project is to demonstrate how different components of a RAG system — preprocessing, chunking, retrieval, and prompting — impact overall answer quality.

---

## Author

Misba Shaikh

