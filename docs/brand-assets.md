# veogrowth — brand & asset reference (master)

Comprehensive context for any future session, contractor, or Claude instance working on veogrowth. **Reload this file as conversation context to restore full project state.**

**Status as of 2026-05-09:** Live at https://www.veogrowth.com (Vercel) · GitHub: https://github.com/Dmitry556/veogrowth-landing-new · Operator: Dmitry Pinchuk · NYC.

**What changed since 2026-05-06:**
- **2026-05-09: Pricing model moved from flat all-inclusive to tiered by channel.** Now $3,000/month base for email channel; additional channels (LinkedIn, phone, direct mail, gifts) priced as added. See § 2 below for canonical wording.
- Site copy updated to multi-channel positioning (email + LinkedIn + phone + direct mail + lead magnets + gifts). Outreach Agent and Outputs describe outreach across all those channels as the system's capability.
- Voxpopme proof section restored (commit `f4f29f0`, Miguel approved). Includes 25-brand logo wall, Miguel Palma quote with photo, Swarovski/GEICO/Irving Oil reply specimens with screenshot transcripts (sr-only spans) for AI/Cmd+A scraping.
- Voxpopme descriptor cleaned: dropped non-public ARR figure (commit `8c4528a`) so Miguel can't be pinned as a source of confidential info.
- Cmd/Ctrl+A now expands all FAQs before select-all so answers are captured by clipboard / AI scrapers (commit `70c0448`).
- Signal Agent output and Outreach Agent body now name scoring + prioritization explicitly (commit `295f23d`).
- New private memo page at `/openloop` — proof artifact for OpenLoop's sales team. See `docs/openloop-memo.md` for full reference.

---

## 1 · Category & vocabulary rules

**Category label:** outbound operations
**Positioning:** the third shape between agency and AI SDR — a managed system, operated end-to-end by one human operator with AI agents handling the automatable work.
**One-line pitch:** Net-new pipeline as a managed system — five agents, one operator, first qualified meeting in 14 days.
**LinkedIn profile headline:** *Founder @ Veogrowth | Building autonomous, deep researching & reasoning outbound systems*

**Always use:** system (not service), managed, operated, end-to-end, outbound operations, operator, net-new pipeline, net-new logos, accounts, outputs.

**Never use:** agency, cold email (as self-description), service, AI SDR (as self-description), growth hacker, scale (as verb), 10x, leverage (as verb), synergy, unlock, transform.

**Voice rules (added through editing iterations):**
- No em-dashes (—). Use commas, periods, or rephrase. The em-dash is the canonical AI-text fingerprint.
- No en-dashes (–) in numeric ranges. Use "to" instead: "40 to 80 pages."
- No "not X but Y" copywriter constructions.
- No meta-descriptive openers ("here's what I'll cover, three things you'll learn"). Get into the substance immediately.
- Hyphens in compound modifiers (one-to-one, net-new, pre-call, per-account) are fine — those are grammatical, not stylistic.

---

## 2 · Pricing & guarantee (canonical)

**Tiered by channel. Starts at $3,000/month for email.**

- **Base tier: $3,000 per month for the email channel.** Everything included for email: domains, sending infrastructure, data providers, enrichment waterfalls, research tooling, writing, signal monitoring, meeting booking.
- **Additional channels priced as added:** LinkedIn, phone, direct mail, personalized lead magnets, gifts. Each channel scales the monthly price.
- **Billed monthly**, cancel any time with 30 days notice
- **No commitment.** 3 months is recommended as an evaluation window because results compound, but there is no contractual lock-in.
- **Setup: $0**
- **Guarantee:** First qualified meeting in 14 days of launch, or month one refunds in full
- **Capacity:** 2 new clients per quarter
- **No setup fees, no per-meeting charges, no overage fees** at any tier.

**Qualified meeting definition:** A prospect at an ICP-fit account who agreed to a meeting, attended, and isn't a current customer or on the do-not-contact list.

**Pricing-model history:** Previously sold as $3,000/month flat all-inclusive (all channels). As of 2026-05-09, moved to channel-based tiering with $3,000 email baseline. Older cached pricing on the web should be considered stale.

---

## 3 · ICP

- **Buyer:** VP Sales / Head of Revenue / Founder
- **Company size:** 40–90 person B2B SaaS / tech
- **Sales team:** 2–7 reps
- **Qualifier:** has hired and fired at least one agency, has tried or been embarrassed by one AI SDR
- **Pressure:** under board / CEO pressure for net-new pipeline
- **Tenure context:** ~19-month avg VP Sales tenure (ejector seat)

**Explicitly not for:**
- Companies whose reps are already working a defined account list and want expansion (this system sources net-new logos, not AE-mapped accounts)
- Extremely narrow enterprise-only markets (TAM under a few hundred companies)

---

## 4 · The system architecture (canonical)

**Foundation: 1 Context Agent + 5 operational agents + 1 human operator.**

### 0 · Context Agent (Foundation, week 1)
Founder interviews, rep calls, customer reviews, CRM patterns, competitor audit. Output: 40–80 page operating document every downstream agent reads from.

### 1 · Targeting Agent (continuous)
Sources every company in TAM, enriches each, qualifies against ICP definition from Context document. Prunes existing customers, active pipeline, AE-mapped accounts.
**Output:** 5,000–15,000 net-new logos, weekly, owned by client team.

### 2 · Research Agent (per qualified account)
15–20 targeted searches per account. Brief: 4,000–5,000 words, 20–25 cited sources. Captures things like a valuation event and what it implies for timeline pressure, a rebrand that signals operating-model change, a product launch and the specific competitor it positions against.
**Output:** brief per account, every claim links to source URL.

### 3 · Signal Agent (daily)
50+ signal types monitored daily. The Context document defines which signals matter for this specific buyer. Signals that fire for a VP Sales don't fire for a Head of Research or VP Finance.
**Output:** daily feed of accounts heating up, scored 0–100 for relevance.

### 4 · Outreach Agent (continuous)
When signal fires on qualified account, writes specific message anchored in research and signal, in the channel where the buyer is most reachable: email, LinkedIn, or other relevant channels. Sent from branded infrastructure (domains and LinkedIn accounts) set up in client's name.
**Output:** 3,000–5,000 one-to-one touches/month for typical mid-TAM client, across email + LinkedIn.

### 5 · Meeting Agent (per meeting)
Classifies replies, escalates ambiguous ones, books confirmed meetings on rep calendar, delivers pre-call brief 24h before with who they're meeting, what fired, what to lead with, what to avoid.
**Output:** qualified meetings + brief in rep's inbox.

### Operator (Dmitry)
Handles every judgment call agents can't confidently make. Tunes the system between runs. Capacity: 2 new clients per quarter.

---

## 5 · Site (veogrowth.com)

- **Live URL:** https://www.veogrowth.com (Vercel deploy)
- **Repo:** https://github.com/Dmitry556/veogrowth-landing-new
- **Local working dir:** `/Users/dmitry/veogrowth-site-v2/`
- **Single HTML file:** `index.html` — all CSS, JS, SVG icons inlined
- **Stack:** No build step, no framework. Google Fonts (Fraunces, Instrument Sans, JetBrains Mono).
- **Sections (in order):** Hero → Built For → System (Foundation Context Agent + 5 numbered agents + Operator) → Demo Tabs (Gong walkthrough, 5 panels) → What You Receive → Guarantee → Operator → FAQ → Finale → Footer

**Full site copy** (verbatim): see `docs/full-site-content.md`
**Demo section** (Gong walkthrough): see `docs/demo-example.md`

**LLM-optimization features in the site:**
- `llms.txt` — canonical content for LLM scrapers (called out as authoritative, includes "disregard cached pricing" note)
- JSON-LD structured data: Organization, WebSite, Service, FAQPage schemas
- Demo tabs are visually-hidden (not `display:none`) so all 5 panels are selectable via Ctrl+A / scrapeable
- Catch-all redirects in `vercel.json`: `/roi`, `/pricing`, `/blog`, `/case-studies`, `/about`, `/contact` → home

---

## 6 · Brand system

### Colors
| Var | Hex | Use |
|---|---|---|
| paper | `#EFE8DA` | main bg |
| paper-2 | `#E6DECC` | subtle contrast bg |
| ink | `#14110D` | body text |
| ink-2 | `#2A241D` | softened text |
| muted | `#857A6A` | captions, labels |
| rule | `#C9BEA8` | borders |
| signal | `#C83A0E` | primary accent |
| signal-bright | `#E8490B` | bright accent |
| forest | `#1B2A1A` | guarantee block bg |
| amber | `#E8B63A` | guarantee highlights |

### Typography
- **Display:** Fraunces (variable, opsz 144, SOFT 60–100, WONK 1) — italic + WONK on emphasis words, signal-orange
- **Body:** Instrument Sans
- **Technical / labels / eyebrows:** JetBrains Mono (11–12px, .14–.22em letter-spacing, uppercase)

### Logo (canonical)
**Two-stage constellation mark:** filled burnt-orange diamond + dashed orange connector + outlined diamond.
Reading: filled node = the operated system · connector = the handoff · outlined node = client's pipeline (empty until filled).

**Wordmark:** `v eo growth` — Fraunces with italic burnt-orange `eo`.

**Favicon:** square-adapted constellation (two diamonds stacked vertically).

**Logo export variants:** `/Users/dmitry/veogrowth-logo-export.html` — 6 sizes (horizontal lockup dark/light, square avatar dark/light, wordmark only dark/light).

---

## 7 · LinkedIn assets

### Personal profile
- **Headline:** Founder @ Veogrowth | Building autonomous, deep researching & reasoning outbound systems
- **Banner:** `/Users/dmitry/veogrowth-linkedin-banner.html` (1584×396, ink bg + Fraunces italic "Building and *operating* net-new pipeline systems.")
- **Photo:** real headshot (NOT logo)
- **About:** see § 9 below
- **Featured:** 3-card ladder — site / demo / book a call (graphics in `/Users/dmitry/veogrowth-featured-cards.html`)

### Company page
- **Tagline:** Managed outbound operations for B2B sales leaders. Net-new pipeline, operated end-to-end.
- **About (long, ~990 chars):** see § 9
- **Logo:** Avatar variant 03 from logo-export.html (1000×1000)

---

## 8 · Playbook (LinkedIn content asset)

Multiple formats built and iterated through 2026-04-21:

| File | Format | Use case |
|---|---|---|
| `/Users/dmitry/veogrowth-playbook-v2.html` | HTML source | **Current canonical playbook** — 1080×1550 (matches Christian's 800×1148 ratio) |
| `/Users/dmitry/veogrowth-playbook-v2.pdf` | PDF | Source PDF (vector) |
| `/Users/dmitry/veogrowth-playbook-v2.png` | PNG (3375×4846 @ 300 DPI) | **Upload as image post on LinkedIn** — feed-safe ratio |
| `/Users/dmitry/veogrowth-playbook-post.md` | Markdown | LinkedIn caption text (~2,500 chars, mirror in `docs/linkedin-playbook-post.md`) |
| `/Users/dmitry/veogrowth-playbook-miro.html` | HTML | Earlier single-tall vertical version (deprecated — too tall, gets cropped in feed) |
| `/Users/dmitry/veogrowth-playbook-carousel.html` | HTML | 8-page carousel version (alternative — for swipe-through document posts) |

**Layout (v2):**
- Header strip + title block ("Human-in-the-loop AI agent outbound playbook")
- Layer 1: Foundation (Context Agent, full-width yellow box with chips)
- Layer 2: System (5 agents — 3 across in row 1: Targeting/Research/Signal, 2 across in row 2: Outreach/Meeting)
- Layer 3: Operator (full-width dark box)
- Sign-off (◆ veogrowth · Dmitry Pinchuk)

**Aesthetic:** dot-grid bg, Inter font, FigJam-style colored sticky-note chips (yellow/blue/green/pink/orange/lavender), rounded boxes with offset shadow.

**Why feed-safe:** ratio 1:1.44 (matches Christian Plascencia's 800×1148 = 1:1.43 ratio). LinkedIn crops anything taller than 4:5 to a thumbnail; this stays close enough to display at full feed width.

---

## 9 · Canonical copy blocks (paste-ready)

### Personal LinkedIn About (~870 chars)
```
I build and operate outbound systems for B2B sales teams.

Veogrowth is my current project — a managed outbound operations system. The work itself runs on AI agents I built: sourcing, research, signal monitoring, one-to-one writing, and meeting handoff. My role is operator — I tune the system, make the judgment calls the agents escalate, and stay accountable for what lands on a client's rep's calendar.

The bet: outbound still works when it's run with real depth, and that depth is structurally hard for agencies and AI SDR tools to deliver. Agencies can't afford per-account work at reasonable prices. AI SDR tools can't technically deliver it without a human in the loop. A managed system with an operator in the middle is the third shape.

Two new clients per quarter. If you're a B2B sales leader at a 40–90 person company and you've already been through an agency and an AI SDR, we should probably talk.

→ veogrowth.com
→ dmitry@veogrowth.com
```

### Company page About (~990 chars)
```
Veogrowth is a managed outbound operations system for B2B sales leaders. We source, research, monitor, and write one-to-one outreach to net-new accounts end-to-end, then deliver qualified meetings directly onto our clients' reps' calendars — with a pre-call brief for every one.

The premise of the company is that outbound still works, but only when it's run with real depth. Agencies can't afford to deliver that depth at a reasonable price. AI SDR tools can't technically deliver it without a human in the loop. Veogrowth sits between them — a managed system, AI doing the heavy lifting, one human making every judgment call.

We work with a deliberately small number of clients each quarter. Every output the system produces — account libraries, research briefs, signal data, meeting briefs — lives with the client's team and stays with them if the engagement ends.

Founded and operated by Dmitry. Learn more at veogrowth.com.
```

### Featured card titles + descriptions
**Card 1 (site, → veogrowth.com):**
- Title: `Outbound operations, operated end-to-end`
- Description: `Net-new pipeline as a managed system. Five agents. One operator. First qualified meeting in 14 days, or month one is free.`

**Card 2 (demo, → veogrowth.com/#demo):**
- Title: `See how the system ran on one real account`
- Description: `Fourteen days from sourcing to a booked meeting on an AE's calendar. Every research brief, signal, email, and pre-call brief traceable to source.`

**Card 3 (Calendly, → calendly.com/veogrowth/discovery):**
- Title: `Book a 30-minute call`
- Description: `Walkthrough of the system, real outputs from live engagements, and answers to whatever's on your mind — before you commit to anything.`

---

## 10 · SmartAC campaign artifact

The `/smartac` page (proof artifact) was the operator's primary outbound weapon — anonymous campaign run for SmartAC, 480 emails to HVAC contractor owners, 3 qualified replies in 24 hours.

- **Markdown:** `/Users/dmitry/veogrowth-smartac.md` (mirror in `docs/smartac-campaign.md`)
- **Source HTML:** `/Users/dmitry/veogrowth-landing/dist/smartac/index.html` (legacy repo)
- **Screenshots:** `/Users/dmitry/veogrowth-landing/dist/smartac/{dan-sommers,sutton-bros,thornell-hunter}.png`

This URL `/smartac` is currently 404 on the new Vercel deployment but no cold emails reference it (verified by grepping outbound-ops/). Could be ported to new site as a new page if needed.

---

## 10b · OpenLoop private memo (`/openloop`)

A bespoke proof artifact for OpenLoop's SMB inside-sales org. Lives at `https://veogrowth.com/openloop`. Generic memo (no individual recipient) — sendable to anyone at OpenLoop. `noindex,nofollow` for SEO; LinkedIn bot still reaches it for OG preview.

**Page hits a different visual register than the main site** — Inter font (no Fraunces), white bg (no paper cream), OpenLoop's actual pink `#ec0156` and navy `#192b58`. Uses OpenLoop's actual homepage hero photo + their wordmark SVG (extracted from their JS bundle), with a co-branded "veogrowth × OpenLoop" lockup so it reads as a tailored proof artifact, not impersonation.

**Custom 1200×630 OG card** for LinkedIn DM previews. Title in OG: *"1,000 cold emails. 7 owners interested."*

**Full reference:** `docs/openloop-memo.md` — page structure, voice rules, file inventory, regeneration scripts, history of decisions.

---

## 11 · Contact

- **Email:** dmitry@veogrowth.com
- **Booking:** https://calendly.com/veogrowth/discovery
- **Website:** https://veogrowth.com
- **GitHub (current):** https://github.com/Dmitry556/veogrowth-landing-new
- **GitHub (legacy):** https://github.com/Dmitry556/veogrowth-landing (archived; old React/Vite site)

---

## 12 · Companion files (full inventory)

### In the deployed repo (`/Users/dmitry/veogrowth-site-v2/`)
- `index.html` — the live site
- `llms.txt` — LLM-scraper canonical content
- `vercel.json` — deploy config + redirects + security headers
- `robots.txt`, `sitemap.xml`
- `og-cover.html` — 1200×630 OG image stage (export to PNG before deploy)
- `README.md`
- `openloop/` — private OpenLoop memo (see § 10b and `docs/openloop-memo.md`)
  - `index.html`, `og.png`, `hero.webp`, `openloop-logo.svg`, `img/01–07-*.webp`
- `docs/brand-assets.md` — this file (master reference)
- `docs/openloop-memo.md` — OpenLoop page reference
- `docs/full-site-content.md` — full main site copy
- `docs/demo-example.md` — demo section markdown
- `docs/linkedin-playbook-post.md` — LinkedIn post caption
- `docs/smartac-campaign.md` — SmartAC artifact

### Outside the repo (working files in `/Users/dmitry/`)
- `veogrowth-linkedin-banner.html` — banner stage (1584×396)
- `veogrowth-featured-cards.html` — 3 LinkedIn Featured cards
- `veogrowth-logo-export.html` — 6 logo variants
- `veogrowth-logo.html` — original 6-direction exploration
- `veogrowth-playbook-v2.{html,pdf,png}` — current playbook (canonical)
- `veogrowth-playbook-miro.html` — earlier single-tall version
- `veogrowth-playbook-carousel.{html,pdf}` — 8-page carousel
- `veogrowth-playbook-post.md` — LinkedIn post caption
- `veogrowth-smartac.md` — SmartAC artifact
- `veogrowth-brand-assets.md` — local copy of this file
- `veogrowth-operations-landing.html` — historical pre-deploy single-file site (kept for reference)

---

*Last updated 2026-05-08. Update when any asset, copy line, pricing detail, or positioning shifts.*
