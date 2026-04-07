# Hey, I'm a Web3 Engineer

I build scalable decentralized applications on **Solana** and **EVM-compatible chains** — from smart contract architecture to production-ready frontends. My focus is turning complex on-chain problems into clean, maintainable solutions that actually ship.

---

## What I Work On

**Smart Contracts**
Solidity and Rust (Anchor) contracts built for security, gas efficiency, and upgradability. Audited, tested, and production-hardened.

**DeFi Protocols**
AMMs, lending markets, yield optimizers, vaults, and liquidity infrastructure. Deep experience with protocol mechanics, tokenomics design, and composability across ecosystems.

**NFT & P2E Systems**
On-chain game logic, NFT minting pipelines, staking mechanics, reward distribution, and marketplace contracts. Built for scale and low-friction UX.

**AI Agents on Chain**
Autonomous agents that interact with smart contracts — executing transactions, managing positions, and responding to on-chain events without human intervention.

---

## Chains & Ecosystems

| Chain | Stack |
|---|---|
| Solana | Rust, Anchor, SPL Tokens, Metaplex |
| Ethereum | Solidity, Hardhat, Foundry, ethers.js |
| EVM L2s | Abstract, Base, Polygon, Arbitrum, Optimism |

---

## Tech Stack

```
Languages      Rust · Solidity · TypeScript · Python
Frameworks     Anchor · Hardhat · Foundry · Next.js
Libraries      ethers.js · viem · wagmi · web3.js · @solana/web3.js
Tooling        The Graph · Chainlink · OpenZeppelin · Metaplex
Infra          RPC nodes · IPFS · Arweave · Vercel · Railway
```

---

## Highlight Projects

### 🤖 AI-Powered Blockchain Solutions

---

#### 🔷 Koala Koin Toss — Coinflip & Lootbox Platform
> Abstract EVM L2 · [koalafun.xyz](https://koalafun.xyz/)

<img width="100%" height="100%" alt="Koala Koin Toss" src="https://github.com/user-attachments/assets/605c50b8-ba09-492a-8bf7-01aeccba0fca" />


A provably fair on-chain gambling platform on Abstract EVM L2, featuring coinflip and lootbox mechanics with transparent randomness and instant payouts.

**How it works**
- Players wager tokens on a 50/50 coinflip resolved entirely on-chain with verifiable randomness
- Lootbox system offers tiered rewards with weighted odds stored and enforced in the contract
- Koala-themed UI built for smooth, low-friction UX on Abstract chain

**Stack**
```
Blockchain  Solidity · Abstract EVM L2 · on-chain RNG
Frontend    Next.js · ethers.js · wagmi
```

**Results**
- Fully on-chain randomness — no off-chain oracle dependency
- Instant settlement with gas-optimized payout logic
- Deployed and live on Abstract L2

---

#### 🔷 Monstro Finance — Gamified DeFi Platform
> Base · [monstro.fun](https://monstro.fun/)

<img width="100%" height="100%" alt="Monstro Finance" src="https://github.com/user-attachments/assets/605c50b8-ba09-492a-8bf7-01aeccba0fca" />

A gamified DeFi ecosystem on Base featuring tokenized characters, staking pools, and referral mechanics for enhanced yield generation in EVM environments.

**How it works**
- Tokenized characters tied to user positions, adding a gamified layer to staking and yield strategies
- Staking pools with referral mechanics that reward users for growing the ecosystem
- Intuitive frontend dashboard for tracking positions, rewards, and referral activity

**Stack**
```
Blockchain  Solidity · Base (EVM) · low-gas optimized contracts
Backend     Backend services integration for real-time data
Frontend    Next.js · ethers.js · wagmi
```

**Results**
- Secure smart contract architecture covering staking, rewards, and referral logic
- Gas-efficient EVM transactions on Base
- Full-stack delivery: contracts + backend + frontend dashboard

---

#### 🔷 Ape Store — Fair Launch Token Pad
> Base · [ape.store](https://ape.store/)

![Ape Store](assets/ape-store.png)

A user-friendly token launchpad on Base enabling instant token creation and trading with bonding curves, built around anti-rug and fair launch mechanics.

**How it works**
- Creators deploy tokens with zero liquidity required — bonding curves handle price discovery automatically
- Tokens are immediately tradable on launch with no setup friction for buyers
- Anti-rug mechanics enforced at the contract level to protect participants

**Stack**
```
Blockchain  Solidity · Base (EVM) · bonding curve contracts
Frontend    Next.js · wagmi · viem
```

**Results**
- Gas-efficient deployments optimized for Base's low-fee environment
- Trustless fair launch — no privileged creator actions post-deploy
- Accessible DeFi innovation without liquidity bootstrapping overhead

---

#### 🔷 Critters Quest — NFT Staking & Gaming dApp
> Solana · [critters.quest](https://critters.quest/)

![Critters Quest](assets/critters-quest.png)

A blockchain NFT game on Solana where collectibles evolve through staking, trading, and gameplay — fostering value growth via on-chain mechanics.

**How it works**
- Players stake NFT critters to earn $QUEST tokens (59.50M total supply)
- Daily spins and leaderboards drive engagement and competition
- PFP generator lets players customize their critters for identity and community

**Stack**
```
Blockchain  Rust · Anchor · Solana · SPL tokens
Frontend    Next.js · @solana/web3.js
```

**Results**
- Fully on-chain staking and reward distribution
- Gamified economy sustaining token utility through gameplay loops
- PFP customization integrated with on-chain metadata

---

#### 🔷 SolCrash — Crash Game on Solana
> Solana · [solcrash.io](https://solcrash.io/)

![SolCrash](assets/solcrash.png)

A provably fair crash game on Solana — a fork of the original Bustabit concept brought to the Solana ecosystem with on-chain settlement and low-latency gameplay.

**How it works**
- Players place bets before each round; a multiplier climbs until the game crashes at a provably fair random point
- Cash out before the crash to secure winnings; stay in too long and lose the bet
- All results are verifiable on-chain, ensuring no manipulation

**Stack**
```
Blockchain  Rust · Anchor · Solana · on-chain RNG
Frontend    Next.js · @solana/web3.js · real-time WebSocket feeds
```

**Results**
- Provably fair randomness with on-chain verifiability
- Sub-second transaction finality leveraging Solana's throughput
- Full port of Bustabit mechanics to a Solana-native architecture

---

#### 🔷 Solana Shuffle — Multi-Game Casino Platform
> Solana · [solanashuffle.com](https://www.solanashuffle.com/)

![Solana Shuffle](assets/solana-shuffle.png)

A full-featured on-chain casino on Solana offering a suite of provably fair games built for speed, low fees, and seamless wallet UX.

**Games**
Tower · Mines · Shuffle · Coinflip · Plinko · Horse Racing · Dice

**Stack**
```
Blockchain  Rust · Anchor · Solana · on-chain RNG per game type
Frontend    Next.js · @solana/web3.js · real-time game state
Backend     Go
```

**Results**
- Multi-game architecture with shared wallet and balance layer
- Provably fair outcomes across all game types
- High-throughput design exploiting Solana's speed for real-time gameplay

---

#### 🔷 Rafflor — NFT Raffle Platform
> Aptos · [rafflor.aptosmonkeys.club](https://rafflor.aptosmonkeys.club/)

![Rafflor](assets/rafflor.png)

An NFT raffle protocol on Aptos where users enter draws for high-value NFTs, with transparent ticket mechanics and on-chain winner selection.

**How it works**
- NFT holders list assets for raffle with configurable ticket supply and pricing
- Players purchase tickets; winner is selected via on-chain randomness at draw time
- Proceeds go directly to the NFT owner; winner receives the asset trustlessly

**Stack**
```
Blockchain  Move · Aptos framework · on-chain randomness
Frontend    TypeScript · Aptos SDK
```

**Results**
- Trustless raffle settlement with no intermediary custody
- Clean integration with Aptos NFT standards
- Transparent ticket accounting enforced at the contract level

---

#### 🔷 Plutonians — VR Space RPG & MMO
> Solana · [plutonians.tech](https://plutonians.tech/)

![Plutonians](assets/plutonians.png)

A Solana-based VR-enabled space RPG and MMO where players pilot NFT spaceships, explore galaxies, and participate in a fully on-chain economy.

**How it works**
- Players own NFT spaceships and items with real on-chain value and transferability
- Multiple tokens govern gameplay, travel, trading, and protocol governance
- VR integration brings immersive space exploration tied to on-chain asset state

**Stack**
```
Blockchain  Rust · Anchor · Solana · Metaplex · multi-token architecture
Game        VR-compatible client · real-time on-chain economy sync
Frontend    Next.js · @solana/web3.js
```

**Results**
- Full on-chain economy: NFT ownership, token governance, in-game mechanics
- Multi-token design separating gameplay utility from governance rights
- Scalable MMO architecture built on Solana's high-throughput infrastructure

---

## Core Principles

- **Security first.** Every contract is written assuming adversarial conditions.
- **Gas awareness.** Efficient storage layout, minimal calldata, optimized loops.
- **Composability.** Protocols should integrate cleanly with the broader ecosystem.
- **Shipping matters.** Clean architecture without over-engineering. Production, not demos.

---

## Let's Build

Open to protocol work, audits, and long-term engineering partnerships.

Reach out if you're building something serious on-chain.

[Telegram](https://t.me/haredoggy)
