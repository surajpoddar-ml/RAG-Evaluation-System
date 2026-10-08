# RAG-Tutorials

An end-to-end collection of Retrieval-Augmented Generation (RAG) tutorials, pipelines, and evaluation workflows.

## Features

- **Multi-Format Data Ingestion**: Load PDF, TXT, CSV, Excel, Word, and JSON documents via LangChain document loaders.
- **Embedding Pipeline**: Chunk text with recursive character splitting and generate dense representations using `sentence-transformers` (`all-MiniLM-L6-v2`).
- **Vector Storage & Persistence**: Local vector storage and top-k similarity search powered by FAISS.
- **RAG Generation**: Query-context synthesis and response summarization using Groq LLM integration.
- **Comprehensive Notebooks & Tutorials**:
  - Document loaders and parser exploration (`notebook/`)
  - Typesense hybrid/vector search (`typesense.ipynb`)
  - RAG evaluation and retrieval metrics (`1-rag_evaluation.ipynb`)
  - Agentic RAG decision workflows with LangGraph (`agenticrag/1-agenticrag.ipynb`)
  - Vectorless RAG crash course (`PageIndex_Vectorless_RAG_CrashCourse (1).ipynb`)

## Getting Started

### 1. Installation
Clone the repository and install required dependencies:
```bash
pip install -r requirements.txt
```

### 2. Environment Setup
Configure your API keys in a `.env` file:
```env
GROQ_API_KEY=your_groq_api_key
```

### 3. Run the Pipeline
Execute the main application to load documents, index vectors, and run sample queries:
```bash
python app.py
```
