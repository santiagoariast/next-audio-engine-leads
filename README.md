[README.md](https://github.com/user-attachments/files/27050010/README.md)
# Next Audio Prospecting Engine v3.2

AI-powered lead generation and outreach tool for Next Audio's sales team.

## Features

- **Find Leads** — Generate verified prospects with scoring, buying signals, pitch angles, and ready-to-send emails (A/B versions) for any industry and market
- **Daily Brief** — Hot and warm market signals updated in real time + follow-ups due today
- **Follow-up Generator** — 5-step follow-up sequences with a new angle per email
- **Pipeline** — Track all prospects from contacted to call booked

## Deploy in 3 steps

1. Fork or upload this repo to your GitHub account
2. Go to **Settings → Pages → Source: Deploy from branch → main → / (root)**
3. Your engine is live at `https://your-username.github.io/next-audio-engine`

## Usage

1. Open the app URL in any browser
2. Enter your Anthropic API key (stored locally in your browser only — never shared)
3. Select industry + market + buying signals → click **Generate Leads**
4. The engine verifies contacts, scores leads, and produces email drafts inline

## Tech

Single HTML file. No dependencies. No backend. Runs entirely in the browser.
Uses the Anthropic Claude API (claude-sonnet-4-20250514) for all AI generation.

## Security

- API key is stored in `localStorage` — it never leaves your browser
- All API calls go directly from your browser to Anthropic — no middleman
- No data is stored anywhere outside your browser session

---

*Next Audio · santiago@nextbroadcast.media*

Engine leads generator.
