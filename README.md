# niron-rag-demo

# RAG Demo — Secure Document Q&A

Live demo: [Launch →](https://biflowlabs.github.io/niron-rag-demo)

## Stack
- Retrieval: keyword scoring with TF-style overlap matching
- Generation: Claude API (Anthropic claude-sonnet-4)
- Chunking: 400-word overlapping windows (50-word overlap)
- Deployment: static HTML — no backend required

## Note on production RAG
My production RAG system (built for a prior employer) uses
Docker + Qdrant vector DB + OpenAI embeddings + n8n orchestration
and cannot be shared publicly due to proprietary institutional data.
This demo illustrates the same core retrieval → generation pipeline
using sample Niron-relevant documents.
