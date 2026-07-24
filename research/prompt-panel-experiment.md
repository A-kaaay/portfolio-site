# AI Visibility Prompt-Panel Experiment — Brief for the browser session

## Paste everything below into a fresh Claude session that has browser access

---

**Your task:** Run an original data experiment on how AI engines answer B2B software buyer questions. I need structured results I can quote in a published guide, so accuracy and consistent formatting matter more than speed.

### The goal
For a set of 30 buyer-intent prompts, find out — across 5 different AI engines — **which brands each engine recommends** and **which websites it cites as sources**. This produces original stats like "third-party sites accounted for X% of citations" and "the 5 engines agreed on a brand only Y% of the time."

### The 5 engines to test (in this order, per prompt)
1. **ChatGPT** (chatgpt.com) — use a fresh chat, logged out if possible; if login is required, start a new chat and do not rely on memory/personalization
2. **Perplexity** (perplexity.ai)
3. **Google Gemini** (gemini.google.com)
4. **Claude** (claude.ai) — fresh chat
5. **Google AI Overview** — run the query at google.com and read the AI Overview box at the top (note if none appears)

### Method rules (these protect the credibility of the data)
- Run each prompt **once per engine**, verbatim. Do not rephrase or add follow-ups.
- **Fresh session / new chat** for every prompt so answers don't contaminate each other.
- **Logged out where possible**; note where you had to log in.
- Record the **date** and, if visible, the **model version** for each engine.
- For each answer, capture **the order brands are mentioned** (order matters) and **every source/citation domain** shown.
- If an engine refuses to rank, or gives no direct answer, record that too — it's a finding.
- Take a screenshot of each answer as a receipt where you can.

### What to record — one row per (prompt × engine)
Produce a single markdown table (and, if you can, a CSV) with these columns:

| prompt_id | category | query_type | engine | date | direct_answer (Y/N) | brands_mentioned (in order) | num_brands | first_brand | sources_cited (domains, in order) | num_sources | notes |

### After the runs, give me a short summary with these headline numbers
1. Total unique brands mentioned across everything
2. % of citations that came from **third-party sites** (G2, Capterra, Reddit, TrustRadius, review blogs) vs **vendor's own site**
3. The 5 most-cited domains overall
4. How often all engines that answered agreed on the #1 brand (agreement rate)
5. Which query types triggered a Google AI Overview and which didn't
6. Any engine that consistently refused to make recommendations

---

## The 30 prompts

**CMMS / maintenance software**
1. What is the best CMMS software for manufacturers?
2. Best maintenance management software for small manufacturing plants
3. MaintainX vs UpKeep vs Fiix — which is best?
4. What are good alternatives to UpKeep for CMMS?
5. How do I choose a CMMS for a mid-sized factory?

**Project management software**
6. What is the best project management software for software teams?
7. Best project management tool for a remote agency
8. Asana vs Monday.com vs ClickUp for a growing team
9. What are the best alternatives to Jira for product teams?
10. What project management software do startups use?

**CRM software**
11. What is the best CRM for B2B startups?
12. Best CRM for a small sales team
13. HubSpot vs Salesforce vs Pipedrive for SMBs
14. What are good alternatives to Salesforce for small business?
15. Which CRM is easiest to set up for a founder-led sales team?

**Cybersecurity software**
16. What is the best endpoint security software for mid-market companies?
17. Best identity and access management tools for SaaS companies
18. CrowdStrike vs SentinelOne for a growing company
19. What are alternatives to Okta for single sign-on?
20. What cybersecurity tools does a Series A startup need?

**HR / payroll software**
21. What is the best HR software for startups?
22. Best payroll software for small businesses
23. Rippling vs Gusto vs BambooHR — which should I pick?
24. What are good alternatives to BambooHR?
25. Which HR platform is best for a distributed remote team?

**Customer support / helpdesk software**
26. What is the best customer support software for SaaS?
27. Best helpdesk software for a small support team
28. Zendesk vs Intercom vs Freshdesk for B2B SaaS
29. What are alternatives to Zendesk for startups?
30. Which customer support tool is best for a product-led SaaS company?

---

### Query-type key (for the query_type column)
- Prompts 1, 6, 11, 16, 21, 26 = **category-discovery**
- Prompts 2, 7, 12, 17, 22, 27 = **segment-specific**
- Prompts 3, 8, 13, 18, 23, 28 = **head-to-head comparison**
- Prompts 4, 9, 14, 19, 24, 29 = **alternatives**
- Prompts 5, 10, 15, 20, 25, 30 = **job-to-be-done / founder framing**

This 6-categories × 5-query-types design lets the results be cross-tabbed by category and by query type, which is what makes the findings quotable.
