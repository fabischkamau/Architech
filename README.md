# Architech Monorepo

Architech is an AI-powered platform for generating, refining, and visualizing modern software architectures. It enables you to describe your vision in natural language and receive a production-ready, visual system architecture that you can refine and export.

---

![Example Architecture Plan](<assets/architech_plan%20(12).png>)

---

## Project Overview

Architech consists of a frontend web application and a backend AI agent server:

- **Frontend**: A modern, responsive web app built with Next.js and React. It provides an interactive canvas for creating, editing, and exporting architecture plans, along with authentication and collaboration features.
- **Backend**: A FastAPI Python server orchestrating a multi-agent AI system. It analyzes user prompts, recommends technologies using a Neo4j knowledge graph, and generates detailed architecture plans with explanations.

**Key Features:**

- Instantly generate comprehensive software architectures from a simple prompt.
- Multi-agent AI system for requirement analysis, technology selection, and plan refinement.
- Interactive visual canvas for real-time editing and visualization.
- Export options for documentation, diagrams, and starter code.
- Secure authentication and user management.

---

## Repository Structure

- `frontend/` — Next.js 14 app (React, TypeScript)
- `backend/` — FastAPI Python app
- `assets/` — Example images and diagrams

---

## Getting Started

For detailed installation and setup instructions for each part of the project, please refer to the respective README files:

- [frontend/README.md](frontend/README.md) — Frontend setup, environment variables, and usage
- [backend/README.md](backend/README.md) — Backend setup, environment variables, and API documentation

---

## Development

- Frontend: edit files in `frontend/app/`, `frontend/components/`, etc.
- Backend: edit files in `backend/agents/`, `backend/orchestrator/`, etc.

---
