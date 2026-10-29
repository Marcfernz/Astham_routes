# Asthma-friendly London routes
I'm learning web development. When you use a concept for the first time, explain it in two or three sentences.

## Stack
- Web app: React + TypeScript + Vite, MapLibre GL JS for the map
- API: TypeScript serverless functions in /api
- Data prep: one-off Python scripts in /data-prep
- Mobile: Capacitor wraps the web app for Android, then iOS

## Commands
- npm run dev: start the app locally
- npm test: run the tests (Vitest)

## Rules
- API keys live in .env and are never committed or sent to the browser
- Inhaler logs stay on the device; only a sensitivity number is sent to the API
- Every change to /api/scoring needs a test
- One feature per commitCLAUDE.md
