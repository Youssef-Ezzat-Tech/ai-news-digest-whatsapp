# ai-news-digest-whatsapp

# AI News Digest — Automated WhatsApp Pipeline

## What This Is
Fully automated pipeline that scrapes TechCrunch headlines, summarizes them into 5 bullet points using a free LLM, and delivers the digest to WhatsApp every 3 days — zero manual input, zero cost.

## Stack
Make.com | TechCrunch RSS | OpenRouter | Poolside Laguna M.1 (free) | CallMeBot

## Pipeline
`Watch RSS` → `Retrieve Items` → `Text Aggregator` → `OpenRouter LLM` → `CallMeBot` → `WhatsApp`

## Stats
- 6-module pipeline, fully automated on a 3-day schedule
- 5 articles processed per run → 1 summarized digest delivered
- ~27s end-to-end execution time (25.7s LLM response)
- $0.00/month infrastructure cost
- Survived a live model deprecation (Hunyuan → Laguna M.1) with zero architecture changes

## Files
- `blueprint.json` — Make.com scenario export (importable)
- `screenshots/` — scenario canvas, execution history, node configs, WhatsApp output

## Skills Shown
No-code automation • LLM prompt engineering • API integration • pipeline debugging • free-tier infrastructure design
