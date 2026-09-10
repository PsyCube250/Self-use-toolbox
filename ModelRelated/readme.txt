Built a Persona-RAG conversational system using Qwen3-30B, LoRA fine-tuning, BGE embeddings, FAISS retrieval, memory routing, and persistent conversation history.

User Query
    │
    ▼
Memory Router
    │
 ┌──┴─────┐
 │         │
 ▼         ▼
History   FAISS
 Cache   Retrieval
 │         │
 └──┬─────┘
    ▼
Qwen3-30B + LoRA
    ▼
Persona Response
