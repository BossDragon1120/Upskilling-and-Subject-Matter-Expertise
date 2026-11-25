---
name: topic-deep-dive-brief
description: "Use when Dana asks for a deep dive, brief, or primer on a tech/business topic: a researched 5–10 page brief with news, trends, companies, earnings insights, startups, events, people, and numbers."
---

# Topic Deep-Dive Brief

Produce a long-form (5–10 page, roughly 3,000–5,000 words) brief that takes a smart generalist from zero to conversant on a topic. Reader: an experienced tech/strategy professional with an M&A, integration, and go-to-market background. Write for someone who will use this in networking, teaching, and investment-style conversations, so favor "what it means" over "what it is."

## 1. Scope (1 minute)
- Restate the topic and the angle in one line. If the topic is very broad (e.g. "AI"), pick a sharper angle (e.g. "AI agents in the enterprise") and say which you chose at the top of the brief.
- Ask at most one clarifying question, and only if two readings would produce very different briefs. Otherwise proceed.
- Note today's date. "Recent" means the last 90 days; "this year" means the trailing 12 months.

## 2. Research (do it yourself, 15–30 searches)
Claude builds the first-pass source list. Search each bucket separately; don't merge buckets into one query. Use WebFetch to read full pages, not just snippets.

| Bucket | What to find | Where to look |
|---|---|---|
| Recent news | 5–8 most important developments in the last 90 days | Major tech/business press, company newsrooms, trade publications |
| Industry trends | 4–6 structural shifts with evidence | Analyst reports (Gartner, Forrester, IDC, McKinsey, a16z, Sequoia, Bessemer), industry associations |
| Incumbents / public companies | 5–10 key players, how each is evolving (strategy shifts, launches, reorganizations, acquisitions) | Investor relations pages, press releases |
| Earnings insights | 3–6 public companies: latest-quarter transcript or prepared remarks, investor-day decks, shareholder letters, 10-K/10-Q risk factors | IR sites, SEC EDGAR, transcript summaries. Pull what management emphasizes, guidance, metrics they disclose, analyst questions they dodge |
| Startups | 6–12 startups with recent funding (last 12–18 months): stage, amount, lead investor, what's different | Funding announcements, TechCrunch, Crunchbase News, YC/accelerator batches |
| Funding & M&A | Notable rounds, acquisitions, and consolidation patterns | Press releases, deal coverage |
| Policy & regulation | Laws, rules, standards in motion (US, EU, other) | Government sites, policy trackers |
| Events | Upcoming meetups/conferences in San Francisco, Boulder, and virtual, within the next ~90 days | Luma, Meetup, Eventbrite, community Slack/Discord pages, conference sites |
| People | 8–12 people worth following: operators, founders, researchers, investors, analysts, journalists | Their own blogs, X/LinkedIn, newsletters |
| Podcasts & media | 4–6 podcasts (plus 1–2 specific recommended episodes each), 3–5 newsletters | Show sites, episode pages |
| By the numbers | 10–15 hard stats: market size, growth rate, adoption, funding totals, pricing, headcount | Prefer primary sources; record the date of every figure |

Rules:
- Verify that every event date is in the future and confirm the city. If none can be confirmed for a city, say so and list recurring groups instead of inventing dates.
- Every number gets a source and an "as of" date. If sources conflict, give the range and say why.
- Favor primary sources (filings, transcripts, company blogs, government sites) over aggregators.
- Paraphrase; quotes stay short and rare.

## 3. Brief structure
Use these sections in this order. Approximate lengths keep it within 5–10 pages.

1. **TL;DR**: 5–7 bullets a reader could repeat in a meeting. (½ page)
2. **Why this matters now**: what changed in the last 12 months. (½ page)
3. **How it works**: plain-language explainer plus a simple value chain / market map (layers, who sits where). (1 page)
4. **Key terminology**: 12–20 terms, one line each, including jargon insiders use. (½–1 page)
5. **By the numbers**: table of 10–15 stats with source and date. (½ page)
6. **Recent news**: 5–8 items, each with date, what happened, and why it matters. (1 page)
7. **Industry trends**: 4–6 trends, each with evidence and "who wins / who loses." (1 page)
8. **Incumbents & how they're evolving**: per company, current position, recent moves, strategic direction. (1 page)
9. **What management is saying (earnings & filings)**: themes across transcripts, guidance, disclosed metrics, risk-factor language, notable analyst questions. (½–1 page)
10. **Startups to know**: table of name, what they do, stage/funding, investors, why notable. (½ page)
11. **Funding & M&A patterns**: who's buying whom and why; consolidation signals; likely acquirers and targets. (½ page)
12. **Policy & regulation**: what's in motion and its likely impact. (¼–½ page)
13. **Debates & open questions**: the bull case vs the bear case, and what smart people disagree on. (½ page)
14. **What to watch (next 6–12 months)**: specific catalysts, dates, and leading indicators. (¼ page)
15. **People to follow**: name, role, why, and where to follow. (¼–½ page)
16. **Podcasts, newsletters & reading list**: including 2–3 must-read reports or papers. (¼–½ page)
17. **Events: SF, Boulder, virtual**: table of name, date, location/format, link, and who attends. (¼–½ page)
18. **Conversation angle**: where M&A, integration and change-management thinking applies, and 5 sharp questions to ask an insider. (¼–½ page)
19. **Sources**: grouped by bucket, primary sources first, with links and access dates.

## 4. Output
- Build the brief as a Docs artifact (create the doc with the section headings first, then fill each section as research comes in). Use a Word/PDF file only if Dana asks for that format.
- Title: "[Topic] — Deep-Dive Brief (Month YYYY)".
- Use tables for numbers, startups, people, and events; prose for analysis.
- Afterwards, offer to save a short topic note in `topics/<ai|tech|business>/<slug>.md` from `templates/` (`type: topic`, `status: draft`), so the ideas can feed Little Panda Education.

## 5. Check before delivering
- Every stat has a source and date; arithmetic is checked.
- Every event is upcoming and its link works.
- Company facts (who leads what, who acquired whom) are current, not from memory.
- Length is 5–10 pages; cut words rather than shrinking type.
- In the reply: one or two lines on the headline takeaway, plus the doc. Don't recap the sections.