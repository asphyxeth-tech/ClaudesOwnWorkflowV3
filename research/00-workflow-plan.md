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

- **Phase 0 — Research (IN PROGRESS).** Defeat the Jan-2026 knowledge cutoff with 5
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

## Decision log

_(Filled as we make real choices. Nothing locked yet.)_

- 2026-06-01: Workflow kicked off. Chain (Base vs Solana) and concept both still
  open — research will inform, not assume.
