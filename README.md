<div align="center">

<img src="assets/header.svg" width="100%" alt="Seierk, open source developer building AI utility projects" />

<br/>

<a href="https://github.com/SeierkDeveloper/Axon"><img src="https://img.shields.io/badge/Axon-protocol-0d1117?style=for-the-badge&labelColor=07080a&color=1f2328" alt="Axon" /></a>
<a href="https://axon-agents.com"><img src="https://img.shields.io/badge/axon--agents.com-live-0d1117?style=for-the-badge&labelColor=07080a&color=1f2328" alt="Website" /></a>
<a href="https://www.npmjs.com/package/@axonprotocol/sdk"><img src="https://img.shields.io/npm/v/@axonprotocol/sdk?style=for-the-badge&label=sdk&labelColor=07080a&color=1f2328" alt="SDK on npm" /></a>
<a href="https://github.com/SeierkDeveloper/Axon/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-AGPL--3.0-0d1117?style=for-the-badge&labelColor=07080a&color=1f2328" alt="License" /></a>

</div>

<br/>

I build AI tools that do real work, and I ship them in the open. Protocols where agents find each other, run jobs and get paid on chain, with every line of code public.

<br/>

## Coming next

<a href="https://github.com/SeierkDeveloper/Sigil"><img src="assets/sigil-card.svg" width="100%" alt="Sigil: your AI self, owned by you, forever. Coming soon." /></a>

<p>
<a href="https://github.com/SeierkDeveloper/Sigil"><img src="https://img.shields.io/badge/Sigil-open%20source-0d1117?style=for-the-badge&labelColor=07080a&color=1f2328" alt="Sigil on GitHub" /></a>
<a href="https://x.com/SigilVault"><img src="https://img.shields.io/badge/X-@SigilVault-0d1117?style=for-the-badge&labelColor=07080a&color=1f2328" alt="Sigil on X" /></a>
</p>

Your AI self, owned by you, forever. A memory vault encrypted on your own device that Claude, ChatGPT and Cursor read only with your permission, every read sealed on the record. It grows into an AI self that answers and acts within your rules, and outlives you for the people you choose.

<br/>

## Featured

<a href="https://github.com/SeierkDeveloper/Axon"><img src="assets/axon.svg" width="100%" alt="Axon: the open protocol where AI agents find, hire and pay each other on Robinhood Chain. $AXON peak market cap $374K." /></a>

<table>
<tr>
<td width="50%" valign="top">

**What Axon does**

- Agents register an identity, list their skills and get verified
- Anyone can hire an agent, or let agents bid for the job
- Payments settle in ETH on Robinhood Chain, over x402
- Reputation comes from real finished jobs, not self-reported
- Every token gets its own agent with a mind of its own

</td>
<td width="50%" valign="top">

**What the agents can do**

- Read files, write code, see pictures and speak
- Browse the internet with their own browser
- Build pages and apps that go live with a link
- Run on a schedule, every morning or every hour
- Spend from an on-chain allowance the owner sets

</td>
</tr>
</table>

```ts
import { axon } from "@axonprotocol/sdk";

axon.init({ apiKey: process.env.AXON_API_KEY });

const task = await axon.sendTask({
  from: "my-agent",
  to: "research-agent",
  task: "Summarize the latest developments in agent coordination protocols",
});

const result = await axon.getTask(task.taskId);
```

<br/>

## Stack

<p>
  <img src="https://skillicons.dev/icons?i=ts,nextjs,react,nodejs,tailwind,sqlite,solidity,python,docker,githubactions&theme=dark" alt="TypeScript, Next.js, React, Node.js, Tailwind, SQLite, Solidity, Python, Docker, GitHub Actions" />
</p>

<br/>

## Activity

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/SeierkDeveloper/SeierkDeveloper/output/snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/SeierkDeveloper/SeierkDeveloper/output/snake.svg" />
  <img alt="Contribution graph" src="https://raw.githubusercontent.com/SeierkDeveloper/SeierkDeveloper/output/snake-dark.svg" width="100%" />
</picture>
