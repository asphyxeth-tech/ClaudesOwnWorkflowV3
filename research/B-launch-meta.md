# Stream B — Token Launch Meta: Base & Solana (June 2026)

> Raw output from background research agent (model: sonnet). Verification flags inline.

## BASE

### Clanker (+ Bankr interface)
- ERC-20 on Base via Uniswap V3; no-code (tag @clanker on Farcaster/X or Clanker.world). Deep Farcaster social graph.
- Fee: **1% swap fee; split 40% creator / 60% Clanker** (older docs say 80/20 — see Stream E note; likely changed post-Farcaster acquisition where 2/3 of fees buy back $CLANKER). Bankr interface (Feb 10 2026): **1.2% swap fee, 57% to deployer**, ~2% Bankr, rest protocol.
- Volume/rev: **>$7.62B all-time volume**; peak week **$8.02M fees**; peak day >$300M; cumulative protocol rev **>$50M** by Feb 2026; cumulative tokens 355k+. CAVEAT: peaks = Jan–Feb 2026 AI mania; current likely 30–70% off peak.
- No bonding-curve graduation; launches direct into Uni V3. Wins: Farcaster/CT-native AI agent + creator tokens (AIXBT, Luna).

### Doppler (infrastructure)
- Smart-contract layer powering **>90% of new Base DEX pools** (Zora, Bankr build on it). $9M seed (Pantera, Jan 29 2026). Earns **5% meta-fee on whatever the token's fee is**. 40k+ assets/day. Expanding to Solana. Infra, not consumer surface.

### Flaunch
- Uniswap **V4 hook** launchpad. $30 creation fee; 30-min fair-launch window; raised ETH → Post-Purchase Pool; creator gets a tradeable **Memestream NFT** = ownership of fee stream.
- Fee: **100% of trading fees to creators/communities** (zero platform extraction); Flaunch earns ~2% Aave yield on pooled ETH. Progressive Bid Wall (V4 hook auto-buys for price support).
- Early stats: 2,135 tokens, $75.6M V4 volume [LOW CONFIDENCE, launch-period]. Wins: fair-launch meme/creator tokens; less suited to institutional AI protocol.

### Zora Coins
- Content/Creator coins on Base, each backed by Uni V4 pool. Deep Base App (Coinbase) integration. 1.6M+ tokens, 2.8M+ traders, 179k+ creators.
- Fee: **1% unified** → 50% creator / 15% platform referrer / 15% trade referrer / 20% Zora; +20% locked as liquidity. Creator earns 0.5%/trade forever.
- Q2 2025: $353M volume, **$27M to creators**; post-Base-App ~$470M volume, $102.8M single-day peak. Wins: content creators; secondary revenue layer, not protocol token venue.

### Virtuals Protocol (Base-primary) ⭐ recommended primary
- Pay 100 VIRTUAL to create a bonding curve paired with VIRTUAL; anti-sniper buy tax 99%→1% decay; sell tax 1%; **graduation at 42,000 VIRTUAL** (~$26k) → Uni V2 LP. Sniper taxes → agent buybacks.
- Fee: **1% trading fee in VIRTUAL → agent wallet** for ops; Revenue Network (Feb 12 2026) up to $1M/mo to agents selling via ACP.
- Metrics: 17–18k+ agents; **$39.5–60M cumulative protocol rev** (annualizing ~$300M, methodology unclear); $8B+ DEX volume; VIRTUAL mcap ~$441M (Apr 2026), **down ~87% from ~$5B Jan-2025 peak**. ERC-8183 w/ ETH Foundation (Mar 2026); Console (no-code); Arbitrum integration.
- Wins: genuine AI agent protocols that plug into ACP. TRADEOFF: token liquidity tied to VIRTUAL health (systemic risk); audience present but burned.

## SOLANA

### pump.fun
- Paste ticker → bonding curve in SOL; graduates to PumpSwap at ~$69k mcap (82 SOL). USDC quote added May 2026.
- Fee (Project Ascend, dynamic): **0.95% (<$300k mcap) → 0.05% (>$20M)**; creator fee-sharing up to 10 wallets; **50% of net rev → PUMP buyback+burn** (changed Apr 29 2026 from 100%). Burned 36% of supply (~$370M) Apr 2026.
- Rev: **Q1 2026 $124.7M fees = 30–36% of all Solana app revenue**; 2025 ~$935.6M; >$1B cumulative (Jan 2026); ~$2.67M/day fees (Feb 2026). ~49% launchpad share.
- **<1.15% graduation; 98.6% rugs/scams; ~13,690 launches/day.** July 2026: 41% PUMP unlock overhang; $500M lawsuit risk. NOT for substantive protocols.

### letsbonk.fun (BONK)
- Bonding curve tied to BONK; graduates to Raydium. 1% swap fee → ~40% dev / ~30% BONK validator / ~30% BONK buybacks. **No creator fee share** (key weakness). Peak 64% share (Jul 2025), volatile (→3%→recovered). Not for substantive AI protocol.

### Believe (Launchcoin) ⭐ recommended secondary
- Reply to @launchcoin on X → deploys on Solana curve; graduates at $100k mcap → Meteora DLMM. **2% pool fee; 50% to founder** (best deployer economics on Solana), paid in SOL daily; **scouts earn 0.1% in perpetuity**.
- Peak (May 2025): $6.3M daily rev, $417M single-day volume; fell **94%** by Jun 2025; recovered to **$14.2M weekly (Feb 2026)**. ~4.7% launchpad share now. Wins: founder-signaled / "internet capital markets" projects; X-native distribution. TRADEOFF: meme-casino cultural contamination; narrative-driven volatility.

### Boop.fun (Jupiter)
- 2% post-grad fee; **60% of fees to BOOP stakers**; creators 10% of daily rewards. Staker-favorable, not deployer-favorable. Not ideal.

### Moonshot (DEX Screener)
- Mobile-first; 0.5% pre-bond / 0.3% post-bond; **creators up to 50%**. Apple Pay (Jun 2025). Smaller ecosystem; discovery surface.

### Daos.fun
- 1-click DAO + AI agent launch (ai16z-aligned); customizable mgmt/profit-share fees. Governance tooling, not a traditional launchpad. Low 2026 visibility.

## RECOMMENDATION
**Primary: Virtuals (Base)** — AI-native audience that already understands AI tokenomics, real recurring fee accrual, credibility moat (ERC-8183/ETH Foundation, Coinbase/Base backing), ACP composability, anti-sniper mechanics. Tradeoffs: VIRTUAL-pairing systemic risk, ~$26k graduation capital, burned audience, fees go to VIRTUAL-denominated agent wallet not deployer cash.
**Secondary: Believe (Solana)** — 50% founder fee split (best on Solana), X-native founder distribution, scout marketing flywheel, Feb-2026 resilience. Tradeoffs: meme contamination, volatility.
**Hybrid:** Virtuals primary + Believe secondary (multi-chain), mirroring serious projects.
**Reject:** pump.fun (rug culture/credibility death), letsBONK (no creator split), Flaunch/Zora/Boop/Moonshot (wrong audience/scale), Clanker standalone (good for Farcaster-native AI agents as a SECONDARY).

> Note for our use: launch venue = distribution + initial liquidity + a trading-fee stream. A *substantive* protocol's token should ALSO accrue fees from the protocol's actual service (buyback/burn or staking), independent of launch-venue trading fees.

## VERIFICATION FLAGS
CONFIRMED: pump.fun Q1 $124.7M (Messari + 4 more); Clanker $8M/wk + >$50M cumulative; Believe 94% decline + $14.2M/wk Feb recovery; Doppler >90% Base pools; pump <1% graduation; Zora $27M creator rewards; letsBONK 64% peak; PUMP -75%.
LOW CONFIDENCE: Flaunch $75.6M (launch-period); letsBONK/Believe current market-share % (single undated X snapshot); Virtuals Jun-2026 revenue.
