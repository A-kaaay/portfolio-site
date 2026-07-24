# AI Visibility Content Roadmap

Last updated: 2026-07-24

Funnel: **homepage** (money page, retargeted title/meta only) ← **informational pillar** (hub) ← **cluster blogs/guides** (spokes). Clusters link up to the pillar; the pillar links to the homepage as its conversion CTA.

Titles are kept clean of em dashes and hyphens (copy rule). All keyword volumes/difficulty are from OpenSEO pulls on 2026-07-23/24. "Emerging" = real query, near-zero measured volume, first-mover bet.

---

## Layer 1 — Commercial capture: retargeted homepage (not a separate page)

Decision (2026-07-24): skip building a dedicated service page. The homepage (`index.html`) already has the full offer, proof, pricing, process, and FAQ — a second page would duplicate it and risk cannibalizing the same commercial intent. Instead, retargeted the homepage's `<title>` and meta description only. Hero, H1, and all visible copy unchanged.

Confirmed via Ahrefs (US, 2026-07-24) — replaces earlier OpenSEO estimates:

| Keyword | Volume | KD | Notes |
|---|---|---|---|
| ai seo services | 4,200 | 11 | Primary anchor, in title |
| ai seo company | 1,800 | 15 | |
| generative engine optimization agency | 1,200 | **9** | Full spelled-out GEO term, clean signal |
| generative engine optimization services | 1,700 | 19 | |
| geo agency | 1,000 | 22 | Category "SEO and marketing," parent kw "siegemedia" — legit despite "Local" tag |
| aeo services | 1,000 | 5 | Watch: category tagged "Apparel," some branded intent — treat cautiously |
| chatgpt seo | 800 | 17 | |
| aeo agency | 700 | 13 | |
| ai seo companies | 200 | 5 | |
| ai visibility agency | 150 | 6 | Matches pillar framing |
| ai seo for saas | 70 | **2** | Exact positioning match, near-zero difficulty, low volume — body copy candidate, not title |

**Confirmed contaminated, do not target:** `geo services` (600 / KD 40, category "Consulting; Geology," parent kw "geo group") and `geo consultant` (20 / KD 24, parent kw "geo environmental consultants") — both are land/environmental consulting, not generative engine optimization. `seo agency` (56,000 / KD 11) is misleadingly low-KD for how saturated it actually is with local-pack and big-agency competition — not realistically winnable, ignore despite the score.

**Live edit made:**
- Title: `AI SEO Services (GEO) for B2B SaaS | Ali Kamran`
- Meta description: `AI SEO services and generative engine optimization for B2B SaaS: get your brand cited by ChatGPT, Perplexity, and Google's AI. Start with a fixed-price, one-week audit.`
- Status: [x] Done (2026-07-24)

---

## Layer 2 — Pillar page (informational, the hub)

Broad H1/meta, narrows to B2B SaaS inside the body.

| Field | Value |
|---|---|
| Title / H1 | How to Increase Your AI Visibility: Getting Your Brand Mentioned by ChatGPT, Perplexity, and Google's AI |
| Meta title | How to Increase Your AI Visibility in 2026 |
| Primary keyword | how to increase ai visibility for my business (PAA-backed broad query) |
| Secondary | ai search visibility, how do I get my business to show up on ai |
| Intent | Informational, top of funnel |
| Contains original data | Yes — the prompt-panel experiment (Section 6) |
| Status | [ ] Outline under review |

Section outline under discussion separately. Publishes as a complete standalone guide; cluster links get wired in as each spoke ships.

---

## Layer 3 — Cluster blogs/guides (informational, narrowed to B2B SaaS)

Tiers: **Traffic** = real volume, win on quality. **Intent** = low volume, ready buyer. **First-mover** = emerging term + gives the pillar topical depth. **Anchor** = already live.

| # | Title | Primary keyword | Vol / KD | Tier | Status |
|---|---|---|---|---|---|
| 1 | Why Your SaaS Doesn't Show Up in AI Answers | how do I get my business to show up on ai | emerging | Intent | [ ] |
| 2 | How AI Assistants Choose Which Products to Recommend | how does chatgpt decide what to recommend | emerging | First-mover (SIGIR-backed) | [ ] |
| 3 | AI SEO vs Traditional SEO for B2B SaaS | ai seo tools (2,400 / KD 15); seo for ai search (260 / KD 35) | mixed | Traffic | [ ] |
| 4 | How to Measure AI Referral Traffic in GA4 and Search Console | track chatgpt referral traffic | emerging | First-mover (own data) | [ ] |
| 5 | AI Visibility Tools: What They Actually Show You | ai visibility tools (1,600 / KD 19); ai visibility tracker (390 / KD 21) | real volume | **Traffic (magnet)** | [ ] |
| 6 | How to Get Your SaaS Cited on the Sources AI Trusts | how to get cited by chatgpt | emerging | First-mover (experiment-backed) | [ ] |
| 7 | The AI Visibility Checklist for B2B SaaS (gated lead magnet) | ai visibility checklist | low | Lead magnet | [ ] |
| 8 | What Google Actually Says About Ranking in AI Search | already ranking | — | Anchor (needs update, see below) | [x] Live |

---

## Supporting workstreams

### Original research experiment
- Brief: `research/prompt-panel-experiment.md`
- 30 buyer prompts × 5 AI engines (ChatGPT, Perplexity, Gemini, Claude, Google AI Overview)
- Run by a separate browser-enabled Claude session
- Output feeds pillar Section 6 and the #6 cluster piece
- Status: [x] Complete (2026-07-24) — 30 prompts × 5 engines, all rows filled including Perplexity (took 2 sessions due to free-tier limits). Findings written into `research/pillar-draft.md` Section 6. Not yet copied into the live HTML guide.

### Existing post update
- File: `blog/what-google-says-about-ranking-in-ai-search.html`
- Add a bridging section: Google's AI (still SEO) vs standalone assistants (real citation factors), linking into the new pillar
- Reconciles the "it's still SEO" claim with the KDD/SIGIR research
- Status: [ ] Not started

### Lead magnet gating (Netlify)
- `data-netlify="true"` form → redirect to gated checklist / thank-you page
- Powers cluster piece #7
- Status: [ ] Not started

### YouTube companions
- Required for cluster #1 and the pillar (video showed repeatedly in AI Overviews for this query cluster)
- Status: [ ] Not started

---

## Key stats bank (for citing in content, primary sources only)

- Forrester 2026 Buyer Insights (~18,000 buyers): 2x as many named generative AI / conversational search as their most meaningful research source than any other
- G2 / Demand Gen Report: ~half of B2B software buyers start research with AI chatbots
- Gartner: buyers spend only ~17% of purchase time with any one supplier; ~27 total interactions; buying group ~6 to 11 people (https://www.gartner.com/en/sales/insights/b2b-buying-journey)
- Ahrefs (Feb 2026): AI Overviews cut top-result CTR ~58%
- SparkToro (2026): <1/3 of Google searches still send a click
- Search Engine Land: zero-click ~68% early 2026
- AI referral traffic grew ~16x from 2024 to 2026; ChatGPT ~75%+ of AI referrals (SE Ranking / Conductor)
- GEO paper (Aggarwal et al., KDD 2024, arXiv 2311.09735): optimization raised visibility in generative responses up to 40%
- "What Gets Cited" (SIGIR 2026, arXiv 2605.25517): 252k trials, 6 LLMs, 18 factors. Gatekeepers: on-topic, pricing mentioned, recent timestamp, list position. Boosters: statistics, specifications, evidence for claims, comparisons

Avoid aggregator sites (demandsage, memeburn, thestacc, omnibound) — they recycle numbers. Cite the primary source above.
