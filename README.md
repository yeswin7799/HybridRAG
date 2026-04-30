# HybridRAG — Customer Complaint Classifier

A RAG system that classifies customer complaints using hybrid retrieval
(semantic search + keyword search) and LLM structured output.

## Tech Stack
- Python, FAISS, sentence-transformers (Semantic Search)
- scikit-learn TF-IDF (Keyword Search)
- Ollama + Mistral 7B (LLM Classification)
- Streamlit (UI)

## Dataset
Consumer Complaint Database (CFPB) — 49,949 complaints across 11 categories

## Progress
- [x] Step 1 — Data preprocessing
- [x] Step 2 — Semantic search (FAISS + all-MiniLM-L6-v2)
- [x] Step 3 — TF-IDF keyword search
- [ ] Step 4 — Hybrid retrieval
- [ ] Step 5 — LLM classification
- [ ] Step 6 — Streamlit UI
