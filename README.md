# cse4104-7f-t05-ai-symptom-checker
This is a software development group project called ai symptom checker .
AI Symptom Checker 

**CSE 4104 - Software Development III** | Northern University of Business and Technology, Khulna
Department of Computer Science and Engineering

> **Status:** Week 2 - Proposal stage

## Team Information

| Field | Details |
|---|---|
| Team Name | CSE4104-7F-T05 |
| Section | 7F |
| Project Title | AI Symptom Checker  |
| Team Leader | Arnob Paul |

| # | Name | Student ID |
|---|---|---|
| 1 | Arnob Paul (Team Leader) | 230321390 |
| 2 | Nishat Salsabil Mou | 230321543 |
| 3 | Shahriar Rashid Nibir | 230321412 |
| 4 | Mridul Biswas | 230321400 |

## Project Description

Many people search the internet for their symptoms before deciding whether to see a doctor, and the results are often confusing, generic, or alarming. This web application lets a registered user describe symptoms in plain Bangla or English and answer a few AI-generated follow-up questions. The system then returns a structured result: possible causes to consider, a suggested urgency level (self-care, see a doctor soon, or emergency care), and general next steps.

A rule-based red-flag layer works independently of the AI model and immediately recommends emergency care for serious warning signs such as chest pain or breathing difficulty.

> **Disclaimer:** This project is an information and guidance tool only. It does not give a medical diagnosis and does not replace a licensed doctor.
## Proposed Features

**Must-have**
- Authentication with User and Admin roles (JWT, bcrypt)
- AI chat symptom intake with adaptive follow-up questions
- Structured assessment: possible causes, urgency level, next steps
- Red-flag emergency alerts (rules + AI)
- Health profile (age, gender, existing conditions) used as context
- Private symptom history
- Downloadable PDF summary to share with a doctor
- Bangla-English support
- Admin dashboard (usage statistics, disclaimer and safety content management)

**Should-have:** user feedback on AI responses and AI performance monitoring; personal health analytics charts.
**Could-have:** interactive body map, voice input, nearby facility finder, audit logs and notifications.
