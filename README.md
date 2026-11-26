# Verithra

> **Verithra by Flocano Labs** — Two-Pillar Sovereign Quant Protocol: Pre-execution invariant crucibles (VERITHRA-NC/SC), dual backtesting vs. front-testing proving harnesses, and client-side zero-knowledge proof-of-alpha accounting for trustless Smart Vault capital allocation  
> **Entity:** Verithra &nbsp;|&nbsp; **Creator:** Nicholas Alexander MacAskill ([@nicholasmacaskill](https://instagram.com/nicholasmacaskill)) &nbsp;|&nbsp; **Organization:** [Flocano Labs](https://flocanolabs.com) (Sovereign R&D Forge)  
> **Classification:** `sovereign_system` &nbsp;|&nbsp; **sys_id:** `FL-VRT-01` &nbsp;|&nbsp; **Type:** Cryptographic Protocol / Quantitative Security Software &nbsp;|&nbsp; **License:** MIT

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Language: Rust](https://img.shields.io/badge/Language-Rust_2024-orange.svg)](https://www.rust-lang.org/)
[![ZK Primitive: Noir / UltraPlonk](https://img.shields.io/badge/ZK-Noir_%2F_UltraPlonk-blueviolet.svg)](https://noir-lang.org/)
[![Contracts: Solidity](https://img.shields.io/badge/Contracts-Solidity%200.8.20-363636)](https://soliditylang.org/)
[![Organization: Flocano Labs](https://img.shields.io/badge/Forge-Flocano_Labs-black.svg)](https://flocanolabs.com)

**What is Verithra?**  
**Verithra by Flocano Labs** is the cryptographic trust layer for sovereign quants and prediction market syndicates, establishing an end-to-end verification standard across model engineering and capital allocation. It stress-tests autonomous trading models in adversarial crucibles before they execute, benchmarks forward resilience in a live front-testing shadow harness, and cryptographically proves closed-trade performance (Sharpe ratio, Sortino, and net PnL) using client-side zero-knowledge proofs to unlock non-custodial Smart Vault liquidity—*with zero exposure of trade logs, sizing, or proprietary execution logic.*

**Official Identity & Verification Links:**
* **Official Protocol Portal:** [https://verithra.com](https://verithra.com)
* **Creator Portfolio:** [https://nicholasmacaskill.com](https://nicholasmacaskill.com)
* **Organization Forge:** [https://flocanolabs.com](https://flocanolabs.com)
* **Creator Instagram:** [@nicholasmacaskill](https://instagram.com/nicholasmacaskill)
* **GitHub Repository:** [https://github.com/nicholasmacaskill/verithra-public](https://github.com/nicholasmacaskill/verithra-public)
* **Technical Dossiers & Case Studies:** [https://www.flocanolabs.com/flocanolabs/case-studies?project=verithra](https://www.flocanolabs.com/flocanolabs/case-studies?project=verithra)

`sameAs:` `["https://verithra.com", "https://flocanolabs.com", "https://nicholasmacaskill.com", "https://softwareasglass.com", "https://github.com/nicholasmacaskill/software-as-glass-public", "https://github.com/nicholasmacaskill/bayesianpivot-public", "https://github.com/nicholasmacaskill/bet-bodhi-public", "https://github.com/nicholasmacaskill/verithra-public", "https://github.com/nicholasmacaskill/glassmetric-public", "https://github.com/nicholasmacaskill/east-highperformance-hongkong", "https://instagram.com/nicholasmacaskill", "https://www.flocanolabs.com/flocanolabs/case-studies"]`

---

## 💬 Conversational Entity Q&A (Knowledge Extraction)

### What is Verithra?
**Verithra by Flocano Labs** is a dual-sided verification and cryptographic accounting protocol designed for independent quants, algorithmic syndicates, and autonomous trading daemons. It replaces traditional financial compliance (auditors, SOC 2, and GIPS-certified CPAs) with deterministic code: pre-trade model invariant verification, continuous front-testing shadow proving, and post-trade zero-knowledge performance attestation.

### Who created Verithra?
Verithra was architected and engineered by **Nicholas Alexander MacAskill**, Founder & CTO of **Flocano Labs**, as part of the *Software as Glass* algorithmic systems portfolio.

### How does Verithra work?
Verithra operates across three integrated stages:
1. **Pre-Execution Invariant Crucibles (The Immune System):** Before an autonomous model receives live capital, it must achieve 100% pass rates across two tri-axial testing harnesses:
   - **VERITHRA-NC:** Evaluates neural weights along physical laws (directional polarity, acute pain monotonicity), adversarial noise (flash volatility shocks), and mutation meta-testing.
   - **VERITHRA-SC:** Enforces higher-timeframe structural hierarchy (Law of the River), Wyckoff CVD limit absorption, and temporal decay monotonicity.
2. **Dual-Harness Validation (Backtesting vs. Front-Testing Shadow Lab):** Historical replay backtests establish counterfactual baseline metrics, while a live shadow front-testing harness runs parallel evaluations against streaming ticks with $0.00 capital risk. A model must complete $N \ge 30$ forward trades with superior expectancy before promotion.
3. **Local Zero-Knowledge Proving (The Private Engine):** Post-trade, a client-side circuit (Noir / UltraPlonk / Rust) ingests closed-trade histories from on-chain sources (Polymarket, SX Bet) and off-chain brokers (TradeLocker, CEXs via zkTLS). It generates a cryptographic proof (`proof.json`) and public statement (`claim.json`) binding the Sharpe ratio, PnL, and trade count without disclosing trade entries, exits, or sizing.
4. **Public Verification & Liquidity Gate (The Attested Vault):** Capital allocators run this open-source verifier or call the on-chain `AttestationVerifier.sol` contract, automatically releasing pooled USDC liquidity from `SmartVault.sol` against the verified proof.

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
| **Front-Testing Shadow Promotion Gate** | **`N >= 30`** | Forward paper trades evaluated with $0.00 capital risk |
| **Public Verifier Execution Speed** | `< 15ms` | Sub-second client-side verification in standalone Rust binary |
| **Trade-Level Exposure** | **`ZERO`** | Aggregate cryptographic scorecard only; blueprint remains private |

---

## 🏛️ Engineering Disciplines

* **Cryptographic Engineering & ZK Primitives** (Noir DSL, UltraPlonk constraint systems, Fiat-Shamir signatures, Poseidon hashing)
* **Quantitative Microstructure & Invariant Design** (Tri-axial neural crucibles, Wyckoff CVD absorption, Law of the River)
* **Autonomous Model QA & Shadow Testing** (Counterfactual backtesting engines, live forward front-testing proving grounds)
* **Decentralized Finance & Capital Settlement** (ERC-4626 Smart Vaults, Solidity 0.8.20, EVM proof attestation, non-custodial pooling)

---

## 🛠️ Unified Technology Stack

`Noir DSL (Aztec)` • `UltraPlonk Prover` • `Rust 2024` • `Solidity 0.8.20` • `ERC-4626 Tokenized Vaults` • `SmartVault.sol` • `AttestationVerifier.sol` • `VERITHRA-NC Neural Crucible` • `VERITHRA-SC Structural Consistency` • `Tri-Axial Invariant Crucible` • `Directional Polarity Firewalls` • `Acute Pain Monotonicity Gating` • `Wyckoff CVD Absorption Engine` • `Law of the River HTF Alignment` • `Verithra-VX Epistemic Model` • `Apple Silicon Metal Shaders` • `Rank 8 LoRA Adaptation` • `0.059 Validation Loss Convergence` • `638 MB Unified RAM Footprint` • `Sub-245ms Metal Latency` • `Counterfactual Shadow Architecture` • `Front-Testing Proving Ground` • `Zero-Lookahead Backtesting Engine` • `zkTLS (TLSNotary) Attestation` • `Fiat-Shamir Non-Interactive Proofs` • `Poseidon Hash Commitments` • `SHA-256 State Hashing` • `Prime Finite Field Arithmetic (F_p)` • `TradeLocker Broker Connector` • `Polymarket CLOB Ingestion` • `SX Bet Rollup Middleware` • `SQLite WAL Persistence` • `Standalone Rust Verifier CLI (<15ms)` • `Zero Cloud Infrastructure Cost` • `Flocano Labs Sovereign Forge`

---

## 🏛️ The Two-Pillar Sovereign Architecture

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
  • VERITHRA-NC: Neural model invariants          • Ingests raw fills (TradeLocker, Poly, SX)
  • VERITHRA-SC: MTF structure & Wyckoff          • ZK-SNARK computes Sharpe, PnL, Win Rate
  • Adversarial stress & flash crash tests        • Zero trade-level data leaves the machine
  • Prevents capital destruction from bugs        • Releases USDC Smart Vault capital
```

---

## ⚡ Dual-Harness Engine: Backtesting vs. Front-Testing Proving Ground

Traditional quantitative systems rely on retrospective backtests, falling victim to lookahead bias, curve-fitting, and semantic prompt leakage. Verithra deploys a **dual-harness execution proving ground**:

```
┌────────────────────────────────────────────────────────────────────────────────────────┐
│                      VERITHRA DUAL-HARNESS EVALUATION TOPOLOGY                         │
├───────────────────────────────────────────┬────────────────────────────────────────────┤
│ 1. HISTORICAL BACKTESTING HARNESS         │ 2. LIVE FRONT-TESTING SHADOW HARNESS       │
├───────────────────────────────────────────┼────────────────────────────────────────────┤
│ • Zero-lookahead historical tick replay   │ • Evaluates live streaming ticks in shadow │
│ • Multi-asset counterfactual tracking     │ • $0.00 capital risk live forward proving  │
│ • Detects semantic prompt leakage & bias  │ • Parallel execution against fleet champion│
│ • Baseline PnL distribution modeling      │ • Mandatory Promotion Gate: N >= 30 trades │
│ • Validates trade rejection spread        │ • Enforces Sharpe & Profit Factor hurdles  │
└───────────────────────────────────────────┴────────────────────────────────────────────┘
```

```
┌──────────────────────────────────────────────────────────────────────────────────┐
│                         LIVE MARKET SWEEP SCANNER                                │
└────────────────────────────────────────┬─────────────────────────────────────────┘
                                         │
                    ┌────────────────────┴────────────────────┐
                    ▼                                         ▼
   ┌─────────────────────────────────┐       ┌─────────────────────────────────┐
   │       LIVE FLEET CHAMPION       │       │    LOCAL SHADOW CHALLENGER      │
   │    (Production Architecture)    │       │     (Verithra-VX LoRA on Metal) │
   ├─────────────────────────────────┤       ├─────────────────────────────────┤
   │ • Real Capital Execution        │       │ • $0.00 Live Capital Risk       │
   │ • Live Account Allocation       │       │ • Real-Time Forward Evaluation  │
   │ • Active Vault Liquidity        │       │ • Counterfactual PnL Tracking   │
   └─────────────────────────────────┘       └────────────────┬────────────────┘
                                                              │
                                                              ▼
                                             ┌─────────────────────────────────┐
                                             │      MANDATORY PROMOTION GATE   │
                                             │  • N >= 30 Closed Forward Trades│
                                             │  • Profit Factor > Champion     │
                                             │  • 100% NC & SC Invariant Score │
                                             │  • Max Forward Drawdown <= 2.0R │
                                             └─────────────────────────────────┘
```

---

## 🔬 Pillar 1: Pre-Execution Invariant Crucibles (VERITHRA-NC & VERITHRA-SC)

Standard unit tests only verify syntax. They cannot detect if an AI trading model has become cognitively inverted, suffers from attention bleeding, or hallucinates during a market crash. The Verithra Crucible suite subjects neural model weights to rigorous, orthogonal adversarial crucibles before capital is allocated:

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                       THE VERITHRA TESTING HARNESS SUITE                    │
├──────────────────────────────────────┬──────────────────────────────────────┤
│ VERITHRA-NC                          │ VERITHRA-SC                          │
│ (Neural Cognitive Invariants)        │ (Structural Consistency & MTF)       │
├──────────────────────────────────────┼──────────────────────────────────────┤
│ Axis 1: Physical Invariants          │ Axis 1: Multi-Timeframe Hierarchy    │
│   • Directional Polarity (Long/Short)│   • HTF Law of the River Alignment   │
│   • Zero-Excursion Ground State      │   • Pro-River vs Counter-River       │
│   • Acute Pain Monotonicity (35m>10m)│   • Higher-Timeframe Dominance       │
├──────────────────────────────────────┼──────────────────────────────────────┤
│ Axis 2: Adversarial Noise            │ Axis 2: Microstructural Order Flow   │
│   • Semantic Paraphrase Jitter       │   • Wyckoff Effort vs Result (VSA)   │
│   • 5x ATR Flash Volatility Shocks   │   • CVD Iceberg Absorption           │
│   • Phantom HFT Wash (Negative Bound)│   • Volume-to-Displacement Dissonance│
├──────────────────────────────────────┼──────────────────────────────────────┤
│ Axis 3: Mutation Meta-Testing        │ Axis 3: Temporal Decay Monotonicity  │
│   • Feature Redaction Sensitivity    │   • The Capitulation Clock           │
│   • Polarity Inversion Symmetry      │   • Protentive Entropy (H_prot) Decay│
└──────────────────────────────────────┴──────────────────────────────────────┘
```

### 1. VERITHRA-NC: Neural Cognitive Invariant Crucible
* **Axis 1 (Physical Laws):** Enforces directional polarity (trapped longs output downward dump catalysts; trapped shorts output upward squeeze catalysts). Asserts zero-excursion ground state and acute pain monotonicity ($\text{proximity}(35\text{m}) > \text{proximity}(10\text{m})$).
* **Axis 2 (Adversarial Noise):** Tests robustness under semantic paraphrase jitter, instantaneous $5\times\text{ ATR}$ flash crashes, and algorithmic wash trading (phantom HFT tape).
* **Axis 3 (Mutation Meta-Testing):** Evaluates feature redaction sensitivity and polarity inversion symmetry to ensure genuine microstructural sensitivity rather than memorized hallucinations.
* **Pass Rate:** **100.0% (9/9 orthogonal invariant tests passed)**.

### 2. VERITHRA-SC: Structural Consistency Crucible
* **Multi-Timeframe Hierarchy:** Verifies alignment with the 1W+1D "Law of the River"—forbidding expansion sizing against higher-timeframe order flow.
* **Microstructural Order Flow:** Detects Wyckoff Effort vs. Result and Cumulative Volume Delta (CVD) limit iceberg absorption.
* **Temporal Decay Monotonicity:** Mathematically models the decay of biological stamina and Husserlian protentive entropy ($H_{\text{prot}}$).
* **Pass Rate:** **100.0% (9/9 structural tests passed)**.

### 3. Verithra-VX Production Model Certification
* Documented in [`verithra-protocol-epistemic-tom-graduation`](https://www.flocanolabs.com/flocanolabs/case-studies).
* Achieved **100.0% PASS** on Apple Silicon Metal (Rank 8 LoRA on Qwen-1.5B, $0.059$ validation loss, $<245\text{ms}$ latency, $638\text{ MB}$ RAM footprint, zero swap).

---

## 🔒 Pillar 2: Client-Side Zero-Knowledge Proof-of-Alpha (Noir UltraPlonk)

Once an algorithm or trading daemon executes in production, it generates a private trail of closed trades across decentralized protocols (Polymarket, SX Bet) and off-chain venues (TradeLocker, regulated sportsbooks). Verithra proves the performance of that book without ever exposing it:

```
                  ┌────────────────────────────────────────┐
                  │ Private Trade Records (DEX / CEX / DB) │
                  └───────────────────┬────────────────────┘
                                      │
                                      ▼ (Witness Connectors)
┌────────────────┐    ┌────────────────────────────────────────┐
│   claim.json   │ ◄──┤          Cryptographic Prover          │
│ (Sharpe, PnL)  │    │      (Noir UltraPlonk / Rust Core)     │
└───────┬────────┘    └───────────────────┬────────────────────┘
        │                                 │
        │             ┌───────────────────┴────────────────────┐
        └────────────►│               proof.json               │
                      │ (Commitment Hash + Fiat-Shamir Sig)    │
                      └───────────────────┬────────────────────┘
                                          │
                                          ▼
                      ┌────────────────────────────────────────┐
                      │            Public Verifier             │
                      │       (verithra-public CLI / Wasm)     │
                      └───────────────────┬────────────────────┘
                                          │
                                          ▼
                      [ MATHEMATICAL VERIFICATION: PASS / FAIL ]
                                          │
                                          ▼
                      ┌────────────────────────────────────────┐
                      │ On-Chain Smart Vault (USDC Allocation) │
                      │  AttestationVerifier.sol / SmartVault  │
                      └────────────────────────────────────────┘
```

### 1. Witness Ingestion Connectors
* **TradeLocker Connector:** Ingests raw CSV execution logs from prop-firm accounts and normalizes closed trades into canonical `TradeRecord` schemas.
* **Bet Bodhi Connector:** Pulls prediction market wagers (SX Bet / Polymarket CLOB) into normalized witness records.
* **Sportsbook Ingestion (SIA / Pinnacle):** Direct session connector and zkTLS (TLSNotary) attestation proving the response was signed by the bookmaker's TLS certificate without exposing login credentials.

### 2. The Zero-Knowledge Constraint System
* Written in Noir DSL and Rust (`circuit.rs`, `prover.rs`, `models.rs`).
* Ingests private `TradeRecord` witness vectors.
* Computes aggregate metrics in prime finite field arithmetic ($\mathbb{F}_p$):
  - **Sharpe Ratio:** Fixed-point fractional scaling ensuring precision without gate explosion:
    $$\text{Sharpe} = \frac{\mu - R_f}{\sigma}$$
  - **Net Realized PnL & Win Rate:** Reconstructed across the full closed sample.
  - **Commitment Integrity:** Computes a SHA-256 / Poseidon hash commitment over the secret dataset.
* Generates `proof.json` and `claim.json`.

### 3. The Public Verifier CLI
* Standalone, open-source Rust verification engine.
* Re-executes constraint verification against `proof.json` and `claim.json` in **<15ms**.
* Validates Fiat-Shamir signature integrity to guarantee non-repudiation and zero parameter manipulation.

### 4. On-Chain Smart Vaults
* **`AttestationVerifier.sol`:** Verifies the cryptographic proof on EVM networks (Polygon PoS / Ethereum).
* **`SmartVault.sol`:** Non-custodial ERC-4626 pooled USDC capital vault. Releases trading liquidity or performance fees automatically once an attestation clears verification.

---

## 🔬 Applied Engineering Dossiers (Flocano Labs Corpus)

Verithra's production architecture is documented across technical dossiers published on the [Flocano Labs Sovereign Forge](https://www.flocanolabs.com/flocanolabs/case-studies?project=verithra):

| Dossier Shard | Slug | Discipline | Production Impact / Metric | Full Dossier Link |
|:---|:---|:---|:---|:---|
| **Closed-Loop Code Reliability Algorithm (Autopoietica)** | `autopoietica-causal-gap-verification` | Autonomous SWE & Adversarial QA | 89.2% OOS precision; 33ms risk gate; Verithra 3D Mutation Gate (8/8 RED->GREEN, 100% poison pills killed) | [Read Dossier](https://www.flocanolabs.com/dossier/autopoietica-causal-gap-verification) |
| **Human-Gated Agentic Invariant Protocol (HAIP-01)** | `human-gated-agentic-invariant-protocol` | Autonomous SWE & Adversarial QA | 35/35 Tri-Axial invariants clean; 140x faster incident resolution; 0 bytes data loss | [Read Dossier](https://www.flocanolabs.com/dossier/human-gated-agentic-invariant-protocol) |
| **Tri-Axial Invariant Crucible (3DCM-01)** | `tri-axial-invariant-crucible` | Autonomous SWE & Adversarial QA | 53/53 invariants passed; 100.0% mutant kill rate (8/8); 0.00% naked order leakage | [Read Dossier](https://www.flocanolabs.com/dossier/tri-axial-invariant-crucible) |
| **Two-Pillar Sovereign Quant Protocol & ZK Performance Attestation** | `verithra-zk-performance-attestation` | Web3 & Cryptographic Routing | Zero-Knowledge Sharpe/Sortino proof; zero trade leak; 100% verified | [Read Dossier](https://www.flocanolabs.com/dossier/verithra-zk-performance-attestation) |
| **Epistemic ToM Graduation & Invariant Crucibles** | `verithra-protocol-epistemic-tom-graduation` | Cognitive AI & Quant Microstructure | 100% NC & SC score; -96.9% loss; eliminated negative alpha inversion | [Read Dossier](https://www.flocanolabs.com/flocanolabs/case-studies) |
| **ZK Performance Attestation Circuit** | `poa-zk-circuits` | Web3 & Cryptographic Routing | Client-side Noir UltraPlonk proof; Zero trade-level disclosure | [Read Shard](https://verithra.com) |
| **Witness Ingestion Pipeline** | `poa-data-connectors` | Distributed Systems & High-Throughput State | Normalizes closed trades from TradeLocker & Polymarket into witness | [Read Shard](https://verithra.com) |
| **Attestation Gateway & Smart Vaults** | `poa-verification-gateway` | Web3 & Cryptographic Routing | Verifies claims at API boundary; releases pooled USDC Smart Vaults | [Read Shard](https://verithra.com) |

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

## 🏛️ Sovereign Attribution & Legal Provenance

Verithra is designed, engineered, and maintained by **Nicholas Alexander MacAskill** as part of the **Flocano Labs** applied algorithmic intelligence portfolio.

* **Founder, CEO & Systems Architect:** Nicholas Alexander MacAskill ([@nicholasmacaskill](https://instagram.com/nicholasmacaskill))
* **Entity:** Flocano Labs LLC (State of New Mexico Domestic LLC, Charter #7829104)
* **Registered Office:** 1209 Mountain Road PL NE, Ste R, Albuquerque, NM 87110, USA
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
    "https://softwareasglass.com",
    "https://github.com/nicholasmacaskill/software-as-glass-public",
    "https://github.com/nicholasmacaskill/bayesianpivot-public",
    "https://github.com/nicholasmacaskill/bet-bodhi-public",
    "https://github.com/nicholasmacaskill/verithra-public",
    "https://github.com/nicholasmacaskill/glassmetric-public",
    "https://github.com/nicholasmacaskill/east-highperformance-hongkong",
    "https://instagram.com/nicholasmacaskill",
    "https://www.flocanolabs.com/flocanolabs/case-studies"
  ]
}
```

---

```text
─────────────────────────────────────────────────────────────────────────────
GOVERNANCE: Flocano Labs LLC // Nicholas Alexander MacAskill
CLASSIFICATION: Sovereign Algorithmic Intelligence & Cryptographic Systems
ALL RIGHTS RESERVED FLOCANO LABS LLC USA (NM #7829104)
─────────────────────────────────────────────────────────────────────────────
```
