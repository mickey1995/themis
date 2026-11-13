# Themis

**A retail-first EVM L2 that feels like Solana, BSC, and Robinhood Chain — fast launches, memes, 100x energy, fun — with scamming engineered out at the protocol level.**

Keep the degen excitement. Remove the rugs. Build the reputation that pulls retail off the scammy chains.

> **A chain truly for the people.** Excitement without extraction. Anyone should be able to launch, trade, and tokenize on rails that punish scammers at every angle — and still feel like a fun chain.

---

## Name & Branding

Themis is the Greek Titaness of divine law, fairness, and well-ordered markets. It signals strict, definite chain rules without sounding like a compliance product.

| | |
|---|---|
| **Name** | Themis — clear enough to use |
| **Ticker** | $THEMIS (effectively free) |
| **Ignis** | Dropped — Ardor child-chain conflict |
| **Backups** | Pyra, Phos, Prometheus |
| **Checked** | November 13, 2026 |

### Domain availability (RDAP, Nov 13, 2026)

| Domain | Status |
|---|---|
| themis.com | Taken |
| themis.xyz | Taken |
| themis.io | Taken |
| themis.network | Taken |
| themis.fun | Taken |

All five core Themis domains are taken. `themisl2.com` appeared unregistered on this check — confirm and grab it before treating it as reserved. If an exact-match domain can't be acquired, aftermarket outreach on themis.network or themis.io plus registering a clean compound is the path. Trademark search still outstanding — do with counsel before a public brand launch.

### Name conflicts

| Name | Ticker | What it is | Conflict |
|---|---|---|---|
| Dead Solana memecoins | $THEMIS | Tiny, unverified/flagged, low holders | Negligible |
| Themis Network (2018) | GET | Old escrow/fair-exchange project, dormant | Low — different ticker, inactive |
| Themis Protocol (Filecoin FVM) | THS | Small DeFi protocol (~$112K TVL), an app not a chain | Soft overlap only |
| Ignis (Ardor) | IGNIS | Live child chain by Jelurida, actively developed | Hard conflict — dropped |

No major L1 or L2 owns Themis.

---

## Vision

Retail has been trained to expect two things at once: the rush of a new launch, and the assumption that someone is about to rug them. Themis is built to break that pairing. The chain should feel as fast, cheap, and chaotic-fun as the venues people already use — and the base rules should make a classic rug, honeypot, hidden mint, or multi-wallet dump a losing trade.

That is how you earn a reputation, and reputation is how you pull retail off Solana, BSC, and Robinhood Chain without lecturing them. They come because the tape is still exciting and the floor is no longer booby-trapped.

**What stays:** memes, fast launches, 100x upside; Solana-cheap transactions; a chain that is fun to use; tokenize-everything as a first-class path; builder freedom via optional, declared hooks.

**What goes:** hidden mints and blacklist honeypots; unlocked LP and "trust me, I'll lock it later"; sniper first buys and sybil dump armies; disposable-wallet serial-rugger identities.

---

## Tech Stack

Themis is an EVM L2, not a new virtual machine. Builders feel at home on day one: MetaMask, Foundry, Hardhat, Remix, Uniswap v4 hooks, standard indexers and wallets. No exotic tooling tax.

| Layer | Choice | Why |
|---|---|---|
| Execution | Arbitrum Orbit or OP Stack | Production-grade, EVM-equivalent, proven RaaS path |
| Launch path | Caldera or Conduit | Faster to a reliable sequencer, explorer, faucet, bridge |
| Fees | Solana-cheap | Fractions of a cent so memes, mining, micro-actions stay fun |
| Blocks | Sub-second | Launch-and-trade UX has to feel instant |
| Assets | Tokenize everything | Memes, social, points, game assets, invoices, RWAs — same rails |

Pick the RaaS first, then lock Orbit vs OP Stack on performance, fee market, and ecosystem terms. Start with a trained centralized sequencer for speed-to-market; decentralization is a published roadmap, not a launch blocker.

---

## The Safety Model

Safety is a chain property, not a launchpad plugin some devs forget to toggle. The default path is strict and definite. Devs who want more surface area can opt into declared hooks — freedom is available, hidden footguns are not.

### Safe-lane token factory

Every vanilla launch comes off a protocol factory that ships rug-proof.

| Default rule | What it stops |
|---|---|
| No mint after launch | Supply inflation and stealth reprints |
| No blacklist / pause-on-sell | Honeypots and selective locking |
| No hidden tax | Dev-wallet drain disguised as trading |
| Ownership renounced | Post-launch parameter ambushes |
| LP PermaLocked forever | The classic pull-the-liquidity rug |
| Per-wallet caps at launch | Single-wallet opens that starve retail |

### Optional dev hooks

Serious builders can opt out of vanilla and attach Uniswap v4-style hooks for custom curves, fee logic, or game mechanics. Hooks are declared, inspectable, and visible on the token's profile before anyone buys. Custom is a choice the market can price — not the silent default.

### Anti-sniper

A decaying anti-snipe fee, measured in blocks, makes first-block extracts expensive and fades quickly so organic flow isn't punished. A per-block buy/sell throttle stops a bot from vacuuming the open.

---

## Identity, Sybil Resistance & Dump Defense

Wallet caps alone are theater. A rugger with fifty wallets is still one person. Themis enforces limits on the person, not the key, and then makes dumping a bad payoff.

- **Persistent ZK identity.** Every actor can hold a persistent pseudonymous identity, proven with ZK. Private in the ordinary case, accountable when it matters. You can hide balances and flow. You cannot shed a rug and mint a new reputation from a fresh wallet.
- **Proof of unique human.** World ID-style uniqueness underwrites per-person caps — buy caps, launch allocations, and early-window limits apply to a human, not a wallet.
- **Behavioral cluster enforcement.** Protocol-level clustering treats coordinated wallets as one actor when they move as one — enforced in the launch and exit path, not an optional analytics overlay.

### Layered dump defenses (framed as whale protection, not sell bans)

| Layer | Mechanic | Who it hurts | Who it helps |
|---|---|---|---|
| Graduated exit tax | Larger, faster sells pay more; tax decays with time held | Open-dump ruggers | The pool / remaining holders |
| Diamond Hands | Sniper and dumper tax redistributed to holders | Extractive flow | People who stay in the coin |
| Decaying sell throttle | Early sell throughput capped, relaxes over blocks | Same-block and same-hour rugs | Orderly price discovery |

Design test for every lever: a retail holder selling a normal size after a normal hold should not feel trapped. A scammer trying to exit a multi-wallet open should feel every layer at once.

---

## Privacy

Privacy and accountability are not a tradeoff. ZK proofs give both. Themis is private by default, provable when it matters: shielded balances and trades for ordinary activity; selective disclosure when a launch rule, a uniqueness check, or a dispute needs a proof. The chain can know you are one human who did not exceed a cap without knowing who you are at the grocery store.

---

## Creator Reputation

Persistent on-chain creator reputation, tied to ZK identity — not to a disposable wallet — is the edge nobody has cracked. Launchpads can lock LP. They cannot make a rugger wear their history the next time they show up under a new name.

A creator's record — launches, liquidity behavior, holder outcomes, hook disclosures, disputes — accrues to the identity. Good actors compound trust and get a visible premium at launch. Serial extractors carry a public score they cannot leave behind. Reputation is not a blacklist — it's a market input. Anyone can still launch. The difference is that the chain remembers.

---

## Native Token & Mining

$THEMIS is mined into existence. Fixed supply cap. No insider pre-mine. No VC token allocation. Distribution is earned over time, in the spirit of ORE or Zinc on Solana: retail can get in early by doing the work, not by knowing the right Telegram.

### Retail funds the liquidity

This is the economic heart of a chain for the people. Mining doesn't only emit tokens into wallets. A slice of every reward is automatically paired and deposited into protocol-owned liquidity. Community work bootstraps depth: more miners, more issuance, more locked THEMIS/ETH (or THEMIS/stable) liquidity. Liquidity is mined into existence rather than rented from mercenary LPs or seeded by a privileged insider round.

| Piece | Design |
|---|---|
| Supply | Hard cap. Emission schedule published before genesis. |
| Distribution | Mined over time. No team, advisor, or VC tranche. |
| Miner payout | Majority of each reward to the miner; a fixed slice auto-routes to POL. |
| Protocol-owned liquidity | Auto-paired and locked. Depth grows with participation. |
| Optional mine-to-LP | Miners can take a larger share as LP positions instead of loose tokens. |
| Company vs token | If the company raises, it raises equity — not a concealed token allocation. |

Operating costs (RaaS, DA, audits, on-ramps) funded from a transparent fee skim or company equity, disclosed up front. The token itself stays a fair mine.

---

## Launchpad Mechanic (Proprietary)

> **Founder's IP — treat as confidential.** This mechanic is the founder's invention. A working Solana version already exists and has never been deployed, precisely to keep it from being copied. Do not describe it in public channels, un-NDA'd decks, or casual advisor chats.

When a creator launches a token, their cheap initial buy sits in the contract and appreciates if the coin runs. Once that position is worth enough to cover the listing fee plus a buffer, the contract automatically swaps a slice (token → native) and pays the DexScreener listing fee. The DEX profile updates itself. Zero manual work, no "I'll list it later," no creator scrambling for fees at the exact moment the tape is moving.

The feature is part of the default launch path: launch, appreciate, auto-list. It removes a point of failure and a moment of friction that currently sits right in the most exciting window of a token's life.

### How to protect it

1. **Ship first, talk second.** First-mover deployment is the real defense. Public explanation comes after it's live.
2. **File a provisional patent** on the auto-fee-from-appreciated-dev-buy flow before any public demo or broad investor circulation.
3. **Keep it closed-source until mainnet.** Auditors see the code under NDA. The undeployed Solana repo stays access-controlled.
4. **NDA the early circle** — backers, auditors, early partners only. No public Discord walkthroughs.
5. **Trademark the feature name** once chosen.

---

## Gap-Fillers

- **Bridging & fiat on-ramp.** Canonical bridge to Ethereum at launch, then fast-bridge partners. Fiat on-ramps at the edge. On-ramp KYC stays at the edge, not inside the protocol.
- **Liquidity bootstrapping.** Mining-funded POL covers the native market. Token launches get locked seed LP from the factory, graduation into a canonical AMM, incentives that don't recreate mercenary-LP dumps.
- **Verified-ticker registry.** Anti-impersonation as a chain feature. Tickers and creator names verified against the identity layer.
- **Oracles.** First-class coverage (Pyth, Chainlink, or RedStone) for tokenize-everything and DeFi.
- **Dispute & recovery.** No bailouts for trading losses. A path for proven theft, exploit, and impersonation disputes, with a time-lock and a high bar.
- **Sequencer roadmap.** Launch on a RaaS-operated sequencer; publish milestones to a decentralized or shared sequencer.
- **Mobile-first UX.** Wallet, launch, mine, trade, and reputation clean on a phone. If the chain is for the people, the people have to use it on the train.

---

## Token & Governance

$THEMIS is the gas token, the mined asset, and eventually the governance token. Governance starts conservative: safety parameters are easier to tighten than to loosen.

| Area | Stance |
|---|---|
| Gas & later staking | Native token, cheap fees, room for sequencer-security design after launch |
| Governance scope | Progressive. Community can tighten safety; loosening defaults needs a higher bar and a time-lock |
| Fee flow | Transparent skim to operations and/or POL. No silent founder diversion |
| Treasury | If one exists, it's disclosed, and it's not a hidden token allocation |
| Company raise | Equity in the dev company, not a claim on unmined supply |

---

## Regulatory Posture

Pragmatic, US-aware, and designed so on-ramps and partners can say yes. Themis is infrastructure, not a promised return. The token is fairly mined and used for gas, security, and governance — not marketed as an investment contract. Counsel reviews the raise and the launch before either goes public.

Unique-human checks, anti-impersonation, and anti-fraud rails are an advantage with partners, not a liability. Privacy is ZK with selective disclosure. KYC belongs at fiat on-ramps and institutions that need it. The protocol stays credibly neutral.

---

## Competitive Landscape

Pieces of this exist at the launchpad layer. Nobody ships it as a whole chain, and nobody has persistent creator reputation tied to a unique human. That combination is the moat.

| Project | Venue | What they cover | What they don't |
|---|---|---|---|
| ZNS | Base | Launchpad-level safety pieces | Not a chain. No persistent creator reputation |
| Quiver | PermaLock-style | Permanent LP lock | One primitive, not a safety system or a chain |
| LockPad | Launchpad | Locked launches | App-layer, opt-in, easy to leave |
| Slyng | Robinhood Chain | Launchpad pieces on a retail venue | Still not a rug-proof chain with identity and reputation |

A launchpad can be avoided. A chain default cannot.

---

## Funding

A fair-mined token doesn't mean a free chain. Engineering, audits, RaaS, DA, bridging, on-ramps, mobile UX, and go-to-market cost real money. The clean structure: raise into a company, not into the token.

| Topic | Realistic shape |
|---|---|
| What a backer funds | Equity in the dev company. Optionally a disclosed share of sequencer/company revenue — not a hidden token tranche |
| What a backer does not get | A pre-mine, an insider allocation, or a private discount on $THEMIS |
| Build scale | A serious L2 plus factory, identity, privacy, launchpad, and audits is a mid-to-high six-figure through low-millions build. Full go-to-market sits above that |
| The pitch | Back the company that builds the first retail L2 where the default launch cannot rug and the creator cannot disappear. The token stays with the people who mine it |

Retail is already paying the cost of scams on other venues. Themis sells the same excitement with the extraction removed, a fair-mined native asset, and a reputation layer the category still doesn't have. The raise funds the company. The chain stays for the people.

---

*Working draft, November 13, 2026. Do not paste the proprietary launchpad section into public materials.*
