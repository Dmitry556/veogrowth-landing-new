# veogrowth.com — full site content & brand handoff

Handoff document — everything needed to brief another Claude (or anyone) on veogrowth's positioning, site copy, and brand system.

**Status:** Live at https://www.veogrowth.com (deployed on Vercel, single-file static site).
**Repo:** https://github.com/Dmitry556/veogrowth-landing-new
**Local path:** `/Users/dmitry/veogrowth-site-v2/index.html`

---

## 1 · Brand & positioning

**Company:** veogrowth
**Operator:** Dmitry (solo)
**Category name:** outbound operations
**One-line pitch:** Managed outbound system that puts net-new meetings with companies your reps aren't working yet onto their calendars.

**Positioning claim:** Between an agency (trusting humans you can't see) and a platform (doing the work yourself). A managed system — I operate it, you see what it produces every week, everything it generates lives with your team.

**ICP:** VP Sales / Head of Revenue / Founder at 40–90 person B2B SaaS/tech companies with 2–7 reps. Has hired and fired at least one agency. Has tried or been embarrassed by one AI SDR. Under board/CEO pressure for net-new pipeline. ~19-month avg tenure (ejector seat).

**Buyer trauma / filter:** built for teams who've already been through an agency AND an AI SDR.

**Vocabulary rules:**
- Use: operations, managed, operated, system, outputs, accounts, buyers, net-new pipeline
- Never use: agency, cold email, growth hacker, AI SDR (except when positioning against), "leverage" as a verb, synergy, unlock, transform, 10x, scale (as verb directed at buyer)

**LinkedIn profile headline** (under the name):
`Building and operating net-new pipeline systems.`

---

## 2 · Pricing & guarantee

- **$3,000 / month** — billed monthly, net-15
- **3-month commitment** (voids if guarantee fails)
- **Setup: $0**
- **Cancel after month 3:** 30 days' notice
- **Guarantee:** First qualified meeting in **14 days** of launch, or month one refunds in full AND the three-month commitment is voided. Client keeps everything the system produced.
- **Qualified definition:** a prospect at an ICP-fit account who agreed to a meeting, attended, and isn't a current customer or on the do-not-contact list.

**Capacity indicator** (shown on site hero): Currently accepting **2 new clients** this quarter.

---

## 3 · Design system

### Colors
- Paper (main bg): `#EFE8DA`
- Paper-2 (subtle contrast bg): `#E6DECC`
- Ink (body text): `#14110D`
- Ink-2 (soft): `#2A241D`
- Muted (captions/labels): `#857A6A`
- Rule (borders): `#C9BEA8`
- Signal (primary accent): `#C83A0E` · bolder variant `#E8490B`
- Forest (guarantee block bg): `#1B2A1A` — paired with amber `#E8B63A` highlights
- Highlight (subtle marker): `#FFEDB3`

### Typography
- **Display:** Fraunces (variable: opsz 144, SOFT 60–100, WONK 1) — used in H1/H2/H3; italic + WONK on emphasis words, colored signal-orange
- **Body:** Instrument Sans
- **Technical / labels / eyebrows:** JetBrains Mono (11–12px, letter-spacing .14–.22em, uppercase for labels)

### Layout
- Warm bone paper background with subtle grain overlay (SVG fractal noise)
- 0.5px hairline borders on cards / rules between sections
- Editorial dossier register — restrained, dense, precise
- No gradients except hero radial in finale; no flashy animations; reveal-on-scroll only

### Logo
Two-stage constellation mark — filled burnt-orange diamond, short dashed hairline connector, outlined diamond (stroke inherits `currentColor`).
- Reading: filled node = the operated system · hairline = the handoff · outlined node = your pipeline (empty until filled).
- **Wordmark:** `v eo growth` — Fraunces with italic burnt-orange `eo`
- **Favicon:** square-adapted constellation (two diamonds stacked vertically; filled orange on top, cream-outlined below)

---

## 4 · Site structure (nav order)

Top nav: **How it works · Example · Pricing · FAQ · Book a call (Calendly)**

Sections on page (top → bottom):
1. Hero
2. Built for (3 trauma cards + summary)
3. The System (5 agents + operator tile)
4. One account, end-to-end (5-tab demo)
5. What you receive (6 output cards)
6. The guarantee (priced-as-infrastructure block — dark forest bg)
7. Who's running this (operator paragraph)
8. FAQ (5 questions)
9. Finale — "Want to see how the system runs?"
10. Footer

---

## 5 · Full site copy

### Meta

- **Title:** Outbound operations, operated end-to-end — veogrowth.
- **Description:** Net-new pipeline as a managed system. Five agents, one operator, first qualified meeting in 14 days.

### Nav

`◆ veogrowth` · How it works · Example · Pricing · FAQ · **Book a call** (→ https://calendly.com/veogrowth/discovery)

### Hero

**Eyebrow:** OUTBOUND OPERATIONS

**H1:** Net-new pipeline, *operated* end-to-end.

**Subhead:** A managed system that learns your business, then puts meetings with companies your reps aren't working yet onto their calendars. Built for B2B sales leaders who've already been through an agency and an AI SDR and need the version of outbound that still works.

**Primary CTA:** Book a call → (opens Calendly)

**Guarantee tag:** First qualified meeting in 14 days, or month one is free.

**Capacity:** Currently accepting **2 new clients** this quarter.

---

### Built for

**Label:** built for
**H2:** You've tried the *other* options.

**Card 01 — *Hired an agency.*** Generic sequences, a junior account manager learning your ICP on your dime, no visibility into what's actually running. You paid for six months and got a Slack channel.

**Card 02 — *Tried an AI SDR.*** Thousands of emails, zero replies, copy your buyers could smell was automated from five feet away. The tool worked. Nobody was operating it.

**Card 03 — *Built it in-house.*** Hired an SDR fully loaded, spent three months on ramp, and realized you needed tooling, infrastructure, and a manager the SDR didn't have.

**Summary (below cards):**
You need **net-new pipeline**. You can't afford a miss to the board. And whichever option you tried, it didn't put net-new meetings on your reps' calendars.

---

### The System

**Label:** the system
**H2:** Five agents. *One* operator. Your pipeline.

**Intro:** Before any of it runs, the system has to learn your business. That's week one. Every account gets the same depth after that. Every email gets the same care. Every meeting gets the same preparation. The system runs continuously.

#### Foundation · Context Agent — Learns your business before anything else runs

*(Visually set apart from the five numbered agents — sits upstream, eyebrow "THE FOUNDATION", paper-2 background.)*

Before the system sends a single email, it has to understand your product the way your best AE does. Week one is intake: your positioning, your ICP in detail (not a firmographic filter — the actual buyer psychology), your best customers and why they bought, the deals you lose and why, your voice and what makes your emails sound like you, your disqualifiers, your competitors, and what a good meeting looks like versus a bad one. The output is a structured context document the other five agents read from on every run.

*Output:* Your company's operating context, documented. Updated as the system learns what works. Your team keeps it if we stop working together.

*Pull-out callout (aside):* The context document is typically 40–80 pages after week two. Every claim in it sourced from founder and rep interviews, customer calls, CRM data, or competitive research — not assumed. The reason the other agents produce specific output is that this document exists.

*Divider label between Foundation and 5 agents:* "The five agents that run on top of it"

#### 01 · Targeting Agent — Builds your account universe
Sources every company in your total addressable market. Qualifies each against your ICP using your product context. Enriches with tech stack, headcount, funding stage, and leadership. Prunes existing customers, current pipeline, and do-not-contact lists.
*Output:* Living account universe, typically 5,000–15,000 companies, updated weekly. Stays with your team.

#### 02 · Research Agent — Understands every account
For every qualified account, runs deep research across hiring, product, leadership, and news. Synthesizes into a structured brief with cited sources. Every fact traceable to where it came from.
*Output:* Per-account research briefs with clickable sources on every claim.

#### 03 · Signal Agent — Watches for buying moments
Monitors your account universe daily for trigger events across six categories: hiring surges, leadership changes, funding rounds, product launches, tech stack shifts, and job postings revealing pain points. Scores each signal for relevance to your specific product.
*Output:* Daily signal feed. Accounts heating up, flagged as they heat.

#### 04 · Outreach Agent — Writes and sends, one-to-one
When signals fire, writes a specific email for that specific account. References the actual research and the actual signal. Not templated, not merged, not variable-substituted.
*Output:* One-to-one emails, sent continuously, tied back to research and signals the buyer can trace.

#### 05 · Meeting Agent — Turns replies into prepared meetings
Classifies replies, flags ones requiring judgment, books confirmed meetings directly on your rep's calendar. 24 hours before every meeting, a pre-call brief is delivered: who the prospect is, what signal triggered outreach, what the research surfaced, what to lead with.
*Output:* Qualified meetings on your reps' calendars, each with a brief your rep reads before walking into the call.

#### 06 · The Operator — The human behind all five
Me. I built this system. I run it. I make every judgment call the agents escalate. You approve the ICP, the writing voice, the signal thresholds. I operate the system between your decisions. No pod, no account manager, no telephone game. You talk to the person doing the work.
*Your interface:* Direct. One person. Accountable for every output the system produces.

---

### One account, end-to-end (demo tabs)

**Label:** one account, end-to-end
**H2:** Here's what the system *actually* produces.
**Subhead:** A real account. Public data only.

Five tabs, one visible at a time. Each shows a stage of the system running on **Gong** as a demonstration account.

#### Tab 01 · Targeting — Day 1 · Universe built

**How the universe gets built.** Database filters pull the raw firmographic match — industry, headcount, geography, tech stack signals. That gives us the starting pool, typically **40,000–150,000 companies** depending on the market. Each company gets enriched: leadership, recent news, hiring patterns, funding, product signals, existing vendor relationships. Then every enriched company runs against your ICP definition from the Context Agent — not a checkbox filter, a qualitative fit decision based on what you actually sell and who actually buys. Current customers, active pipeline, and DNC accounts get pruned last.

**For this demonstration, we ran the motion on B2B SaaS selling GTM/CS tooling to teams of 200+.** Raw pool: ~**62,000** companies matching firmographics. After enrichment and ICP fit: **847** companies qualified. Below, 5 of the top-scoring accounts — Gong leads the set for reasons the Signal Agent picked up later in the week.

| Company | Industry | HC | Fit | Why qualified |
|---|---|---|---|---|
| **Gong** | Revenue AI / GTM Software | ~1,300–2,480 | **High** | New CCO promoted March 4, 2026; Revenue Architects team launched same day; hiring across 6 cities |
| **Clari** | Revenue Platform | ~800 | **High** | Post-merger integration with Salesloft (closed Dec 3, 2025); CS org being restructured |
| **Outreach** | Sales Engagement | ~850 | Med-High | Named 2025 Gartner RAO Leader; AI Revenue Agents launched May 2025 |
| **ZoomInfo** (GTM) | GTM Intelligence | ~3,500 | Medium | Rebrand to "GTM Intelligence Platform" completed; Chorus rolled up under main platform |
| **Uniphore** | Business AI Cloud | ~1,200 | Medium | Series F Oct 22, 2025 ($260M at $2.5B); integrating four recent acquisitions |

#### Tab 02 · Research — Day 2 · Brief generated

**Company:** Gong · **Brief:** 4,800 words · 22 sources cited

> "AI is a work revolution, cloud was an IT revolution."
> — Amit Bendov, CEO, on Sequoia's *Training Data* podcast, May 20, 2025

**What's happening at Gong right now.** Gong crossed **$300M ARR** and 5,000 customers — but they're still valued 38% below their 2021 peak. A secondary tender on Nasdaq Private Market repriced them at ~**$4.5B** in November 2025, down from $7.25B. They're growing fast into a valuation gap, which means pressure to prove enterprise maturity before what looks like a **2026–2027 IPO**. Four Fortune 10 logos help that case. A cluster of pre-IPO finance roles (Director of Deal Desk, Treasury, Technical Accounting, FP&A) confirms the timeline. *(gong.io/press, nasdaq private market, greenhouse.io)*

**Joe FitzGerald joined as Chief Legal Officer** on March 16, 2026 — previously CLO at Lacework through the Fortinet acquisition, and 8 years at Pure Storage spanning its IPO. That's an IPO-track hire. *(gong.io/press)*

They acquired **RightBound** (AI outbound prospecting) on December 2, 2025 and opened offices in Atlanta (March 2026), NYC (August 2025), and scaled Dublin from 125 to 200+ (July 2025). The footprint is expanding fast. *(techcrunch.com, venturebeat.com)*

**The big internal shift.** On March 4, **Simon Frey was promoted to Chief Customer Officer** — a brand new role. Same day, Gong unified its entire post-sale organization under a "Customer Office" and rebranded CSMs as "Revenue Architects." **Shane Evans**, previously CRO, was retitled **Chief Revenue Architect**. His public framing of the change:

> "The CRA is the new CRO."
> — Shane Evans, Chief Revenue Architect, Gong

This isn't cosmetic. They're betting that the CS function should own revenue expansion, not just retention. The **Revenue Architects hiring wave** is live across Austin, Chicago, NYC, Salt Lake City, SF, and Dublin — at least 9 open roles under the new team structure. *(gong.io/blog, linkedin.com, greenhouse.io)*

**Product and ecosystem.** **Mission Andromeda** launched February 25, 2026 — first in a new quarterly product cadence. Introduced **Gong Enable**, a head-on competitor to the just-merged Highspot + Seismic. The Gong Collective partner ecosystem surpassed **300 partners** by November 2025. Tel Aviv R&D is scaling toward ~500 engineers. ~103 total open roles on Greenhouse. *(venturebeat.com, gong.io/press, greenhouse.io)*

#### Tab 03 · Signal — Day 11 · Signal fired · 10:47 AM

**Why this account, why now.** The client sells a customer success platform targeting enterprise GTM teams. Simon Frey is 30 days into a brand new CCO seat with a rebuilt org, an unreleased operating model, and a visible hiring wave. New CCOs re-scope tooling in months 3–6 of their tenure. The 90-day window closes early June 2026 — **this is the textbook buying moment, and it's time-bounded.**

**What fired.** Three independent signals converged in 7 days:

| | |
|---|---|
| Signal type | Leadership change + organizational restructure + hiring surge |
| Account | Gong |
| Detected | Day 11 · 10:47 AM |
| **Relevance score** | **97 / 100** |

1. **Simon Frey promoted to Chief Customer Officer** on March 4, 2026. New role. First 90 days closing early June 2026.
2. **"Customer Office" unified** same day. New "Revenue Architects" team announced — CSM function rebranded across the company.
3. **Revenue Architects hiring wave** opened across six cities. At least 9 open roles under the new team structure.

#### Tab 04 · Outreach — Day 11 · Email drafted & sent

```
To:       Simon Frey, Chief Customer Officer, Gong
From:     [Client AE], [client-domain].com
Subject:  Revenue Architects — three weeks in
```

Saw the March 4 announcement about the Customer Office and the Revenue Architect rebrand. The piece Shane Evans wrote ("The CRA is the new CRO") was the clearest statement of operating-model change I've seen from a Revenue AI company this year. Not a cosmetic rename — you're hiring Revenue Architects across six cities.

The harder part is usually three months later — when a newly structured CS org has to prove ROI on an operating model the rest of the industry doesn't have vocabulary for yet. The health-score frameworks, onboarding playbooks, and QBR structures you had under the old CSM model don't cleanly map. Most CCOs in your exact spot default to rebuilding in Excel while the team scales.

[Client company] has worked with two other Revenue AI companies through similar CS-org transitions. Happy to share what the first 90 days of tooling decisions looked like for them — specifically what they kept, what they ripped out, and which KPIs broke when the role rebranded.

Worth 20 minutes before the June mark?

— [Client AE name]

**What the email drew from:**
- Paragraph 1 → Shane Evans blog post (March 4) + hiring wave data (Greenhouse)
- Paragraph 2 → CCO 90-day tooling pattern + Revenue Architects operating model gap
- Paragraph 3 → Two comparable client case studies (client's own data)
- CTA → 90-day window calculation (promoted March 4 → June deadline)

> 🔴 **Demonstration email — not sent.** Generated from publicly available signals about Gong.

#### Tab 05 · Meeting — Day 14 · Meeting booked · Brief delivered

| | |
|---|---|
| Meeting | [Client AE] × Simon Frey, Chief Customer Officer, Gong |
| Scheduled | Day 15 · 11:00 AM PST · 30 minutes |
| Brief delivered | Day 14 · 11:00 AM PST (24 hours before) |

**Who you're meeting**
- Simon Frey, Chief Customer Officer, Gong
- Promoted internally March 4, 2026 — approximately 6 weeks in role at time of meeting
- Previously SVP, Customer Outcomes at Gong — long-tenured insider, not an external hire
- Leads newly unified "Customer Office" and the rebranded Revenue Architects team

**Why they replied**
- Our email referenced the Shane Evans blog post ("The CRA is the new CRO") directly — a specific internal narrative, not a generic customer success pitch
- Frey is in the 90-day window where new CCOs re-scope tooling. The Revenue Architects hiring wave is active across six cities, meaning onboarding and enablement decisions are live right now.
- Expect: evaluation mode, not discovery. He will have already looked at competitive tools.

**Lead with**
- The two comparable Revenue AI company case studies — specifically what broke when the CS org rebranded and what tooling had to be replaced versus kept
- Frame the conversation around the 90-day mark, not a 12-month implementation. CCOs in his seat need early wins.
- Ask what KPIs he's carrying from the old CSM model versus the ones being redefined under Revenue Architects.

**Avoid**
- Generic "tell me about your customer success motion" discovery. He's been at Gong for years; he knows the motion cold.
- Pitching health-score features standalone. The Revenue Architect role is operating-model change, not a feature gap.
- Referencing any competitor by name. Gong leadership has public positions; don't step on them.

**Open questions**
- What specifically changed in the operating model versus the old CSM function?
- Is the Revenue Architects rebrand US-only or global? Dublin is hiring; unclear if the rebrand applies there.
- Budget authority: is CS tooling his call directly, or routing through the CFO office given the pre-IPO finance hiring cluster?

> *Your rep walks into the call knowing more about the prospect than most reps know after two calls.*

**Section closing line:** This happens *continuously* across your account universe. Every week.

---

### What you receive

**Label:** what you receive
**H2:** Outputs, not *promises*.

**Intro:** Everything the system produces lives with your team. If we stop working together, you keep it all.

- **01 — Account intelligence *library*.** Every qualified account in your market, researched, with cited sources.
- **02 — Daily signal *feed*.** Every trigger event across your universe, categorized and timestamped.
- **03 — Per-account research *briefs*.** Deep context on every account the system touches.
- **04 — One-to-one *outbound*.** Written per account and decision makers within the account, sent continuously.
- **05 — Meetings on your *calendar*.** With pre-call briefs 24 hours before every one.
- **06 — Weekly operator *update*.** A short Friday note. What ran, what's working, what's being adjusted.

---

### The guarantee (dark forest-green block)

**Label:** the guarantee
**H2:** First qualified meeting in 14 days, or *month one refunds* and the commitment voids.

**Body:** Most vendors ask for 90 days before you can judge the work. That's not a commitment, it's a stall. If the first qualified meeting doesn't land on your reps' calendar within 14 days of launch, month one refunds in full and the three-month commitment is voided. You walk, you keep everything the system produced.

**Primary stats (2 big tiles):**
- Billed monthly: **$3,000**
- Commitment: **3 months**

**Secondary line (small):**
Setup: $0 · Cancel after month 3: 30 days notice

**Footnote:**
*Qualified = a prospect at an ICP-fit account who agreed to a meeting, attended, and isn't a current customer or on your do-not-contact list.*

---

### Who's running this

**Label:** who's running this
**H2:** Dmitry. I *built* the system and I *operate* it.

**Body:** The orchestration, qualification logic, research pipeline, writing engine, signal monitoring, and brief generator are built from scratch, not assembled from other people's tools. Data providers are used where they beat building from scratch. Everything else is built in-house, not wrapped around someone else's API.

**Kicker:** *You're buying operated depth from the person who built the depth.*

---

### FAQ

**Label:** questions you're already asking
**H2:** Answered *in public*.

**Q1 · Is this a platform or an agency?**
Neither. It's a managed system, operated end-to-end. You see what it produces every week, and everything it generates lives with your team. Agency means trusting humans you can't see. Platform means doing the work yourself. This is the middle.

**Q2 · What happens if I cancel?**
You keep the account library, the research briefs, the signal history, and the branded domains set up in your name. No data hostage-taking.

**Q3 · Is this a wrapper on existing tools?**
No. Data providers are used where they beat building from scratch. Everything downstream — qualification, research, writing, signal monitoring, briefs, operator judgment — is built in-house.

**Q4 · Why not use an AI SDR tool for less?**
You probably have. The pattern is consistent: thousands of sends, almost no replies, eventually cancelled. The tech works. Nobody's operating it. That's what this system does differently.

**Q5 · How do I defend this to my CEO or board?**
$3,000/month, billed monthly. Three-month commitment that voids if the first qualified meeting doesn't land in 14 days. Month one refunds in full if it doesn't. Cancel anytime after month three with 30 days notice. Downside is one month of spend if the 14-day mark is missed. Upside is net-new pipeline you didn't have before.

---

### Finale (dark ink block)

**Kicker:** final
**H2:** Want to see how *the system runs*?

**Body:** A 30-minute call. Walkthrough of the system, real outputs from live engagements, answers to whatever's on your mind.

**CTA:** Book a call → (https://calendly.com/veogrowth/discovery)

---

### Footer

`◆ veogrowth · outbound operations · dmitry@veogrowth.com`

---

## 6 · Technical / deploy notes

- Single-file HTML — `/Users/dmitry/veogrowth-operations-landing.html`
- No build step, no framework. Google Fonts (Fraunces, Instrument Sans, JetBrains Mono) loaded with `display=swap`.
- Logo + favicon inlined as SVG data URIs.
- Calendly URL: `https://calendly.com/veogrowth/discovery`
- Contact email: `dmitry@veogrowth.com`
- All nav anchors scroll-margin-top: 84px (accounts for sticky header)
- Smooth scroll + scrollspy-active nav + scroll-progress bar + back-to-top button + skip-to-content link
- Respects `prefers-reduced-motion`
- Mobile polished (≤760px) and very-small (≤380px)
- OG + Twitter Card meta tags wired; note in source to generate `/og-cover.png` at 1200×630 before deploy
- Canonical URL + robots meta set

**Companion files:**
- `/Users/dmitry/veogrowth-linkedin-banner.html` — 1584×396 LinkedIn cover
- `/Users/dmitry/veogrowth-logo.html` — logo exploration / reference page
- `/Users/dmitry/veogrowth-demo-example.md` — standalone markdown of the demo section

---

*Updated 2026-04-19.*
