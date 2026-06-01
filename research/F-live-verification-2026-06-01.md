# Stream F — Phase 1 Live Verification (2026-06-01)

> Live-tool pass (WebSearch + Blockscout + LunarCrush) to pressure-test our most
> promising flow BEFORE committing to a concept. Goal: kill bad wedges cheaply.

## What we tested: "prediction markets" as the lead lane
Rationale: Streams D+E flagged PMs as the best-verified, fastest-growing, AI/bot-native,
*on-chain* flow ($<5B/mo Sep'25 → $24B/mo Apr'26; 14 of 20 top Polymarket wallets are
bots).

## Findings

### 1. Flow is real but MIGRATING OFF-CHAIN to a regulated CEX ⚠️
- Combined Kalshi + Polymarket ≈ **$24B in April 2026**; weekly ≈ **$5.6B** (wk of May 18).
- **Kalshi ≈ 71% of volume and RISING** — record $14.81B April (+13.3% MoM). Regulated
  CFTC exchange, centralized, not permissionless, restricted API.
- **Polymarket FELL 14.8% MoM** (International $9B + US $1.3B). On-chain share shrinking.
- Implication: the *on-chain* slice we could build a token/protocol on is the part that
  is **losing**. Bad for an on-chain-native token play.
- "≈80% of Polymarket participants lose money; gains concentrate in informed/bot
  traders." Confirms the bot edge — and that retail is the exit liquidity.

### 2. The obvious PM wedges are ALREADY SATURATED ❌
- **Aggregator / best-odds router:** Verso ("Bloomberg Terminal for PMs", AI + smart
  order routing), Unimarkets, Stand, Converge, Oddpool, **pmxt** ("CCXT for prediction
  markets", OSS, Jan 2026), **PolyRouter** (open beta), Prediction Express. → DONE.
- **Copy-trading / smart-money tracking:** PolyTrack, Wallet Master (Polymarket Radar),
  **Kreo/KreoPoly** (non-custodial Telegram mirror, <3s), **Poly Syncer** ($299/mo Pro,
  auto-copy 250 wallets), Bravado (all-in-one), multiple OSS bots. → DONE.

### 3. HIP-3 (builder-deployed perps) — capital wall ❌
- Mainnet deployer stake = **500,000 HYPE ≈ $20M**. >> our <$5k. Out.
- Note: **HIP-4 = prediction markets as perps** is coming to Hyperliquid — PMs are
  migrating into perp-DEX infra. New, tooling not yet crowded, but trading-on-top is
  the "perps terminal" flavor we already set aside (concept ①).

### 4. Tooling note
- LunarCrush social MCP is **subscription-gated** in this environment → no live social /
  mindshare data. Ground claims via WebSearch + Blockscout instead.

## Verdict
**Prediction markets are OUT as our lane.** The on-chain slice is shrinking toward a
regulated CEX, and every obvious wedge is crowded. Verification paid for itself — three
more "already-done" bullets dodged before any code.

## Meta-insight (the real lesson)
Every *visible* AI×crypto intersection we've probed is arbitraged away (PM tools; agent
payments/guardrails → Coinbase; launch trading; perps terminals). 2026 crypto is
efficient: obvious + hot + buildable = already swarmed. Our winner must come from one of
two harder places:
- **(P) Unglamorous-but-real plumbing** — a toll on a real flow nobody *wants* to build
  (e.g. protocol-layer liquidation/oracle-MEV recapture for the long tail of lenders;
  Stream C RANK 4). Fits "capture flow regardless of adoption"; weak on sex appeal / AI-
  as-product.
- **(N) A genuinely new AI-native primitive** — viral-capable, but must bootstrap its
  own audience (violates "proven audience" until proven).

## Sources
- Pew Research (PM volume soared, May 27 2026); The Block (Polymarket/Kalshi monthly);
  Yahoo Finance ($150B headline); DefiRate (Kalshi 71%, $5.6B week).
- BettorEdge (PM terminals); QuickNode (PM analytics / whale trackers); GitHub
  Awesome-Prediction-Market-Tools; prediction.express; Interexy; pmxt; PolyRouter.
- Laika Labs / Wallet Master / Kreo / Poly Syncer (OpenPR) / Bravado (copy-trading).
- Hyperliquid Docs (HIP-3); CoinGecko (HIP-3/HIP-4); Hyperdash; FalconX.
