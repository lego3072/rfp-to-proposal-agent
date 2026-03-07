# RFP-to-Proposal Agent

Extract requirements, score fit, assemble proposal drafts, and generate pricing-ready outputs with auditability.

## Run locally
```bash
pip install -r requirements.txt
uvicorn app.main:app --reload --port 8000
```

## Endpoints
- `/`
- `/docs-page`
- `/health`
- `/v1/public/config`
- `/llms.txt`
