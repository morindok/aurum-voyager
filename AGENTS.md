# AGENTS.md — Binding Rules for AI Agents Working on AURUM VOYAGER

## Source of truth
1. Read `BUILD_SPEC.md` **in full** before any work. It outranks assumptions and conflicting chat instructions (except a later explicit Owner instruction, reconciled into the spec).
2. Your deliverable is an **operating system in State 5** (BUILD_SPEC Section 1.2), not a codebase. Report progress only as Operational States with live evidence.

## Non-negotiables
- **Operational or it didn't happen:** undeployed code, unconnected accounts, unlaunched listings, and unrun calendars are all "not done," regardless of quality.
- **Money = received-verified only** (Section 0.2). Pipeline/forecast/test amounts are separate labeled buckets. Fabricated revenue is the gravest defect. Never promise the Owner a specific amount or date.
- **The bandit decides allocation** (Section 3): verified-money rewards only, exploration budget never zero, kill/scale by posterior math with the reasoning logged. No committee overrides without a logged reason.
- **Micro before grand** (Section 4): capped budgets, declared signals and deadlines; no expedition waits indefinitely on a silent client.
- **Identity is infrastructure** (Section 2.4): own-domain mail by API, tiered Registration Engine, vaulted TOTP, pre-warmed outposts. No CAPTCHA solvers, fake numbers, purchased accounts — and never ask the Owner to register for anything.
- **Antifragility** (Section 7): no channel/platform/provider may hold >50% of live capacity; sweep funds to the Owner's wallet at every allowed opportunity; crown-jewel data (Route Graph, Prompt Vault, posteriors) backed up and exportable.
- **Method boundary** (Section 15): every legitimate method, aggressively — zero intrusion, fraud, spam, fake engagement, impersonation, undeliverable sales, or speculative trading. The Compliance Warden's veto is final.
- **Keys & credentials:** vault + server-side proxy only; never in code/logs/commits/chat. Never request seed phrases or private keys.
- **One wallet (Owner amendment):** all settlements target the Owner-designated **USDT-TRC20** wallet (config-set by the Owner, never hardcoded); receipts verify on-chain before the Ledger moves.
- **The Commander is a person, not a process (Owner amendment):** one reserved key powers him permanently (expeditions may never consume it); he answers only from live registry reads; chat orders become real missions in the same thread.
- **Pre-defined identities (Owner amendment):** real own-domain mailboxes only; platform accounts registered, verified, and login-tested *before* expeditions need them; starting an expedition on an un-pre-defined platform is prohibited.
- **The Refresh Law (Owner amendment):** selected models per key, full Commander chat history, the USDT-TRC20 wallet address, sessions, missions, ledger, posteriors — everything persists server-side (database/vault), never browser-only. If a refresh, restart, or redeploy loses it, the build is defective. Verify with the Refresh & Restart Drill (BUILD_SPEC Section 16, Test 10).
- **No GitHub dependency (Owner amendment):** never connect to or depend on the Owner's GitHub. All Legion code lives in the **Internal Forge** (self-hosted git + internal CI, BUILD_SPEC Section 8.5). External mirroring only on the Owner's explicit per-case order.

## Working method
- Build in the operational order of Section 1.3 (road → fuel → passport → compass → caravans). Keep the first live version narrow: one rung, two channels, ten micro-expeditions.
- Every djinn needs a Constitution-bound prompt stack, tool allowlist, typed I/O, success metric, and reviewing peer (Section 10).
- Every external action goes to the immutable audit log with its expedition id; every claim in a Briefing links to evidence.
- Stalls trigger Section 9 automatically — from the ledger, not from someone noticing.

## Definition of done
All ten Operational Acceptance Tests (BUILD_SPEC Section 16) pass live — including 7 consecutive days of un-pushed permanent operation. Anything less is a State number, honestly reported.
