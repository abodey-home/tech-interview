# 🧪 Senior Python Developer Take-Home Exercise

Welcome, and thanks for your interest!

This exercise is designed to evaluate your skills across backend development, architecture thinking, documentation, and production-readiness. We want to see not just working code, but how you **think like a senior developer**.

---

## 📌 The Task

Build a minimal, production-ready backend service using **FastAPI** that manages a resource of your choice — for example: `bookings`, `invoices`, `documents`, `contacts`, `files`, etc.

You should expose a simple set of **RESTful endpoints** to:
- Create a new resource
- Retrieve a specific resource
- List all resources

The goal is not to cover every possible operation, but to show how you approach building a real backend service.

---

## 🎯 Objectives

Your submission should demonstrate:

- ✅ FastAPI development practices
- ✅ Database integration (preferably MongoDB, but open to others)
- ✅ Logging and debugging readiness
- ✅ API documentation and structure
- ✅ Deployment considerations (e.g., Docker)
- ✅ A clear thought process

---

## 🔧 Requirements

You're free to make assumptions, but please include:

### 1. FastAPI Service
- Use [FastAPI](https://fastapi.tiangolo.com/) with [Pydantic](https://docs.pydantic.dev/)
- Route structure and validations that reflect production use

### 2. Database
- Use **MongoDB** (preferred) or any database you're comfortable with
- Include connection setup and basic schema/model
- Provide sample data if needed

### 3. Logging
- Include structured and meaningful logs
- Add logs that could help diagnose issues in production

### 4. API Docs
- Use FastAPI's built-in Swagger UI (`/docs`)
- Add relevant descriptions, request/response models

### 5. Deployability
- Include a `Dockerfile` to containerize the app
- Add a basic healthcheck endpoint (`/health` or similar)

### ✅ Bonus (Optional, Not Required)
- Prometheus/Grafana metrics endpoint or logging middleware
- CI/CD script (GitHub Actions, shell script, or Docker Compose)
- API authentication via token or basic auth

---

## 📁 What to Submit

- A GitHub repository (public or private — just share access)
- Include a `README.md` with:
  - What the service does
  - How to run it locally
  - Assumptions you made
  - How to test the API
  - Any notes about deployment or architecture choices

---

## 🚀 How We'll Evaluate

| Area                     | What We're Looking For                                                                 |
|--------------------------|----------------------------------------------------------------------------------------|
| ✅ API Design            | RESTful principles, validation, consistency                                            |
| ✅ Code Quality          | Clarity, modularity, separation of concerns                                            |
| ✅ Database Integration  | Clean handling of persistence and querying                                             |
| ✅ Logging               | Use of structured and actionable logs                                                  |
| ✅ Deployability         | Docker setup, startup readiness                                                        |
| ✅ Documentation         | Clear instructions, assumptions explained                                              |
| ✅ Engineering Maturity  | Thoughtful design, good defaults, and signs of ownership                              |

---

## 🙅 What We're *Not* Looking For

- A fully-featured app — keep it small and focused
- AI-generated code with no explanation
- Frontend, styling, or UI considerations

---

## 🕒 Time Guidelines

We expect this to take around **3–5 hours**, depending on how much depth you go into. Please don’t over-engineer — focus on quality, not quantity.

---

Looking forward to your submission!

Good luck! 🚀
