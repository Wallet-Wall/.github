<div align="center">

<h1>WalletWall</h1>

<p>
  <strong>A read-only vault-readiness platform powered by wallet intelligence — holder behavior, stablecoin concentration, and whale activity — with post-quantum migration as supporting research.</strong>
</p>

<p>
  <a href="#status"><img alt="Status" src="https://img.shields.io/badge/status-active_development-B84923?style=flat-square"></a>
  <a href="#research-direction"><img alt="Research" src="https://img.shields.io/badge/research-post--quantum_wallets-D6A85A?style=flat-square"></a>
  <a href="#security-posture"><img alt="Security" src="https://img.shields.io/badge/security-non--custodial-2B2118?style=flat-square"></a>
  <a href="https://docs.walletwall.org"><img alt="Docs" src="https://img.shields.io/badge/docs-walletwall.org-A7B0B5?style=flat-square"></a>
</p>

</div>

---

## Product journey

<picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="../assets/diagrams/adaptive/profile-readme-product-journey-01-dark.svg"
  />
  <img
    src="../assets/diagrams/adaptive/profile-readme-product-journey-01-light.svg"
    alt="Product journey: flowchart diagram"
    width="100%"
  />
</picture>

_Appearance-aware WalletWall diagram. Open the full-size [light](../assets/diagrams/adaptive/profile-readme-product-journey-01-light.svg) or
[dark](../assets/diagrams/adaptive/profile-readme-product-journey-01-dark.svg) variant. [Mermaid source](../diagrams/adaptive/profile-readme-product-journey-01.mmd)._

---

## System map

<picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="../assets/diagrams/adaptive/profile-readme-system-map-02-dark.svg"
  />
  <img
    src="../assets/diagrams/adaptive/profile-readme-system-map-02-light.svg"
    alt="System map: flowchart diagram"
    width="100%"
  />
</picture>

_Appearance-aware WalletWall diagram. Open the full-size [light](../assets/diagrams/adaptive/profile-readme-system-map-02-light.svg) or
[dark](../assets/diagrams/adaptive/profile-readme-system-map-02-dark.svg) variant. [Mermaid source](../diagrams/adaptive/profile-readme-system-map-02.mmd)._

---

## Operating principles

> [!IMPORTANT]
> WalletWall is non-custodial by design. Wallet analysis should never require seed phrases, private keys, or unsafe signatures.

> [!NOTE]
> Public research and product surfaces are separated. Vault and verifier work should be treated as research unless explicitly marked otherwise.

> [!TIP]
> Coinstellation is the discovery layer. Wallet-level context should resolve into Whale Watcher, Stable Seer, Holder Wall, or Quantum Intelligence depending on the source context.

---

## Product surfaces

| Surface                  | Focus                                                                                       |
| ------------------------ | ------------------------------------------------------------------------------------------- |
| **Whale Watcher**        | Wallet-level holder intelligence, whale activity, and large-wallet behavior.                |
| **Stable Seer**          | Stablecoin peg, liquidity, and pool-market context.                                          |
| **Holder Wall**          | Holder analytics — ownership concentration, retention, and distribution.                    |
| **Coinstellation**       | Token, pool, and wallet discovery through graph-based exploration.                          |
| **Quantum Intelligence** | Wallet-level exposure, migration readiness, and post-quantum research framing.              |
| **Stablecoin Vault**     | Read-only vault-readiness journey and Sepolia testnet migration-path rehearsal.              |

---

## Public repositories

| Repository                                                                                | Purpose                                                                                                        | State                        |
| ----------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- | ---------------------------- |
| [**walletwall-vault**](https://github.com/Wallet-Wall/walletwall-vault)                   | Post-quantum wallet migration research, verifier feasibility, attestation flows, and vault-readiness patterns. | `research`                   |
| [**walletwall-whale-watcher**](https://github.com/Wallet-Wall/walletwall-whale-watcher)   | Public Whale Watcher workspace and wallet-intelligence surface.                                                | `product surface`            |
| [**walletwall-stable-seer**](https://github.com/Wallet-Wall/walletwall-stable-seer)       | Stable Seer stablecoin-concentration surface running on bundled fixtures.                                      | `demo surface (fixture-only)` |
| [**walletwall-holder-wall**](https://github.com/Wallet-Wall/walletwall-holder-wall)       | Holder Wall behavior-and-concentration surface running on bundled fixtures.                                    | `demo surface (fixture-only)` |
| [**walletwall-coinstellation**](https://github.com/Wallet-Wall/walletwall-coinstellation) | Coinstellation token, pool, and wallet discovery surface running on bundled fixtures.                          | `demo surface (fixture-only)` |
| [**walletwall-evidence-simulator**](https://github.com/Wallet-Wall/walletwall-evidence-simulator) | Reproducible, fixture-only container that rehearses the evidence-normalization pipeline with no live data.     | `verification artifact`      |
| [**.github**](https://github.com/Wallet-Wall/.github)                                     | Public organization profile and shared community defaults.                                                     | `metadata`                   |

---

## Research direction

WalletWall is researching practical wallet migration paths for a post-quantum environment.

The work focuses on:

* wallet-level exposure modeling
* clear user-facing risk language
* non-custodial migration readiness
* verifier and attestation boundaries
* research-to-product separation

> [!NOTE]
> WalletWall research focuses on wallet-level exposure, readiness signals, and migration-path design. It does not claim that any specific wallet is compromised.

The research is not financial advice, custody infrastructure, or a claim that any specific wallet is compromised. It is a framework for understanding public wallet exposure and preparing safer migration paths.

---

## Security posture

| Boundary              | Position                                                                                               |
| --------------------- | -------------------------------------------------------------------------------------------------------- |
| **Custody**           | WalletWall does not custody funds.                                                                     |
| **Secrets**           | WalletWall does not request seed phrases or private keys.                                              |
| **Signing**           | WalletWall does not require unsafe transaction signing for wallet analysis.                            |
| **Research boundary** | Experimental vault and verifier work should be treated as research unless explicitly marked otherwise. |

> [!IMPORTANT]
> WalletWall does not request seed phrases, private keys, or unsafe wallet signatures for analysis.

---

## Links

| Destination    | URL                                                     |
| -------------- | ------------------------------------------------------- |
| App            | https://walletwall.org                                  |
| Docs           | https://docs.walletwall.org                             |
| Vault research | https://github.com/Wallet-Wall/walletwall-vault         |
| Whale Watcher  | https://github.com/Wallet-Wall/walletwall-whale-watcher |

---

## Status

WalletWall is in active development.

Public repositories may represent research, prototypes, or standalone product surfaces while the main application continues to evolve.

> [!TIP]
> Public repositories may represent research, prototypes, or standalone product surfaces while the main application continues to evolve.

<sub>WalletWall is a non-custodial intelligence and research project. Public materials should not be interpreted as financial, legal, or security guarantees.</sub>
