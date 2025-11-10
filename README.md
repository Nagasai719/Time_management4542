# Agentic-AI (local run)

This repo contains a Next.js frontend (in the repo root / `app/`) and a simple Express backend in `backend/`.

Quick start (Windows PowerShell):

1. Install dependencies for the frontend and backend
   cd 'c:\Users\svksn\Downloads\time management\Agentic-AI-main'; npm install
   cd 'c:\Users\svksn\Downloads\time management\Agentic-AI-main\backend'; npm install

2. Start the backend (port 4000)
   cd 'c:\Users\svksn\Downloads\time management\Agentic-AI-main\backend'; npm start

3. Start the frontend (Next dev server, port 3000)
   cd 'c:\Users\svksn\Downloads\time management\Agentic-AI-main'; npm run dev

Endpoints:
- Backend: GET http://localhost:4000/api/hello
- Frontend: http://localhost:3000

Notes:
- If ports are occupied change PORT for backend or the Next `-p` flag.
