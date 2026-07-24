# PILLAR DRAFT (prose for review)

**Working H1:** How to Increase Your AI Visibility: Getting Your Brand Mentioned by ChatGPT, Perplexity, and Google's AI
**Meta title:** How to Increase Your AI Visibility in 2026
**Meta description:** Your buyers now ask AI who to trust before they reach your site. Here is what the research shows actually gets a brand mentioned in ChatGPT, Perplexity, and Google's AI, and what to ignore.

> Draft covers Sections 1 to 5 and 7 to 11. Section 6 (original experiment data) is a placeholder pending the 30-prompt panel. Every stat, study, and quote carries its source link inline. Copy follows the no-dash rule.

---

## 1. Your buyers now ask AI before they ask you

Something quiet has changed in how a B2B software purchase begins. The first description of your product that a buyer reads is often not written by you. It is written by an AI, summarizing you to someone you will never see click.

The numbers are no longer small. In Forrester's 2026 Buyer Insights survey of 18,000 global business buyers, twice as many buyers named generative AI or conversational search as a more meaningful source of information than any other, ahead of vendor websites, product experts, and sales reps ([Forrester, 2026](https://www.forrester.com/press-newsroom/forrester-2026-the-state-of-business-buying/)). In the same survey, 94% used AI during their most recent purchase: 55% to compare vendors, 54% to research products, and 47% to build the internal business case, much of it before any vendor was contacted ([Forrester, 2026](https://www.forrester.com/press-newsroom/forrester-2026-the-state-of-business-buying/)). Roughly half of B2B software buyers now start their research with an AI chatbot rather than a search box ([G2, via Demand Gen Report](https://www.demandgenreport.com/industry-news/news-brief/half-of-b2b-software-buyers-now-start-their-research-with-ai-chatbots-g2/52737/)).

This lands on top of a buying process that was already mostly invisible to you. Gartner has found that B2B buyers spend only about 17% of their total purchase time meeting with any potential supplier, spread across a buying group of roughly six to eleven people who each arrive with their own independently gathered research ([Gartner](https://www.gartner.com/en/sales/insights/b2b-buying-journey)). Now a large share of that independent research runs through a model that will name a handful of vendors and quietly omit the rest.

That is what "AI visibility" actually protects. Not vanity. The question of whether your name comes up at all in the room where the decision is being shaped.

## 2. What "AI visibility" actually means

The term gets used loosely, so here is the plain version. AI visibility is whether your brand shows up, and shows up accurately, across the AI surfaces your buyers use. Those surfaces are not one thing:

- **Google AI Overviews** are the AI summaries that appear at the top of a normal Google results page.
- **Google AI Mode** is the fuller conversational search experience inside Google.
- **Standalone assistants** are the tools people open directly and ask: ChatGPT, Perplexity, Claude, and Gemini.

You will also see two acronyms. **GEO** (generative engine optimization) usually means optimizing to be cited by generative systems. **AEO** (answer engine optimization) usually means optimizing to be the direct answer to a question. They overlap heavily, and for the purposes of this guide they describe the same goal from slightly different angles: getting chosen, by a machine, as worth mentioning.

The important point is that these surfaces do not all work the same way. Which is the whole reason most advice about them is wrong.

## 3. The two different games

Here is the distinction almost nobody draws, and it is the one that saves you money.

**For Google's own AI, it is still SEO.** Google is unusually direct about this in its own documentation: optimizing for its generative features is, in its words, still search engine optimization, because AI Overviews and AI Mode are built on the same index and the same ranking systems as regular Search ([Google Search Central](https://developers.google.com/search/docs/fundamentals/ai-optimization-guide)). There is no separate AI index to game and no secret file that unlocks it. If you already do genuine, well-structured SEO, you are already most of the way there. (I broke down exactly what Google says, section by section, in [What Google actually says about ranking in AI search](/blog/what-google-says-about-ranking-in-ai-search).)

**For standalone assistants, citation is its own game.** This is where the "it is all just SEO" line stops being true. Systems like ChatGPT and Perplexity do not simply rank a list. They retrieve a set of pages and then decide which few to actually cite in the answer. Being retrievable gets you into consideration. Being cited is a separate outcome, and peer-reviewed research shows it responds to specific, measurable properties of your content that are not the same as classic ranking signals. Two academic studies (next section) put real numbers on this.

So the honest framing is: for Google's AI, do excellent SEO. For standalone assistants, do excellent SEO and then optimize specifically for citation. Anyone selling you a single mystical "GEO method" that ignores this split is selling you half a truth.

## 4. What the research actually says gets you cited

Most writing on this topic is opinion. There is now real evidence, and it is worth reading before you spend a dollar or an afternoon.

**Optimizing content measurably raises visibility in AI answers.** In the paper that introduced the term, *GEO: Generative Engine Optimization* (Aggarwal et al., accepted to KDD 2024), the authors built a benchmark of real queries and showed that targeted content changes could increase a source's visibility in generative engine responses by up to 40%, with the effect varying by domain ([arXiv:2311.09735](https://arxiv.org/abs/2311.09735)). Visibility is not random. It moves in response to how content is written.

**But citation has gatekeepers.** The larger and more recent study, *What Gets Cited: Competitive GEO in AI Answer Engines* (SIGIR 2026), ran 252,000 controlled trials across six different language models, testing 18 content factors with brand names hidden and source order counterbalanced so they measured content, not reputation ([arXiv:2605.25517](https://arxiv.org/abs/2605.25517)). The findings split cleanly into two tiers.

Some factors are **gatekeepers**. Fail one and your citation odds collapse, regardless of everything else:

- **On-topic relevance.** Off-topic content is not rescued by any other quality.
- **Explicit pricing.** Content that stated pricing was dramatically more likely to be cited than content that omitted it.
- **Recency.** A current date beat a stale one by a wide margin.
- **List position.** Being higher in the retrieved set still mattered strongly.

Other factors are **boosters**. Once the gatekeepers are satisfied, these separate you from the pack:

- **Statistics and specific numbers.**
- **Concrete specifications** rather than vague description.
- **Evidence for claims** rather than unsupported assertion.
- **Direct comparisons** against alternatives.
- **Confident, non-hedged language.**

Read that booster list again, because it is quietly the most useful thing in this guide. The properties that make content citable by AI are the same properties that make content genuinely good: numbers, specifics, evidence, honest comparison, a clear point of view. There is no trick. There is a standard, and most content does not meet it.

## 5. The myths to stop paying for

A whole market has grown up selling AI visibility as a set of secret mechanical tricks. Google names several of these directly in its own guidance and says plainly that they do not help ([Google Search Central](https://developers.google.com/search/docs/appearance/ai-features)):

- **"AI text files" such as llms.txt.** You do not need to create special machine-readable files to appear in Google's AI features. Making one neither helps nor hurts.
- **Chunking content into tiny fragments** so AI can supposedly parse it. There is no requirement to break content into small pieces for AI to understand it.
- **Writing in a special "AI-friendly" style.** The systems understand synonyms and normal meaning. There is no secret phrasing that ranks better.
- **Manufacturing fake "mentions"** across the web to fabricate citations. Quality systems focus on genuine signals, and other systems exist specifically to catch this kind of manipulation.

Every item on that list is a way to feel busy without being better. The research in Section 4 points the other way entirely: toward content that is more specific, more evidenced, and more current. That is harder to fake, which is exactly why it works.

## 6. I ran 30 buyer prompts through five AI engines. Here is what I found

Everything above is drawn from other people's research. This part is mine.

**The method.** I wrote 30 buyer prompts, the kind a real B2B software buyer types, spread evenly across six categories: maintenance software, project management, CRM, cybersecurity, HR and payroll, and customer support. Within each category the prompts covered five shapes of question: open category discovery ("what is the best X"), segment fit ("best X for a small team"), head to head ("A vs B vs C"), alternatives ("alternatives to X"), and the founder framing ("which X is easiest to set up"). I ran every prompt through five surfaces: ChatGPT, Perplexity, Gemini, Claude, and Google's AI Overview.

One deliberate choice matters for how you read this. I did not use paid power user accounts or hand pick which model answered. I used brand new free accounts and took whichever model each tool opened with by default, the way an ordinary buyer would who is not a power user and has not tuned anything. The point was to see what a normal person actually gets, not what an expert can coax out.

**What that surfaced first was a limitation worth reporting, not hiding.** Perplexity's free tier ran out of queries partway through the first pass. It was the only one of the five that did. ChatGPT, Gemini, and Claude all ran the full 30-prompt set in a single free-account session; Google's AI Overview has no login at all. Perplexity took a second session, on a second day, on a second free account, to finish. That is itself a small finding: of the standalone assistants, Perplexity puts the tightest cap on a free user, which shapes how often an ordinary buyer actually reaches for it versus the other three.

Two more honest caveats. These are single runs, not repeated trials, so treat the patterns as directional, not statistically bulletproof. And AI answers drift over time, so this is a snapshot from late July 2026, not a permanent ranking. With that said, the patterns were consistent enough across 30 prompts and six unrelated categories that they are hard to dismiss.

### Finding 1: the engines crowd around the same few names

In every one of the six categories, the five engines converged on the same two or three incumbent brands, then scattered across a long tail that only showed up in one or two answers. Maintenance software returned MaintainX almost every time. Project management circled Jira and Linear. CRM came back to HubSpot and Pipedrive. Cybersecurity to CrowdStrike and SentinelOne. HR to Rippling and Gusto. Support to Zendesk and Intercom.

Of the 30 prompts, 5 were not really "who's best" questions at all: three-way head-to-heads and pure decision frameworks that do not have a single winner by design. Of the 25 that were, the panel converged strongly on one name in about 11, roughly four in every ten. Another handful showed partial agreement, two or three of the five engines landing on the same brand while the rest scattered. In the remaining third, there was no consensus at all: five different engines, five different favorites. Put plainly: **AI does not hand out attention evenly, but it is not monolithic either.** For a genuinely dominant category incumbent, the engines mostly agree with each other. For anything else, the "top pick" you get depends heavily on which engine your buyer happened to open. If you are not one of the two or three default names in your category, the goal is not to leapfrog them tomorrow. It is to get into the tail, and then into the consideration set, consistently, on the engines where the field is actually still open.

### Finding 2: the question shape decides whether a newcomer appears at all

The prompt type changed the answer more than any single engine did.

"A vs B vs C" prompts almost never introduced a fourth option. Ask an engine to compare three named tools and it compares those three, full stop. But "alternatives to X" prompts did the opposite: they were an open invitation, and that is where the smaller and newer vendors surfaced. Names like Oxmaint, Fabrico, Tractian, Attio, WorkOS, and Plain appeared far more in "alternatives" answers than anywhere else.

The implication is sharper than it looks. **You cannot win a comparison you were never entered into.** A head to head only ranks the names already in the prompt, so being the fourth name a buyer never typed does you no good there. The place a newcomer actually gets discovered is the "alternatives" and open discovery questions, which means the job is to be the credible non obvious answer, not to beat a specific competitor head on.

### Finding 3: the five engines behave like different animals

They are not interchangeable, and optimizing for them is not one job.

- **Perplexity and Gemini cited real source links** the most, dropping named citations to specific pages inside their answers. These are the surfaces where being a retrievable, citable page matters most directly.
- **ChatGPT and Claude mostly named brands without linking sources**, reading more from digested knowledge than live citation. Different surface, different lever.
- **Claude was the consistent skeptic.** Across unrelated categories it repeatedly flagged that "best of" lists are "bought and paid for" and pushed the reader toward testing over rankings. If Claude matters to you, sounding evidenced rather than promotional appears to count for more there.
- **Google's AI Overview stayed shortest and least diverse**, usually a sentence or two naming only the consensus leaders, and in a couple of cases it returned a plain featured snippet instead of an AI answer at all. It is the hardest surface to break into and the smallest to influence.

### Finding 4: both channels earn citations, not just one

Going in, I expected the citations to lean heavily toward third party review sites, since that is the standard advice: get onto G2, get onto Capterra, get reviewed on Reddit. The transcripts do show plenty of that. Reddit threads, G2, TechRadar, and Forbes all show up repeatedly as sources, especially from Perplexity and Gemini.

But a real share of the citations went somewhere else: the vendor's own site. Small maintenance and CRM tools were cited straight from their own comparison and pricing pages, not through a review site at all. Oxmaint and Fabrico, two names most people have never heard of, got cited directly from their own blogs in the CMMS "alternatives" prompts. Pipedrive, WorkOS, and Zendesk showed up cited from their own product and pricing pages elsewhere in the set.

The honest read is that it is not either or. **Third party presence and your own published content both function as real citation sources**, and the second one is the part most "get listed on G2" advice leaves out entirely. That lines up with the gatekeeper factors from the research in Section 4: on topic, priced, recent, evidenced. A page that meets that bar can earn its own citation directly. It does not have to borrow all of its credibility from somewhere else.

### What this experiment cost to run

Worth saying plainly, since it is a real part of the method: this was not automated. Thirty prompts, five engines, one at a time, read and logged by hand, on free accounts, the way an actual buyer would run into these tools. It took two sessions to get through Perplexity alone. If you are reading advice about AI visibility that was clearly generated by a tool rather than actually observed, that is worth noticing.

## 7. The playbook: what to actually do

Translated from the evidence above into an order of operations any business can follow.

1. **Fix retrievability first.** If Google cannot cleanly crawl, index, and render your pages, nothing downstream matters, and this is still ordinary SEO ([Google Search Central](https://developers.google.com/search/docs/fundamentals/ai-optimization-guide)). Indexed, snippet-eligible, semantic HTML, unblocked JavaScript, minimal duplication.
2. **State your pricing.** The single clearest gatekeeper in the citation research. If your pricing is hidden, you are handing the citation to a competitor who published theirs ([arXiv:2605.25517](https://arxiv.org/abs/2605.25517)).
3. **Keep it current.** Recency is a gatekeeper. Stale dates lose. Maintain and visibly update your key pages.
4. **Lead with numbers, specifics, and evidence.** The booster factors. Replace adjectives with figures, claims with proof, description with specification.
5. **Publish honest comparisons.** Direct comparison content is both a citation booster and the exact format buyers ask AI for (best X, X versus Y, alternatives to X).
6. **Earn genuine third-party presence.** AI answers lean heavily on independent sources. Being present and accurate on the review sites and communities your buyers trust feeds the systems that cite them.
7. **Measure, then repeat.** Instrument it (Section 9) so you are improving against reality, not guessing.

## 8. If you run a B2B SaaS product specifically

Everything above applies to any business. Here is where it gets specific for B2B SaaS, because the buying pattern is different.

**You are being evaluated by a committee, through a machine.** With buying groups of roughly six to eleven people each doing independent research ([Gartner](https://www.gartner.com/en/sales/insights/b2b-buying-journey)), the AI answer is often the common starting reference several stakeholders share. You are not trying to win one searcher. You are trying to be the vendor that keeps surfacing across a group's separate queries.

**The queries are predictable, so own them.** B2B SaaS buyers ask AI in recognizable shapes: category discovery (best CMMS for manufacturers), segment fit (best CRM for a small sales team), head-to-head (Zendesk versus Intercom), alternatives (alternatives to Salesforce), and job framing (which tool is easiest for a founder-led team). Each of those is a page you can own with genuine, specific, current comparison content.

**Third-party sources carry unusual weight for SaaS.** Review platforms such as G2 and Capterra, and communities such as Reddit, appear repeatedly in AI answers about software. For SaaS specifically, your presence and accuracy on those platforms is not a side channel. It is part of your AI visibility, because it is part of what the model reads before it answers.

**Optimize for pipeline, not traffic.** A consumer brand wants reach. You want the right eight people at one account to keep seeing you named as a credible option. That reframes success from visits to whether you are consistently in the consideration set the committee assembles.

## 9. How to measure your AI visibility

You cannot improve what you cannot see. Three layers to instrument:

- **AI referral traffic.** Traffic arriving from AI tools is now a real and fast-growing channel. Referrals from AI sources grew many times over between 2024 and 2026, with ChatGPT driving the majority ([SE Ranking research](https://seranking.com/blog/ai-traffic-research-study/)). Track it in GA4 by isolating referrals from the AI domains, so you can see which pages actually earn it. (Full method in the measurement guide, linked below.)
- **Google's own AI performance data.** Google reports AI-surface performance inside Search Console, so you can watch impressions and behavior instead of guessing ([Google Search Central](https://developers.google.com/search/docs/appearance/ai-features)).
- **Direct mention tracking.** Periodically run the real prompts your buyers use across ChatGPT, Perplexity, Gemini, and Google AI Overviews, and record whether and how you appear. This is exactly the method behind the experiment in Section 6, and it is the most honest read on where you actually stand.

Two related realities make this worth doing now rather than later. A randomized field experiment found Google AI Overviews cut organic clicks on triggered queries by about 38%, with zero-click searches rising from 54% to 72% when an overview appeared ([Search Engine Journal](https://www.searchenginejournal.com/ai-overviews-cut-organic-clicks-38-field-study-finds/573145/)), and by 2026 fewer than a third of Google searches still send a click at all ([SparkToro](https://sparktoro.com/blog/in-2026-less-than-one-third-of-google-searches-still-send-a-click/)). Being named inside the answer is increasingly the visibility that remains.

## 10. Where to go next

This guide is the map. The detailed tactics live in the pieces it links to:

- Why your SaaS does not show up in AI answers, and how to fix it
- How AI assistants choose which products to recommend
- AI SEO versus traditional SEO for B2B SaaS
- How to measure AI referral traffic in GA4 and Search Console
- AI visibility tools: what they actually show you
- How to get your SaaS cited on the sources AI trusts
- The AI visibility checklist for B2B SaaS (free)

If you would rather have this handled than do it yourself, that is what [AI SEO services for B2B SaaS](/ai-seo-services) is for.

## 11. FAQ

**How do I get my business to show up on AI?**
Make sure your key pages are cleanly indexable by Google, state concrete details like pricing, keep them current, and publish specific, evidenced, comparison-style content. For standalone assistants, also build accurate presence on the third-party sites and communities they cite. See Sections 4 and 7.

**How do I get AI to suggest my business?**
Being suggested is a citation decision, and citation responds to specific content properties: on-topic relevance, explicit pricing, recency, and supporting evidence and statistics, per controlled research across six models ([arXiv:2605.25517](https://arxiv.org/abs/2605.25517)). Meet those and you move from retrievable to recommended.

**How do I increase AI visibility for my website specifically?**
Start with retrievability (Google's AI uses the same index as Search), then add the citation boosters. It is ordinary SEO plus a deliberate layer of specificity and evidence.

**Is AI visibility just SEO?**
For Google's AI Overviews and AI Mode, largely yes, by Google's own account ([Google Search Central](https://developers.google.com/search/docs/fundamentals/ai-optimization-guide)). For standalone assistants like ChatGPT and Perplexity, no: citation is a separate outcome with its own measurable factors.

**Do I need an llms.txt file or special AI formatting?**
No. Google states these are not required and do not confer an advantage ([Google Search Central](https://developers.google.com/search/docs/appearance/ai-features)). Spend the effort on content quality instead.
