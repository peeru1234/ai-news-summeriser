# Verity — AI-Powered News Verification Assistant

Full-stack React + Express application for organizing claims, evidence, reviewer decisions, and Gemini-assisted verification research. AI output is explicitly presented as a draft for human review, never a truth verdict.

## Run locally

1. Copy `backend/.env.example` to `backend/.env` and add your Gemini key (optional; the app has a safe demo-analysis fallback).
2. Run `npm install`, `npm run install:all`, then `npm run dev`.
3. Open `http://localhost:5173`.

The API is at `http://localhost:5000`. Development data is held in memory; replace `backend/src/store.js` with a database adapter for production.
