### Hi, I'm Subash.

I build [FDEOps](https://github.com/suboss87/FDEOps), [SeedCamp](https://github.com/suboss87/SeedCamp2.0) and [CodeQuorum](https://github.com/suboss87/CodeQuorum). My work here spans coding-agent workflows, AI pipelines and developer tooling. I also contribute fixes to OpenClaw and write about cloud architecture and applied AI.

I'm a Field CTO with a background in cloud and enterprise architecture. The repositories below are where you can try the tools, read the code and see the tradeoffs.

### Selected projects

#### [FDEOps](https://github.com/suboss87/FDEOps)
[Releases](https://github.com/suboss87/FDEOps/releases) · [Install](https://github.com/suboss87/FDEOps/blob/Main/docs/install.md) · [npm](https://www.npmjs.com/package/fdeops)

FDEOps packages the working method of a forward deployed engineer as skills for AI coding agents. Its task skills cover discovery, scoping, building, verification and handover, and a local record keeps each customer's decisions between sessions. It [installs into](https://github.com/suboss87/FDEOps/blob/Main/docs/install.md) Claude Code, Cursor, Codex and Copilot.

<a href="https://github.com/suboss87/FDEOps"><img src="assets/fdeops-fieldbook.png" width="100%" alt="The FDEOps fieldbook: a read-only view of three client engagements that shows the recommended first action for each client and the risks that need attention."></a>
The fieldbook, a read-only view of local customer records. Run <code>npx fdeops demo</code> to generate it from sample notes.

#### [SeedCamp](https://github.com/suboss87/SeedCamp2.0)
Python · FastAPI · Docker · [CI on every push](https://github.com/suboss87/SeedCamp2.0/actions/workflows/ci.yml) · MIT

SeedCamp is a reference architecture for generating AI video in batches. It routes each job to a premium or cheaper model, retries failures, checks prompts before spending money and records the cost of every video. The README states its limit, a few hundred videos per run, and documents how to go past it.

#### [CodeQuorum](https://github.com/suboss87/CodeQuorum)
Python · LangGraph · GitHub Action · [Tests](https://github.com/suboss87/CodeQuorum/actions/workflows/tests.yml) · MIT

CodeQuorum runs three reviewer agents with different priorities on each pull request. A problem is marked "fix it" only when at least two of them find it independently, with the reviewers' reasoning included for a human to assess ([example review](https://github.com/suboss87/CodeQuorum#example-pr-comment)).

### Contributions

[Merged fixes in OpenClaw](https://github.com/openclaw/openclaw/pulls?q=is%3Apr+author%3Asuboss87+is%3Amerged): Slack reconnects, Telegram approvals, Ollama model IDs, OpenAI reasoning blocks and hook context.

### Writing

- [Multi-Cloud Handbook for Developers](https://www.packtpub.com/en-us/product/multi-cloud-handbook-for-developers-9781804617090) (Packt), a book on designing and running cloud-native applications across AWS, Azure and GCP, co-written with Jeveen Jacob.
- [Agentic AI Architecture Framework for Enterprises](https://www.infoq.com/articles/agentic-ai-architecture-framework/) on InfoQ, co-written with Ahilan Ponnusamy.
- [Articles on The New Stack](https://thenewstack.io/author/subash-natarajan/) about multicloud strategy and FinOps.
- [FDE field notes](https://fdeops.substack.com/), a newsletter on forward deployed engineering.

### Contact

[subash.io](https://subash.io) · [LinkedIn](https://www.linkedin.com/in/subashn/) · [suboss87@gmail.com](mailto:suboss87@gmail.com)
