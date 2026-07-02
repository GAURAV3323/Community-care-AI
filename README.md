# CommunityCare AI

**Theme:** AI for Better Living and Smarter Communities
**Built for:** Google Cloud Gen AI Academy — APAC Edition, Hackathon Prototype Submission
**Participant:** Gaurav Tripathi

## What it is

A single-page web app prototype that helps underserved and elderly residents:

1. **Symptom & Wellness Chat** — plain-language triage guidance (emergency / see a doctor soon / home care)
2. **Medication & Routine Reminders** — simple, large-tap-target reminders with a streak tracker
3. **Mental Wellbeing Check-in** — daily mood check-in with supportive responses
4. **Community Pulse Dashboard** — aggregated, anonymised symptom trends for local health workers/NGOs

The current build uses a lightweight rule-based engine so it works instantly with zero setup. In production, the chat would call a Gen AI model (e.g. Gemini via Vertex AI) with a medically-reviewed safety and escalation layer, and the dashboard/reminders would be backed by a real database.

It's a single self-contained `index.html` — no build step, no dependencies.

## How to deploy it (get your public Deployment Link)

Pick whichever is fastest for you:

### Option A — Netlify Drop (easiest, ~1 minute)
1. Go to https://app.netlify.com/drop
2. Drag the `index.html` file onto the page
3. Netlify gives you a live public URL instantly — copy it into the form as your **Working Prototype Deployed Link**

### Option B — GitHub Pages (also gives you the GitHub link the form asks for)
1. Create a new public GitHub repository (e.g. `communitycare-ai`)
2. Upload `index.html` (and this `README.md`) to the repo
3. Go to **Settings → Pages**, set Source to the `main` branch, root folder
4. Your live URL will be `https://<your-username>.github.io/communitycare-ai/`
5. Use the repo URL as your **GitHub Repository Link**, and the Pages URL as your **Deployment Link**

### Option C — Vercel
1. Go to https://vercel.com/new, import the GitHub repo (or drag-and-drop the folder)
2. Deploy — Vercel gives you a public `.vercel.app` URL

## Demo video (≤3 minutes) — suggested flow
1. (10s) State the problem: limited access to first-line health guidance in underserved communities
2. (60s) Show the Wellness Chat — try "chest pain" (emergency), then "mild headache" (home care)
3. (30s) Show Medication Reminders — add one, mark it done, show streak
4. (30s) Show Mood Check-in — pick a mood, show the response and mini log
5. (30s) Show Community Pulse dashboard — explain how this helps NGOs/health workers allocate resources
6. (20s) Close with the tech direction: Gemini/Vertex AI integration + real backend for production

## Submission form — Brief Description (copy-paste ready)

> CommunityCare AI is a Gen AI-powered health companion for underserved and elderly residents in APAC communities. It offers plain-language symptom triage, simple medication reminders, and daily mental wellbeing check-ins for individuals — while giving local health workers and NGOs an anonymised, aggregated "community pulse" dashboard to spot rising health trends early and allocate resources before small issues become crises. Built with accessibility in mind: large tap targets, plain language, and no medical jargon.

