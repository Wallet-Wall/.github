<div align="center">

<h1>WalletWall</h1>

<p><strong>Read-only wallet intelligence. Evidence-led migration readiness.</strong></p>

<p>Understand public-wallet exposure, investigate what a migration would require, and explore the boundaries of post-quantum authorization—without handing over custody.</p>

<p><img alt="Read-only intelligence · Non-custodial" src="https://img.shields.io/badge/READ--ONLY-NON--CUSTODIAL-B84923?style=flat-square"></p>

<p><a href="https://walletwall.org/">Explore the application</a> · <a href="https://docs.walletwall.org/introduction">Read the documentation</a> · <a href="https://docs.walletwall.org/concepts/product-status">Check product status</a></p>

</div>

---

WalletWall turns read-only, public Ethereum observations into context about cryptographic signature exposure, stablecoin and asset concentration, dormancy, and wallet behavior. The workflow is **scan → assess → recommend → report → monitor**. The goal is to make evidence and migration questions legible—not to move funds or guarantee a wallet's safety.

## The platform today

- **Vault · Available, read-only research interface.** [Stablecoin Vault](https://vault.walletwall.org/) offers a hosted migration-readiness journey. It does not accept deposits, custody assets, or execute migrations.
- **Intelligence · Available, read-only analysis.** [Quantum Intelligence](https://docs.walletwall.org/features/quantum-intelligence), [Wallet Profile](https://docs.walletwall.org/features/wallet-profile), and wallet reports put exposure signals and uncertainty in context. Quantum scores are planning heuristics, not predictions of Q-Day or present-day compromise.
- **Evidence · Available, read-only inspection.** The [Evidence index](https://walletwall.org/evidence) and [WallPrint](https://docs.walletwall.org/mcp/wallprint) disclosure model help explain a claim's sources, limits, and provenance. Publication or a digest does not establish factual truth.
- **MCP · Installable, local, pre-release.** [WalletWall MCP](https://docs.walletwall.org/mcp/overview) assesses structured evidence you supply. It does not fetch chain data, sign, trade, custody assets, or run on a WalletWall-hosted MCP endpoint.

The **Vault Simulator** is a separate, **unaudited local/Sepolia testnet prototype** using mock assets; signing-enabled workflows are restricted to developer/testnet builds. The vNext kernel, SP1 proving, and on-chain ML-DSA verification remain **research, not production capabilities**. The [product-status page](https://docs.walletwall.org/concepts/product-status) is the authority on availability and maturity.

## Research at the frontier

- **Blockchain evidence:** distinguish source claims from independently supported observations; preserve provenance, freshness, conflicts, and missing data.
- **Post-quantum migration readiness:** explore signature exposure, realistic migration paths, and the limits of forward-looking risk models.
- **Vault and verifier architecture:** investigate hybrid authorization, policy-gated execution, ML-DSA verifier boundaries, and trusted-attestation assumptions.
- **Reproducibility and proof research:** publish bounded artifacts and explicit limitations without treating prototypes, test results, or proof concepts as security certifications.

## Exploring an uncertain frontier

> WalletWall doesn't need to prove that the frontier is safe before exploring it. It needs to explore the frontier without pretending the unknown has disappeared.

WalletWall explores emerging technologies through bounded experiments, clear evidence boundaries, and practical learning. It does not confuse assurance with certainty or prototypes with production guarantees. Unknowns remain visible, and security-critical boundaries remain non-negotiable.

## Developer ecosystem

[**WalletWall MCP and GitHub Copilot**](https://github.com/Wallet-Wall/walletwall-copilot) ship a local, read-only evidence engine with six tools and eleven resources. The Copilot integration adds guidance skills and an evidence canvas. It can be installed from the repository as a user-added plugin marketplace; **it is not an official Copilot catalog listing**.

[**WalletWall for Claude Code**](https://github.com/Wallet-Wall/walletwall-claude) distributes the same engine as a source-pinned local plugin, not a second implementation. Both plugins are **pre-release, not independently security reviewed**. The official MCP Registry entry provides discovery metadata, not endorsement. [Install and connect locally.](https://docs.walletwall.org/mcp/install)

The engine evaluates supplied evidence against published policies; **policy-supported does not mean independently verified or true**. WalletWall does not retain MCP query history, but your AI client and model provider may process submitted inputs.

## Public repositories

- [**walletwall-copilot**](https://github.com/Wallet-Wall/walletwall-copilot) — MCP engine, Copilot plugin, evidence contracts, and tests.
- [**walletwall-claude**](https://github.com/Wallet-Wall/walletwall-claude) — generated Claude Code plugin distribution.
- [**walletwall-vault**](https://github.com/Wallet-Wall/walletwall-vault) — source-available, **unaudited** hybrid-authorization and verifier research; local/testnet only.
- [**walletwall-evidence-simulator**](https://github.com/Wallet-Wall/walletwall-evidence-simulator) — deterministic fixture-only normalization artifact, not live intelligence.
- [**walletwall-audio-visual-docs**](https://github.com/Wallet-Wall/walletwall-audio-visual-docs) — documentation-derived audiovisual tooling with validation and provenance.
- **Fixture-only concept demos:** [Whale Watcher](https://github.com/Wallet-Wall/walletwall-whale-watcher), [Stable Seer](https://github.com/Wallet-Wall/walletwall-stable-seer), [Holder Wall](https://github.com/Wallet-Wall/walletwall-holder-wall), and [Coinstellation](https://github.com/Wallet-Wall/walletwall-coinstellation). Their **standalone hosted surfaces are retired**, even though some underlying intelligence remains in the main product.

These public repositories do **not** expose the private hosted application or imply that experimental code is deployed. Licenses differ: the vault research repository is source-available but not OSI-licensed. [Understand the public/private boundary.](https://docs.walletwall.org/concepts/public-and-private)

## Security and trust

The hosted intelligence and readiness surfaces need **no wallet connection, seed phrase, private key, or signature**. Their provider readings, snapshots, and analytical inferences remain distinct from independent verification. Testnet signing experiments are not hosted wallet-analysis behavior.

WalletWall has **no production or mainnet custody path** and makes **no audit, quantum-safe, Q-Day prediction, or wallet-protection guarantee**. Read the [organization security policy](https://github.com/Wallet-Wall/.github/blob/main/SECURITY.md) and [vault boundaries](https://docs.walletwall.org/vault/boundaries) before assessing research claims.

**Start here:** [Use WalletWall](https://walletwall.org/) · [Review status and limitations](https://docs.walletwall.org/concepts/product-status) · [Try the MCP quickstart](https://docs.walletwall.org/mcp/quickstart) · [Inspect vault research](https://github.com/Wallet-Wall/walletwall-vault)
