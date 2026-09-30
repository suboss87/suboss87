### Hi, I'm Subash.

I love code and everything around it, especially figuring out what is worth building in the first place. Design thinking helps me start with the people facing a problem. Systems thinking helps me see how a fix fits into the bigger picture, and I like going back to first principles when the usual approach doesn't make sense.

I'm drawn to big, pressing problems, but I look for a small, useful place to start. In my free time, I use GitHub to explore what developers and enterprises are struggling with and build solutions they can try, question and improve.

### Selected projects

#### [FDEOps](https://github.com/suboss87/FDEOps)
[Releases](https://github.com/suboss87/FDEOps/releases) · [Install](https://github.com/suboss87/FDEOps/blob/Main/docs/install.md) · [npm](https://www.npmjs.com/package/fdeops)

Skills for AI coding agents, from scoping a problem through verification and handover. FDEOps keeps a local record of decisions so the next session can pick up the work. It [installs into](https://github.com/suboss87/FDEOps/blob/Main/docs/install.md) Claude Code, Cursor, Codex and Copilot.

<a href="https://github.com/suboss87/FDEOps"><img src="assets/fdeops-fieldbook.png" width="100%" alt="The FDEOps fieldbook: a read-only view of three client engagements that shows the recommended first action for each client and the risks that need attention."></a>
The fieldbook, a read-only view of local customer records. Run <code>npx fdeops demo</code> to generate it from sample notes.

#### [Awesome Enterprise AI](https://github.com/suboss87/awesome-enterprise-ai)
Python · [Try the workspace](https://github.com/suboss87/awesome-enterprise-ai#try-it-in-two-minutes) · [Tests and evaluation](https://github.com/suboss87/awesome-enterprise-ai/blob/main/docs/VERIFICATION.md) · MIT

Small workflows for the work around enterprise AI: investigating incidents, checking claim evidence, answering business questions and coordinating operations. Each includes examples, tests and clear adoption limits. Nine are reviewed references; the proposal-evidence project remains experimental.

#### [SeedCamp](https://github.com/suboss87/SeedCamp2.0)
Python · FastAPI · Docker · [CI on every push](https://github.com/suboss87/SeedCamp2.0/actions/workflows/ci.yml) · MIT

A reference architecture for generating AI video in batches. The interesting part for me is the workflow around generation: routing jobs between models, retrying failures and tracking cost. The README documents the operating limits and what would need to change for larger runs.

#### [CodeQuorum](https://github.com/suboss87/CodeQuorum)
Python · LangGraph · GitHub Action · [Tests](https://github.com/suboss87/CodeQuorum/actions/workflows/tests.yml) · MIT

Three agents review a pull request with different priorities. Findings backed by at least two reviewers are marked "fix it"; a human can inspect the reasoning in the [review comment](https://github.com/suboss87/CodeQuorum#example-pr-comment). Agreement is a signal to investigate, not a guarantee that the finding is correct.

### Contributions

[Merged fixes in OpenClaw](https://github.com/openclaw/openclaw/pulls?q=is%3Apr+author%3Asuboss87+is%3Amerged): Slack reconnects, Telegram approvals, Ollama model IDs, OpenAI reasoning blocks and hook context.

### Writing

- [Multi-Cloud Handbook for Developers](https://www.packtpub.com/en-us/product/multi-cloud-handbook-for-developers-9781804617090) (Packt), a book on designing and running cloud-native applications across AWS, Azure and GCP, co-written with Jeveen Jacob.
- [Agentic AI Architecture Framework for Enterprises](https://www.infoq.com/articles/agentic-ai-architecture-framework/) on InfoQ, co-written with Ahilan Ponnusamy.
- [Articles on The New Stack](https://thenewstack.io/author/subash-natarajan/) about multicloud strategy and FinOps.
- [FDE field notes](https://fdeops.substack.com/), a newsletter on forward deployed engineering.

### Get in touch

If you try one of these tools, I'd like to hear where it helps and where it falls short. Reproducible problems and small contributions are welcome.

[subash.io](https://subash.io) · [LinkedIn](https://www.linkedin.com/in/subashn/) · [suboss87@gmail.com](mailto:suboss87@gmail.com)
