# Behavioural Brief Wizard (Next.js)

Next.js + Tailwind single-repo app for capturing media-centric behavioural briefs. Uses localStorage, supports Export JSON, and prints cleanly to PDF.

## Quick Start
```bash
npm install
npm run dev
# open http://localhost:3000/brief
```

## Deploy (Vercel — easiest)
1. Push this folder to a **new GitHub repo**.
2. Go to **vercel.com → Add New → Project → Import Git Repository**.
3. Accept defaults and Deploy. Share the `/brief` URL with your team.

## Notes
- Data is stored per-user in their browser via `localStorage`.
- No backend required. You can add Supabase/Auth later if you want shared Save/Load.
