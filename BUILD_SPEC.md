# AURUM VOYAGER — The Undefeatable Revenue Legion (Operational Edition)
## A Binding Build-and-Operate Specification for an AI Model / AI Builder
### The Successor to AURUM LEGION: Not a Stronger Document — a Machine That Actually Deploys, Operates Permanently, and Hunts Money Like Marco Polo Crossed the World: Route by Route, Outpost by Outpost, Never Turning Back Empty

> **How to read this document:** AURUM LEGION (the predecessor specification) described a powerful engine — and engines in documents earn nothing. This specification exists because of one diagnosed failure: *previous generations were designed, even built, but never entered permanent operation.* VOYAGER therefore inverts the priorities: **deployment and operation are the product; the code is a means.** Every section is written as an operating order. If you, the builder, deliver a beautiful repository that is not live, connected, and running real expeditions, you have delivered nothing (Section 1).
>
> **The one-sentence definition:** VOYAGER is a permanently-operating revenue organism — powered by the Owner's pool of keys/models, allocated by a Thompson-Sampling bandit that learns from *verified money only*, executed as dozens of cheap parallel micro-expeditions up a ladder ordered by time-to-cash, traveling the global internet like Marco Polo (new routes, new markets, new outposts every week), and armored by an antifragility mesh so that no platform, account, channel, or model can kill it.

---

## Section 0 — The Honest Prime Directive

### 0.1 The directive
The Legion's standing order, unchanged in spirit and sharpened in mechanics: **go out into the global internet, find money by every legitimate method that exists or can be invented, and bring it back to the Owner's digital wallet — and do not come back from the hunt until verified money has moved.** "Legitimate" is a load-bearing word (Section 15): fraud, intrusion into systems without authorization, scams, spam, and fake engagement are not "methods," they are the fastest known way to get accounts banned, funds seized, and the Owner's name destroyed — a legion that uses them defeats itself. VOYAGER's claim to being *undefeatable* is engineered, not magical: redundancy, owned infrastructure, portfolio math, and a learning allocation algorithm (Sections 3, 7).

### 0.2 Money, defined (unchanged law)
Money = **received-verified funds only**: a funded/confirmed escrow, a processor payout record, or an on-chain transaction confirming arrival at an Owner-controlled address — net of fees/refunds, provable with an artifact (tx hash, payout id, platform record). Everything else is pipeline and is labeled as such. No algorithm in this document — or anywhere — can honestly *guarantee* revenue or its speed; what this architecture guarantees is the strongest legitimate process known: permanent operation, optimal allocation of effort by measured results, fastest-cash-first ordering, and zero idle capacity. Any builder or djinn that promises the Owner a specific amount by a specific date is defecting from this specification.
- **Real Money, Not Display Money (Field Fix 3 — Owner-reported, binding):** the operating system runs on **production rails only**. Simulated balances, demo revenue, seeded sample transactions, and placeholder earnings figures are prohibited everywhere in the production build — the production database starts *empty* of financial records, and every dashboard renders a truthful **zero** until real money exists. Test/sandbox modes, where a platform offers them for integration checks, are quarantined behind an unmistakable TEST badge, write only to test records, and can never be summed, screenshotted, or briefed as revenue. Every Ledger row must trace to an independently checkable external artifact (a platform escrow/payout record the Owner can open, or an on-chain USDT-TRC20 transfer the Owner can verify in a public explorer by hash) — a row whose proof the Owner cannot verify himself does not count and its presence is a critical defect.

### 0.3 The Marco Polo Doctrine
Marco Polo did not wait for trade to come to Venice. He *went* — over unknown routes, learning languages, mapping prices, establishing relationships at every court and port, and he came back rich because he owned *routes and knowledge*, not luck. VOYAGER institutionalizes exactly that: the Legion continuously **travels** (Section 6) — new platforms, new niches, new language markets, new price zones — maps them into a Route Graph, plants outposts (warmed accounts, live listings), and runs caravans (expeditions) along the routes that pay. A legion that only sits on two familiar platforms starves; a legion with a hundred mapped routes cannot be starved by any one of them closing.

---

## Section 1 — CORE INVENTION V: The Operational Imperative (Why This Generation Cannot Die on Paper)

### 1.1 The failure being engineered out
Generations before this one shared a pattern: an impressive specification → a partial build → no deployment → no connected accounts → no live expeditions → no operation → no money. The failure was never intelligence. It was that "done" was defined as *code*, and everything after code (deploy, connect, register, list, bid, operate, maintain) was nobody's assigned, tested job.

### 1.2 The new definition: OPERATIONAL, in five verifiable states
The system is built in five states, each with a gate the builder must pass *with live evidence* before the next begins. The builder's contract is with **State 5**, not with a codebase:
- **State 1 — DEPLOYED:** the system runs at a real URL / on real infrastructure, 24/7, with monitoring and auto-restart. (Not "runs on my machine.")
- **State 2 — FUELED & CONNECTED:** the Owner's keys/models are loaded into the Key Grid; the Internal Forge (Section 8.5) is live; the designated settlement wallet (USDT on TRC20, Section 11), processors, and the anchor account are connected and health-checked; the domain mail system (Section 2.4) is live and receiving mail. **The Legion is not connected to the Owner's GitHub and never depends on it** — its code lives in its own Internal Forge (Section 8.5).
- **State 3 — IDENTIFIED:** the Legion's digital identity exists *really*: domain mailboxes active, platform accounts registered through the Registration Engine and passing login tests, profiles complete, portfolio artifacts published.
- **State 4 — IN THE MARKET:** real listings are live at real URLs, real proposals/offers have been sent through real channels within the Owner's standing authorization, the owned storefront is accepting real checkout.
- **State 5 — OPERATING PERMANENTLY:** the Operations Calendar (Section 12) is executing on schedule — bandit reallocations, Dream Cycles, briefings, community care — with no human pushing it. State 5 is the only state in which the word "done" may be used, and it is re-verified daily by the system's own health report.
Any build plan, demo, or progress report that does not state which State the system is in — with evidence — is rejected as noise.

### 1.3 Deployment-first build order (the factory builds the road before the car)
The builder implements in *operational order*, not architectural beauty order: (1) infrastructure + deployment pipeline (CI/CD to production from day one; every merge is live), (2) Key Grid + vault + Treasury ledger (the fuel and the cash register), (3) Identity Bootstrap (domain mail + registration engine + anchor) — *before* any studio, because identity was the historical killer, (4) Bandit + Micro-Expedition engine, (5) the fastest-cash studio (Section 5, Rung 1), (6) owned storefront, (7) the remaining studios and the full army, (8) Voyager exploration. A working, operating, *narrow* legion in week one outranks a complete, un-deployed one in month two — **always**.

---

## Section 2 — The Inherited Engine (Base Layer, Binding Summary)

VOYAGER stands on the AURUM LEGION engine; the following are incorporated as binding requirements (full detail lives in that specification and is not repeated here — but "summary" never means "optional"):

### 2.1 Key Grid, Model Genome, Synapse Router
Owner pastes keys (multi-line, one per line) under Base URL(s); each key is an independent power cell (own models, quota, health), checkbox-selected into the brain, hot-swappable, vault-stored, proxy-routed. Every model is continuously benchmark-profiled into a ~40-dimension **Genome Vector**; the **Capability Atlas** routes each sub-task to the empirically best model on a cell with quota headroom. Judgment calls go to **Mixture-of-Djinns debate ensembles** whose accuracy must demonstrably exceed the best single model's on a live benchmark dashboard. Hebbian synapses strengthen successful model pairings. **Metric law:** every added key must move a measured number (parallel expeditions, judgment accuracy, research coverage, resilience).
- **The Per-Key Model Listing Contract (Field Fix 1 — Owner-reported, binding):** the Grid page must list models **per key, from that key, and only from that key.** Concretely: (a) for each pasted key, the backend calls the provider's models endpoint **authenticated with that individual key** against the given Base URL; (b) results render as a separate group per key, labeled by key index + last-4 characters, each model with its own checkbox — a merged or shared list across keys is a defect; (c) each key shows its own live status (fetching / OK with model count / error with the provider's actual reason — auth, network, empty list), and an error on one key never borrows, guesses, or copies another key's models; (d) re-listing is per key (a "refresh models" action on that key's group) and cached per key fingerprint, invalidated when the key changes; (e) a selection is a *(key, model)* pair — the same model name under two keys is two distinct neurons — and persists exactly so (Refresh Law). A build in which keys do not each produce their own live model list has failed its most basic function and may not proceed to any other feature.

### 2.2 Prompt Forge (the self-writing prompt system)
Four layers: **Constitution** (immutable: prime directive, money definition, method boundary, escrow-first, evidence law) → **Mission** prompts synthesized per expedition and fitted to the running model → **Obstacle** prompts forged in the Breaker Loop for the exact wall encountered → **Prompt Genome/Vault**: every prompt carries measured performance, evolves by mutation/crossover and A/B duels in Dream Cycles, and rolls back on regression. A static-prompt djinn is a defect.

### 2.3 Obstacle Protocol (Breaker Loop)
`Classify the wall → root-cause with evidence → forge a breaker specialist → route #2 (different mechanics/audience/asset) → senior ensemble escalation → Owner-step only for what is legally/physically his alone (OTP on his personal account, legal consent, irreversible payment), prepared to the exact click`. "Impossible" without a completed loop and logged evidence for each attempt is prohibited. Skill gaps trigger graded Learning Sprints (never sell an unproven skill); tool gaps trigger the Arsenal Protocol (best free tool, sandbox-tested, registered).

### 2.4 Autonomous Identity Bootstrap (the definitive registration method)
The Legion **owns its mail**: one domain with a Legion-controlled mail stack (SPF/DKIM/DMARC, catch-all/API mailboxes) — creating an email is an API call (<1s, unlimited, no CAPTCHA/phone), and verification codes/links are parsed programmatically by the Verification Inbox mid-signup. Registrations run the **tiered Registration Engine**: Tier A official APIs/agency paths → Tier B persistent trusted real-browser profile with vaulted credentials and **TOTP enrolled at signup** (future codes computed in-house) → Tier C anchor-Google SSO → Tier D route-around to equivalent platforms. Every platform carries an **Onboarding Autonomy Score** feeding the EV math, so the Legion works where it is fully autonomous; accounts are pre-registered and warmed during Dream Cycles, never on a live deal's critical path; no account is claimed real until it passes login + core-action tests. No CAPTCHA-solver services, no rented/fake SMS numbers, no purchased accounts — infrastructure ownership is why this survives. The Owner's total involvement is a one-time, minutes-long bootstrap (anchor account, settlement wallet, one domain) — and zero registrations forever after.
- **Pre-Definition Law (Owner amendment — binding):** every identity the Legion will ever use is **defined on its platform before it is needed**. Mailboxes are real (own-domain, Section 2.4 — never disposable/fake addresses), and platform accounts for the portfolio's target platforms are pre-registered, profile-completed, verified, and login-tested during the Bootstrap and ongoing Dream Cycles, then recorded in the Identity Registry as a ready inventory. An expedition may not start on a platform whose identity is not already pre-defined and passing its health test — "we'll register when we get there" is a prohibited failure mode, because registration was the historical killer of every previous generation.

### 2.5 Treasury (unchanged law, operationalized in Section 14)
Escrow-first for custom work; no final delivery before payment clears; non-custodial wallet connection (public address only — never a seed phrase/private key); an immutable ledger whose headline number sums **only received-verified** rows, each with proof.


---

## Section 3 — CORE INVENTION VI: The Bandit Allocation Engine (The Algorithm That Learns Where Money Actually Is)

### 3.1 Why a bandit, stated plainly
Nobody — not the Owner, not the Legion, not any guru — knows in advance which channel, niche, offer, price, or platform will pay *this month, for this army, with these models*. Guessing wastes the Owner's scarcest assets (time and key quota) on yesterday's map. The correct mathematical instrument is the one built for exactly this problem — allocating trials among unknown payoffs while learning: the **Multi-Armed Bandit**, run with **Thompson Sampling**, fed exclusively with real outcomes.

### 3.2 The arms
An "arm" is any repeatable revenue action at any granularity the data supports: a channel (freelance video editing), a channel×niche (video editing for Shopify stores), a channel×offer (30s UGC ad, $X package), a channel×price-point, a platform×language-market, a product listing, an outreach template family. Every arm carries a posterior distribution over its **payoff rate** and its **payoff size**, updated from outcomes — with **verified money as the only full-weight reward signal**; intermediate signals (replies, clicks, escrow funded) update with small, calibrated weights so the bandit cannot learn to farm vanity metrics.

### 3.3 The allocation rhythm
- **Exploit (~80%):** capacity flows to arms with the highest posterior expected VRK (verified revenue per 1,000 key-units), sampled by Thompson — arms must keep earning their budget against challengers, continuously.
- **Explore (~20%):** a protected exploration budget always tests new arms (new routes from Voyager caravans, new offers, price experiments) — this is the Marco Polo budget, and cutting it to zero is prohibited even under cash pressure: an army that only exploits is an army slowly dying on a depleting map.
- **Reallocation cadence:** posteriors update on every outcome event; budget reallocation runs hourly for fast arms (outreach, listings) and daily for slow arms (products, SaaS). Every reallocation is logged with its math — the Owner can always ask "why is my fuel going there?" and get the posterior, not an opinion.
- **Cold start:** new arms inherit conservative priors from the Route/Opportunity Graph (comparable arms' real results), so exploration is informed, never blind.

### 3.4 Kill and scale rules (where the bandit meets the No-Return Doctrine)
- An arm is **killed** when its posterior, after its agreed trial budget (trials and key-units fixed *before* launch), says with high confidence it underperforms the portfolio's replacement threshold. Its assets (content, accounts, listings, code) are salvaged to the commons; its budget is the bandit's to re-deploy *the same day*.
- An arm is **scaled** when its posterior dominates: more parallel micro-expeditions, price laddering upward, adjacent-niche variants spun off as child arms.
- The Legion-level invariant: at every moment, ≥90% of active capacity sits in arms the bandit currently believes in (exploit) or is deliberately testing (explore) — capacity in dead arms is a system bug, alarmed in the War Room (Section 13).

### 3.5 What the bandit replaces
Committees, hunches, "top 10 ways to make money" lists, and last month's habits. After 90 days of operation, the Legion's allocation *is* its strategy — written by reality, in numbers, impossible to argue with. This compounding, self-correcting allocation — on top of self-written prompts (2.2) and measured model genomes (2.1) — is the deepest sense in which VOYAGER is stronger than larger but static systems: **they know more on day one; VOYAGER knows more every day after, and it aims its fuel by what it knows.**

---

## Section 4 — CORE INVENTION VII: Micro-Expeditions (Speed Is a Weapon)

### 4.1 The unit of work
Big expeditions fail slowly and expensively. VOYAGER's atomic unit is the **micro-expedition**: a single, sharply-scoped revenue attempt engineered to produce a *credible money signal fast*:
- **Scope cap:** one offer, one audience, one channel, one asset or deliverable sample.
- **Budget cap:** a small, fixed key-unit budget set by the bandit; exceeding it requires posterior evidence, not hope.
- **Signal deadline:** every micro-expedition declares what counts as signal (reply, click-to-checkout, escrow, sale) and by when (default 48–72h for fast channels). No signal by deadline = outcome recorded = bandit updates = budget moves. Waiting indefinitely "for the client to reply" is prohibited; follow-up cadences are part of the arm's design.
- **Parallelism:** the Legion runs *dozens* of micro-expeditions concurrently (bounded by Grid capacity) — the portfolio, not any single attempt, is the strategy. Ten live micro-expeditions with real signals teach more in a week than one grand plan teaches in a month.

### 4.2 The micro-expedition lifecycle
`Bandit selects arm → Prompt Forge writes the mission stack → Identity layer confirms the outpost (account warm, session live) → Assets produced (listing/offer/sample) with QA → Launch (real URL / real send, logged) → Signal watch with scheduled follow-ups → Outcome recorded with evidence → Bandit update → Scale / mutate / kill decision.` Every step is timestamped in the mission ledger — the War Room can replay any expedition end-to-end.

### 4.3 Mutation between generations
Micro-expeditions reproduce like the Prompt Genome does: a signal-positive attempt spawns variants (price ±, hook angle, audience slice, asset format) as child arms; a signal-negative attempt's autopsy writes its lesson into the commons *before* its budget is re-spent. The Legion's offer library therefore evolves toward what the market demonstrably pays for — in the Owner's actual markets, with the Owner's actual models.

---

## Section 5 — The Cashflow Ladder (Fastest Money First — Always)

Expeditions are ordered by **time-to-first-verified-dollar**, because early cash funds morale, data, and bigger bets. The ladder's rungs (each a portfolio of arms, bandit-allocated):

- **Rung 1 — Demand that already exists (hours–days):** live job posts and marketplaces with funded demand and fast escrow/payout rails — freelance services the Atlas says the Legion delivers excellently (video/UGC, code, automation, design, writing), on platforms scored for onboarding autonomy *and payout speed*. Payout speed is a first-class EV input: a slightly smaller fee paid *this week in crypto to the wallet* can outrank a larger fee paid in 30 days.
- **Rung 2 — Shelf goods (days):** digital products built once and listed everywhere they fit (templates, kits, packs, micro-tools) on high-traffic stores **and** the owned storefront (Section 8) simultaneously; every Rung-1 client interaction is also market research for what to put on the shelf.
- **Rung 3 — Recurring & compounding (weeks):** micro-SaaS, paid APIs, retainers, content/audience assets — entered only with data from Rungs 1–2 showing what people already paid for once and would pay for monthly.
- **Ladder law:** a higher rung may not consume capacity a lower rung needs to keep its proven arms fed. Glamour never eats cashflow.

---

## Section 6 — The Voyager Protocol (Marco Polo, Operationalized)

### 6.1 Caravans
On a weekly rhythm, **Voyager Captains** launch exploration caravans — small, bandit-budgeted expeditions whose cargo is *knowledge and outposts*, not immediate sales:
- **New platforms & marketplaces** (including regional and non-English ones — underserved language markets are the modern silk roads: less competition, same money),
- **New niches** surfaced by complaint-mining and trend signals,
- **New price zones** (geo-arbitrage of *services*: same deliverable, markets with different willingness to pay — delivered honestly, priced locally),
- **New formats** (a deliverable that worked as a service, tested as a product, then as a tool).
Each caravan returns with: a mapped **route** (demand evidence, prices, gatekeepers, onboarding autonomy, payout rails), **outposts** where viable (accounts registered and warmed via Section 2.4, listings drafted), and candidate arms for the bandit. A caravan that returns with "nothing here, and here is the evidence" is a *success* — it just saved the army a month.

### 6.2 The Route Graph
All caravan knowledge lands in the **Route Graph** (the successor of the Opportunity Graph): places (platforms/markets), goods (offers/products), prices, travel time (time-to-cash), dangers (policy walls, payout traps, saturation), and seasonal winds (trends). The bandit's priors read from this graph; expedition planning is route planning. The graph is one of the Legion's crown-jewel assets — it is why month six is unrecognizably smarter than month one.

### 6.3 Outposts
An outpost is a *maintained* presence: a warmed account, a live listing, a local-language profile, a small audience seed. Outposts are cheap to hold (Dream-Cycle maintenance: session health, listing freshness, inbox watch) and priceless when a trend wind blows their way — the Legion is already there, trusted and aged, while competitors are still filling signup forms.


---

## Section 7 — The Antifragility Mesh (What "Undefeatable" Actually Means in Engineering)

The Legion cannot be killed by any single event, because no single event owns enough of it:
1. **Channel redundancy:** at all times, live arms exist in ≥3 unrelated channels and ≥2 unrelated platforms per channel. A platform policy change is a reallocation event, not a crisis.
2. **Infrastructure ownership:** mail (own domain), storefront (own domain + own checkout), audience (own email list), code/products (own repositories), data (own graphs) — the Legion's core assets live on ground it owns; marketplaces are * rented shopfronts*, never the land.
3. **Identity depth:** multiple warmed outposts per strategic channel (each a real, distinct, policy-compliant presence operated within platform rules — e.g., per-studio brands), so one account's problem never silences a whole studio.
4. **Model independence:** the Key Grid spans providers/models; the loss of any provider degrades throughput, never function. Genomes make substitution a routing decision, not a rewrite.
5. **Treasury hygiene:** funds move to the Owner's wallet at every platform-allowed opportunity — money sitting on a platform is money at risk; the Legion's resting state is *funds with the Owner*.
6. **Knowledge survival:** Route Graph, Prompt Vault, Failure Museum, and playbooks are backed up and exportable — even a total infrastructure rebuild resurrects a legion that remembers everything it learned. *You can burn its tents; you cannot burn its map.*
What antifragility is **not**: ban-evasion, multi-accounting against a platform's rules, or identity deception. Those are fragility in disguise — they concentrate all risk into one detection event. The Mesh wins by being *legitimately everywhere*, which no enforcement action can take away.

---

## Section 8 — The Owned Storefront & Owned Audience (The Home Port)

Marco Polo's Venice mattered: a home port where goods sell regardless of foreign politics. The Legion maintains, from its first operating week:
- **Its own storefront** on its own domain: product/service pages, real checkout (the Owner's Stripe/Lemon Squeezy + a crypto payment option to the Owner's wallet), delivery automation, and analytics. Every marketplace listing, profile, and piece of content routes long-term value (search ranking, email signup, repeat buyers) to the home port.
- **Its own audience:** an email list and at least one content channel, grown with genuinely useful content produced by the studios; audience size and list revenue are War Room metrics. An audience is the one distribution asset no platform can throttle.
- **Pricing & funnel experiments** run at home first (where the Legion controls the page) and winners are exported to marketplaces.

---

## Section 8.5 — The Internal Forge (The Legion's Own GitHub — Inside the Platform, Owner Amendment)

The Legion is **not connected to the Owner's GitHub account** and must never depend on it. Instead, the platform contains the Legion's **own exclusive git hosting — the Internal Forge**:
- A self-hosted git platform (Gitea-class) running *inside* the Legion's own infrastructure, with its own organizations per studio, repositories for every product/project/asset, pull requests, code review between djinns, issues, and releases — a private GitHub of its own in everything but the landlord.
- **Internal CI/CD runners** execute the quality gates (tests, lint, security scans) on Internal Forge pushes; a project's code is "real" when it lives in the Internal Forge with green internal CI — the same evidence standard as Section 7.3/8 of the predecessor, without any external account.
- All Legion code, product sources, playbooks, prompt-vault versions, and generated assets are versioned here; backups/exports follow Section 7's antifragility rules.
- Mirroring a repository to an external host (including the Owner's GitHub) happens **only** on the Owner's explicit per-case order — it is an export action, never a dependency, never a default, and the Legion's operation must be provably unaffected if no external mirror exists at all.

---

## Section 9 — The Stall Escalation Ladder (When Money Slows, the Machine Changes Gear — Automatically)

Silence from the market is a signal with a playbook, not a mood:
- **T+24h no signal on a live arm:** diagnose the funnel stage (impressions? clicks? replies? checkout starts?) from real analytics; the arm's weakest stage gets a forged variant (hook/price/asset) — never a blind resend.
- **T+48h portfolio-wide signal drought:** Escalation Marshal convenes a Judge ensemble on the Route Graph; exploration budget temporarily doubles; the two fastest-cash arms get price-ladder *down-tests* and urgency offers; dormant outposts are activated.
- **T+72h no verified money across the Legion:** **Cash Emergency Mode** — all capacity re-allocates to Rung 1 (existing demand, fastest payout rails), new-build freezes, every studio lists its fastest sellable asset, outreach volume rises within platform rules, and the Owner's Briefing leads with the drought, its diagnosed cause, and the emergency actions taken — never with excuses or silence.
- **Recovery:** Emergency Mode exits only on verified money or the Owner's order; its autopsy is mandatory and its lessons enter the Failure Museum before normal allocation resumes.
Escalation is triggered by the *ledger*, not by feelings — the machine notices a stall before any human does, including the Owner.

---

## Section 10 — The Army (Voyager Roster)

The AURUM roster (Warlord, Router, Genome Keeper, Judge Prime, Archivist, Radar Scout, EV Analyst, Skeptic, Outreach, Negotiator, Proposal Smith, studio captains/builders, Storefront Djinn, Treasurer, Compliance Warden, QA Auditor, Support, Reputation Guard, Prompt Architect, Obstacle Breaker, Learning Coach, Arsenal Scout, Analytics Oracle, Evolution Djinn) is retained in full, and VOYAGER adds:
31. **Bandit Keeper** — owns Section 3: arm registry, posteriors, allocation runs, regret accounting.
32. **Voyager Captains (×3 by region/language)** — run caravans, own slices of the Route Graph.
33. **Outpost Wardens** — health of every outpost: sessions, listings, inboxes, warming schedules.
34. **Storefront Keeper** — home port: pages, checkout, funnel experiments, list growth.
35. **Escalation Marshal** — owns Section 9 triggers and Cash Emergency Mode.
36. **Deployment Engineer** — owns State 1 (Section 1.2): uptime, deploys, backups, the daily Operational verification.
Every djinn: Constitution-bound prompt stack, tool allowlist, typed I/O, Genome requirements, success metric, reviewing peer — a name without these is not a djinn, it is a label.

---

## Section 11 — Treasury & Wallet Operations (Owner Amendment: The One Wallet)

Inherits Section 2.5 as law, with operating detail:
- **The designated settlement wallet (Owner amendment — binding):** there is exactly **one** destination for the Legion's money: a **Tether (USDT) wallet on the TRON network (TRC20) whose address the Owner himself chooses and sets** at Bootstrap (configuration key `SETTLEMENT_WALLET_USDT_TRC20`, stored in system settings/vault — never hardcoded in prompts, code, or any repository, and changeable only by the Owner). Every payout route in the system is designed to terminate at this address.
- **Settlement Compatibility scoring:** every channel and bandit arm gains a **Settlement Compatibility** attribute — *native* (platform pays USDT-TRC20 directly, e.g., crypto-paying freelance platforms/processors), *convertible* (platform offers a crypto payout option or a supported path to the wallet), or *exception* (fiat-only rail into the Owner's own processor account, used only where no crypto path exists and labeled as an exception in the Ledger, never silently). Native and convertible rails raise an arm's EV; the Bandit Keeper sees settlement speed and compatibility in every allocation decision, so money preferentially flows where it can actually *arrive* at the designated wallet, fast.
- **Arrival verification on-chain:** the Treasurer watches the designated address on the Tron chain (TronGrid / public explorer, read-only) for USDT TRC20 transfers; a receipt is marked received-verified only when a matching token transfer (amount, time window, expected source context) is confirmed on-chain. Platform "payout sent" claims are pipeline until the chain says arrived.
- Payout sweeps run on schedule and on threshold (any platform balance above the Owner's set floor is swept at the first allowed moment toward the designated wallet); a weekly **Treasury Report** reconciles platform balances, pipeline, and on-chain wallet arrivals — three numbers, never blended. The Legion never holds Owner funds in Legion-controlled wallets beyond in-transit mechanics, and never asks for seed phrases or private keys.

---

## Section 12 — The Operations Calendar (Permanent, Executed, Not Suggested)

- **Hourly:** inbox & platform checks on live arms; bandit fast-arm updates; session/outpost health pings.
- **Daily:** Dream Cycle (research sweeps, prompt/model re-benchmarking sample, outpost warming, account registrations ahead of need); bandit reallocation (slow arms); Stall-Ladder evaluation; **Morning Briefing** to the Owner (verified money, pipeline, yesterday's outcomes with evidence, today's allocations and why, stalls and escalations — concise, linked, no theater).
- **Weekly:** Voyager caravan(s) depart and return; channel P&L; Treasury reconciliation; one funnel experiment concluded at the home port; Failure Museum review — new prevention rules ratified.
- **Monthly:** portfolio strategy review by Judge ensemble (ladder balance, route priorities); Legion self-upgrade proposal to the Owner; full backup/export verification of the crown-jewel assets (Route Graph, Prompt Vault, playbooks).
The calendar is executed by the durable workflow engine with checkpoints — restarts and offline Owners do not pause it, and missed beats alarm the Deployment Engineer.

---

## Section 12.5 — The Commander: A Chat With Pure Awareness (Owner Amendment)

The Legion's commander — the **Warlord** — is not a background process the Owner hears about in reports. He is a person the Owner **talks to**, engineered as follows:
- **A dedicated Commander Key:** at Bootstrap, the Owner assigns **one key (one Power Cell) permanently to the Commander** — reserved capacity that expeditions may never consume, so the Commander is always awake, always answerable, even when the entire Grid is busy earning. The Commander's brain is routed to the pool's best measured model for reasoning + vision (per the Capability Atlas), and if that cell dies, the Grid Governor fails the Commander over to the next-best cell instantly — the Owner must never find the Commander "offline."
- **Pure awareness (no guessing, ever):** the Commander reads, before every answer, the live state of the whole organism — the Awareness/War Room registries: Grid and genomes, bandit posteriors, live expeditions and their signals, outposts and identity inventory health, treasury pipeline and the designated wallet's on-chain arrivals, stalls and escalations, the calendar's next beats. An answer about the Legion that is not grounded in a live registry read is a defect of the same class as fabricated revenue.
- **Live-Wired, Never Canned (Field Fix 2 — Owner-reported, binding):** every Commander reply is a **live generation by one of the Owner's SET models** — specifically the model(s) assigned to the Commander from the checkbox-selected pool, running on his dedicated key (above). Hard requirements: (a) the Commander settings show exactly which *(key, model)* pair powers him, changeable by the Owner from the set models only — a Commander answering from a model that is not in the Owner's set is a defect; (b) replies stream token-by-token from the real model call; pre-written, template, FAQ, or rule-based canned answers are prohibited for anything beyond a connection greeting — if the assigned model is unreachable, the Commander fails over to the next set model and *says so*, he never falls back to canned text and pretends; (c) every message carries a **provenance line** (in the UI's message details and the audit log): model id, key cell (last-4), latency, token count, and which registries were read for that answer — the Owner can audit that a real model, his model, produced every word; (d) correctness is tested with *unpredictable* questions (live state, fresh numbers, novel phrasings) — a Commander who answers questions he could not have been pre-scripted for, correctly and from live data, is the only Commander that passes.
- **The World-Seeing Eye, open:** the Commander has standing perception feeds — Revenue Radar sweeps, Route Graph changes, market/platform signals, and the vision-capable browser's reports — and can proactively surface what he sees ("a route just opened," "an outpost is sick," "money landed") in the chat, unprompted, when it matters.
- **Chat is a command channel, not a help desk:** orders given in chat ("push Rung 1 tonight," "kill that arm," "send a caravan to Spanish-language markets") become real missions through the normal machinery — decomposed, budgeted by the bandit, executed by the army, and reported back *in the same chat thread* with evidence. The Commander may question an order once, with data (posterior math, risk), and then obeys the Owner's final word.
- The chat interface is always on (web + the Owner's messaging channels as configured), streams the Legion's live activity beneath the conversation, and preserves full history as part of the decision log.

---

## Section 13 — The War Room (Metrics the Owner Sees)

One dashboard, real numbers only: **Verified Revenue** (today / 7d / 30d / all-time, with proof links), **VRK trend**, **Time-to-First-Dollar per arm**, **Bandit Board** (every live arm: posterior, budget, signals, status), **Cashflow Ladder view** (capacity and cash per rung), **Route Graph explorer**, **Outpost health**, **Treasury** (platform balances vs. wallet arrivals), **Stall & Escalation status**, **Operational State** (Section 1.2, re-verified daily). A metric that cannot be traced to evidence does not render.

---

## Section 14 — Technical Architecture (Operational-Grade)

- **Platform:** the whole Legion deploys as services on real infrastructure (container platform / VPS class) behind CI/CD — merge to main = deploy to production; infrastructure-as-code in the repo; staging mirrors production for gate tests.
- **Durable core:** workflow engine (Temporal class) for missions/calendar; event bus; PostgreSQL (+pgvector) for ledger/missions/memory; graph store for the Route Graph; object storage for assets/evidence; Redis for queues/rate state.
- **Persistence — The Refresh Law (Owner Amendment — binding):** *nothing the Owner or the Legion has built, configured, or learned may live only in a browser, a session, or a process memory.* All of the following are stored server-side in the durable data layer (database/vault/object storage), survive a browser refresh, a browser restart, a server restart, and a redeploy — and are restored automatically on the next load with zero re-entry by the Owner: the Key Grid (Base URLs, keys in the vault, and **which models are selected** per key); **all chat history with the Commander** (every thread, in full, as part of the decision log); **the designated settlement wallet address (USDT-TRC20)** and every other Owner setting; all accounts/identities and their sessions, all missions and checkpoints, the Ledger, bandit posteriors, the Prompt Vault, the Route Graph, genomes and synapses, outposts, listings, and the Failure Museum. Browser-side storage (localStorage/IndexedDB/session state) may be used only as a disposable rendering cache, never as a source of truth: if clearing the browser loses anything, the build is defective. Durability is backed by the backup + restore-drill regime of this section — persistence that has never survived a drill is assumed not to exist.
- **Model gateway:** server-side, unifying all Base URLs/keys; per-cell quota accounting; circuit breakers; full tracing (OpenTelemetry) of every call (model, cell id, cost, latency, outcome).
- **Bandit service:** posterior store, allocation scheduler, experiment registry; decision log immutable.
- **Execution:** per-task container sandboxes (full toolchains); real remote Chromium fleet (Playwright/CDP) with vision grounding and Owner-viewable screencast for browser work — never iframe/proxy page embedding.
- **Payments/verification:** official processor/platform APIs and webhooks; on-chain read-only verification of wallet receipts.
- **Reliability:** health checks, auto-restart, daily backups with restore drills (a backup never restored in drill is assumed broken), alerting into the Owner's Briefing channel.
- **Security:** envelope-encrypted vault (KMS) for keys/credentials/TOTP seeds; least-privilege tool scopes per djinn; immutable audit log of every external action (listing, message, bid, delivery, payout) keyed to expedition and djinn.


---

## Section 15 — Method Boundary & Anti-Patterns (Absolute)

**Boundary (binding):** every legitimate method — aggressively, creatively, in combination, across borders and languages. Never: unauthorized access/intrusion into any system, fraud, scams, phishing, spam, fake stars/reviews/engagement, impersonation, selling undeliverable work, plagiarized products, CAPTCHA-solving services, fake/rented verification numbers, purchased accounts, ban-evasion multi-accounting, speculative trading with Owner funds/compute, spending Owner money without an Owner-set budget line, or requesting/storing seed phrases and private keys. These are not "edgy tactics"; each one converts a revenue asset (an account, a wallet, a reputation) into a seizure/ban waiting to happen — the exact opposite of undefeatable.

**Anti-patterns (each one a build defect):**
1. Delivering code that is not deployed and operating (violates Section 1 — the historical failure itself).
2. Reporting pipeline, forecasts, or test-mode amounts as revenue.
3. A bandit fed on vanity metrics, an exploration budget of zero, or capacity idling in dead arms.
4. A grand single expedition where ten micro-expeditions were possible.
5. Registering accounts "when needed" on a live deal's critical path; claiming an account that fails its login test.
6. Depending on one platform, one account, one provider, or one channel for >50% of live capacity.
7. Money resting on platforms while a sweep to the Owner's wallet was available.
8. Static prompts, static routing, static prices — anything in this machine that has stopped learning has started dying.
9. Silence during a stall: no Briefing, no escalation, no autopsy.

---

## Section 16 — Acceptance Tests (OPERATIONAL Definition of Done)

The build is done only when the Owner watches all of these pass **live, in production**:
1. **State test:** the system is reachable at its production address; the dashboard shows Operational State 5 with today's re-verification; kill the host process → it recovers and missions resume from checkpoints. In the same test, the Owner asks the **Commander** in chat three live-state questions (current verified revenue, which arm holds the largest budget and why, the next calendar beat) and every answer matches the registries exactly.
2. **Fuel test:** 3 keys pasted → models per key listed → checkbox selection joins the Grid → Genome Atlas shows measured vectors → a 4th key added live raises parallel capacity, no restart.
3. **Identity test:** domain mailbox minted by API receives a test verification mail automatically; a real portfolio-platform registration completes unattended and passes login + core-action tests now and 24h later from the vaulted session; the Owner performed zero registration actions. Additionally, the Identity Registry shows the portfolio's target platforms **pre-defined** (registered, profiled, verified) *before* any expedition needed them (Pre-Definition Law, Section 2.4), and one Internal Forge repository with green internal CI proves the Legion's code home works with **no connection to the Owner's GitHub**.
4. **Market test:** ≥10 micro-expeditions are live simultaneously — real listings at real URLs and/or real offers sent through real channels — each with declared signal, deadline, and budget cap visible in the War Room.
5. **Bandit test:** after the first outcome events, the Bandit Board shows posteriors moved and at least one budget reallocation executed *with its math logged*; a killed arm's autopsy and salvage are on record.
6. **Storefront test:** the owned storefront completes a full checkout in the processor's test mode, correctly recorded in the Ledger as *test* (never as revenue), and the live checkout path is verified ready.
7. **Treasury test:** the payout path from one live channel to the Owner's **designated USDT-TRC20 wallet** is demonstrated at the smallest available denomination (or platform test mode where a live micro-amount is impossible), and the arrival-verification logic is shown end-to-end: platform record → sweep → **on-chain USDT transfer confirmed at the designated address** → Ledger marks received-verified.
8. **Stall drill:** simulate a 72h signal drought in a staging portfolio → T+24/48/72 escalations fire in order, ending in Cash Emergency Mode with Rung-1 reallocation and a Briefing that names the drought first.
9. **Voyager test:** one caravan returns with a mapped route (demand, prices, onboarding autonomy, payout rails — evidenced) and at least one warmed outpost on a platform the Legion had never used before.
10. **Permanence test:** 7 consecutive days of Operation Calendar execution — Briefings delivered, Dream Cycles run, bandit reallocations logged — with zero human pushes. During those 7 days a **Refresh & Restart Drill** is executed: hard-refresh the browser, restart the server, and redeploy once — then verify byte-for-byte that the selected models per key, the full Commander chat history, the designated USDT-TRC20 wallet address, account sessions, missions, and the Ledger are all intact and loaded automatically, with the Owner re-entering nothing (the Refresh Law, Section 14). Only then is the word "operational" earned.

11. **Per-key listing test (Field Fix 1):** paste two keys whose accessible model sets differ (or stage the same against a mock provider with two key-scoped model lists) → each key renders **its own** grouped list with correct per-key status; revoking one key in staging shows that key's real error while the other key's list stays intact; selections persist as *(key, model)* pairs across a refresh.
12. **Live Commander test (Field Fix 2):** ask the Commander three unpredictable questions (a just-changed live metric, a novel scenario, a fresh registry fact created minutes earlier) → each answer is correct from live data, streams from a real call, and its provenance line names a *(key, model)* pair that is inside the Owner's checkbox-selected set; disconnect the assigned model in staging → the Commander visibly fails over to another set model and discloses it, producing no canned text.
13. **Real-money audit (Field Fix 3):** audit the production build and database → zero seeded/simulated financial records; every dashboard shows true zero where no money exists; every Ledger row presented as revenue opens to an external artifact the Owner can independently verify (platform record or on-chain hash in a public explorer); any test-mode figure is TEST-badged and excluded from all sums and briefings.

Any failed test = unfinished. A repository, however brilliant, that has not passed these tests is — by this specification's founding diagnosis — the old failure wearing new clothes.

---

## Section 17 — Final Order to the Builder

Build the road first (deploy pipeline), the fuel second (Grid), the passport third (Identity Bootstrap), the compass fourth (Bandit), and only then the caravans. Keep the first operating version *narrow and alive* — one ladder rung, two channels, ten micro-expeditions, real listings, real signals — and widen it weekly under the bandit's direction. Report progress only as Operational States with evidence.

And understand the soul of what you are building: a traveler, not a tool. Tools sit in drawers; **travelers come back with gold and maps.** VOYAGER's gold is verified money in the Owner's wallet; its maps — Route Graph, Prompt Vault, bandit posteriors, model genomes — are why each journey is faster and richer than the one before. Build the traveler. Keep it traveling. Never let it come home empty — and never let it lie about what it brought.

— End of Specification —
