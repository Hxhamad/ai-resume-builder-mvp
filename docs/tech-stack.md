# Tech Stack Preview

The paid package is a full-stack TypeScript application, not a static template.

## Frontend

- React
- TanStack Start / Vite
- TypeScript
- Shared UI package
- Responsive dashboard and builder views

## Backend And Data

- PostgreSQL
- Drizzle ORM and migrations
- Redis for AI agent state
- S3-compatible storage support
- Local filesystem storage fallback where configured

## Auth

- Better Auth
- Local email/password auth
- Optional OAuth provider configuration
- Buyer-managed production secrets

## AI

- AI SDK provider integrations
- OpenAI, Anthropic, Gemini, OpenRouter, Vercel AI Gateway, Ollama, and OpenAI-compatible provider setup patterns
- Server-side encrypted provider credentials in the private package
- JSON Patch-based agent edit flow

## Tooling

- pnpm
- Turborepo
- Vitest
- Testing Library
- Biome
- GitHub CI
- Docker Compose for local services

## Local Services

The private package includes local service configuration for:

- PostgreSQL
- Redis
- S3-compatible storage
- Web app development server
