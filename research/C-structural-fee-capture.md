# Stream C — Structural Flow-Capture: Fee Pools & Opportunity Matrix (June 2026)

> Raw output from background research agent (model: sonnet). For niches where a
> small team earns recurring fees independent of retail adoption.

## FEE-POOL SIZING

### MEV (arb/sandwich/backrun)
- **Ethereum L1:** ~$561M total MEV volume 2025 (sandwiches ~$289.8M); CEX-DEX arb ~$120M/yr run-rate; ~$180M/mo gross at peak. **Top 3 searchers (Wintermute, SCP, Kayle) ~90% by Q1 2025**; exclusive searcher-builder verticals. Barriers MAXIMUM; solo dev squeezed out. AI edge marginal.
- **Solana:** $142.8M/yr identified arb ($1.58 avg/tx, 90.4M tx); Jito sandwiching ~$161M/yr run-rate; realistic searcher pool $200–350M/yr. Jito ~95%+ stake. Barriers high but more permeable ($10–50k infra start). **AI edge moderate** — memecoin pool sniping + Jupiter route arb across fragmented DEXes still soft; long-tail under $ minimums open.
- **Base:** ~$8.4M/mo network rev (Feb 2026); MEV pool ~$20–50M/yr, growing. **Dominated by only 2 spam entities** → open space for smarter low-gas strategies. Moderate barriers, softening.

### Liquidations
- Aave: ~295k liquidations / $3.3B cumulative; >$250M in one day (Oct 10 2025 stress). Lending TVL ~$75–80B (Apr 2026). Morpho $4.5B loans; Kamino $3.2B (largest Solana). Annual bonus pool **$200–600M/yr, regime-dependent**.
- >70% of liquidatable positions auto-liquidated instantly. **Aave Chainlink SVR now recaptures oracle MEV to protocol** ($1.1M of $32M SVR liquidations, 65/35 Aave/Chainlink). Kamino cut bonuses **90% (1%→0.1%) Sep 2025**. Flash loans remove capital need; moat = latency+gas. **AI edge: health-factor prediction + cross-protocol position aggregation.** Niche: thin Morpho isolated markets. SECULAR HEADWIND (compression).

### Intent / Solver Flow
- CoW $9B+/mo ATH (Jul 2025), proj $12B+/mo 2026; Across $28–34B cumulative; deBridge $1.53B/mo; 1inch Fusion $700B+ lifetime ($67.6M/day Q3 2025). **Combined intent-settled $15–25B/mo.** Solver spreads: 1–5 bps majors, **10–50 bps thin L2 routes**.
- Captured by ~12 MM firms (Wintermute, Propeller Heads…). deBridge **1 solver = 94%**. Access GATED: UniswapX permissioned; CoW needs $1M pool or DAO approval; Across needs hours of float capital ($500k–$2M/chain). **AI edge strong on thin L2 routes** (Scroll/zkSync/Mantle/Linea/Manta) incumbents ignore.

### Oracle / Keeper / Automation
- Chainlink: 70%+ oracle share, 2,400+ integrations, CCIP $18B/mo (+62% YoY). Node operators PERMISSIONED. Gelato = fee-for-service automation; Keep3r thin. **Chainlink SVR most actionable new stream** (~3.4% recapture on SVR liquidations). B2B sales cycles. AI edge limited (service business, not structural capture).

### Restaking / AVS (EigenLayer, Symbiotic)
- EigenLayer $18B TVL, 1,900 operators, 93.9% share; Symbiotic $897M. **Real AVS fee revenue minimal — mostly EIGEN emissions (8% inflation).** Operator economics ~3–4% staking + 1–2% AVS. EigenCompute mainnet alpha (Jan 2026). **2027+ bet; don't model revenue on this in 2026.**

### Sequencing / Preconf / LST-LRT routing
- Sequencer rev captured by rollup operators; shared sequencers (Espresso/Astria) early; Arbitrum TimeBoost ~$2,500/slot. Preconfs research-stage, no live $ at scale. **LST/LRT yield routing: Morpho curator fees grew $2M→$13M in 2025 (+600%)**, mgmt up to 5%/yr + perf up to 50%.

## RANKED SHORTLIST (best for a small team)

**RANK 1 — Morpho Vault Curation (LST/LRT + stablecoin yield routing).** Pool: $13M/yr curator fees (+600% YoY), $4B+ vault TVL; **curator keeps ALL fees** (Morpho takes 0). New curator w/ $100M TVL earns $500k–$2M/yr. Wedge: ERC-4626 vault on Morpho with ML-driven allocation; target RWA/LST-LRT/cross-chain markets. Lift: moderate (~500 LOC vault + off-chain allocation engine + automation), 2 eng / 3–6 mo. **Main risk: TVL acquisition is the bottleneck, code moat thin** (Steakhouse/Gauntlet/Re7 have distribution). Structurally recurring: fees accrue on TVL in flat markets.

**RANK 2 — Long-tail Intent Solver on underserved L2 routes.** Pool: $15–25B/mo; thin routes 10–50 bps. $50M/mo on thin routes @20bps ≈ $100k/mo gross, $30–70k net. Wedge: whitelisted solver on CoW long-tail / Across underserved routes / deBridge (94% concentrated). AI edge: gas prediction + batch timing + cross-chain float rebalancing. Lift: moderate-high, 4–8 mo, 2–3 eng; **CoW DAO whitelist + $500k–$2M capital**. Risk: incumbents can enter any profitable route in weeks; capital-intensive.

**RANK 3 — Solana long-tail MEV + liquidation hybrid.** Pool: $30–80M/yr accessible. Wedge: Raydium/Meteora new-pool arb within 100ms; liquidation bots optimized for 0.1% bonuses; Jupiter route backruns. Lift: moderate, Rust+Anchor, 2 eng / 2–4 mo. Risk: sr-AMMs erode sandwiching; private mempools; most direct 24/7 bot competition.

**RANK 4 — Chainlink SVR-style MEV recapture as a service (protocol-layer).** Pool: $10–30M/yr addressable if extended to Morpho/Euler/Compound/Spark; infra provider takes ~35%. Wedge: build the searcher/auction rails protocols need to recapture liquidation MEV (or an SVR-equivalent for Morpho). **Highest-leverage (build rails, not scraps)** but Lift HIGH (oracle/MEV expertise), 6–12 mo, regulatory + Chainlink-competition risk.

## INCUMBENT MOAT (entry verdicts)
- ETH CEX-DEX arb / sandwich: **hopeless, don't enter.**
- Solana arb small pools / sandwich long-tail: **niche viable.**
- Major-protocol liquidation: marginal (SVR absorbing, gas wars).
- **Morpho vault curation: strong opportunity (barrier = TVL, not code).**
- Intent solver majors: marginal; **thin L2 routes: real opportunity.**
- AVS operator: 2027+ bet. Chainlink oracle: closed. Preconf: speculative.

## HONEST CAVEATS
1. ETH MEV dominated beyond recovery for small teams.
2. Liquidation bonuses being systematically compressed (secular headwind).
3. AVS economics are tokenomics, not cash flows in 2026.
4. Intent solver TAM real but access gated; new solvers start at zero history.
5. "AI advantage" in DeFi is often hype; real edge = latency-insensitive niche-specific optimization. Feb 2026 cascade ($400M coordinated liquidations) shows correlated-AI behavior is a systemic RISK, not a moat.

## KEY SOURCES
Extropy MEV 2025; arxiv 2507.13023 (CEX-DEX), 2602.12104 (liquidations), 2602.17805 (intent bridges); Helius Solana MEV; BlockEden EigenLayer (Mar 20 2026); Aave V4 liquidations; Chainlink SVR ($1.1M); Morpho Effect 2025; Messari 1inch Q2/Q3 2025; Kamino -90% (Sep 2025); EigenFoundation incentives (Dec 2025).
