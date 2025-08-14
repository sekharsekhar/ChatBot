# ChatBot Project

A simple chatbot web application with a Node.js backend and HTML/CSS/JS frontend. The backend uses **Express** and the **OpenAI API** to generate responses.  

---

## Features

- Users can input messages and receive AI-generated responses.
- Backend API powered by **Node.js** and **OpenAI**.
- Frontend built with pure HTML, CSS, and JavaScript.
- Environment variables handled securely with `.env`.
- Deployable on Render or any Node.js hosting platform.

---

## Folder Structure

CHATBOT/
│
├─ client/ # Frontend HTML/CSS/JS files
│ ├─ index.html
│ ├─ style.css
│ └─ script.js
│
├─ server/ # Backend Node.js server
│ ├─ server.js
│ └─ .env # API keys (ignored in Git)
│
├─ .gitignore
├─ package.json
└─ README.md

*Deployment
##Backend (Render)##

Choose New → Web Service on Render.

Connect GitHub repo.

Root Directory: server

Build Command: npm install

Start Command: npm start

Add environment variable OPENAI_API_KEY.

Deploy — Render provides a public URL for your API.

##Frontend (Static Site)##

Choose New → Static Site on Render.

Root Directory: client

Build Command: (leave empty if pure HTML/CSS/JS)

Publish Directory: .

Deploy — Render provides a public URL for your frontend.
