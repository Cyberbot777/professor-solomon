# Solomon – AI Coding Mentor

**“Learn to code through wisdom, not shortcuts.”**
Solomon is your personal AI mentor — calm, knowledgeable, and human. Ask questions, debug code, or explore concepts through rich conversation. You’ll learn by thinking, not just copying.

## Meet Your Mentor: Professor Solomon

Professor Solomon is your calm and trusted guide — a seasoned mentor with a sharp mind and a steady hand.
He won’t give you answers, but he’ll help you find them.
Ask your question, explain your bug, or just say what’s confusing you. Then choose how you want to learn — whether through gentle guidance, direct debugging, or deep conceptual insight.
Solomon will meet you where you are — and push you one step further.

## Overview

Solomon is a full-stack educational web app that helps aspiring developers:
- Understand errors through guided AI feedback
- Learn coding concepts through short explanations
- Choose how they learn best via different “mentor modes”
- Select the programming language or topic they want to focus on

Unlike tools that solve problems for you, Solomon teaches you how to think like a developer — through questions, principles, and patient mentoring.

## Tech Stack

Frontend
- React (Vite)
- Tailwind CSS
- React Router

Backend
- FastAPI (Python)
- PostgreSQL
- JWT Authentication
- OpenAI API (GPT-3.5 turbo)

Deployment
- Vercel (frontend)
- Render (backend)

## Core Pages

/ - Home
- Branding + purpose
- “Meet Solomon” intro
- CTA to login or register

/register - Register
- Create account with name, email, password
- Redirects to dashboard

/login - Login
- Auth with JWT
- Local/session storage or cookie

/dashboard - Main App Interface
- Textarea input: paste code or question
- Choose learning mode from dropdown
- Choose language or topic from second dropdown
- Output section with AI-guided response
- Option to save session

/session/:id (optional)
- Review saved conversations

## Mentor Modes (Selectable Personas)

Each learning style adjusts Solomon's behavior using dynamic system prompts:

Default – Professor Solomon
> Wise, patient, and supportive. Teaches through guidance, not shortcuts.

Mode 1 – The Architect
> A calm senior engineer. Clear, direct, grounded. Explains patterns and teaches through questions.

Mode 2 – Beginner Guide
> Gentle, encouraging, breaks everything into steps. Uses analogies and checks for understanding.

Mode 3 – Debug Like a Pro
> Efficient, honest, sharp. No fluff. Identifies bugs and root causes quickly — but doesn’t spoon-feed.

Mode 4 – Concept First
> Explains the why before the how. Teaches the underlying principle before touching the user’s code.

## Language Focus (Selectable Topics)

Users can also choose the programming context for answers:

- General Concepts (default)
- Python
- JavaScript / React
- SQL
- HTML / CSS

This adjusts how Solomon tailors examples and explanations, while still honoring the selected mentor mode.

## Features

- Ask coding questions in natural language
- Paste code or errors for debugging help
- AI guides you instead of solving for you
- Choose different teaching modes
- Choose a language or topic focus
- Save and review past sessions

## Learning Goals

This app helps reinforce:
- React + Tailwind frontends
- Python/FastAPI REST APIs
- Working with OpenAI’s API
- Dynamic prompts & persona switching
- JWT authentication
- PostgreSQL integration
- Full-stack deployment with CI/CD

## Future Ideas

- AI-generated flashcards based on sessions
- Markdown rendering + syntax highlighting
- “Lesson of the day” feature
- User analytics (streaks, growth map)
- Optional Night Mode persona with poetic responses

## Credits

Created by: Richard Hall  
https://github.com/Cyberbot777  