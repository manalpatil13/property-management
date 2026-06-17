# Estate — Property Rental Management System

**Version 3.0** — Image upload & redesigned dashboard

This version brings the interface to life. Property owners can now upload
photos for each listing, and the whole app has been redesigned into a clean,
modern dashboard with at-a-glance portfolio stats.

## What's new in v3
- Image upload — photos saved to `static/uploads/` and shown on cards
- Redesigned "Estate" dashboard: forest + brass theme, Bricolage + Inter
- Stats band: total properties, available, rented, monthly rent
- Image-led property cards with status badges
- Demo account seeded with sample properties

## Carried over
- JWT authentication & per-user data (v2)
- Full property CRUD on FastAPI + SQLite (v1)

## Stack
- Backend: Python, FastAPI, SQLAlchemy
- Auth: JWT, bcrypt
- Database: SQLite
- Frontend: HTML + CSS

## Run it
```bash
python -m venv .venv
.venv\Scripts\activate        # Windows
pip install -r requirements.txt
uvicorn main:app --reload
```
Open http://127.0.0.1:8000
Demo login: **demo@rental.app** / **demo1234**

## Roadmap
- v4 — Tenants, agreements & payment records (full system)