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


