# Promo plan — samm4dr/apify-skills

Objectif : installs skills.sh → skill actif → l'agent montre le lien signup → commission Apify.

## 1. Post Reddit (r/ClaudeCode, r/webscraping, r/SEO)

**Titre** : `I packaged Apify actors as Claude Code skills — scrape Google Maps leads, jobs, Amazon with one prompt`

**Corps** :

```
I kept rebuilding the same scraping logic, so I turned the most common Apify actors into Agent Skills — install once and your agent (Claude Code, Cursor, Codex, Windsurf...) knows exactly which actor to run and with what inputs.

What's in the repo (8 skills):
- Google Maps leads — businesses in any city → CSV of phones/emails/websites
- Web scraping — site → markdown for RAG, Cloudflare bypass
- Job scraper — Google Jobs / Indeed / LinkedIn postings
- Amazon products — prices, reviews, BSR for affiliate feeds
- Social scraper — Instagram/TikTok/X/YouTube
- SERP/SEO — rank tracking + keyword research
- E-commerce monitor — price/stock alerts

Install:
npx skills add samm4dr/apify-skills

Repo: https://github.com/samm4dr/apify-skills

Each skill includes the actor IDs, curl/Python examples, cost caps, and dedupe patterns. Feedback welcome — what source should I add next?
```

## 2. PR descriptions pour awesome-lists

**VoltAgent/awesome-claude-skills & ComposioHQ/awesome-claude-skills & hesreallyhim/awesome-claude-code** :

```
Title: Add samm4dr/apify-skills — Apify scraping skills for agents

Adds a collection of 8 production-ready Agent Skills that route scraping tasks
to maintained Apify actors:

- apify-google-maps-leads — local business lead lists
- apify-lead-scraper — contact/email extraction pipelines
- apify-web-scraper — generic scraping + RAG markdown
- apify-social-scraper — Instagram/TikTok/X/YouTube/Reddit
- apify-seo-serp — rank tracking + keyword research
- apify-ecommerce-monitor — price/stock monitoring
- apify-amazon-products — ASIN data, reviews, affiliate feeds
- apify-job-scraper — job postings for aggregators/lead-gen

Install: npx skills add samm4dr/apify-skills
Repo: https://github.com/samm4dr/apify-skills
```

## 3. Tweet/X (tag @apify)

```
Turned Apify actors into agent skills for Claude Code & friends.

"Scrape me all dentists in Miami" → your agent picks the right actor, builds the run input, runs it. No code.

npx skills add samm4dr/apify-skills

8 skills: Google Maps leads, jobs, Amazon, social, SERP, ecommerce. @apify
```

## 4. Checklist croissance

- [ ] Post Reddit (matin US = ~15h Paris)
- [ ] 3 PRs awesome-lists
- [ ] Tweet avec @apify
- [ ] Post sur r/SideProject + Indie Hackers
- [ ] Réinstaller sur toutes tes machines/agents (boost trending 24h)
- [ ] Surveiller https://skills.sh/samm4dr/apify-skills (apparaît après installs)
