# Search Strategy Agent 🧭

An AI agent that turns a job description and intake notes into a complete technical search plan, and helps diagnose searches that have stalled.

Works with a **Claude Project** or a **Gemini Gem**. No code required.

## Why I built it
The hardest searches don't come with a defined bar, a talent map, or a proven sourcing channel. You have to build them from scratch, often for roles that are new to you. This agent does the first draft of that work in minutes, so I can spend my time where it matters: with the hiring manager and with candidates.

## What it does

### 🛠 BUILD: plan a new search
Give it a job description and intake notes. It returns:

| Section | What you get |
|---|---|
| **Role in plain English** | What the person actually does, and whether the title matches the scope |
| **Hiring bar** | Must-haves, nice-to-haves, and the signals that separate top-tier from average |
| **Talent map** | Adjacent titles, where this talent works, communities, and where *not* to look |
| **Sourcing strings** | Narrow and broad LinkedIn Booleans, an X-Ray string, and a GitHub search idea |
| **Outreach** | Two short messages with different angles, with no recruiter clichés |
| **Screen guide** | Questions a non-engineer can ask, with what strong and weak answers sound like |
| **Risks** | What could make the search hard, and how to de-risk it |

### 🔍 DIAGNOSE: fix a stalled search
Give it funnel numbers. It finds where the funnel is breaking, ranks the likely root causes, and drafts a note to the hiring manager with **recommendations, not just a status update**.

### 🎯 CALIBRATE: learn from feedback
Give it notes on candidates the hiring manager liked and passed on. It finds what they're *actually* selecting for and updates the bar, the sourcing strings, and the outreach to match.

## Built-in guardrails
- Never invents facts about companies, people, or salaries. It flags what to verify.
- Never targets or filters by protected characteristics or proxies for them, like graduation year or names.
- Never recommends collecting data in ways that break platform rules.
- Uses plain English and explains technical terms.


## Setup
1. Create a **Claude Project** or **Gemini Gem**.
2. Paste the contents of `agent-instructions.md` into its instructions.
3. Turn on web search if your tool has it. The talent map is much better with it.
4. Start each chat with **BUILD**, **DIAGNOSE**, or **CALIBRATE**, using the templates.

## Tips
- **Intake notes beat job descriptions.** The best input is what the hiring manager said, not what the posting says.
- **Treat the output as a first draft.** Verify company suggestions and market claims before acting on them.
- **Use DIAGNOSE weekly** on hard searches to catch problems early.
- **Use CALIBRATE after the first few candidates.** It's the fastest way to close the gap between the job description and what the hiring manager really wants.

---

📫 [Connect with me on LinkedIn](https://linkedin.com/in/candacerwalker)
