# pocket-tournaments-api

Backend API and database layer for the Pocket Tournaments companion app.

## Features

- REST API and Supabase Edge Functions
- Scheduled card sync from [v4.json](https://github.com/chase-manning/pokemon-tcg-pocket-cards)
- Endpoints for:
  - Cards
  - Decks
  - Players
  - Matches / Results
- Discord OAuth + Firebase/Supabase Auth
- Fuzzy matching + card search

## Tech Stack

- Node.js or Deno
- Supabase (Postgres, Auth, Edge Functions)
- GitHub Actions (data sync)
- TypeScript

## Setup

```bash
npm install
cp .env.example .env
# Configure Supabase keys
npm run dev
```

## License

MIT
