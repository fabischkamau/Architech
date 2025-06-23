# Architech Monorepo

This repository contains both the frontend (Next.js/React) and backend (FastAPI/Python) for the Architech AI project.

## Structure

- `frontend/` — Next.js 14 app (React, TypeScript)
- `backend/` — FastAPI Python app

---

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18+ recommended)
- [pnpm](https://pnpm.io/) (for frontend)
- [Python 3.13+](https://www.python.org/downloads/)
- [uv](https://github.com/astral-sh/uv) (for backend, or use pip if preferred)

---

### Frontend Setup

```sh
cd frontend
pnpm install
pnpm dev
```

Visit [http://localhost:3000](http://localhost:3000) in your browser.

---

### Backend Setup

```sh
cd backend
uv install
fastapi dev main.py
```

The FastAPI server will run at [http://localhost:8000](http://localhost:8000).

---

### Environment Variables

Copy `.env.example` to `.env` in both `frontend/` and `backend/` and fill in your secrets.

---

## Development

- Frontend: edit files in `frontend/app/`, `frontend/components/`, etc.
- Backend: edit files in `backend/agents/`, `backend/orchestrator/`, etc.

---

##
