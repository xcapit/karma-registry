# karma-registry
# 🌍 Karma Registry

**Karma Registry** is a public reputation platform for humanitarian NGOs, developed during the [HackMeridian 2025](https://www.stellar.org/events/meridian) hackathon. It leverages Stellar smart contracts, Reflector Oracles, and decentralized identity protocols (DID + VC) to bring transparency, trust, and verifiability to the humanitarian aid sector.

🔗 website: [karma-registry.lovable.app](https://karma-registry.lovable.app)  
📦 Repository: [github.com/xcapit/karma-registry](https://github.com/xcapit/karma-registry)

---

## 💡 What is Karma Registry?

Karma Registry enables NGOs to receive a dynamic, verifiable **reputation score** based on a combination of on-chain and off-chain data:

- **SoulBound Tokens (SBTs)** represent the verified identity and trust level of each organization.
- A **Trust Index** is calculated based on on-chain aid transactions, beneficiary verification, audit submissions, and operational capacity.
- All credentials and claims are anchored on-chain using Stellar smart contracts and validated through Reflector Oracles.

---

## 🔐 Key Features

- ✅ **SoulBound Token issuance** after KYB verification
- 📊 Dynamic, transparent **Trust Index**
- 🔗 **Reflector Oracles** for audit validation, price feeds, and contextual data (climate, region)
- 🪙 Currency normalization across local fiat and crypto using on-chain oracles
- 🪪 **Decentralized Identity** using Veramo agents + Verifiable Credentials (W3C standard)

---

## 🧠 Tech Stack

- **Smart Contracts**: [Soroban](https://soroban.stellar.org/) (Stellar WASM)
- **Oracle Layer**: [Reflector](https://reflector.network/)
- **Identity Layer**: [Veramo](https://veramo.io/) — off-chain DID/VC agent
- **Blockchain**: Stellar 

---

## 🛠 Architecture Overview

1. NGOs complete KYB and link a Stellar wallet.
2. A **SoulBound Token** is issued on-chain to represent their identity.
3. Humanitarian program data is ingested and indexed.
4. **Reflector Oracles** validate off-chain reports and normalize aid value using price feeds.
5. A real-time **Trust Index** is calculated based on a weighted formula.
6. DIDs and Verifiable Credentials are managed off-chain with **Veramo**, while hashes are anchored on Stellar to ensure tamper-proof attestations.

---

## 🗺 Roadmap

| Phase | Feature Set |
|-------|-------------|
| 🧪 Phase 1 | KYB flow, SBT minting, dashboard UI, testnet deployment |
| 🔍 Phase 2 | Reflector Oracle integration: audits, price feeds, climate/territory context |
| 🔐 Phase 3 | Decentralized Identity (DID/VC) with Veramo + cross-org credential registry |

---

## 🤝 Built by

- 🧠 [Xcapit](https://xcapit.com) – Blockchain & AI software factory
- 🎨 [Lovable Studio](https://lovable.studio) – Product & UX design
- 🌐 Powered by [Stellar](https://stellar.org), [Reflector](https://reflector.network), and [Veramo](https://veramo.io)

---

## 📜 License

This project is licensed under the **GNU Affero General Public License v3.0 (AGPL-3.0)**.  
See [LICENSE](./LICENSE) for more details.

---

## 🙌 Acknowledgements

Special thanks to the Stellar community, the HackMeridian team, and all contributors and open-source projects that made this possible.

> A decentralized trust layer for humanitarian coordination.
