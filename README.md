# 📄 AI_PDF_Chatbot_RAG

An AI-powered document question-answering system that enables users to upload PDF documents and ask natural language questions. The system retrieves the most relevant document sections using semantic search and generates context-aware answers using an open-source Large Language Model.

---

## 🚀 Features

- 📄 Upload PDF documents
- ✂️ Intelligent document chunking
- 🧠 Semantic embeddings using Sentence Transformers
- 🔍 Fast similarity search with FAISS
- 🤖 Context-aware answer generation using FLAN-T5
- ⚡ Fully offline RAG pipeline (No API Key Required)

---

## 🛠 Tech Stack

- Python
- Google Colab
- PyPDF
- LangChain
- Sentence Transformers
- FAISS
- Hugging Face Transformers
- FLAN-T5
- NumPy
- PyTorch

---

## 🏗 Architecture

```
                    PDF
                     │
                     ▼
              Read PDF
                     │
                     ▼
               Chunking
                     │
                     ▼
        Sentence Embeddings
                     │
                     ▼
             FAISS Index
                     │
                     ▼
         Retrieve Top-k Chunks
                     │
                     ▼
          Prompt Construction
                     │
                     ▼
              FLAN-T5 LLM
                     │
                     ▼
              Generated Answer
```

---

## 📌 Workflow

1. Upload a PDF document.
2. Extract text from each page.
3. Split the document into overlapping chunks.
4. Generate semantic embeddings using Sentence Transformers.
5. Store embeddings in a FAISS vector database.
6. Convert the user query into an embedding.
7. Retrieve the most relevant chunks.
8. Construct a prompt using the retrieved context.
9. Generate the final answer using FLAN-T5.

---

## 📂 Project Structure

```
Enterprise-Document-Intelligence-Assistant-RAG/
│
├── Enterprise_Document_Intelligence_Assistant_RAG.ipynb
├── README.md
├── requirements.txt
├── sample.pdf
└── assets/
```

---

## 📷 Demo

Example Question

```
What is this document about?
```

Example Response

```
The document describes an AI / Machine Learning Engineering Internship at Ivanti, including company information, responsibilities, qualifications, and required skills.
```

---

## 🎯 Future Improvements

- Streamlit Web Interface
- Multi-PDF Support
- Chat History
- Source Citation
- Hybrid Search (BM25 + FAISS)
- Llama 3 / Gemma Integration
- Deployment using Hugging Face Spaces

---

## 📚 Concepts Used

- Retrieval-Augmented Generation (RAG)
- Semantic Search
- Vector Databases
- Embedding Models
- Prompt Engineering
- Large Language Models (LLMs)

---

## 👨‍💻 Author

Naman Raj

M.Tech Data Science

National Institute of Technology Patna

An AI-powered document question-answering system that enables users to upload PDF documents and ask natural language questions. The system retrieves the most relevant document sections using semantic search and generates context-aware answers using an open-source Large Language Model.

---

## 🚀 Features

- 📄 Upload PDF documents
- ✂️ Intelligent document chunking
- 🧠 Semantic embeddings using Sentence Transformers
- 🔍 Fast similarity search with FAISS
- 🤖 Context-aware answer generation using FLAN-T5
- ⚡ Fully offline RAG pipeline (No API Key Required)

---

## 🛠 Tech Stack

- Python
- Google Colab
- PyPDF
- LangChain
- Sentence Transformers
- FAISS
- Hugging Face Transformers
- FLAN-T5
- NumPy
- PyTorch

---

## 🏗 Architecture

```
                    PDF
                     │
                     ▼
              Read PDF
                     │
                     ▼
               Chunking
                     │
                     ▼
        Sentence Embeddings
                     │
                     ▼
             FAISS Index
                     │
                     ▼
         Retrieve Top-k Chunks
                     │
                     ▼
          Prompt Construction
                     │
                     ▼
              FLAN-T5 LLM
                     │
                     ▼
              Generated Answer
```

---

## 📌 Workflow

1. Upload a PDF document.
2. Extract text from each page.
3. Split the document into overlapping chunks.
4. Generate semantic embeddings using Sentence Transformers.
5. Store embeddings in a FAISS vector database.
6. Convert the user query into an embedding.
7. Retrieve the most relevant chunks.
8. Construct a prompt using the retrieved context.
9. Generate the final answer using FLAN-T5.

---

## 📂 Project Structure

```
Enterprise-Document-Intelligence-Assistant-RAG/
│
├── Enterprise_Document_Intelligence_Assistant_RAG.ipynb
├── README.md
├── requirements.txt
├── sample.pdf
└── assets/
```

---

## 📷 Demo

Example Question

```
What is this document about?
```

Example Response

```
The document describes an AI / Machine Learning Engineering Internship at Ivanti, including company information, responsibilities, qualifications, and required skills.
```

---

## 🎯 Future Improvements

- Streamlit Web Interface
- Multi-PDF Support
- Chat History
- Source Citation
- Hybrid Search (BM25 + FAISS)
- Llama 3 / Gemma Integration
- Deployment using Hugging Face Spaces

---

## 📚 Concepts Used

- Retrieval-Augmented Generation (RAG)
- Semantic Search
- Vector Databases
- Embedding Models
- Prompt Engineering
- Large Language Models (LLMs)

---

## 👨‍💻 Author

Naman Raj

M.Tech Data Science

National Institute of Technology Patna
