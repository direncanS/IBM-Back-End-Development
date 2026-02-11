# IBM Back-End Development (Python)

This repository tracks my progress through the IBM Back-End Development Professional Certificate and contains a growing Python backend project.

## What’s inside
- **FastAPI app** with a basic health endpoint
- **Tests** with pytest
- **Learning notes** organized by module/week

## Quickstart (local)
```bash
python -m venv .venv
# Windows PowerShell
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt -r requirements-dev.txt
python -m pytest -q
uvicorn app.main:app --reload

## Endpoints
- GET /health -> {"status": "healthy"}

## Docs
- Swagger UI: http://127.0.0.1:8000/docs

## Repo structure
- app/ FastAPI source code
- tests/ pytest tests
- docs/learning/ module/week notes
- docs/tracker/ progress tracking

