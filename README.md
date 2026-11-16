# Gate Control Center (GCC)

**Self-hosted Gate.io trading, native trading bot monitoring, portfolio analytics, and wallet management.**

[**Explore the GCC Live Demo**](https://zolpho.github.io/gate-bot-dashboard/) · [Developer: zolnode](https://github.com/Zolpho)

Gate Control Center (GCC) brings Gate.io operations into a unified web interface. Originally built to monitor exchange-native trading bots, it has evolved to include supported trading operations, multi-account wallet management, analytics, security, and administrative controls.

> **Project status:** Active development · **Source:** Private / proprietary · **Exchange:** Gate.io

## Screenshots

These captures illustrate the Aurora interface. Some screens use isolated simulated demo data, while native bot metrics may reflect live exchange read-only data. Screenshots are illustrative, not investment results or evidence of live demo trading.

### Overview

[![GCC Overview](screenshots/01-overview.webp)](screenshots/01-overview.webp)

Portfolio performance and native bot status at a glance.

### Native bot performance

[![GCC Bot Performance](screenshots/02-bot-performance.webp)](screenshots/02-bot-performance.webp)

Cumulative performance charts and trading metrics for supported native bots.

### Trading

[![GCC Trading](screenshots/03-trading.webp)](screenshots/03-trading.webp)

Market data, candlestick chart, order book, and simulated Limit and Market order entry in Demo.

### Wallet

[![GCC Wallet](screenshots/04-wallet.webp)](screenshots/04-wallet.webp)

Account-scoped wallet balances and asset reporting using simulated Demo balances.

<details>
<summary>More screenshots — Bot Control and Security</summary>

### Bot Control

[![GCC Bot Control](screenshots/05-bot-control.webp)](screenshots/05-bot-control.webp)

Simulated Spot Grid strategy configuration and review.

### Security

[![GCC Security](screenshots/06-security.webp)](screenshots/06-security.webp)

Isolated Demo-session security presentation.

</details>

[**Open GCC Live Demo →**](https://zolpho.github.io/gate-bot-dashboard/)

## Features

- **Native trading bots:** Monitor and manage supported Gate.io Spot Grid and Infinity Grid bots; review configuration, status and performance.
- **Spot Trading:** Limit and Market Buy/Sell order entry, order previews and confirmations, market data, order history, and supported order management through the Gate.io API. Live execution is subject to account authorization and operational safeguards; Demo trading is simulated.
- **Wallet:** View assets, balances, and supported deposit, withdrawal and transfer workflows.
- **Security:** Authentication, per-account action controls, Administrator policies, and auditing.
- **Interfaces:** Aurora, Classic, and isolated Demo experiences.

## Development Activity

GCC is actively developed in a private source repository. This public activity feed exposes only **commit dates and reviewed commit titles**—not source code, hashes, authors, diffs, private links, credentials, or operational details.

<!-- gcc-development-activity:start -->

**Private `main` history:** **519** published commits from **August 1, 2026** through **November 15, 2026**.

**By month:** **August:** 237 · **September:** 106 · **October:** 124 · **November:** 52

### Recent activity

- **2026-11-15** — Harden Gate VM operator workflow
- **2026-11-15** — Add Gate capability refresh lifecycle
- **2026-11-15** — Show Gate API access modes in My Permissions
- **2026-11-15** — Use cached Gate capabilities in My Permissions
- **2026-11-15** — Add read-only Gate capability refresh
- **2026-11-15** — Add Gate API capability snapshot foundation
- **2026-11-15** — Clarify Exchange API configured state
- **2026-11-15** — Update security architecture documentation
- **2026-11-14** — Move grid market labels to right gutter
- **2026-11-14** — Restore inline grid guides with Demo references
- **2026-11-14** — Add expandable grid diagram views
- **2026-11-14** — Align grid explainer warning styles

[**View the complete development history →**](DEVELOPMENT.md)

<!-- gcc-development-activity:end -->

### GitHub contribution graph

For broader development activity, [view Zolpho's GitHub profile and contribution graph](https://github.com/Zolpho). When GitHub's **Private contributions** option is enabled, private-repository activity appears there anonymously. The profile graph covers overall GitHub activity, not GCC exclusively.

## Issues, Feedback & Roadmap

The public [GCC Issues tracker](https://github.com/Zolpho/gate-control-center/issues) is the place for:

- reproducible product bugs
- user-facing feature requests
- feedback about GCC behavior or usability
- selected public roadmap and exploration items

GCC development and source remain private. Internal implementation work, deployment/infrastructure details, security investigations, and other operationally sensitive work are intentionally kept out of the public tracker.

**Never post API keys, API secrets, account credentials, recovery material, private account details, or sensitive screenshots in a public issue.**

### Selected roadmap

- [Native Open Orders for Spot Grid and Infinity Grid](https://github.com/Zolpho/gate-control-center/issues/1)
- [Telegram notifications and read-only bot integration](https://github.com/Zolpho/gate-control-center/issues/2)
- [Passkey / WebAuthn login](https://github.com/Zolpho/gate-control-center/issues/3)
- [Show the actual Gate VIP level for each Wallet account](https://github.com/Zolpho/gate-control-center/issues/5)
- [Multi-exchange support (KuCoin and Binance)](https://github.com/Zolpho/gate-control-center/issues/6) — **Exploring / nice to have**

Completed public product milestones may also be retained in Issues for context, such as [Demo mode](https://github.com/Zolpho/gate-control-center/issues/4) and [Limit / Market Trading](https://github.com/Zolpho/gate-control-center/issues/9).

## Availability

**The application source code is private and not published here.** This public repository showcases the product and is not an installable open-source release.

## Disclaimer

Gate Control Center is an independent third-party project, not affiliated with or endorsed by Gate.io. Cryptocurrency trading carries financial risk. Functionality depends on available APIs, exchange permissions, and configured safeguards.

---

Developed and maintained by **zolnode**.
