# CopyPump

**Follow smart money. Keep control.**

CopyPump is building **non-custodial autonomous trading infrastructure on Solana** — designed around user custody, explicit risk limits, constrained wallet authority, and auditable execution.

> **Status:** technical alpha · Solana Devnet hardening · Mainnet intentionally blocked

### Start here

- **Public repository:** https://github.com/CopyPumpApp/CopyPump
- **Architecture:** https://github.com/CopyPumpApp/CopyPump/blob/main/docs/ARCHITECTURE.md
- **Devnet status:** https://github.com/CopyPumpApp/CopyPump/blob/main/docs/DEVNET_STATUS.md
- **Roadmap:** https://github.com/CopyPumpApp/CopyPump/blob/main/docs/ROADMAP.md

## What CopyPump is building

CopyPump is designed to discover high-signal on-chain trading activity and automate only the trading actions permitted by the user — without requiring a centralized platform to take custody of funds.

```text
SMART-MONEY SIGNAL
        ↓
QUALIFICATION
        ↓
RISK / POLICY CHECKS
        ↓
PERMITTED EXECUTION
        ↓
POSITION MANAGEMENT
        ↓
PnL / FEES
        ↓
AUDIT TRAIL
```

Target position lifecycle:

```text
BUY → POSITION → PARTIAL SELL → FULL SELL
```

## Design principles

- **User custody** — wallet keys remain under the user's control.
- **Bounded authority** — automation operates only inside explicit permissions and capital/risk limits.
- **Deterministic safety** — Risk/Policy checks remain authoritative.
- **Auditability** — important decisions and execution state should be traceable.
- **Factual status** — simulations, UI state, or AI output are never presented as proof of production readiness.

## Current engineering focus

The immediate focus is validating the execution and safety model on **Solana Devnet** before any production deployment.

Current work includes Phantom wallet integration, smart-money discovery and qualification, bounded authority, capital/risk controls, transaction confirmation and reconciliation, position lifecycle management, PnL/fee accounting, audit evidence, localization, and runtime/browser QA.

Mainnet execution remains intentionally blocked until the required safety and verification work is complete.

## Follow the build

- **GitHub:** https://github.com/CopyPumpApp/CopyPump
- **X:** https://x.com/CopyPumpAI
- **YouTube:** https://youtube.com/@copypumpapp
- **Pump.fun:** https://pump.fun/profile/CopyPumpApp
- **Contact:** copypumphq@gmail.com

If you're following the project, **star or watch the public repository** — public technical milestones and selected source material will be added as they clear security, privacy, and licensing review.

## Security

Please report suspected vulnerabilities privately. Never send seed phrases, private keys, API keys, session secrets, or production user data.

- **Security policy:** https://github.com/CopyPumpApp/.github/blob/main/SECURITY.md
- **Contribution guidelines:** https://github.com/CopyPumpApp/.github/blob/main/CONTRIBUTING.md

---

**Independent project. Not affiliated with pump.fun.**
