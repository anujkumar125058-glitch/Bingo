# Bingo 25 — Vercel deployment package

## Project contents
- React 18 + Vite 6
- 5 × 5 Bingo board with numbers 1–25
- Auto Fill, manual editing, tap-to-mark
- Easy / Medium / Hard point modes
- Verify rows, columns and diagonals
- Score and current-session leaderboard panel
- Responsive mobile styling

## Deploy
1. Extract this ZIP.
2. Upload the **contents** of the extracted folder to the root of a GitHub repository.
3. Import that repository at https://vercel.com/new.
4. Set Framework Preset to **Vite**.
5. Set Install Command to `npm install`.
6. Set Build Command to `npm run build`.
7. Set Output Directory to `dist`.
8. Keep Root Directory as `./`, then deploy.

## Run locally
Requires Node.js 18+:
```bash
npm install
npm run dev
```

No backend, environment variables, or database are needed. The leaderboard shown in this version is local to the current browser session and is not a shared online leaderboard.
