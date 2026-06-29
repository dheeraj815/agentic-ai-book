# Chapter 10 — Memory Systems & Persistent Agent State
### Four-Layer Memory Architecture for Production Systems

## Files
chapter10/

├── memory/

│   ├── context_window.py   ← Layer 1: Context management

│   ├── vector_memory.py    ← Layer 2: ChromaDB retrieval

│   ├── entity_memory.py    ← Layer 3: Entity extraction

│   └── episodic_memory.py  ← Layer 4: Episode storage

├── orchestrator.py         ← Memory orchestrator

├── memory_crew.py          ← Memory-augmented CrewAI

└── memory_api.py           ← User-facing memory API

## What You Learn
- Four-layer memory stack
- Context window management strategy
- Vector memory write and retrieval flow
- Entity memory extraction and recall
- Episodic memory schema
- Memory orchestrator assembly
- Production memory guardrails

## Setup
```bash
pip install chromadb langchain-chroma spacy
python -m spacy download en_core_web_sm
```

## Run
```bash
python orchestrator.py    # Full memory system demo
python memory_api.py      # Memory management API
```
