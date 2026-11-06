# AI Notes

An AI-assisted notes workspace for capturing ideas, organizing information, and transforming notes into clearer summaries or action items.

## Features

- Create and edit notes
- Search the notes workspace
- Ask AI to summarize or improve note content
- Turn notes into actionable task suggestions
- MongoDB/Mongoose persistence layer
- Responsive knowledge-workspace interface

## Technology

- React 18 and Vite 5
- Node.js 24
- Express and Mongoose
- MongoDB
- OpenAI-compatible model API
- Vercel deployment configuration

## Requirements

- Node.js 24.x and npm
- AI provider API key for AI actions
- MongoDB URI for persistent storage

## Local setup

```bash
git clone https://github.com/Siddharthsingh123456/ai-notes.git
cd ai-notes
npm install
```

Create a local `.env` file using `.env.example`:

```env
OPENAI_API_KEY=your_api_key
OPENAI_MODEL=gpt-4o-mini
MONGODB_URI=your_mongodb_connection_string
```

Keep the file untracked and never publish credentials.

## Development

```bash
npm run dev
```

Production build:

```bash
npm run build
npm run preview
```

Run the repository's build check with `npm run check`.

## Deployment

Deploy the repository root to Vercel and configure the required environment variables in the project settings. Test note creation, editing, search, AI actions, and persistence in the deployed environment.

## Privacy note

Do not store passwords, financial details, health information, or other sensitive data in notes unless the application has been specifically reviewed and approved for that use.

## License

No license file is currently specified. Contact the repository owner before reuse.
