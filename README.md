# HireFlow — AI-Powered Recruitment Intelligence Platform

![HireFlow Dashboard](screenshots/dashboard.png)

**Recruit smarter. Evaluate with evidence.**

HireFlow is an AI-powered recruitment intelligence platform that helps recruiters screen candidates using **evidence-backed matching and evaluation**.

##  Features

*  Upload Job Descriptions and candidate resumes
*  Automatic resume & JD information extraction
*  Requirement-by-requirement candidate matching
*  Candidate scoring and grouping
*  Evidence-based matching with source text
*  Personalized interview question generation
*  Interview notes evaluation
*  Evidence-backed candidate reports
*  Natural-language candidate search
*  Fairness-focused, job-relevant evaluation
*  Audit trail for recruitment decisions
*  Works with or without an LLM

##  How It Works

```text
JD + Resumes
     ↓
Extraction Agent
     ↓
Matching Agent
     ↓
Grouping & Ranking
     ↓
Interview Agent
     ↓
Interview Notes
     ↓
Evaluation Agent
     ↓
Final Evidence-Based Report
```

##  Tech Stack

**Frontend**

* Next.js
* TypeScript
* Tailwind CSS

**Backend**

* FastAPI
* Python
* SQLAlchemy
* SQLite / PostgreSQL

**AI/ML**

* Sentence Transformers
* Semantic Similarity
* Rule-based Matching
* Optional LLM Integration

## Setup

### Backend

```bash
cd backend

python -m venv .venv
```

Activate the environment:

**Windows**

```bash
.venv\Scripts\activate
```

**Linux/macOS**

```bash
source .venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Create environment file:

```bash
cp .env.example .env
```

Run backend:

```bash
uvicorn app.main:app --reload --port 8000
```

### Frontend

```bash
cd frontend
npm install
npm run dev
```

Open:

```text
http://localhost:3000
```

Backend API documentation:

```text
http://localhost:8000/docs
```

##  Demo

Use **Dashboard → Load Demo Data** to test HireFlow with the bundled sample Job Description and candidate resumes.

##  Privacy & Safety

HireFlow focuses only on **job-relevant candidate evidence**. It does not use protected personal attributes for candidate evaluation and does not generate automatic hire/no-hire recommendations.

## Project Status

**Production-oriented MVP**

Built to demonstrate explainable, evidence-driven recruitment intelligence.

##  Author

**Md Zahid Ansari**

B.Tech CSE — Artificial Intelligence & Machine Learning
