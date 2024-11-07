A sophisticated Retrieval Augmented Generation (RAG) system that combines vector and keyword-based search using LangChain's components (Qdrant vector store, BM25, and ensemble retrieval) to enhance document retrieval accuracy. Integrates Groq's powerful LLM through LangChain's interface to generate contextually relevant responses, supporting advanced question-answering capabilities with the retrieved documents.

**Objectives:**

1. Create a robust RAG system using Groq LLM
2. Implement multiple retrieval methods
3. Enable document processing and storage
4. Provide performance evaluation and visualization
5. Track experiments using MLflow

### **Implementation Steps:**

1. Setup Environment
2. Initialize Core Componennts
3. Process Document
4. Setup Retrieval System
5. Implement Workflow
6. Evaluate System

1. **Environment Setup**
    - Install required packages
    - Configure environment variables
    - Set up Groq API key

    2. **Core Components**
    - Initialize Groq LLM
    - Set up embeddings model
    - Configure MLflow tracking

    3. **Document Processing**
    - Implement document loading
    - Text splitting functionality
    - Document storage system

    4. **Retrieval System**
    - Configure Qdrant vector store
    - Implement BM25 retriever
    - Create hybrid retrieval system
    - Add reranking capability

    5. **Workflow Implementation**
    - Create RAG workflow class
    - Implement query routing
    - Set up response generation
    - Add error handling

    6. **Evaluation System**
    - Track performance metrics
    - Generate visualizations
    - Log experiments