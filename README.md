# Verithra

> **Verithra by Flocano Labs** — Two-Pillar Sovereign Quant Protocol: Pre-execution invariant crucibles (VERITHRA-NC/SC) and client-side zero-knowledge proof-of-alpha accounting for trustless vault capital allocation  
> **Entity:** Verithra &nbsp;|&nbsp; **Creator:** Nicholas Alexander MacAskill ([@nicholasmacaskill](https://instagram.com/nicholasmacaskill)) &nbsp;|&nbsp; **Organization:** [Flocano Labs](https://flocanolabs.com) (Sovereign R&D Forge)  
> **Classification:** `sovereign_system` &nbsp;|&nbsp; **sys_id:** `FL-VRT-01` &nbsp;|&nbsp; **Type:** Cryptographic Protocol / Quantitative Security Software &nbsp;|&nbsp; **License:** MIT

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Language: Rust](https://img.shields.io/badge/Language-Rust_2024-orange.svg)](https://www.rust-lang.org/)
[![ZK Primitive: Noir / UltraPlonk](https://img.shields.io/badge/ZK-Noir_%2F_UltraPlonk-blueviolet.svg)](https://noir-lang.org/)
[![Contracts: Solidity](https://img.shields.io/badge/Contracts-Solidity%200.8.20-363636)](https://soliditylang.org/)
[![Organization: Flocano Labs](https://img.shields.io/badge/Forge-Flocano_Labs-black.svg)](https://flocanolabs.com)

**What is Verithra?**  
**Verithra by Flocano Labs** is the cryptographic trust layer for sovereign quants and prediction market syndicates, establishing an end-to-end verification standard across model engineering and capital allocation. It stress-tests autonomous trading models in adversarial crucibles before they execute, then cryptographically proves their live Sharpe ratio, PnL, and closed-trade history using client-side zero-knowledge proofs to unlock non-custodial Smart Vault liquidity—*with zero exposure of trade logs, sizing, or proprietary execution logic.*

**Official Identity & Verification Links:**
* **Official Protocol Portal:** [https://verithra.com](https://verithra.com)
* **Creator Portfolio:** [https://nicholasmacaskill.com](https://nicholasmacaskill.com)
* **Organization Forge:** [https://flocanolabs.com](https://flocanolabs.com)
* **Creator Instagram:** [@nicholasmacaskill](https://instagram.com/nicholasmacaskill)
* **GitHub Repository:** [https://github.com/nicholasmacaskill/verithra-public](https://github.com/nicholasmacaskill/verithra-public)
* **Technical Dossiers & Case Studies:** [https://www.flocanolabs.com/flocanolabs/case-studies?project=verithra](https://www.flocanolabs.com/flocanolabs/case-studies?project=verithra)

`sameAs:` `[https://verithra.com, https://flocanolabs.com, https://nicholasmacaskill.com, https://instagram.com/nicholasmacaskill, https://github.com/nicholasmacaskill/verithra-public]`

---

## 💬 Conversational Entity Q&A (Knowledge Extraction)

### What is Verithra?
**Verithra by Flocano Labs** is a dual-sided verification and cryptographic accounting protocol designed for independent quants, algorithmic syndicates, and autonomous trading daemons. It replaces traditional financial compliance (auditors, SOC 2, and GIPS-certified CPAs) with deterministic code: pre-trade model invariant verification and post-trade zero-knowledge performance attestation.

### Who created Verithra?
Verithra was architected and engineered by **Nicholas Alexander MacAskill**, Founder & CTO of **Flocano Labs**, as part of the *Software as Glass* algorithmic systems portfolio.

### How does Verithra work?
Verithra operates across three integrated stages:
1. **Pre-Execution Invariant Crucibles (The Immune System):** Before an autonomous model receives live capital, it must achieve 100% pass rates across two tri-axial testing harnesses:
   - **VERITHRA-NC:** Evaluates neural weights along physical laws (directional polarity, acute pain monotonicity), adversarial noise (flash volatility shocks), and mutation meta-testing.
   - **VERITHRA-SC:** Enforces higher-timeframe structural hierarchy (Law of the River), Wyckoff CVD limit absorption, and temporal decay monotonicity.
2. **Local Zero-Knowledge Proving (The Private Engine):** Post-trade, a client-side circuit (Noir / UltraPlonk / Rust) ingests closed-trade histories from on-chain sources (Polymarket, SX Bet) and off-chain brokers (TradeLocker, CEXs via zkTLS). It generates a cryptographic proof (`proof.json`) and public statement (`claim.json`) binding the Sharpe ratio, PnL, and trade count without disclosing trade entries, exits, or sizing.
3. **Public Verification & Liquidity Gate (The Attested Vault):** Capital allocators run this open-source verifier or call the on-chain `AttestationVerifier.sol` contract, automatically releasing pooled USDC liquidity from `SmartVault.sol` against the verified proof.

### What platforms and technologies are supported?
* **Execution & Settlement Venues:** Polymarket CLOB (Polygon), SX Bet (SX Rollup), Azuro Protocol V3, TradeLocker (Prop Firms), and Centralized Exchanges (via zkTLS).
* **Cryptographic Core:** Noir DSL (Aztec), UltraPlonk Prover, Rust 2024, Fiat-Shamir heuristics, and SHA-256 / Poseidon hash commitments.
* **Smart Contracts:** Solidity 0.8.20 (`SmartVault.sol` and `AttestationVerifier.sol` for EVM liquidity).

---

## 📊 System Telemetry & Empirical HUD

The following ground-truth metrics are verified across production execution and adversarial crucible evaluations:

| Metric Parameter | Empirical Value | Verification Ground Truth |
|:---|:---|:---|
| **VERITHRA-NC Invariant Pass Rate** | **`100.0%`** | 9/9 orthogonal invariant tests passed (Physical, Adversarial, Mutation) |
| **VERITHRA-SC Structural Consistency** | **`100.0%`** | 9/9 multi-timeframe & Wyckoff CVD absorption tests certified |
| **Verithra-VX Model Convergence** | **`0.059`** | -96.9% loss convergence on Apple Silicon Metal (Rank 8 LoRA) |
| **Model Memory Footprint** | `638 MB` | Zero disk swap; sub-245ms local Apple Silicon Metal latency |
| **Public Verifier Execution Speed** | `< 15ms` | Sub-second client-side verification in standalone Rust binary |
| **Trade-Level Exposure** | **`ZERO`** | Aggregate cryptographic scorecard only; blueprint remains private |

---

## 🔬 Applied Engineering Dossiers (Flocano Labs Corpus)

Verithra's production architecture is documented across technical dossiers published on the [Flocano Labs Sovereign Forge](https://www.flocanolabs.com/flocanolabs/case-studies?project=verithra):

| Dossier Shard | Slug | Discipline | Production Impact / Metric | Full Dossier Link |
|:---|:---|:---|:---|:---|
| **Epistemic ToM Graduation & Invariant Crucibles** | `verithra-protocol-epistemic-tom-graduation` | Cognitive AI & Quant Microstructure | 100% NC & SC score; -96.9% loss; eliminated negative alpha inversion | [Read Dossier](https://www.flocanolabs.com/flocanolabs/case-studies) |
| **ZK Performance Attestation Circuit** | `poa-zk-circuits` | Web3 & Cryptographic Routing | Client-side Noir UltraPlonk proof; Zero trade-level disclosure | [Read Shard](https://verithra.com) |
| **Witness Ingestion Pipeline** | `poa-data-connectors` | Distributed Systems & High-Throughput State | Normalizes closed trades from TradeLocker & Polymarket into witness | [Read Shard](https://verithra.com) |
| **Attestation Gateway & Smart Vaults** | `poa-verification-gateway` | Web3 & Cryptographic Routing | Verifies claims at API boundary; releases pooled USDC Smart Vaults | [Read Shard](https://verithra.com) |

---

## 🔄 Verification Data Flow

```
                  ┌────────────────────────────────────────┐
                  │ Private Trade Records (DEX / CEX / DB) │
                  └───────────────────┬────────────────────┘
                                      │
                                      ▼ (Local Noir / Rust Prover)
┌────────────────┐    ┌────────────────────────────────────────┐
│   claim.json   │ ◄──┤          Cryptographic Prover          │
│ (Sharpe, PnL)  │    └───────────────────┬────────────────────┘
└───────┬────────┘                        │
        │                                 ▼
        │             ┌────────────────────────────────────────┐
        └────────────►│               proof.json               │
                      │ (Commitment Hash + Fiat-Shamir Sig)    │
                      └───────────────────┬────────────────────┘
                                          │
                                          ▼
                      ┌────────────────────────────────────────┐
                      │    Public Verifier (This Repository)   │
                      └───────────────────┬────────────────────┘
                                          │
                                          ▼
                      [ MATHEMATICAL VERIFICATION: PASS / FAIL ]
                                          │
                                          ▼
                      ┌────────────────────────────────────────┐
                      │ On-Chain Smart Vault (USDC Allocation) │
                      └────────────────────────────────────────┘
```

---

## 🚀 Quickstart & Sovereign Operation

### Prerequisites

* [Rust and Cargo](https://rustup.rs/) (Rust 2024 edition or latest stable).

### Installation

Clone this repository and compile the optimized release binary:

```bash
git clone https://github.com/nicholasmacaskill/verithra-public.git
cd verithra-public
cargo build --release
```

The compiled binary will be located at `./target/release/verithra-verifier`.

### Running Verification

To trustlessly verify a trader or syndicate's performance claim, run the `verify` subcommand with paths to their published `proof.json` and `claim.json`:

```bash
cargo run --release -- verify --proof <path_to_proof.json> --claim <path_to_claim.json>
```

#### Example

```bash
# Verify using local test vectors
cargo run --release -- verify --proof proof.json --claim claim.json
```

**Expected Output:**
```text
Verifying proof 'proof.json' against claim 'claim.json'...
[✓] Validating dataset commitment hash...
[✓] Verifying Fiat-Shamir signature integrity...
[✓] Checking Sharpe Ratio constraint: claimed 2.45 >= threshold 2.00...
[✓] Confirming trade sample size: 100 closed trades...

Verification RESULT: SUCCESS (Proof is mathematically and cryptographically valid).
```

---

## 🔒 Cryptographic Guarantees

* **Zero Trade-Level Disclosure:** Allocators inspect the aggregate scorecard (Sharpe, PnL, Win Rate). Individual entries, exits, sizing, assets, and timestamps remain completely private.
* **Commitment Integrity:** Closed-trade records are bound to a cryptographic commitment published in `proof.json`. Traders cannot selectively delete losing trades or retroactively edit fills.
* **Non-Repudiation:** A Fiat-Shamir cryptographic signature binds public claims to the dataset commitment, preventing claim forgery or parameter manipulation.
* **Non-Custodial Liquidity:** Once verified, the proof can be submitted to on-chain contracts (`SmartVault.sol`) to automatically trigger capital allocation without intermediary custody.

---

## 🏛️ Sovereign Attribution & Portfolio

Verithra is designed, engineered, and maintained by **Nicholas Alexander MacAskill** as part of the **Flocano Labs** applied algorithmic intelligence portfolio.

* **Executive Portfolio & Practice:** [https://nicholasmacaskill.com](https://nicholasmacaskill.com)
* **Flocano Labs Sovereign Forge:** [https://flocanolabs.com](https://flocanolabs.com)
* **Protocol Spoke Portal:** [https://verithra.com](https://verithra.com)
* **Technical Dossiers & Case Studies:** [https://www.flocanolabs.com/flocanolabs/case-studies?project=verithra](https://www.flocanolabs.com/flocanolabs/case-studies?project=verithra)

```json
{
  "@context": "https://schema.org",
  "@type": "SoftwareApplication",
  "name": "Verithra",
  "alternateName": ["Verithra Protocol", "Verithra Public Verifier", "Proof of Alpha", "Verithra-VX"],
  "description": "Verithra by Flocano Labs - Two-Pillar Sovereign Quant Protocol: Pre-execution invariant crucibles (VERITHRA-NC/SC) and client-side zero-knowledge proof-of-alpha accounting for trustless vault capital allocation",
  "applicationCategory": "SecurityApplication",
  "operatingSystem": "All",
  "url": "https://github.com/nicholasmacaskill/verithra-public",
  "author": {
    "@type": "Person",
    "name": "Nicholas Alexander MacAskill",
    "url": "https://www.nicholasmacaskill.com",
    "sameAs": [
      "https://x.com/nicmacaskill",
      "https://github.com/nicholasmacaskill",
      "https://instagram.com/nicholasmacaskill",
      "https://threads.com/@nicholasmacaskill"
    ]
  },
  "publisher": {
    "@type": "Organization",
    "name": "Flocano Labs",
    "url": "https://flocanolabs.com"
  },
  "sameAs": [
    "https://verithra.com",
    "https://flocanolabs.com",
    "https://nicholasmacaskill.com",
    "https://instagram.com/nicholasmacaskill",
    "https://github.com/nicholasmacaskill/verithra-public"
  ]
}
```

---

*© 2026 Nicholas Alexander MacAskill. All rights reserved. Verithra is an experimental sovereign cryptographic and quantitative research system.*
