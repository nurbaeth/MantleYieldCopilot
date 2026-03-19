```
███╗   ███╗ █████╗ ███╗   ██╗████████╗██╗     ███████╗
████╗ ████║██╔══██╗████╗  ██║╚══██╔══╝██║     ██╔════╝
██╔████╔██║███████║██╔██╗ ██║   ██║   ██║     █████╗  
██║╚██╔╝██║██╔══██║██║╚██╗██║   ██║   ██║     ██╔══╝  
██║ ╚═╝ ██║██║  ██║██║ ╚████║   ██║   ███████╗███████╗
╚═╝     ╚═╝╚═╝  ╚═╝╚═╝  ╚═══╝   ╚═╝   ╚══════╝╚══════╝
         YIELD COPILOT — AI-powered DeFi assistant
```

<div align="center">

![Mantle](https://img.shields.io/badge/Built%20on-Mantle-1d9e75?style=flat-square&logoColor=white)
![Status](https://img.shields.io/badge/Status-Concept-ef9f27?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-4a4f5a?style=flat-square)
![Bounty](https://img.shields.io/badge/Mantle%20Bounty-Topic%202-7f77dd?style=flat-square)

**An AI agent that monitors yield opportunities across the Mantle DeFi ecosystem in real time — and tells you when to move.** 

[Live Demo](./index.html) · [Concept Brief](#concept) · [How It Works](#how-it-works) · [Mantle Integration](#mantle-integration)
 
</div>
  
---  
 
## The Problem   
   
DeFi on Mantle is fast. APYs shift overnight. TVL moves without warning. Utilization rates spike before you notice.  

Most users track 5–10 protocols manually — checking dashboards, reading Twitter, refreshing DefiLlama. By the time they spot an opportunity, it's already gone. 

``` 
Pendle mETH PT yield: +3.1% in 6 hours  →  most users missed it
Lendle utilization:    91%               →  rate risk invisible until too late
Merchant Moe TVL:     -8.4% overnight   →  exit window already closed
```

**Mantle Yield Copilot solves this.**

---

## Concept

> One AI agent. All Mantle protocols. Zero dashboard fatigue.

Mantle Yield Copilot is a proposed AI-powered tool that:

- **Indexes** live on-chain data from Pendle, INIT Capital, Merchant Moe, Lendle, and other Mantle protocols
- **Detects** yield shifts, TVL changes, and utilization anomalies as they happen
- **Generates** plain-English alerts with specific rebalance recommendations
- **Explains** migration steps and risk factors on demand

No spreadsheets. No constant monitoring. Just an AI that watches Mantle for you.

---

## How It Works

```
┌─────────────────────────────────────────────────────────┐
│                   MANTLE BLOCKCHAIN                     │
│  Pendle · INIT Capital · Merchant Moe · Lendle · ...    │
└──────────────────────┬──────────────────────────────────┘
                       │  on-chain events + state reads
                       ▼
┌─────────────────────────────────────────────────────────┐
│                  DATA INDEXER LAYER                     │
│  APY deltas · TVL changes · utilization rates           │
│  liquidity depth · protocol health signals              │
└──────────────────────┬──────────────────────────────────┘
                       │  structured feed
                       ▼
┌─────────────────────────────────────────────────────────┐
│                    AI AGENT CORE                        │
│  Analyzes data → compares risk/reward → scores opps     │
│  Generates alerts · explains tradeoffs · ranks actions  │
└──────────────────────┬──────────────────────────────────┘
                       │  recommendations
                       ▼
┌─────────────────────────────────────────────────────────┐
│                  USER INTERFACE                         │
│  Dashboard · AI chat · one-click action routing         │
└─────────────────────────────────────────────────────────┘
```

---

## Mantle Integration

Mantle's architecture makes this uniquely possible here:

| Layer | Integration |
|---|---|
| **Smart contracts** | Read APY, utilization, TVL directly from protocol contracts |
| **mETH** | Track yield tokenization on Pendle; surface mETH staking opportunities |
| **Transaction layer** | Route rebalance actions through Mantle's low-fee infrastructure |
| **On-chain data** | Index event logs for real-time anomaly detection |

Mantle's low gas fees make frequent, small rebalances economically viable — something that's impossible on mainnet Ethereum.

---

## Interface Preview

The mockup demonstrates the core UX:

- **Network Overview** — live metrics: total TVL, avg APY, active AI alerts
- **Protocol Cards** — Pendle, INIT, Merchant Moe, Lendle with APY sparklines
- **AI Copilot Panel** — natural language recommendations + one-click actions
- **Alert Feed** — ranked by urgency (opportunity / caution / risk)

→ Open `index.html` to explore the full interactive mockup.

---

## Protocols Covered (v1 scope)

| Protocol | Type | AI monitoring |
|---|---|---|
| Pendle Finance | Yield tokenization | APY delta, PT/YT ratio |
| INIT Capital | Lending | Utilization rate, borrow APY |
| Merchant Moe | AMM | TVL shifts, fee APY, impermanent loss signals |
| Lendle | Money market | Variable rate spikes, collateral health |

---

## Why AI + Mantle 

The combination of Mantle's growing DeFi ecosystem and AI's pattern-recognition capability creates a genuine edge:

- Mantle has multiple active protocols each with their own APY dynamics
- Changes happen faster than any human can monitor manually  
- AI can cross-reference multiple signals simultaneously — TVL + APY + utilization + liquidity depth — and surface non-obvious correlations
- The low-cost execution environment means AI recommendations can actually be acted on without gas eating the profit

---

## Submission Info

This concept was created for the **Mantle Squad Bounty — "When AI Meets Mantle"** (Mar 11–31, 2025).

- **Category**: Topic 2 — Design an AI Tool for Mantle

---

## License

MIT — feel free to build on this concept.

---

<div align="center">
<sub>Built with curiosity · Powered by Mantle</sub>
</div>
