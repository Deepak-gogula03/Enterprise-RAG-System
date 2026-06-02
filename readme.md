# 🚀 Enterprise RAG System using LangChain, ChromaDB, Sentence Transformers & Groq Llama 3.3

A complete end-to-end Retrieval-Augmented Generation (RAG) system built using LangChain, ChromaDB, Sentence Transformers, and Groq Llama 3.3. This project demonstrates the implementation of modern AI-powered document intelligence pipelines capable of processing documents, generating semantic embeddings, performing vector-based retrieval, and producing context-aware responses through advanced retrieval workflows.

Unlike basic RAG implementations, this project showcases the evolution of Retrieval-Augmented Generation systems from Traditional RAG to Enhanced RAG and Advanced RAG while incorporating explainability, confidence scoring, streaming responses, query history tracking, and context summarization.

---

# 📖 Overview

Retrieval-Augmented Generation (RAG) is one of the most important architectural patterns in modern Generative AI applications.

Large Language Models possess powerful reasoning capabilities but cannot directly access proprietary documents, organizational knowledge bases, PDFs, research papers, or dynamically changing information.

This project solves that challenge by combining semantic search, vector databases, embeddings, and large language models to build an intelligent knowledge retrieval system capable of providing grounded and explainable responses.

The system processes custom documents, converts them into vector embeddings, stores them within ChromaDB, retrieves relevant context through semantic similarity search, and generates accurate answers using Groq's Llama 3.3 70B model.

---

# 🎯 Project Objective

The primary objective of this project is to design and implement a complete Retrieval-Augmented Generation workflow capable of transforming static document repositories into intelligent AI-powered knowledge systems.

The project focuses on:

* Building reusable document ingestion pipelines
* Implementing semantic search using vector embeddings
* Designing modular retrieval workflows
* Integrating Large Language Models with retrieval systems
* Improving answer quality through context grounding
* Reducing hallucinations using retrieval augmentation
* Providing explainable and trustworthy AI responses

---

# 💼 Business Impact

Organizations generate massive volumes of unstructured information including PDFs, reports, documentation, research papers, manuals, and internal knowledge repositories.

Traditional keyword-based search systems often fail to retrieve relevant information because they depend on exact keyword matching.

This project demonstrates how Retrieval-Augmented Generation can transform static document repositories into intelligent knowledge systems capable of delivering context-aware responses with high retrieval accuracy.

### Potential Real-World Applications

🏢 Enterprise Knowledge Bases

📚 Internal Documentation Search

⚖️ Legal Document Analysis

🏥 Healthcare Knowledge Retrieval

📑 Research Paper Assistants

🎓 Educational Knowledge Platforms

💬 Customer Support Systems

📊 Financial Document Intelligence

---

# 📚 Knowledge Base Information

This project is designed to work with custom document collections and demonstrates how enterprise knowledge can be transformed into searchable AI systems.

Supported Sources:

- PDF Documents
- Text Files
- Multi-Document Directories
- Knowledge Repositories

The ingestion pipeline automatically extracts text, metadata, and contextual information before preparing the documents for vectorization and retrieval.

---

# ⚙️ Custom Components Developed

### 🧠 EmbeddingManager

Responsible for:

- Embedding Generation
- Batch Processing
- Semantic Encoding
- Vector Creation

### 🗄️ VectorStore

Responsible for:

- ChromaDB Integration
- Persistent Storage
- Similarity Search
- Metadata Management

### 🔍 RAGRetriever

Responsible for:

- Query Processing
- Similarity Retrieval
- Top-K Search
- Score Filtering
- Context Ranking

---

# 🌟 Why This Project Stands Out

Unlike most introductory RAG projects, this implementation goes beyond simple retrieval and answer generation.

The project demonstrates:

- Traditional RAG
- Enhanced RAG
- Advanced RAG
- Confidence Scoring
- Source Attribution
- Streaming Responses
- Query History Tracking
- Context Summarization
- Performance Monitoring
- Modular Retrieval Architecture

These capabilities closely resemble the architecture used in modern enterprise-grade AI knowledge systems.

---

# 📊 Project Metrics

| Metric                   | Value                      |
| ------------------------ | -------------------------- |
| AI Framework             | LangChain                  |
| Embedding Model          | all-MiniLM-L6-v2           |
| Embedding Framework      | Sentence Transformers      |
| Vector Database          | ChromaDB                   |
| LLM Provider             | Groq                       |
| Language Model           | llama-3.3-70b-versatile    |
| Retrieval Strategy       | Semantic Similarity Search |
| RAG Variants Implemented | 3                          |
| Custom Classes Developed | 3                          |
| Package Manager          | UV                         |
| Development Environment  | Jupyter Notebook           |

---

# 🏗️ System Architecture

<img width="1536" height="1024" alt="ChatGPT Image Jun 2, 2026, 09_10_41 PM" src="https://github.com/user-attachments/assets/53d775ee-3e9a-4c3a-9411-cf451f6996ca" />

The architecture follows a complete Retrieval-Augmented Generation workflow consisting of document ingestion, embedding generation, vector storage, semantic retrieval, context construction, answer generation, and response optimization.

---

# ✨ Key Features

## 📥 Data Ingestion Pipeline

* Multi-format document loading
* PDF processing and parsing
* Metadata extraction
* Text preprocessing
* Directory-level document ingestion

Supported Loaders:

* TextLoader
* DirectoryLoader
* PyPDFLoader
* PyMuPDFLoader

---

## 🧠 Embedding Pipeline

* Semantic embedding generation
* Sentence Transformer integration
* Batch processing support
* Vector representation generation

Embedding Model:

```text
all-MiniLM-L6-v2
```

Custom Component:

```text
EmbeddingManager
```

---

## 🗄️ ChromaDB Vector Storage

* Persistent vector storage
* Metadata support
* Similarity indexing
* Efficient retrieval architecture

Custom Component:

```text
VectorStore
```

Vector Database:

```text
ChromaDB
```

---

## 🔍 Semantic Retrieval Pipeline

Custom retrieval system capable of:

* Similarity Search
* Top-K Retrieval
* Score Threshold Filtering
* Metadata Retrieval
* Context Ranking

Custom Component:

```text
RAGRetriever
```

---

## 💬 Context-Aware Answer Generation

* Retrieval grounded generation
* Context construction
* Prompt augmentation
* LLM-powered answer generation

Model:

```text
llama-3.3-70b-versatile
```

---

# ⚙️ End-to-End Workflow

### Step 1: Document Ingestion

Documents are loaded using LangChain document loaders and converted into a standardized format.

### Step 2: Text Processing

Raw documents are cleaned, processed, and prepared for embedding generation.

### Step 3: Embedding Generation

Documents are transformed into dense vector representations using Sentence Transformers.

### Step 4: Vector Storage

Generated embeddings are stored in ChromaDB for efficient similarity search.

### Step 5: Query Processing

User queries are converted into vector embeddings.

### Step 6: Semantic Retrieval

Relevant document chunks are retrieved using similarity search.

### Step 7: Context Construction

Retrieved documents are combined into contextual prompts.

### Step 8: Response Generation

Groq Llama 3.3 generates grounded responses using the retrieved context.

### Step 9: Advanced RAG Processing

Confidence scoring, source attribution, history tracking, and response optimization are applied.

---

# 🧬 RAG Pipeline Evolution

This project demonstrates the progression of Retrieval-Augmented Generation architectures.

---

## 🔹 Traditional RAG

Basic retrieval workflow:

```text
Query
   │
   ▼
Retriever
   │
   ▼
Context
   │
   ▼
LLM
   │
   ▼
Answer
```

Features:

* Semantic Retrieval
* Context Construction
* Answer Generation

---

## 🔹 Enhanced RAG

Additional Features:

* Source Citations
* Confidence Scoring
* Context Inspection
* Retrieval Evaluation

Benefits:

* Improved Transparency
* Better Explainability
* Reduced Hallucinations

---

## 🔹 Advanced RAG

Additional Features:

* Query History Tracking
* Streaming Responses
* Context Summarization
* Execution Time Monitoring
* Retrieval Analytics

Benefits:

* Better User Experience
* Improved Observability
* Production Readiness

---

# 🤖 Large Language Model Integration

### Provider

Groq

### Model

```text
llama-3.3-70b-versatile
```

### Why Groq?

* Extremely Fast Inference
* Low Latency
* Large Context Window
* Strong Reasoning Performance
* Production-Grade Deployment

---

# 🔬 Explainability & Evaluation Features

One of the strongest aspects of this project is its explainability layer.

### Confidence Scoring

Measures:

* Retrieval Quality
* Similarity Strength
* Context Relevance

### Source Attribution

Provides:

* Source Documents
* Supporting Context
* Retrieval Evidence

### Context Inspection

Allows retrieved context to be analyzed before answer generation.

---

# 📈 Performance Monitoring

The Advanced RAG Pipeline includes operational monitoring features such as:

* Retrieval Time
* Generation Time
* End-to-End Latency
* Retrieved Document Count
* Similarity Scores
* Confidence Scores

These metrics help evaluate both retrieval quality and overall system performance.

---

# 🛠️ Technology Stack

| Component               | Technology              |
| ----------------------- | ----------------------- |
| Programming Language    | Python                  |
| AI Framework            | LangChain               |
| LLM Provider            | Groq                    |
| Model                   | Llama 3.3 70B Versatile |
| Embeddings              | Sentence Transformers   |
| Embedding Model         | all-MiniLM-L6-v2        |
| Vector Database         | ChromaDB                |
| Document Processing     | PyMuPDF                 |
| Package Manager         | UV                      |
| Development Environment | Jupyter Notebook        |

---

# 📥 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/enterprise-rag-system.git
```

Move into the project directory:

```bash
cd enterprise-rag-system
```

Create UV Environment:

```bash
uv venv
```

Install Dependencies:

```bash
uv sync
```

---

# 🔐 Environment Configuration

Create a `.env` file:

```env
GROQ_API_KEY=YOUR_GROQ_API_KEY
```

---

# 📁 Project Structure

```text
Enterprise-RAG-System/
│
├── notebooks/
│   └── document.ipynb
│
├── data/
│   ├── pdf/
│   ├── text_files/
│   └── chroma_db/
│
├── screenshots/
│   ├── architecture.png
│   ├── ingestion_pipeline.png
│   ├── retrieval_pipeline.png
│   ├── enhanced_rag_output.png
│   └── advanced_rag_output.png
│
├── requirements.txt
├── pyproject.toml
├── uv.lock
├── README.md
└── .env.example
```

---

# 🌟 Project Highlights

* Built a complete end-to-end Retrieval-Augmented Generation architecture
* Implemented custom EmbeddingManager, VectorStore, and RAGRetriever components
* Integrated ChromaDB for persistent vector storage
* Implemented semantic similarity search using Sentence Transformers
* Developed Traditional, Enhanced, and Advanced RAG workflows
* Added confidence scoring and source attribution
* Implemented streaming responses and query history tracking
* Integrated Groq Llama 3.3 70B for high-speed inference
* Demonstrated production-oriented retrieval engineering concepts

---

# 💼 Real-World Applications

* Enterprise Search Systems
* AI Knowledge Assistants
* Internal Documentation Search
* Legal Document Intelligence
* Research Paper Retrieval
* Educational Assistants
* Customer Support Automation
* Financial Knowledge Systems

