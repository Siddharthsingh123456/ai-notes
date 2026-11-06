# AI Notes

An AI-assisted notes workspace for capturing ideas, organizing information, and transforming notes into summaries or action items.

## Features
- Create and edit notes
- Search notes
- AI actions to summarize and improve content
- Turn notes into task suggestions
- MongoDB/Mongoose persistence layer
- Responsive knowledge-workspace interface

## Stack
React 18 · Vite 5 · Node.js 24 · Express · Mongoose · MongoDB · OpenAI-compatible API · Vercel

## Requirements
Node.js 24.x, npm, an AI provider API key for AI actions, and MongoDB URI for persistent storage.

## Setup
```bash
git clone https://github.com/Siddharthsingh123456/ai-notes.git
cd ai-notes
npm install
```
Create `.env` using `.env.example`:
```env
OPENAI_API_KEY=your_api_key
OPENAI_MODEL=gpt-4o-mini
MONGODB_URI=your_mongodb_connection_string
```
Never commit credentials.

## Run
```bash
npm run dev
npm run build
npm run preview
```
Use `npm run check` for the configured build check.

## Deploy
Deploy the repository root to Vercel and configure required environment variables. Verify note creation, editing, search, AI actions, and persistence after deployment.

## Privacy
Do not store sensitive personal, financial, or health information unless the application has been specifically reviewed and approved for that use.

## License
No license file is currently specified. Contact the repository owner before reuse.
