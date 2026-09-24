# Devender Gollapally

**Principal Software Engineer — I build production AI systems in regulated finance.**

I ship agentic, human-in-the-loop LLM systems that operate under real regulatory
constraints (SEC / FINRA), and I'm a co-author of **[ERC-1450](https://eips.ethereum.org/EIPS/eip-1450)** —
now a **Final** Ethereum standard for putting real securities on a public blockchain.
26 years building the systems other engineers build on top of — from payments and
securities infrastructure to the AI layer running on top of it today.

🌐 [devender.me](https://devender.me) · 💼 [LinkedIn](https://www.linkedin.com/in/devender) · 📍 Los Angeles · Remote

---

### 🤖 What I'm focused on now

- **Agentic AI in production** — multi-step LLM workflows with humans in the loop, built for domains where a wrong answer has compliance consequences, not just a bad demo.
- **Compliance-gated automation** — AI that drafts, a person who approves; every action auditable. Built inside a regulated broker-dealer, with compliance as a design partner rather than a review gate.
- **Evaluation & reliability** — the unglamorous half of applied AI: making agent output measurable, idempotent, and safe to put in front of regulated workflows. I publish the numbers, including the ones that don't flatter my own claims.
- **MCP tool design** — what actually makes a tool surface usable *by a model*, measured rather than asserted.

### 🔗 Selected public work

| Project | What it is |
|---|---|
| **[ERC-1450](https://eips.ethereum.org/EIPS/eip-1450)** — RTA-Controlled Security Token Standard | A **Final** Ethereum standard (July 2026): the on-chain token defers to a registered transfer agent, so a real security can live on a public chain without breaking securities law. Co-author — I revived it from *Stagnant* through Draft → Review → Last Call → Final. [Halborn-audited reference implementation](https://github.com/StartEngine/erc1450-reference) (Solidity, UUPS, multi-sig), in production behind hundreds of deployed securities. |
| **[mcpwright](https://mcpwright.com)** — MCP servers for public data | Four published, typed, CI-gated MCP servers: [SEC EDGAR](https://github.com/mcpwright/edgar-mcp), [US Census](https://github.com/mcpwright/census-mcp), [IRS SOI](https://github.com/mcpwright/soi-mcp), [FRED](https://github.com/mcpwright/fred-mcp) — plus [mcpwright-core](https://github.com/mcpwright/mcpwright-core), the shared runtime they're all built on. On PyPI, in the official MCP Registry, and packaged as one-click Claude Desktop extensions. |
| **[hubspot-multi-mcp](https://github.com/devender/hubspot-multi-mcp)** — many HubSpot portals, one conversation | An unofficial MCP server that connects Claude to several HubSpot portals at once, by name. HubSpot's official servers bind one connection to one portal. This one can also search across every portal in a single call. Read-only by construction, and tokens stay on your machine and are never printed. On [npm](https://www.npmjs.com/package/hubspot-multi-mcp): `npx hubspot-multi-mcp setup`. |
| **[mcp-tool-surface-eval](https://github.com/mcpwright/mcp-tool-surface-eval)** | An eval harness for MCP tool-surface design decisions. Two experiments so far — one of which refuted my own hypothesis. I published that too. |
| **[ethers-v6-kms-signer](https://github.com/StartEngine/ethers-v6-kms-signer)** | An ethers.js v6 signer backed by AWS KMS — sign EVM transactions without the private key ever leaving the HSM. |
| **[iofinnet-openapi-spec](https://github.com/StartEngine/iofinnet-openapi-spec)** | Community-maintained OpenAPI 3.0 spec for the IOFinNet MPC custody API. |

### ✍️ Writing

I write about tool design, measurement, and building AI you can actually trust at
**[devender.me](https://devender.me)**:

- [**How Do You Let AI Agents Into Regulated Data?**](https://devender.me/2026/09/24/how-do-you-let-ai-agents-into-regulated-data/) — don't hand the model database credentials; put it behind the governed BI layer you already have.
- [**One MCP Server, All Your HubSpot Portals**](https://devender.me/2026/08/28/one-mcp-server-all-your-hubspot-portals/) — why hubspot-multi-mcp is read-only by construction, and what searching across portals buys you.
- [**What Makes a Good MCP Tool Surface for an LLM**](https://devender.me/2026/06/04/good-mcp-tool-surface/) — six principles, each footnoted to a real shipped server.
- [**When a Tool Description Is the Difference Between Right and Wrong**](https://devender.me/2026/06/10/tool-descriptions-measured/) — the follow-up eval: one caveat sentence took a model from 0% to 100% on correctly reading a capped statistic.

### 🏗️ Background

Before AI, I spent six years building the core of a securities platform that has moved
**$1B+** in compliant offerings: payments, escrow, secondary-market trading, the
recommendation engine, the data warehouse, and the shared libraries every microservice
is built on. Then I built the tokenization stack — hybrid AWS KMS + IOFinnet MPC custody,
hundreds of securities live on Polygon — and the AI platform running on top of all of it.

### 🛠️ Tech

`Python` · `FastAPI` · `TypeScript / Node.js` · `Java / Spring` · `Solidity / Hardhat`
`PostgreSQL` · `Kafka` · `Redis` · `AWS (ECS, KMS, RDS, SES)` · `Terraform`
`Claude` · `OpenAI` · `MCP` · `LangChain`

### 🎒 Beyond the terminal

- ✍️ I write & self-publish children's books as **[D.G Sunny](https://www.amazon.com/author/dgsunny)** — the *Red Robot* series and *The Cat Monster of Blackpine Mountain* (my words and stories; illustrations with AI).
- 🎶 I play ukulele on **[YouTube (@gdevender)](https://www.youtube.com/@gdevender)**.

---

<sub>Always happy to talk about applied AI in regulated domains, agent evaluation, or on-chain securities. Reach me via [devender.me](https://devender.me).</sub>
