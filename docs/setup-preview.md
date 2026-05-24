# Setup Preview

This is a public preview. The full setup guide ships with the paid private source package.

## Expected Prerequisites

- Git
- Node.js with Corepack
- Docker Desktop
- A modern browser
- Optional AI provider account for live agent demos

## Typical Local Flow

```bash
corepack enable
corepack pnpm install
Copy-Item .env.example .env
docker compose -f compose.dev.yml up -d postgres redis seaweedfs seaweedfs_create_bucket
corepack pnpm --filter web dev
```

Open:

```text
http://localhost:3000
```

## What A Buyer Should Test

- Register a local account.
- Sign in and sign out.
- Create a resume.
- Edit resume sections.
- Refresh and confirm edits persist.
- Export JSON, DOCX, and PDF.
- Try public sharing controls.
- Add an AI provider with the buyer's own key.
- Ask the AI agent to make a simple resume edit.

## Production Reminder

Local demo defaults are not production secrets. Before public launch, buyers must configure production secrets, hosting, database, Redis, storage, email, domain, backups, monitoring, and legal policies.
