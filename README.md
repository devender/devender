# Devender Gollapally

**Principal Software Engineer — I build production AI systems in regulated finance.**

I ship agentic, human-in-the-loop LLM systems that operate under real regulatory
constraints (SEC / FINRA), and I co-authored a security-token standard submitted to
Ethereum. 15+ years building the systems other engineers build on top of — from
payments and securities infrastructure to the AI layer running on top of it today.

🌐 [devender.me](http://devender.me) · 💼 [LinkedIn](https://www.linkedin.com/in/devendergollapally/) · 📍 Los Angeles · Remote

---

### 🤖 What I'm focused on now

- **Agentic AI in production** — multi-step LLM workflows with humans in the loop, built for domains where a wrong answer has compliance consequences, not just a bad demo.
- **Compliance-gated automation** — AI that drafts, a person who approves; every action auditable. Vendor due diligence, complaint handling (FINRA 4530), call supervision (FINRA 3110), and personalized investor outreach (voice-cloned + accreditation-gated).
- **Evaluation & reliability** — the unglamorous half of applied AI: making agent output measurable, idempotent, and safe to put in front of regulated workflows.
- **Prompt-caching & cost economics** at production scale.

### 🔗 Selected public work

| Project | What it is |
|---|---|
| **[ERC-1450](https://github.com/StartEngine/erc1450-reference)** — RTA-Controlled Security Token Standard | SEC-compliant security-token standard + Halborn-audited reference contracts (UUPS, multi-sig). Submitted to Ethereum as [ERCs PR #1335](https://github.com/ethereum/ERCs/pull/1335). |
| **[ethers-v6-kms-signer](https://github.com/StartEngine/ethers-v6-kms-signer)** | An ethers.js v6 signer backed by AWS KMS — sign EVM transactions without the private key ever leaving the HSM. |
| **[iofinnet-openapi-spec](https://github.com/StartEngine/iofinnet-openapi-spec)** | Community-maintained OpenAPI 3.0 spec for the IOFinNet MPC custody API. |

### 🏗️ Background

Before AI, I spent six years building the core of a securities platform that has moved
**$1B+** in compliant offerings: payments, escrow, secondary-market trading, the
recommendation engine, the data warehouse, and the shared libraries every microservice
is built on. Then I built the tokenization stack (hybrid AWS KMS + IOFinnet MPC custody,
500K+ on-chain mints on Polygon) and the AI platform running on top of all of it.

### 🛠️ Tech

`Python` · `FastAPI` · `TypeScript / Node.js` · `Java / Spring` · `Solidity / Hardhat`
`PostgreSQL` · `Kafka` · `Redis` · `AWS (ECS, KMS, RDS, SES)` · `Terraform`
`Claude` · `OpenAI` · `MCP` · `LangChain`

---

<sub>Always happy to talk about applied AI in regulated domains, agent evaluation, or on-chain securities. Reach me via [devender.me](http://devender.me).</sub>
