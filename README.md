# Raymond Pitt

**AI Implementation Engineer** — I ship production software by directing AI coding agents.

🔭 **Live proof:** [Peptide①](https://www.thepeptide1.com) — web SaaS + [iOS App Store app](https://www.thepeptide1.com) with Stripe + Apple IAP subscriptions, shipped solo in under a year.

🤖 **Talk to my work:** [Portfolio Agent](https://gts-portfolio-agent-497116845799.us-central1.run.app) — a Google ADK agent deployed on Cloud Run that answers questions about my projects using tools that return verified facts ([code →](https://github.com/pitowski812/gts-portfolio-agent)).

**Applied AI I've shipped in production** — not demos, real product features:
- 🔎 **RAG chatbot** — a retrieval-augmented assistant with cited sources and fail-closed safety gates (refuses rather than guesses), backed by a 50-case answer-quality eval harness.
- 🧠 **Semantic search** — hybrid retrieval combining BM25 keyword search with vector-embedding similarity over a chunked knowledge base.
- 🛠️ **AI tool use** — tool-calling agents where the LLM invokes functions/tools to act (including the live Google ADK agent above), with adversarial review of their output.

**What I actually do:** architecture, specs, adversarial review, testing discipline, and deployment — with AI agents (Claude Code, Codex) as the build team. Real App Store review battles fought and won (3.1.1 / 1.4.1 / 2.5.1). ~30-agent governed orchestration stack with mechanical guardrails ([public patterns →](https://github.com/pitowski812/claude-workflow-patterns)).

**By the numbers** *(from private production repos)*: ~2,000 automated tests · 7 CI gates (pytest · ruff · pyright · pip-audit · security) · ~30-agent orchestration stack · 25+ scheduled automations · dual Stripe + Apple billing with unified entitlements.

**Daily stack:** Python/Flask · StoreKit 2 IAP · Stripe · RAG + semantic search (BM25 + vector embeddings, eval harness) · **LiteLLM + MCP servers in production** · Google ADK + Cloud Run · tool-calling multi-agent workflows on local + cloud models.

📫 ray.m.pitt@gmail.com · 🌐 [pitowski812.github.io](https://pitowski812.github.io) — case studies with architecture detail (no source; the recipe stays private)

*Most production repos here are private (they run a live business). Case studies are on the portfolio site; public pattern repos below.*
