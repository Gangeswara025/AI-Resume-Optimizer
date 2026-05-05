# 🚀 Trintz AI Resume Optimizer

An AI-powered resume optimization platform that analyzes, scores, and rewrites resumes to improve ATS (Applicant Tracking System) compatibility and increase job selection chances.

---

## 🔥 Overview

Trintz AI Resume Optimizer helps job seekers improve their resumes using:

* 📊 ATS scoring system
* 🧠 AI-powered resume rewriting
* 🔍 Keyword gap analysis
* ✨ Structured, optimized output

Built as a full-stack SaaS application using modern technologies.

---

## ⚙️ Tech Stack

### 🖥️ Frontend

* React.js
* TypeScript
* Vite
* Tailwind CSS

### ⚡ Backend

* FastAPI (Python)
* SQLAlchemy
* SQLite (current) → scalable to PostgreSQL

### 🤖 AI Integration

* OpenAI-compatible API (via aicredits.in)
* Structured JSON response handling

### 📧 Services

* Resend (Email verification)
* JWT Authentication

---

## 🚀 Features

* ✅ Resume Upload (PDF/DOCX/TXT)
* ✅ ATS Score Calculation (rule-based)
* ✅ Keyword Matching & Gap Detection
* ✅ AI Resume Optimization
* ✅ Before vs After Improvements
* ✅ Authentication System (JWT)
* ✅ Email Verification Flow
* ✅ Resume History Tracking

---

## 🧠 ATS Scoring Logic

The ATS score is calculated based on:

* 50% → Keyword Match
* 20% → Section Completeness
* 30% → Content Strength (impact-based writing)

---

## 📦 Project Structure

```
trintz-resume-optimizer/
│
├── backend/
│   ├── main.py
│   ├── routers/
│   ├── models/
│   ├── database.py
│   └── requirements.txt
│
├── frontend/
│   ├── src/
│   ├── components/
│   └── vite.config.ts
│
└── README.md
```

---

## ⚙️ Setup Instructions

### 🔹 Backend

```bash
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
```

---

### 🔹 Frontend

```bash
cd frontend
npm install
npm run dev
```

---

## 🌐 Environment Variables

Create `.env` files for backend:

```
RESEND_API_KEY=your_key
EMAIL_FROM=noreply@yourdomain.com

OPENAI_API_KEY=your_key
OPENAI_API_BASE_URL=https://api.aicredits.in/v1

SECRET_KEY=your_secret
ALGORITHM=HS256
ACCESS_TOKEN_EXPIRE_MINUTES=60
```

---

## 🚀 Deployment

* Backend → Render
* Frontend → Vercel (recommended)
* Email → Resend

---

## 🎯 Problem We Solve

Most resumes fail ATS screening due to:

* Missing keywords
* Weak descriptions
* Poor formatting

We solve this using AI + structured optimization.

---

## 🧩 Future Improvements

* PDF export with templates
* Visual resume editor
* Better personalization
* Multi-language support
* PostgreSQL migration

---

## 🤝 Team

Trintz — Student startup team focused on AI-driven solutions for career development.

---

## 📌 Status

✅ MVP Completed
🚀 Actively improving & scaling

---

## ⭐ Contribute

Feel free to fork, improve, and contribute to the project!

---

