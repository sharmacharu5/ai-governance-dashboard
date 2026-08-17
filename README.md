# AI Governance Radar

A prototype dashboard for tracking AI tool usage and spend across an organization — built to answer one question at a glance: **are we overspending on AI tools, and are we blind to any of it?**

🔗 **Live demo:** https://sharmacharu5.github.io/ai-governance-dashboard/ai-governance-dashboard.html

## What this is

Organizations are rapidly adopting AI tools (ChatGPT, Claude, Copilot, Midjourney, etc.) across teams — often without centralized visibility into who's using what, how much it costs, and whether usage stays within approved limits. This is the "Shadow AI" problem.

This dashboard is a prototype built to explore that problem: it surfaces AI tool spend against approved budgets, flags tools operating without sign-off ("Shadow AI"), and tracks how big that blind spot is over time.

## Features

- **KPI overview** — total AI spend, tools tracked, budget utilization, tools over their limit
- **Shadow AI detection** — a live count of tools with spend but no approved budget on record
- **Three key charts:**
  1. Spend vs. approved limit, by tool
  2. Sanctioned vs. Shadow AI spend split
  3. Shadow AI spend as a % of total, over time
- **Tool registry** — a full ledger of every tracked tool, its status, owner department, users, spend, and budget utilization

## Tech

Single self-contained HTML file — no build step, no dependencies, no external network calls. All charts are hand-drawn inline SVG, so it renders identically anywhere, offline included.

## Running it locally

Just open `ai-governance-dashboard.html` directly in any browser — double-click it, or right-click → Open with → your browser of choice.

## Data

All data shown is illustrative/fictional (a mock company, "Northwind Retail Co."), built to sanity-check the design — it does not represent real usage or spend.
