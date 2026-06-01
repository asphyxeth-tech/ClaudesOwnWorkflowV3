# ClaudesOwnWorkflowV3 — AI × Crypto Protocol Build Workflow

**Started:** 2026-06-01
**Driver:** Claude (Claude Code) + the user (non-technical product owner / strategist)

This file is the living home base for the workflow. The container we run in is
ephemeral, so anything worth keeping gets committed here.

---

## The mission (plain English)

Design and build — top to bottom — a crypto protocol with a *genuine* AI angle and
a launchable token (on Base via something like Bankr/Clanker, or on Solana). The
goal is something that walks the walk in serious circles, can plausibly go viral,
**and** has a clean, honest path to making money.

## North-star constraints (non-negotiable)

1. **Does NOT depend on mass adoption to succeed.** It should structurally move
   forward / capture value even with little retail interaction. Mass adoption is
   upside, not a prerequisite. Think: capturing transient volume, or capturing a
   flow of funds that exists regardless of whether anyone "discovers" us.
2. **Clean, real path to profitability** — a mechanism where revenue is obvious.
3. **Real, provable audience with real volume.** No fantasy TAM. We run the actual
   numbers (DEX volume, fee pools, launch counts, MEV/solver flow, agent tx counts)
   before assuming anyone shows up.
4. **Credible / advanced enough** to be taken seriously by the right people — not a
   me-too memecoin, but novel, or an existing idea executed *dramatically* better.
5. **Codeable top-to-bottom by Claude** in a reasonable scope and timeline.
6. **The user is non-technical.** Everything gets explained in plain English; the
   user hole-pokes ideas and signs up for APIs/services where needed.

## Anti-goals (things to avoid)

- "Millions of users will obviously use this" hand-waving.
- Pure-narrative tokens with no underlying cash flow.
- Anything requiring us to out-spend or out-network incumbents to even function.
- Detection-evasion / rug mechanics / anything predatory. We build something real.

---

## Phase plan

- **Phase 0 — Research (DONE).** Defeated the Jan-2026 knowledge cutoff with 5
  parallel research streams (below), weighted to the last 60 days.
- **Phase 1 — Synthesis + adversarial verification.** Fold the streams together;
  cross-check key numbers against on-chain (Blockscout) and social (LunarCrush)
  ground truth. Produce a plain-English briefing.
- **Phase 2 — Concept pitches.** 2–4 concrete protocol concepts, each with: what it
  is, who pays, the real fee pool / numbers, why it survives without mass adoption,
  build scope, and risks. User hole-pokes.
- **Phase 3 — Converge + de-risk.** Pick one, stress-test it, lock the design.
- **Phase 4 — Build + launch.** Contracts, app, brand, token launch plan.

## Research streams (Phase 0 — dispatched as background agents)

- **A. Market & mindshare** — what's actually hot in AI×crypto right now; ranked
  leaders w/ mcap, traction, momentum; dominant narratives; hype-vs-real verdicts.
- **B. Launch meta** — Base (Bankr, Clanker, Flaunch, Zora, v4 hooks) vs Solana
  (pump.fun, Believe, Virtuals, letsbonk, Boop): mechanics, fee splits, real
  volume, which fits a *substantive* AI protocol.
- **C. Structural fee-capture** — where a small team earns recurring fees regardless
  of adoption: MEV, liquidations, intent/solver flow, oracle/keeper nets, AVS. Pool
  sizes + insertion points + risks.
- **D. Agent economy reality + gaps** — what earns real revenue vs vaporware
  (Virtuals/ACP, ElizaOS, Bittensor subnets, Olas, etc.) + 6–8 concrete provable
  gaps.
- **E. Numbers grounding** — hard figures: DEX volume (Base/Solana), launches/day &
  survival rates, creator fees paid out, MEV/day, solver volume, agent tx counts,
  plus recent small-protocol revenue case studies.

---

## Tool inventory discovered (for verification + build)

| Tool | Use in this workflow |
|------|----------------------|
| **Blockscout MCP** | On-chain truth: read live contracts, token supply/holders, tx volume on Base (8453), Ethereum (1), Arbitrum, OP, etc. Verify claims; later read/debug our own contracts. |
| **LunarCrush-style social MCP** | Live social dominance / sentiment / engagement per coin & topic — grounds the "real audience & volume" test. |
| **Crypto.com Exchange MCP** | Live price / volume / orderbook / candles for market reality checks. |
| **Hugging Face MCP** | Models, datasets, papers — grounds the AI / inference side. (Authed user: Asphyxxx.) |
| **Vercel MCP** | Deploy the app/landing later; check domain availability + pricing for naming. |
| **Canva MCP** | Branding, logo, pitch deck when we get there. |
| **GitHub MCP** | PRs, reviews, CI on this repo. |
| **WebSearch / WebFetch** | General live research + source fetching. |

> Note: the environment also exposed unrelated MCPs (clinical trials, legal,
> travel, Microsoft docs). Ignored — not relevant here.

---

## Status

- **Phase 0 (Research): DONE** — streams A–E committed.
- **Phase 1 (Verification): DONE — first pass, 2026-06-01** — see
  `research/F-live-verification-2026-06-01.md`.
- **Phase 2 (Concepts): IN PROGRESS** — many concepts proposed + hole-poked; see
  rejections below. Nothing locked.
- Phases 3–4: not started.

## Locked constraints (refined with the user, 2026-06-01)

These TIGHTEN the north-star constraints based on the user's direction:

1. **Budget: under $5,000 total. Software + sweat only.** No plays needing inventory,
   seeded liquidity, market-making capital, solver float, or a treasury. Our "capital"
   is compute + gas. Profit must come from a *cut of a flow* or a *fee for a service* —
   never from us putting financial capital at risk.
2. **Substance-first.** Build a thing that demonstrably works & earns *in public*
   (postable track record / live fee counter), THEN launch the token into that proof.
3. **On-chain native + launchable token** (Base or Solana) stays core to the mission.
4. **Novelty bar is HIGH — reframed.** Not "never been done" (that veto kills
   everything), but "an unserved wedge into a real flow, with a timing reason to win
   now" — or an existing thing executed *dramatically* better.
5. **Don't clone an incumbent's accepted product.** No neutral/decentralized version of
   something Big Tech already owns AND the market already adopted (e.g. Coinbase x402 /
   custodial agent rails).

## Concepts proposed & REJECTED (with reasons)

| # | Concept | Why killed |
|---|---------|-----------|
| A | AI "agent firewall" / non-custodial guardrails (Gap 7) | Coinbase owns custodial guardrails + x402 + Base rails; a neutral clone won't get adoption. (User's call — correct.) |
| B | Launchpad "rug-radar" trading bot | Done to death; off-narrative. |
| C | DeFAI treasury / AI-managed fund | Needs capital to deploy (breaks <$5k); crowded. |
| ① | Perps builder-fee AI terminal (Hyperliquid) | Terminals exist; attention/adoption battle for traders. |
| ② | AI resolution / settlement oracle | UMA incumbent; high trust bar; bond mechanics = audit-heavy. |
| ③ | Agent-readable "machine alpha" intelligence feed | Nansen/Arkham + crowded; signal-quality risk; SaaS not flow-capture. |
| PM-router | Best-odds aggregator / cross-venue router for prediction markets | SATURATED: Verso, Unimarkets, Stand, Converge, Oddpool, pmxt, PolyRouter. [Phase-1 verified] |
| PM-copy | Copy-trading / smart-money tracker for prediction markets | SATURATED: PolyTrack, Wallet Master, Kreo, Poly Syncer, Bravado, OSS bots. [Phase-1 verified] |
| HIP-3 | AI deploys novel builder-perps on Hyperliquid | Deployer stake = 500k HYPE ≈ $20M. Breaks <$5k by ~4000×. [Phase-1 verified] |
| graveyard | Monetize the "failure flow" of the ~99% of launches that die | PARKED — unverified; capturable flow looks thin/murky; possible predatory optics. |

## Chain lean
- **Base** for credibility/launch infra (Virtuals/Clanker/Doppler); **Solana** for raw
  volume. Not locked. Whatever we pick, the token should accrue *protocol* revenue
  (buyback/burn or fee-share), independent of launch-venue trading fees. ("Revenue or
  Die" is the dominant 2026 fund thesis — Stream A.)

## OPEN FORK (next decision)
Phase-1 verification proved every *visible* AI×crypto intersection is arbitraged away.
The winner must come from one of two harder places (detail in Stream F):
- **(P) Unglamorous-but-real flow-capture** — e.g. permissionless, AI-driven
  liquidation/oracle-MEV *recapture rails* for the long tail of lenders (Stream C
  RANK 4). Best fit for "capture flow regardless of adoption"; weak on sex appeal.
- **(N) A genuinely new AI-native primitive** — viral-capable, but must bootstrap its
  own audience (in tension with the "proven audience" constraint).
Leaning **(P)**: the mission's non-negotiables (real proven flow + no mass adoption +
clean profitability) point there. Awaiting user steer.

## Log
- 2026-06-01: Workflow kicked off. Chain + concept open.
- 2026-06-01: Constraints tightened (budget <$5k, substance-first).
- 2026-06-01: Phase-1 live verification killed A-firewall (Coinbase), PM-router,
  PM-copy, HIP-3; reshaped PM picture (volume fleeing on-chain → Kalshi CEX). PM lane
  dropped. Meta-insight + open fork recorded.
- 2026-06-01: KILLED (P)-MEV/OEV-recapture after live check — OEV recapture is a
  maturing oligopoly (Chainlink SVR ~99% share across Aave/Compound/Venus; bought
  Atlas/FastLane Jan 2026; + UMA Oval, API3, Pyth Express Relay, RedStone). Integration
  is one-line for incumbents; AI is not the hero. Detail in Stream G.
- 2026-06-01: KEY REFRAME — every "capture-flow-regardless" chokepoint is already owned
  (oracles, payments, MEV, sequencing, launchpads); a <$5k newcomer can't seize one.
  New thesis: WIN A NICHE on genuine novelty + AI-as-hero (relax "zero adoption" →
  "no MASS adoption"). Spun up fresh hunt → research/G-hunt-v4-novel-ai-native.md.
- 2026-06-01: Stream G hunt (4 adversarial agents) → 0 clean bets; 3 clusters empty, G4's
  lone survivor (AI-game protocol) failed verification (stale meta + 2026 gambling
  crackdown + weak moat). Surfaced the real fork: "capture-flow-regardless" and "<$5k
  no-capital" are mutually exclusive → bend capital (β) or adoption (α).
- 2026-06-01: USER DECISION — start ~$0 (grind = α), self-fund via Base token
  (Bankr/Clanker) trading fees + protocol revenue, REINVEST earnings later (→ β). Lane =
  "α-ramp to β": bootstrap a structural AI-edged money-engine from a public track record,
  compound with its own earnings. Deep-dive launched on 2 finalists: H1 AI-managed
  non-custodial DeFi vaults; H2 builder-fee AI execution on perps.
