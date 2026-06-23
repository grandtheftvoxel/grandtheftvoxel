<div align="center">

# GRAND THEFT VOXEL

### Steal the block. Run the city. Own the chain.

**A browser-based voxel crime sandbox powered by Three.js on Solana.**
No download. No wallet required to play. 100% fair launch.

[![GitHub Stars](https://img.shields.io/github/stars/grandtheftvoxel?style=flat-square&color=yellow&label=Stars)](https://github.com/grandtheftvoxel)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](LICENSE)
[![Chain: Solana](https://img.shields.io/badge/Chain-Solana-9945FF?style=flat-square&logo=solana)](https://solana.com)
[![Launch: PumpFun](https://img.shields.io/badge/Launch-PumpFun-green?style=flat-square)](https://pump.fun)
[![Twitter](https://img.shields.io/badge/Twitter-@grandtheftvoxel-1DA1F2?style=flat-square&logo=twitter)](https://twitter.com/grandtheftvoxel)

[grandtheftvoxel.fun](https://grandtheftvoxel.fun) &nbsp;|&nbsp;
[@grandtheftvoxel](https://twitter.com/grandtheftvoxel) &nbsp;|&nbsp;
[t.me/grandtheftvoxel](https://t.me/grandtheftvoxel)

</div>

---

## What is Grand Theft Voxel

Grand Theft Voxel is an open-world arcade crime sandbox that runs entirely in your browser. Open the URL, spawn in a procedurally generated voxel city, steal cars, complete missions, and outrun the cops. No installation. No account. No friction.

The $GTV token lives on Solana and powers the V2 progression layer: persistent garages, cosmetic ownership, ranked heist tournaments, and on-chain prize settlement. The game is playable today. The economy launches on PumpFun via 100% fair launch.

**What makes this different:**

- Instant access: one URL opens a fully featured voxel city with physics, AI traffic, and a complete HUD
- Browser-native Three.js engine: no Unity WebGL bloat, no plugins, no 200MB downloads
- Heat x Hustle system: wanted stars escalate dynamically, cops scale to your chaos level
- Token-optional MVP: the game ships before the wallet layer, so the fun is proven first
- On-chain prizes: V2 ranked heists settle payouts directly to winner wallets via Solana

---

## Core Mechanics

| Mechanic | Description |
|---|---|
| Steal Car | Walk up to any vehicle and jack it. Speed tier determines handling. |
| Take a Job | Accept delivery, rampage, or escape missions from the job board. |
| Wanted Stars | 1-5 stars. Each level adds faster, smarter, more aggressive cop units. |
| Police Chase | Cops pathfind through traffic. Lose them by changing vehicles or hiding. |
| Earn CASH | Missions, carnage, and escapes fill your wallet. In-game currency only at MVP. |
| B-Shop | Spend CASH on weapons, armor, and vehicle upgrades mid-session. |
| Escalate | Higher wanted level = harder missions available = bigger payouts. |
| Mobile Ready | Full touch controls: dual joystick + action cluster, no keyboard required. |

---

## Core Loop

```
┌─────────────────────────────────────────────────────────────────────┐
│                      GRAND THEFT VOXEL LOOP                         │
│                                                                       │
│   OPEN URL                                                           │
│      │                                                               │
│      ▼                                                               │
│   SPAWN IN CITY ──► STEAL CAR / TAKE JOB / CAUSE CHAOS              │
│                               │                                      │
│                               ▼                                      │
│                        WANTED STARS RISE (1 → 5)                    │
│                               │                                      │
│                               ▼                                      │
│                        COPS CHASE YOU                                │
│                         ├── ESCAPE ──────────────────┐              │
│                         └── BUSTED (respawn, lose cash)│             │
│                                                       │              │
│                               ▼                       │              │
│                        EARN CASH ◄────────────────────┘             │
│                               │                                      │
│                               ▼                                      │
│                          B-SHOP                                      │
│                         ├── Buy weapon / armor / upgrade             │
│                         └── ESCALATE ──► harder missions ──► MORE $ │
│                                                                      │
└─────────────────────────────────────────────────────────────────────┘
```

---

## Tech Stack

| Layer | Technology |
|---|---|
| 3D Engine | Three.js r160 |
| Language | TypeScript 5.x |
| Build Tool | Vite 5 |
| Rendering | WebGL 2.0 (bloom post-processing, day/night cycle) |
| Game Modules | Procedural city, vehicle physics, AI traffic, cop AI, missions, HUD |
| Mobile | Custom touch controls (dual joystick + action cluster) |
| Chain | Solana (mainnet-beta) |
| Wallet | Phantom / Solflare via @solana/wallet-adapter |
| API (V2) | Node.js REST + WebSocket relay |
| Database (V2) | Managed Postgres |
| Token Launch | PumpFun fair launch |

---

## Roadmap

### Phase 1: Launch (MVP - Live)
- [x] Procedural 7x7 voxel city with roads, blocks, buildings
- [x] 5 car types + bikes with arcade physics
- [x] Fists + auto-aim pistol combat
- [x] 30 varied pedestrians + AI traffic with junctions
- [x] Day/night cycle + bloom post-FX
- [x] Health/armor/cash wallet HUD
- [x] 3 mission types: delivery, rampage, escape
- [x] Minimap HUD: stars, cash, health, speedo, weapon
- [x] Mobile touch controls
- [x] PumpFun 100% fair launch ($GTV)

### Phase 2: Accounts + Garage
- [ ] Wallet connect (Phantom/Solflare)
- [ ] Persistent garage: owned vehicles per wallet
- [ ] Player profile: rep tier, stats, cosmetics
- [ ] V2 Account API live
- [ ] Cosmetic marketplace: premium cars, liveries, weapon skins

### Phase 3: Multiplayer + Ranked
- [ ] WebSocket relay: crew lobbies (4-player)
- [ ] Ranked weekend heist tournaments
- [ ] On-chain prize pool settlement via Solana
- [ ] Leaderboard: Heat x Hustle score ranking

### Phase 4: Living City
- [ ] Expanded city size (14x14 grid)
- [ ] Dynamic events: turf wars, police raids, bounties
- [ ] Governance: $GTV holders vote on city expansion priorities
- [ ] Cross-session rep: STREET -> RUNNER -> BOSS -> KINGPIN progression

---

## $GTV Token at a Glance

| Parameter | Value |
|---|---|
| Token Name | Grand Theft Voxel |
| Ticker | $GTV |
| Chain | Solana |
| Total Supply | 1,000,000,000 (1B) |
| Launch Platform | PumpFun |
| Launch Type | 100% Fair Launch |
| Team Allocation | 0% (no pre-mine) |
| Graduation Threshold | 85 SOL bonding curve |
| Post-Graduation | Raydium AMM |
| Creator Fee | PumpFun standard creator fee |

---

## SCAM WARNING

> **Official links only. There is no team DM. There is no airdrop. There is no presale.**

- Official site: **grandtheftvoxel.fun**
- Official Twitter: **@grandtheftvoxel**
- Official Telegram: **t.me/grandtheftvoxel**
- Official bot: **@grandtheftvoxel_bot**

Anyone DMing you about $GTV tokens, airdrops, presales, or "whitelist spots" is a scammer. The contract address will be announced only through official channels. Never paste your seed phrase anywhere. Never send SOL to anyone claiming to be the team.

---

## Quick Start

```bash
# Clone the game engine
git clone https://github.com/grandtheftvoxel/grandtheftvoxel-engine
cd grandtheftvoxel-engine

# Install dependencies
npm install

# Start local dev server
npm run dev

# Open browser at http://localhost:5173
```

Or play instantly at [grandtheftvoxel.fun](https://grandtheftvoxel.fun) — no install required.

---

<div align="center">

<sub>Grand Theft Voxel ($GTV) is a browser game and experimental token project on Solana. Nothing in this repository constitutes financial advice or an offer to sell securities. Cryptocurrency and token investments carry significant risk including total loss of principal. Play for fun. Research before trading. The team holds zero pre-mined supply.</sub>

</div>
