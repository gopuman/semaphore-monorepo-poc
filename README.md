# Semaphore CI/CD POC: Turbo Monorepo (Python + Next.js)

This is a monorepo to demonstrate a CI/CD pipeline for a Turbo-based architecture using Next.js and Python.

## Structure
- `apps/web`: Next.js frontend
- `apps/api`: Python FastAPI backend
- `packages/ui`: Shared frontend components
- `packages/utils`: Shared utility functions

## Quickstart

```bash
npm install 
npx turbo run dev
```

To run backend:

```bash
cd apps/api
uvicorn main:app --reload
```