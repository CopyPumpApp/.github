# CopyPump

**Follow smart money. Keep control.**

CopyPump is building **non-custodial autonomous trading infrastructure on Solana** — designed around user custody, explicit risk limits, constrained wallet authority, and auditable execution.

> **Status:** technical alpha · Solana Devnet hardening · Mainnet intentionally blocked

### Start here

- **Public contributor repository:** https://github.com/CopyPumpApp/CopyPump
- **Current expert contribution task:** https://github.com/CopyPumpApp/CopyPump/issues/9
- **Contributor intro path:** https://github.com/CopyPumpApp/CopyPump/issues/new
- **Official website source:** https://github.com/CopyPumpApp/CopyPump-Website
- **Discord:** https://discord.gg/DNBQtqw6R
- **Project status:** https://github.com/CopyPumpApp/CopyPump/blob/main/docs/PROJECT_STATUS.md
- **Architecture:** https://github.com/CopyPumpApp/CopyPump/blob/main/docs/ARCHITECTURE.md
- **Devnet status:** https://github.com/CopyPumpApp/CopyPump/blob/main/docs/DEVNET_STATUS.md
- **Roadmap:** https://github.com/CopyPumpApp/CopyPump/blob/main/docs/ROADMAP.md

## Contribute

We welcome volunteer open-source contributors who want to help with Solana, TypeScript/Node.js, QA, performance, security review, documentation, or early product testing.

The previous beginner code task, **[#39: bounded read-only Devnet `getTransaction` lookup](https://github.com/CopyPumpApp/CopyPump/issues/39)**, is now completed in **[PR #42](https://github.com/CopyPumpApp/CopyPump/pull/42)**. The public repository now includes a Devnet-only bounded transaction-read helper, a fail-closed response classifier, and deterministic tests. We are intentionally not opening another `good first issue` merely to create cosmetic activity.

For experienced Solana transaction/runtime engineers, **[#9: review safe Solana v1 send-path resource bounds](https://github.com/CopyPumpApp/CopyPump/issues/9)** is the current expert-review path. It asks for a conservative public safety contract and deterministic negative cases; it does not ask contributors to enable v1 sending.

If #9 does not match your skills, open an issue titled **`Contributor intro: <your area>`** in the public repository and describe what you build, test, research, or use. That lets the maintainer map contributors to real public-safe work instead of manufacturing low-value tasks.

Participation in ordinary public contribution tasks is voluntary and unpaid. CopyPump does not promise bounties, tokens, equity, revenue share, employment, or future compensation for ordinary open-source contributions.

[Contribution guide](https://github.com/CopyPumpApp/CopyPump/blob/main/CONTRIBUTING.md) · [Open issues](https://github.com/CopyPumpApp/CopyPump/issues) · [Discussions](https://github.com/CopyPumpApp/CopyPump/discussions) · [Discord](https://discord.gg/DNBQtqw6R)

Good places to start in Discord: `#questions`, `#devnet-testing`, `#bug-reports`, and `#feature-ideas`.

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

## Current public milestone

The immediate proof target is a reviewed **real Solana Devnet lifecycle** covering execution, confirmation, reconciliation, PnL/fee accounting, and audit evidence for:

```text
BUY → POSITION → PARTIAL SELL → FULL SELL
```

Simulations and paper execution are not presented as equivalent proof. Mainnet remains intentionally blocked while hardening and verification continue.

## Follow the build

- **GitHub:** https://github.com/CopyPumpApp/CopyPump
- **Website source:** https://github.com/CopyPumpApp/CopyPump-Website
- **Discord:** https://discord.gg/DNBQtqw6R
- **X:** https://x.com/CopyPumpAI
- **YouTube:** https://youtube.com/@copypumpapp
- **Pump.fun:** https://pump.fun/profile/CopyPumpApp
- **Contact:** copypumphq@gmail.com

If you're following the project, **star or watch the public repository** — public technical milestones and selected source material will be added as they clear security, privacy, and licensing review.

## Security

Please report suspected vulnerabilities privately. Never send seed phrases, private keys, API keys, session secrets, passwords, 2FA codes, wallet backup phrases, signed secret payloads, or production user data.

- **Security policy:** https://github.com/CopyPumpApp/.github/blob/main/SECURITY.md
- **Contribution guidelines:** https://github.com/CopyPumpApp/.github/blob/main/CONTRIBUTING.md

---

**Independent project. Not affiliated with pump.fun.**
