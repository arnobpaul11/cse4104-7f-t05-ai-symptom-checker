# AI Symptom Checker

**CSE 4104 - Software Development III** | Northern University of Business and Technology, Khulna

A web-based health guidance tool where a user describes symptoms in plain **Bangla or English**, answers adaptive AI follow-up questions, and receives possible conditions to consider, a suggested urgency level, and general next steps.

> **Disclaimer:** This is an information and guidance tool only. It does not give a medical diagnosis and does not replace a licensed doctor. In an emergency, seek medical care immediately.

## Team Information

| Field | Value |
|---|---|
| Team Name | CSE4104-7F-T05 |
| Section | 7F |
| Project Title | AI Symptom Checker |
| Team Leader | Arnob Paul |

| # | Member | Student ID |
|---|---|---|
| 1 | Arnob Paul (Team Leader) | 230321390 |
| 2 | Nishat Salsabil Mou | 230321543 |
| 3 | Shahriar Rashid Nibir | 230321412 |
| 4 | Mridul Biswas | 230321400 |

## Objectives

- Chat-based symptom intake in Bangla and English with adaptive follow-up questions
- Structured result: possible conditions, urgency level (self-care / see a doctor soon / emergency), next steps
- Two-layer red-flag emergency system (rule-based + AI)
- Private health profile and symptom history, PDF summary for doctors
- Admin dashboard, deployed online, tested with 30+ AI scenarios

## Features

| ID | Feature | Priority |
|---|---|---|
| F1 | Authentication and roles (User, Admin) | Must |
| F2 | AI chat symptom intake | Must |
| F3 | Structured assessment | Must |
| F4 | Red-flag emergency alert | Must |
| F5 | Profile-aware assessment | Must |
| F6 | Symptom history | Must |
| F7 | PDF health summary | Must |
| F8 | Bangla-English support | Must |
| F9 | Admin dashboard | Must |
| F10-F11 | Feedback and AI monitoring, personal analytics | Should |
| F12-F15 | Body map, voice input, facility finder, audit logs | Could |

## Technology Stack

| Layer | Technology |
|---|---|
| Frontend | React.js, Tailwind CSS, Recharts |
| Backend | Node.js, Express.js, JWT, bcrypt |
| Database | PostgreSQL (Supabase) |
| AI | Google Gemini API (primary) or OpenAI API, via a provider-independent module |
| PDF | PDFKit |
| Deployment | Vercel (frontend), Render (backend), Supabase (database) |
| Tools | GitHub, Figma, Postman, draw.io, dbdiagram.io |

## Repository Structure

```
cse4104-7f-t05-ai-symptom-checker/
├── frontend/
├── backend/
├── documentation/
│   ├── CSE4104-7F-T05_Proposal.pdf
│   ├── CSE4104-7F-T05_SRS.pdf
│   ├── CSE4104-7F-T05_UseCaseDiagram.pdf
│   ├── CSE4104-7F-T05_ERDiagram.pdf
│   ├── CSE4104-7F-T05_ERDiagram.dbml
│   └── CSE4104-7F-T05_ArchitectureDiagram.pdf
├── screenshots/
├── presentation/
├── testing/
├── .env.example
├── .gitignore
└── README.md
```

## Progress

| Week | Deliverable | Status |
|---|---|---|
| 1-2 | Team, idea, proposal, project plan | Done |
| 3 | SRS, use case diagram, ER diagram, architecture diagram | Done |
| 4 | System design, API structure | Next |

## Branches

`main` (stable), `development` (integration), `frontend`, `backend`, `ai-integration`

## Installation

Setup instructions will be added in Week 6-7 when backend and frontend code is added. Secrets go in `.env` (see `.env.example`) and are never committed.

## Deployment

Live link: not yet deployed (planned for Week 11).
