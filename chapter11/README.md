# Chapter 11 — Multi-Agent Orchestration & Hierarchical Crews
### Manager Agents, Sub-Crews, Fault Tolerance, and Observability

## Files
chapter11/

├── manager_agent.py        ← Manager with ReAct loop

├── sub_crews/

│   ├── finance_crew.py     ← Finance specialist crew

│   ├── legal_crew.py       ← Legal specialist crew

│   ├── market_crew.py      ← Market research crew

│   └── tech_crew.py        ← Tech audit crew

├── conflict_resolver.py    ← 3-stage conflict resolution

├── fault_tolerance.py      ← Failure classification + recovery

├── synthesiser.py          ← Final report synthesiser

├── observability.py        ← Full observability stack

└── due_diligence.py        ← Complete M&A system demo

## What You Learn
- Flat vs hierarchical multi-agent architecture
- Manager agent decision loop
- Parallel sub-crew execution
- Conflict resolution pipeline
- Fault tolerance and recovery tree
- Synthesiser agent patterns
- Enterprise-scale orchestration

## Setup
```bash
pip install crewai langchain-openai celery redis
```

## Run
```bash
python due_diligence.py
# Input: "Ola Electric M&A due diligence"
# Output: Full board-ready report in ~4 minutes
```
