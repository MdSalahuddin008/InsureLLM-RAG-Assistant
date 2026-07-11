# InsureLLM RAG Assistant

A retrieval-augmented generation assistant for InsureLLM, an insurance technology company. The assistant answers employee questions using company, product, contract, and employee knowledge-base documents.

## Files

- `vector_database_setup.ipynb` - embedding and vector database setup.
- `rag_with_langchain.ipynb` - LangChain-based RAG workflow.
- `rag_evaluation.ipynb` - evaluation workflow.
- `advanced_rag_assistant.ipynb` - advanced RAG with chunking, reranking, and query rewriting.
- `app.py` - Gradio app entry point.
- `implementation/` - core ingestion and answer modules.
- `pro_implementation/` - advanced implementation modules.
- `evaluation/` - evaluation scripts and test data.
- `knowledge-base/` - markdown source documents used by the RAG system.
- `requirements.txt` - Python dependencies from the course environment.

## Setup

```bash
pip install -r requirements.txt
python app.py
```

Generated vector databases are intentionally excluded. Rebuild them from `knowledge-base/` using the ingestion notebooks or scripts.
