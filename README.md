# AI Interview Simulator

A FastAPI-based AI interview practice tool with a clean web UI.

## Setup

1. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```
   Or with `uv`:
   ```bash
   uv sync
   ```

2. **Configure API keys** — copy `.env.example` to `.env` and fill in your keys:
   ```
   OPENAI_API_KEY=sk-...
   GEMINI_API_KEY=AIza...
   ```

3. **Run the server**
   ```bash
   uvicorn app.main:app --reload
   ```

4. Open [http://localhost:8000](http://localhost:8000) in your browser.

## Features
- Upload your PDF resume for personalized interview questions
- Chat with GPT-4o (OpenAI) or Gemini 2.5 (Google)
- Quick-prompt buttons for common interview questions
- Response latency tracking
- Rate limiting & caching built-in
