# huduku_compliance

## Development Setup

1. Install nodejs and pnpm package manager
2. Run `pnpm i`
3. Install Docker Desktop or Orbstack
4. Run `docker compose up` or `docker compose up -d`
5. RUN `cp .env.example .env`
6. RUN `pnpm --filter database push` to apply migrations to postgres database
7. RUN `pnpm --filter database generate` to generate prisma types
8. RUN `pnpm dev` to start development server
9. RUN `pnpm --filter scripts create:user` to create admin user