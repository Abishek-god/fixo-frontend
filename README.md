# Fixo Web — Frontend

Next.js frontend for Fixo, an educational Indian-market research and paper-trading app.

## Deploy on Vercel
Import this repository with **Root Directory `./`**.

- Framework: Next.js
- Build command: `npm run build`
- Install command: `npm install`
- Output directory: Next.js default (leave override disabled)

### Vercel environment variables
- `NEXT_PUBLIC_SUPABASE_URL`
- `NEXT_PUBLIC_SUPABASE_PUBLISHABLE_KEY`
- `NEXT_PUBLIC_FIXO_API_BASE_URL=https://fixo-9uf2.onrender.com`
- `AI_BASE_URL` (server-only, OpenAI-compatible provider base URL)
- `AI_API_KEY` (server-only provider key)

Keep AI credentials server-side; never prefix them with `NEXT_PUBLIC_`.

The FastAPI backend remains separately hosted at Render. The backend and Supabase migration/function source are intentionally excluded from this repository.
