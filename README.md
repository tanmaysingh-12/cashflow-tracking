# cashflow-tracking
Author: Tanmay Singh

## What this project does
A personal finance tracker that allows users to log monthly income and expenses,
categorise spending, split bills with others, and visualise spending trends.

## Domain
Personal Finance / Budgeting

## Stack
- **Backend:** Python + Flask, containerised with Docker
- **Frontend:** React + Tailwind (Week 5)
- **Storage:** SQLite + Redis caching (Week 4)

## Running the backend
```bash
cd backend
docker build -t my-stub .
docker run -p 8000:8000 -v $(pwd)/data:/data my-stub
```

## Endpoints
| Method | Route | Description |
|--------|-------|-------------|
| GET | /health | Health check |

## Linked Issues
- #1 feat: containerize backend stub
- #2 feat: build FastAPI backend
- #3 feat: build React frontend
