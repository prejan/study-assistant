#  Study Assistant AI

A full-stack AI-powered study assistant that explains concepts, generates quizzes, and creates structured study notes using Large Language Models.

Built with **Next.js**, **FastAPI**, and **PydanticAI**, deployed using **Vercel** (frontend) and **Render** (backend).

---

##  Features

-  Explain complex topics in simple terms  
-  Generate exam-oriented study notes  
-  Create multiple-choice quizzes  
-  Clean, readable markdown rendering  
-  Fast API responses using OpenRouter LLMs  
-  Fully deployed full-stack application  

---

##  Tech Stack

### Frontend
- **Next.js (App Router)**
- **TypeScript**
- **Tailwind CSS**
- **React Markdown**
- **Lucide Icons**

### Backend
- **FastAPI**
- **PydanticAI**
- **OpenRouter (LLMs)**
- **Uvicorn**

### Deployment
- **Frontend** → Vercel  
- **Backend** → Render
---
##  Repo Structure

```
STUDY-ASSISTANT/
│
├── backend/
│   ├── __pycache__/
│   ├── .vscode/
│   ├── node_modules/
│   │   ├── lucide-react/
│   │   └── react/
│   ├── .env
│   ├── main.py
│   ├── package.json
│   ├── package-lock.json
│   ├── requirements.txt
│   └── vercel.json
│
├── frontend/
│   ├── .next/
│   ├── .vercel/
│   ├── app/
│   │   ├── favicon.ico
│   │   ├── globals.css
│   │   ├── layout.tsx
│   │   └── page.tsx
│   ├── node_modules/
│   ├── public/
│   │   ├── file.svg
│   │   ├── globe.svg
│   │   ├── next.svg
│   │   ├── vercel.svg
│   │   └── window.svg
│   ├── .env.local
│   ├── .gitignore
│   ├── eslint.config.mjs
│   ├── next-env.d.ts
│   ├── next.config.ts
│   ├── package.json
│   ├── package-lock.json
│   ├── postcss.config.mjs
│   ├── tsconfig.json
│   └── README.md
│
├── .gitignore
└── README.md
```

---


##  API Endpoints

### Health Check
GET /health

### Generate Content
POST /generate
```
**Request Body**
```json
{
  "topic": "Backpropagation",
  "task_type": "explain"
}
```
<img width="1789" height="807" alt="image" src="https://github.com/user-attachments/assets/ea747a10-c270-41f3-9300-cd9e39bdb404" />
<img width="1762" height="666" alt="image" src="https://github.com/user-attachments/assets/1b009893-02a0-4305-8374-092d2953e0fd" />

###Live Demo

Frontend: https://study-assistant-frontend.vercel.app

Backend API Docs: https://study-assistant-backend.onrender.com/docs

###Outputs
<img width="1814" height="870" alt="image" src="https://github.com/user-attachments/assets/f156f251-a657-4c0b-a6de-cf891beb8589" />
<img width="1374" height="872" alt="image" src="https://github.com/user-attachments/assets/280208d4-535a-451e-b440-a9bd45cc2fba" />
<img width="1177" height="870" alt="image" src="https://github.com/user-attachments/assets/1fba62e6-17f2-4259-a46f-801c8f8cd2de" />






