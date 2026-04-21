# AI Job Fit Analyzer

A lightweight, single-page tool that analyzes job descriptions against a candidate's resume and returns an instant fit score, tailored resume content, gap analysis, and networking strategy — powered by Claude AI.

## What It Does

Paste any job description and the tool returns:

- **Fit Score** (0–100) — how well the role matches your background, with a plain-English explanation
- **Gap Analysis** — specific skills or experience you're missing, with concrete steps to address each one
- **Tailored Resume Content** — suggested bullet points and a summary rewrite using your actual experience, reframed for the role
- **Networking Strategy** — who to reach out to at the company and a personalized outreach opener for each

## How to Use

1. Open the app in your browser
2. Enter your Anthropic API key in the top-right field and click **Save**
3. Paste a job description, add the company name and role title
4. Click **Analyze Role** and wait a few seconds for results

> Your API key is stored in memory only and never sent anywhere other than the Anthropic API.

## Tech Stack

- Vanilla HTML, CSS, and JavaScript — no frameworks, no build step
- [Claude Sonnet](https://www.anthropic.com/claude) via the Anthropic Messages API
- Google Fonts (DM Serif Display + DM Sans)
- Deployed as a static site via GitHub Pages

## Running Locally

No setup needed. Just open `index.html` in any browser:

```bash
open index.html
```

You'll need an [Anthropic API key](https://console.anthropic.com/) to use the analyzer.

## Project Structure

```
ai-job-fit-analyzer/
└── index.html    # Entire app — styles, markup, and logic in one file
```

---

Built by [Sanjana Shedbale](https://sanjana9702.github.io)
