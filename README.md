# Pip Labs — company site

A Next.js (App Router) site with three pages:

- `/` — About us
- `/team` — Team page, with an illustrated rectangle of the team discussing
  AI problems (LLM, NLP) plus a team grid
- `/contact` — Contact us, with Slack, Telegram, and phone

No external UI libraries — plain CSS in `app/globals.css`, Google Fonts
(Fraunces + Inter) loaded via `@import`. The logo is a hand-built SVG in
`app/components/Logo.jsx` (also used as the favicon in `app/icon.svg`).

## Run locally

```bash
npm install
npm run dev
```

Then open http://localhost:3000.

## Deploy to Vercel

1. Push this folder to a GitHub repo.
2. Go to https://vercel.com/new and import the repo.
3. Vercel auto-detects Next.js — no config needed. Click **Deploy**.

Or from the CLI:

```bash
npm i -g vercel
vercel
```

## Before you ship

Swap the placeholder content for the real thing:
- Company name / copy in `app/page.js`, `app/team/page.js`
- Team member names, roles, initials in `app/team/page.js` (`TEAM` array)
- Slack workspace URL, Telegram handle, and phone number in
  `app/contact/page.js` (`CHANNELS` array)

# fuxi-forecasting
