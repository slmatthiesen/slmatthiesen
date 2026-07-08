<!-- Canonical source for the slmatthiesen/slmatthiesen GitHub profile README. Edit here, paste to that repo. Public surface — follow privacy.md (no primary email). -->
<div align="center">

<h2>AI Engineer building agentic systems</h2>

<br/>

<a href="https://www.linkedin.com/in/smatthiesen"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<img src="https://img.shields.io/badge/San_Francisco-1e2327?style=for-the-badge&logo=googlemaps&logoColor=white" alt="San Francisco"/>
<img src="https://komarev.com/ghpvc/?username=slmatthiesen&style=for-the-badge&color=7C3AED&label=PROFILE+VIEWS" alt="Profile views"/>

</div>

---

### 👋 &nbsp;/me

```ts
const steven = {
  role:    "AI Engineer · CTO @ INTU",
  focus:   ["LLM agents", "agentic issue-fix pipelines", "RAG",
            "multimodal doc + image ingestion", "evals", "observability", "fully agentic systems"],
  stack:   ["React", "Node", "Python", "Rust", "Postgres", "GraphQL"],
  web3:    ["MPC", "DKG", "EVM", "Solana", "Solidity"],
  shipping: "production agent systems",
};
```

I build agent systems that survive contact with production — tool-using LLMs wired through **MCP**, grounded by **RAG**, gated by **eval harnesses**, and instrumented end-to-end so failures are observable instead of mysterious. Before AI I spent four years deep in **Web3**, leading an MPC wallet-infrastructure team across cryptography, smart contracts, and Rust.

---

### 🔁 &nbsp;/method

```text
   ideas ──▶ evals ──▶ guardrails ──▶ build ──▶ review ──▶ production
     ▲                                                           │
     └─────────── observe · measure · iterate · harden ◀────────┘
```

Design intent before code: I write the evals and guardrails *before* a line ships, then let observability close the loop — every production failure feeds the next iteration instead of disappearing.

---

### 🧠 &nbsp;/stack

**AI / ML**

![MCP](https://img.shields.io/badge/MCP_Servers-000000?style=flat-square&logo=anthropic&logoColor=white)
![RAG](https://img.shields.io/badge/RAG_·_Hybrid_Retrieval-7C3AED?style=flat-square)
![Evals](https://img.shields.io/badge/Evals_·_RAGAS_·_LLM--as--judge-DB2777?style=flat-square)
![LangSmith](https://img.shields.io/badge/LangSmith_·_Langfuse-FF6F00?style=flat-square)
![pgvector](https://img.shields.io/badge/pgvector-336791?style=flat-square&logo=postgresql&logoColor=white)
![Google ADK](https://img.shields.io/badge/Google_ADK-4285F4?style=flat-square&logo=google&logoColor=white)

**Languages & Core**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)

**Platforms**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-DD2C00?style=flat-square&logo=firebase&logoColor=white)
![Vertex AI](https://img.shields.io/badge/Vertex_AI-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white)
![Cloud Run](https://img.shields.io/badge/Cloud_Run-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Gemini API](https://img.shields.io/badge/Gemini_API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![DigitalOcean](https://img.shields.io/badge/DigitalOcean-0080FF?style=flat-square&logo=digitalocean&logoColor=white)


**Web3**

![Solidity](https://img.shields.io/badge/Solidity-363636?style=flat-square&logo=solidity&logoColor=white)
![Ethers](https://img.shields.io/badge/Ethers.js-2535A0?style=flat-square&logo=ethereum&logoColor=white)
![MPC](https://img.shields.io/badge/MPC_·_DKG-00C2A8?style=flat-square)
![The Graph](https://img.shields.io/badge/The_Graph-6747ED?style=flat-square&logo=thegraph&logoColor=white)

---

### 🚀 &nbsp;/review

#### ☁️ [Drafture](https://drafture.dev) — Plain-English → safe, costed AWS architecture &nbsp;·&nbsp; **Live** &nbsp;·&nbsp; [`source`](https://github.com/slmatthiesen/drafture)

You describe a system in plain English; Drafture returns a recommended AWS design as a labeled data-flow diagram, ordered setup steps, and cost estimates in each service's **native unit** — across **budget / balanced / resilient** tiers, with a security floor baked into all three (the budget tier is the *minimum safe cost*, never a security-relaxed one). The LLM returns a **validated typed graph** (provider-abstracted, Claude by default); the backend renders Mermaid diagrams and cost tables **deterministically** from it, so diagrams are reliable and costs are computable. A curated knowledge base grounds generation, with an optional research-and-cache step for unseen topics.

`Structured Output` · `RAG` · `Claude` · `AWS` · `Fastify` · `React`

<a href="https://youtu.be/Z1jUKFBpayk" target="_blank" rel="noopener noreferrer"><img src="https://img.youtube.com/vi/Z1jUKFBpayk/maxresdefault.jpg" alt="Watch the Drafture demo" width="100%" /></a>

▶️ <a href="https://youtu.be/Z1jUKFBpayk" target="_blank" rel="noopener noreferrer"><strong>Watch the demo</strong></a>

---

<table>
<tr>
<td width="50%" valign="top">

#### 🤖 Agentic Github Issues Fixer
**Autonomous coding agent**

An agent that triages open GitHub issues, reproduces the bug, drafts a fix, and opens a PR — closing the loop from issue to reviewable change. **Proof:** [medplum/medplum#9293](https://github.com/medplum/medplum/pull/9293) — an upstream OSS fix landed **fully agentically** ([working branch](https://github.com/slmatthiesen/medplum/tree/archon/task-fix-medplum-issue-1779744141849)).

`Agents` · `Tool Use` · `GitHub API` · `OSS`

<a href="https://youtu.be/KUgnANt6aTs" target="_blank" rel="noopener noreferrer"><img src="https://img.youtube.com/vi/KUgnANt6aTs/maxresdefault.jpg" alt="Watch the agentic issue-fix demo" width="100%" /></a>

▶️ <a href="https://youtu.be/KUgnANt6aTs" target="_blank" rel="noopener noreferrer"><strong>Watch the demo</strong></a>

</td>
<td width="50%" valign="top">

#### 🩺 OpenEMR Clinical Agent
**Selected Project · 2026**

LLM agent layered onto an open-source EHR that reads patient charts and relays clinical context on demand. Lab-report ingestion pipeline produces summaries with **source-page citations**, so clinicians can verify any agent-surfaced claim — a RAG pattern tuned for high-stakes clinical use.

`RAG` · `LLM Agents` · `Citations` · `Healthcare`

<a href="https://youtu.be/majmoNyEHqY" target="_blank" rel="noopener noreferrer"><img src="https://img.youtube.com/vi/majmoNyEHqY/maxresdefault.jpg" alt="Watch the OpenEMR Clinical Agent demo" width="100%" /></a>

▶️ <a href="https://youtu.be/majmoNyEHqY" target="_blank" rel="noopener noreferrer"><strong>Watch the demo</strong></a>

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🍻 [Happy Hour Friends](https://happyhourfriends.com) — Crowdsourced happy hour finder
**Live · 2026** &nbsp;·&nbsp; [`source`](https://github.com/slmatthiesen/happyhourfriends)

Fully **agent-operated** site: every update — **parsed automatically** from the web or **submitted by users** — passes strict **agentic moderation gates** (classify → verify, versioned prompts, audited apply path) before going live. The test: can my agent safeguards run the site without my intervention? The product itself is dead-simple — venues and deals in one sortable, filterable view, kept current by **crowdsourcing**.

`Agents` · `Crowdsourcing` · `Moderation Gates` · `Next.js`

<a href="https://youtu.be/Y9ncwzkj4Qc" target="_blank" rel="noopener noreferrer"><img src="https://img.youtube.com/vi/Y9ncwzkj4Qc/maxresdefault.jpg" alt="Watch the Happy Hour Friends demo" width="100%" /></a>

▶️ <a href="https://youtu.be/Y9ncwzkj4Qc" target="_blank" rel="noopener noreferrer"><strong>Watch the demo</strong></a>

</td>
<td width="50%" valign="top">

#### 📈 Algorithmic Futures Trading
**Quant Research · WIP**

Backtest harness and execution research for systematic futures strategies — applying the same eval + observability discipline I use on AI agents to strategy selection, slippage modeling, and live risk.

`Python` · `Quant` · `Backtesting` · `WIP`

<a href="https://youtu.be/RvMFT4ZE9_w" target="_blank" rel="noopener noreferrer"><img src="https://img.youtube.com/vi/RvMFT4ZE9_w/maxresdefault.jpg" alt="Watch the algorithmic futures trading demo" width="100%" /></a>

▶️ <a href="https://youtu.be/RvMFT4ZE9_w" target="_blank" rel="noopener noreferrer"><strong>Watch the demo</strong></a>

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🔐 [INTU](https://intu.xyz) — Web3 onboarding via MPC
**CTO · Lead Engineer**

Open-source NPM package orchestrating **distributed key generation (DKG)** and multi-party computation, removing seed phrases from the onboarding flow. Cross-chain transaction flows across EVM networks, bridged to Solana — sending a Solana tx authorized by an EVM signature. Self-hosted **The Graph** indexers for chains without hosted support.

`Rust` · `Solidity` · `MPC` · `EVM` · `TypeScript`

</td>
<td width="50%" valign="top">

#### 🍽️ [GURUPass / Pass Rewards](https://apps.apple.com/us/app/pass-rewards/id6757899189) — Restaurant AI Agents
**Lead AI & Blockchain Engineer**

Tool-using LLM agents handling order intake and menu Q&A, wired through **MCP** with structured-output validation. Curated eval set + offline regression harness catches failures before deploy; production traces drive failure-mode analysis. Personalization layer surfaces targeted coupons from purchase history.

`MCP` · `Agents` · `Evals` · `Personalization`

</td>
</tr>
</table>

<!-- More entries coming. Template:
#### [Project Name](repo-url)
One-line description.  `Tag` · `Tag` · `Tag`
-->

---

<div align="center">

### ⚡ &nbsp;Efficiency &gt; token-maxing

<p>
I burn a lot of tokens — <em>on purpose</em>. But spending them to look busy is waste.<br/>
The craft is <strong>signal per token</strong>: tight context, sharp evals, and failure modes that are observable instead of mysterious.<br/>
Every system above was designed, built, and shipped on a <strong>~$100/month plan</strong>.
</p>

<a href="https://www.linkedin.com/in/smatthiesen"><img src="https://img.shields.io/badge/Let's_connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
&nbsp;
<!--a href="https://www.youtube.com/channel/UCdTbjwhCXshKvpvJv697LXQ"><img src="https://img.shields.io/badge/Watch_the_builds-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube"/></a-->

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=7C3AED&height=120&section=footer" width="100%" alt="" />
