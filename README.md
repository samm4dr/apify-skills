# Apify Agent Skills

Production-ready [Agent Skills](https://skills.sh) that teach AI coding agents (Claude Code, Cursor, Codex, Windsurf, Gemini CLI...) how to scrape the web properly with **Apify actors** — no brittle custom scrapers, no proxy headaches.

> 🤖 **Try it live first** — free Poe bots that generate the exact actor + run input + code for your use case:
> 🤖 **Try it live** — [Lead List Generator](https://poe.com/leadlistgenerator) · [Job Postings Miner](https://poe.com/jobpostingsminer)

## Install

```bash
# All skills, all detected agents
npx skills add samm4dr/apify-skills

# Pick one
npx skills add samm4dr/apify-skills --skill apify-lead-scraper

# Browse without installing
npx skills add samm4dr/apify-skills --list
```

## Skills

| Skill | Job to be done |
|---|---|
| `apify-google-maps-leads` | Google Maps → local business leads (phones, emails, websites, reviews) |
| `apify-lead-scraper` | Contact/email extraction, B2B prospecting pipelines, SERP leads |
| `apify-web-scraper` | Generic website scraping, Cloudflare bypass, site → markdown for RAG |
| `apify-social-scraper` | Instagram, TikTok, X, Facebook, YouTube, Reddit data extraction |
| `apify-seo-serp` | Google rank tracking, SERP features, keyword research at scale |
| `apify-ecommerce-monitor` | Price/product monitoring, Shopify scraping, stock alerts |
| `apify-amazon-products` | Amazon ASIN data, prices, reviews, affiliate product feeds |
| `apify-job-scraper` | Job postings at scale (aggregators, hiring-signal lead-gen) |

## Get started

### 👉 [Create your free Apify account — monthly credits included](https://console.apify.com/sign-up?fpr=dx06p)

Then grab your API token: Apify Console → Settings → Integrations.

## Why Apify actors

- 5 000+ maintained actors in the Apify Store — most scraping jobs are already solved
- Built-in proxies, headless browsers, retries, scheduling, datasets
- Free tier with monthly credits — no card required

## Skill format

Each skill is a `skills/<name>/SKILL.md` following the [Agent Skills spec](https://github.com/vercel-labs/skills). Compatible with Claude Code, Cursor, Codex, Windsurf, OpenCode, Antigravity, Gemini CLI and more.

## License

MIT — contributions welcome (new actors, better run inputs, more skill categories).
