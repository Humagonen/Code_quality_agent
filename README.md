# Code_quality_agent

## Repo structure

```
code-quality-agent/
│
├─ backend/
│   ├─ main.py (FastAPI)
│   ├─ llm/
│   │   ├─ client.py      # LLM API calls
│   │   └─ prompt.py      # prompt template
│   ├─ analysis/
│   │   └─ quality.py     # scoring logic
│   ├─ github/
│   │   └─ push.py        # GitHub API logic
│
├─ frontend/
│   └─ app.py / react/
│
├─ .env.example
├─ requirements.txt
└─ README.md
```

