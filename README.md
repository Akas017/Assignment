# Insurecure ETL + Redis + FastAPI + React

A sample implementation of an ETL pipeline with Redis caching, FastAPI endpoints, and a small React frontend.

## Quickstart (development)

1. Copy `.env.example` to `.env` and adjust values.
2. Run (requires Docker & Docker Compose):
   ```bash
   docker-compose up --build
   ```
3. Backend: http://localhost:8000
   Frontend: http://localhost:3000

## Contents
- backend/: FastAPI app, ETL modules, DB models
- frontend/: React app (minimal)
- infra/: docker-compose and DB init
- sample_data/: CSV and mock API response

## Notes
This repo is a scaffold. Customize as needed.
