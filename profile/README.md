# CopyPump

**Non-custodial autonomous trading on Solana.**

CopyPump is building a trading platform designed around user custody, explicit risk limits, constrained wallet authority, and auditable execution.

> **Current status:** technical alpha / Solana Devnet hardening. CopyPump is not production-ready and should not be used with real funds.

## What we are building

CopyPump is designed to help users discover high-signal on-chain trading activity and automate permitted trading actions without handing custody of funds to a centralized platform.

The product direction is built around four principles:

- **User custody** — funds remain under the user's control.
- **Explicit limits** — automation operates within defined capital and risk boundaries.
- **Deterministic safety controls** — policy and risk checks gate execution.
- **Auditability** — important decisions and execution state should be traceable.

## Target flow

`SMART-MONEY SIGNAL → QUALIFICATION → RISK / POLICY CHECKS → EXECUTION → POSITION MANAGEMENT → PnL / FEES → AUDIT TRAIL`

The intended execution lifecycle includes:

`BUY → POSITION → PARTIAL SELL → FULL SELL`

## Current engineering focus

We are currently focused on validating the execution and safety model on Solana Devnet before any production deployment.

Current work includes:

- Phantom wallet integration;
- smart-money discovery and signal qualification;
- constrained session / delegated authority architecture;
- capital and risk controls;
- transaction confirmation and reconciliation;
- position lifecycle management;
- PnL and fee accounting;
- audit evidence and failure containment;
- Russian / English product localization;
- runtime and browser QA.

Mainnet execution remains intentionally blocked until the required safety and verification work is complete.

## Public channels

- **X:** https://x.com/copypumpai
- **YouTube:** https://youtube.com/@copypumpapp
- **Pump.fun:** https://pump.fun/profile/CopyPumpApp
- **Contact:** copypumphq@gmail.com

## Repository status

Core product development is currently maintained in private repositories while the project is in active technical hardening and review. Public engineering materials will be added here as they are ready to be shared responsibly.

---

**Independent project. Not affiliated with pump.fun.**
