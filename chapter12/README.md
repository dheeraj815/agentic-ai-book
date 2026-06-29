# Chapter 12 — Security, Guardrails & Safe Agent Deployment
### Prompt Injection, PII, HITL, Audit Trails, and Compliance

## Files
chapter12/

├── security/

│   ├── injection_defence.py  ← 3-layer prompt injection defence

│   ├── tool_sandbox.py       ← Role-based tool restriction

│   └── pii_redactor.py       ← PII detection and redaction

├── rate_limiting.py          ← Multi-level budget enforcement

├── hitl.py                   ← Human-in-the-Loop workflow

├── audit_trail.py            ← Immutable compliance audit log

├── middleware.py             ← Security middleware integration

└── security_checklist.md     ← Pre-production checklist

## What You Learn
- Agentic AI attack surface map
- 3-layer prompt injection defence
- Role-based tool capability matrix
- PII redaction pipeline
- Multi-level rate limiting
- Human-in-the-Loop approval workflow
- Compliance audit trail (SOC2, HIPAA, GDPR)

## Setup
```bash
pip install spacy presidio-analyzer presidio-anonymizer
python -m spacy download en_core_web_lg
```

## Run
```bash
python security/injection_defence.py  # Test injection defence
python hitl.py                        # Test approval workflow
python audit_trail.py                 # View audit logs
```
