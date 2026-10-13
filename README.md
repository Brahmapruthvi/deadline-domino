# Deadline Domino — One Change. Every Team in Sync.

B2B AI event-operations concept demo. Single static file, no build step, no API keys.

## Run locally
Open `index.html` in a browser, or: `python3 -m http.server 8000` then visit http://localhost:8000

## What is simulated
- "AI" extraction, validation and drafting are rule-based, running in the browser
- Business login is demo-only (no real authentication, no backend)
- Message sending is queued locally (no mail server)
- Data persists in the browser's localStorage only

## Next steps toward production
React + TypeScript frontend, Node/Express API, PostgreSQL, real auth provider, LLM API, email provider.
