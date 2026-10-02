### Hi, I'm Subash.

[Field CTO at Siel AI](https://www.linkedin.com/in/subashn/) and a cloud and AI architect. On GitHub I build open-source tools for the work around enterprise AI: [FDEOps](https://github.com/suboss87/FDEOps) for AI coding agents, [Awesome Enterprise AI](https://github.com/suboss87/awesome-enterprise-ai) for business workflows and [CodeQuorum](https://github.com/suboss87/CodeQuorum) for pull request review.

I like figuring out what is worth building in the first place. Design thinking keeps me close to the people facing a problem, systems thinking shows how a fix fits the bigger picture, and first principles help when the usual approach doesn't make sense. [FDEOps](https://github.com/suboss87/FDEOps#why-use-it) is that method written down as skills. I look for a small, useful place to start on big problems. In my own time, I use GitHub to build things developers and enterprises can try, question and improve.

### Selected projects

#### [FDEOps](https://github.com/suboss87/FDEOps)
947 stars · 106 forks · 6,500 [npm downloads](https://www.npmjs.com/package/fdeops) in September · [CI](https://github.com/suboss87/FDEOps/actions/workflows/validate.yml) · [Evals](https://github.com/suboss87/FDEOps/tree/Main/evals) · [51 releases](https://github.com/suboss87/FDEOps/releases)

Skills for AI coding agents, from scoping a problem through verification and handover. FDEOps keeps a local record of decisions so the next session can pick up the work. It [installs into](https://github.com/suboss87/FDEOps/blob/Main/docs/install.md) Claude Code, Cursor, Codex and Copilot.

<a href="https://github.com/suboss87/FDEOps"><img src="assets/fdeops-fieldbook.png" width="100%" alt="The FDEOps fieldbook: a read-only view of three client engagements that shows the recommended first action for each client and the risks that need attention."></a>
The fieldbook, a read-only view of local customer records. Run <code>npx fdeops demo</code> to generate it from sample notes.

#### [Awesome Enterprise AI](https://github.com/suboss87/awesome-enterprise-ai)
Python · [153 tests, a 58-case live evaluation and 20/20 on independently written cases](https://github.com/suboss87/awesome-enterprise-ai/blob/main/docs/VERIFICATION.md) · [Try the workspace](https://github.com/suboss87/awesome-enterprise-ai#try-it-in-two-minutes) · MIT

Small workflows for the work around enterprise AI: investigating incidents, checking claim evidence, answering business questions and coordinating operations. Each includes examples, tests and a [governance file](https://github.com/suboss87/awesome-enterprise-ai/blob/main/projects/customer-resolution/GOVERNANCE.md) that names the business owner, data risks and the thresholds to agree before adoption. Nine are reviewed references; the proposal-evidence project remains experimental. [RAG Scope Check](https://github.com/suboss87/rag-scope-check), a local CI gate for permission-scoped retrieval, is also available on its own; it started from a [practitioner's report](https://www.reddit.com/r/Rag/comments/1w3q78p/our_rag_permissions_filter_is_safe_and_still/) that access filtering was quietly starving retrieval.

#### [SeedCamp](https://github.com/suboss87/SeedCamp2.0)
Python · FastAPI · Docker · [CI on every push](https://github.com/suboss87/SeedCamp2.0/actions/workflows/ci.yml) · [Scaling limits](https://github.com/suboss87/SeedCamp2.0/blob/main/docs/SCALING.md) · MIT

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
