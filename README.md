# Verithra: The Sovereign Quant Protocol
### Public Verifier & Proof-of-Alpha Engine

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Language: Rust](https://img.shields.io/badge/Language-Rust_2024-orange.svg)](https://www.rust-lang.org/)
[![ZK Primitive: Noir / UltraPlonk](https://img.shields.io/badge/ZK-Noir_%2F_UltraPlonk-blueviolet.svg)](https://noir-lang.org/)
[![Organization: Flocano Labs](https://img.shields.io/badge/Forge-Flocano_Labs-black.svg)](https://flocanolabs.com)

**Verithra is the cryptographic trust layer for independent quants, autonomous trading daemons, and prediction market syndicates.** 

This repository contains the standalone, open-source **Public Verifier Engine**. It enables capital allocators, syndicate partners, and smart contracts to trustlessly verify cryptographic performance claims (Sharpe Ratio, Net Realized PnL, Win Rate, and trade count) without requiring access to proprietary execution logs, order books, API credentials, or wallet addresses.

---

## 🏛️ The Two-Pillar Sovereign Architecture

Traditional finance relies on human gatekeepers—compliance officers, SOC 2 auditors, and GIPS-certified CPAs—to establish trust. Verithra replaces bureaucratic overhead with deterministic mathematics across two complementary lifecycle stages:

```
┌────────────────────────────────────────────────────────────────────────────────────────┐
│                                   VERITHRA PROTOCOL                                    │
│                     The Sovereign Quant Verification Lifecycle                         │
└───────────────────────────────────────────┬────────────────────────────────────────────┘
                                            │
                    ┌───────────────────────┴───────────────────────┐
                    │                                               │
                    ▼                                               ▼
     ┌─────────────────────────────┐                 ┌─────────────────────────────┐
     │          PILLAR 1           │                 │          PILLAR 2           │
     │      PRE-EXECUTION QA       │                 │   POST-EXECUTION ACCOUNTING │
     │  (Cognitive Crucible Suite) │                 │  (ZK Proof-of-Alpha Ledger) │
     └──────────────┬──────────────┘                 └──────────────┬──────────────┘
                    │                                               │
                    ▼                                               ▼
       "Is the algorithm sound?"                       "Did the trading make money?"
                    │                                               │
  • VERITHRA-NC: Neural model invariants          • Ingests raw fills (TradeLocker, SIA, Poly)
  • VERITHRA-SC: MTF structure & Wyckoff          • ZK-SNARK computes Sharpe, PnL, Win Rate
  • Adversarial stress & flash crash tests        • Zero trade-level data leaves the machine
  • Prevents capital destruction from bugs        • Releases USDC Smart Vault capital
```

### Pillar 1: Pre-Execution Algorithm QA (The Invariant Crucibles)
Before an autonomous strategy or deep learning model is granted authority over live capital, it must pass the **Verithra Invariant Crucible**:
* **VERITHRA-NC (Neural Cognitive Invariant Crucible):** Evaluates model weights along three orthogonal axes:
  1. *Physical Invariants:* Directional polarity, ground state stability, acute pain monotonicity ($35\text{m} > 10\text{m}$ underwater capitulation).
  2. *Adversarial Noise:* Semantic paraphrase jitter, $5\times\text{ ATR}$ flash volatility shocks, phantom HFT tape.
  3. *Mutation Meta-Testing:* Feature redaction sensitivity and polarity inversion symmetry.
* **VERITHRA-SC (Structural Consistency Crucible):** Enforces multi-timeframe structural hierarchy (1W+1D "Law of the River") and Wyckoff volume-spread analysis (CVD iceberg absorption).
* **Verithra-VX Model:** Production Epistemic Theory of Mind (ToM) model achieving 100.0% Noetic Certification on Apple Silicon Metal prior to live deployment.

### Pillar 2: Post-Execution Cryptographic Accounting (This Verifier)
Once an algorithm executes in production, it generates a private trail of fills across decentralized DEXs (Polymarket, SX Bet) and off-chain venues (TradeLocker, regulated sportsbooks). 
* The **Private Prover** computes statistical metrics in a client-side zero-knowledge circuit, generating a cryptographic proof (`proof.json`) and a public signed statement (`claim.json`).
* This **Public Verifier** independently validates that the claimed performance mathematically corresponds to the cryptographic dataset commitment—**with zero exposure of trade entries, exits, sizing, or signal logic.**

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

## 🚀 Getting Started

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

---

## 🛠️ Usage

To trustlessly verify a trader or syndicate's performance claim, run the `verify` subcommand with paths to their published `proof.json` and `claim.json`:

```bash
cargo run --release -- verify --proof <path_to_proof.json> --claim <path_to_claim.json>
```

### Example Verification

```bash
# Verify using local test vectors
cargo run --release -- verify --proof proof.json --claim claim.json
```

**Expected Console Output:**
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

| Property | Guarantee |
| :--- | :--- |
| **Zero Trade-Level Disclosure** | Allocators inspect the aggregate scorecard (Sharpe, PnL, Win Rate). Individual entries, exits, sizing, assets, and timestamps remain completely private. |
| **Commitment Integrity** | Closed-trade records are bound to a cryptographic commitment published in `proof.json`. Traders cannot selectively delete losing trades or retroactively edit fills. |
| **Non-Repudiation** | A Fiat-Shamir cryptographic signature binds public claims to the dataset commitment, preventing claim forgery or parameter manipulation. |
| **Non-Custodial Liquidity** | Once verified, the proof can be submitted to on-chain contracts (`SmartVault.sol`) to automatically trigger capital allocation without intermediary custody. |

---

## 📜 License

Distributed under the MIT License. See [LICENSE](LICENSE) for details.

---

## 🌐 Ecosystem & Architecture References

* **Official Protocol Portal:** [verithra.com](https://verithra.com)
* **Flocano Labs Engineering Forge:** [flocanolabs.com](https://flocanolabs.com)
* **Author Portfolio & System Shards:** [nicholasmacaskill.com](https://nicholasmacaskill.com)
* **Technical Dossier:** *The VERITHRA Protocol: Epistemic Theory of Mind Graduation & Counterfactual Filter Alpha* (`dossier/verithra-protocol-epistemic-tom-graduation`)
