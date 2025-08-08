# Jeena Baby Tracker (Minimal)

A minimal Next.js + Supabase app for logging baby events (feed, diaper, etc.) with realtime sync.

## 1) Local dev
```bash
npm i
npm run dev
```
Set the env vars:
- `NEXT_PUBLIC_SUPABASE_URL`
- `NEXT_PUBLIC_SUPABASE_ANON_KEY`

## 2) Deploy (Vercel)
- Import this repo in Vercel
- Add the two env vars above
- Deploy

## Notes
- Uses Supabase Realtime to refresh the Today view
- Tables are created by the schema you already ran in Supabase
- Extend UI later (shadcn/MUI) without changing the DB
