# Solomon

**AI-Powered Coding Mentor**  
**Demo (coming soon)**  
**Solomon GPT Link (planned):** Will be integrated directly into the dashboard UI

## Overview

`Solomon` is a full-stack AI mentor application designed to teach developers how to code through guided conversation, not quick fixes. Users can ask questions, debug code, and select both a learning style and language focus. The system responds with thoughtful, mode-specific guidance powered by OpenAI.

Built with React and Tailwind on the frontend, and FastAPI and PostgreSQL on the backend, Solomon is architected to deliver clean, responsive UX and developer-focused AI logic.

## Features

- Mentor Modes: Select how you want to learn (e.g., The Architect, Beginner Guide, Debug Pro)
- Language Context: Choose a language focus (e.g., Python, React)
- Question Interface: Ask coding questions and receive AI feedback
- Session Memory: Save and review past answers (coming soon)
- Modern Dark UI: Consistent design across pages with navbar, route-based layout
- Production Deployment Ready: Vercel for frontend; Render or Fly.io for backend

## Technologies

### Frontend
- React – Component-based frontend framework
- Vite – Lightweight build and dev environment
- Tailwind CSS – Utility-first CSS framework
- React Router – Handles client-side routing
- TypeScript – Strongly typed component structure

### Backend (coming soon)
- FastAPI – Python web framework for fast APIs
- PostgreSQL – Relational DB to store users and sessions
- SQLAlchemy – ORM for managing database models
- Pydantic – Type-safe request/response validation
- JWT (python-jose) – Token-based authentication
- OpenAI API – AI-powered learning guidance
- Alembic – (Planned) Schema migrations

### Deployment
- Vercel – Frontend deployment with CI/CD
- Render (or Fly.io) – Backend and PostgreSQL hosting
- GitHub – Source control and version tracking

## Skills Demonstrated

- Full-stack application structure and deployment
- Role-based AI persona logic via OpenAI
- Type-safe Python and TypeScript workflows
- Tailwind-based dark-mode UI with reusable layout
- REST API design with FastAPI
- Frontend/backend monorepo coordination
- Clean Git and project organization

## Usage Instructions

### 1. Development Setup

```bash
git clone https://github.com/Cyberbot777/professor-solomon.git
cd professor-solomon

# Frontend
cd frontend
npm install
npm run dev

# Backend (coming soon)
cd ../backend
# Set up virtual environment and install dependencies
```

- Create `.env` files for secrets like:
  - `OPENAI_API_KEY`
  - `DATABASE_URL`
  - (Optional future: JWT_SECRET, etc.)

## Author

- Richard Hall

## Timeline

- Created: June 19, 2025  
- Last Updated: June 20, 2025
