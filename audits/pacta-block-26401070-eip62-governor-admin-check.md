# Euler V2 `eIP-62` Frontier Vault `governorAdmin` Verification (Block `26401070`)

- **Pinned Block**: Ethereum Mainnet `26401070` (`0xcf55f6a42ae610c1f8766b5c2fb676d91f178469fa10ef777eccbb76f6506234`)
- **Primary Governance Commitment**: `eIP-62: Optimistic Risk Management via Timelocked Risk Stewards and Limited Rapid Response` (`https://forum.euler.finance/t/eip-62-optimistic-risk-management-via-timelocked-risk-stewards-and-limited-rapid-response/1225`, `SHA-256: 12b7a7210253647b345d73d346d8dbb0e09ed5660133b0efe3e52621a1a81287`)

## 1. Aggregate Block-`26401070` Verification Summary (`EU1` — Specific Vault Addresses Redacted)

| Commitment Check | Verified On-Chain State at Block `26401070` | Status |
| :--- | :--- | :--- |
| **`eIP-62` Commitment** | *"Replace the Euler DAO multisig with `GovernorAccessControlEmergency` instance on all the vaults and oracle routers managed by Euler DAO."* | Baseline |
| **Euler Operational Safe (`0xcAD001c30E96765aC90307669d578219D4fb1DCe`)** | `4-of-8` Gnosis Safe (`guard = 0x0`, `modules = []`) | Verified |
| **Batch `GovSetGovernorAdmin` Event Check (Block `26236508`)** | A batch contract-creation transaction at block `26236508` emitted **49 `GovSetGovernorAdmin` events** (`0x1c145a4c`) assigning `governorAdmin()` on **40 Frontier vaults** directly to the `4-of-8` Safe (`0xcAD001c30E96765aC90307669d578219D4fb1DCe`) and **9 vaults** to a `2`-threshold Safe (`0x7945...bb8e`). | **49 Vault Addresses Quarantined for Private Disclosure** |

## 2. No-Cost (`$0`) Private Responsible Disclosure

In accordance with responsible disclosure standards, the specific addresses of the 49 affected Frontier vaults and the batch deployment trace have been redacted from this public file and are available **at no cost (`$0`)** to Euler security/engineering maintainers via **`pacta@dri.network`**.
