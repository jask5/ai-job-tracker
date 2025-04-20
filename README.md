# ai-job-tracker 

A full-stack, intelligent job application tracker that helps users monitor job applications, get AI-driven resume match scores, and visualize their job hunt progress.


## Why This Project?

Built to solve the pain of applying to dozens of jobs without knowing how well your resume matches the role.  


## Features

- Upload resume + job description
- Get an AI-driven Resume Match Score (using NLP)
- Visual dashboard: apps by company, match quality, status
- Export to CSV
- User Auth (email + password)

---

## Tech Stack
| Layer       | Tech |
|-------------|------|
| **Frontend**| React, Tailwind CSS |
| **Backend** | FastAPI (Python) |
| **AI/NLP**  | spaCy, scikit-learn (cosine similarity), optional: HuggingFace |
| **Database**| Supabase (PostgreSQL) |
| **Storage** | Supabase Storage (for file uploads) |
| **Auth**    | Supabase Auth |
| **Deploy**  | Vercel (frontend), Render (backend) |
