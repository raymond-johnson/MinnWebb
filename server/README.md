# Chat Proxy

This small Express proxy forwards chat messages from the frontend to OpenAI.

Quick start:

1. Copy `.env.example` to `.env` and set `OPENAI_API_KEY`.
2. Install dependencies and start the server:

```bash
cd server
npm install
npm start
```

By default the server runs on port `3000` and exposes `POST /api/chat` which accepts JSON `{ message: string }` and returns `{ reply: string }`.
