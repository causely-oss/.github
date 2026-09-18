# Give your AI agents a causal model of your systems.

**Causely Open Source** is where we share the tools behind our causal context layer for AI ops agents: MCP skills, benchmarks, and the synthetic environments we use to test agent accuracy against ground truth. Causely helps agents resolve issues faster, burn fewer tokens, and stop hallucinating.

---

## 🔌 Connect an Agent

The Causely MCP server is a hosted endpoint, always current, no repo required:

```
https://api.causely.app/mcp
```

Works with Claude Code, Claude Desktop, Cursor, or any MCP-compatible client. Full setup instructions and tool reference: [docs.causely.ai/agent-integration/](https://docs.causely.ai/agent-integration/)

## 🗂️ Featured Projects

A few of the things we're working on or sharing:

- [causely-client](https://github.com/causely-oss/causely-client): Pre-built investigation workflows (alert triage, postmortems, blast radius) for the Causely causal reasoning MCP server. Fork it to build the tool-selection logic for your own reliability agent.
- [background-agents](https://github.com/causely-oss/background-agents): Examples of giving background agents the context to reason about a live system, so they resolve issues faster, with fewer tokens and without hallucinating.
- [awesome-synthetic-apps](https://github.com/causely-oss/awesome-synthetic-apps): Demo applications and telemetry generators for testing agent accuracy against known failure scenarios.
- [chaosmania](https://github.com/causely-oss/chaosmania): Ground-truth fault injection for microservices, used to benchmark whether an agent's diagnosis actually matches the real root cause.
- [automatic-instrumentation-lab](https://github.com/causely-oss/automatic-instrumentation-lab): Techniques for automatic instrumentation, groundwork for any observability pipeline feeding an agent.



## 📊 Why Causal Context

Across 72 experiments spanning four agent frameworks, adding Causely's causal model to agent workflows produced:

- **100%** fault scenario accuracy, up from 75% without causal context
- **48%** fewer tokens per investigation on average
- **63%** faster mean query time

Full methodology: [Benchmark](https://www.causely.ai/product/benchmark) or reproduce it with [this repo](https://github.com/causely-oss/otel-demo/blob/main/BENCHMARK.md).

## 🤝 Contribute & Collaborate

We're building in the open because we believe in community-driven innovation.
Want to get involved?

- 📥 Clone & explore the code
- 🐞 Open issues or suggest enhancements
- 🔁 Submit PRs, we welcome contributions
- 💬 Start a discussion, we're listening

---



## 🌐 Learn More

- 🌐 [Website](https://www.causely.ai)
- 📝 [Blog](https://www.causely.ai/blog)
- 📖 [Docs](https://docs.causely.ai)
- 🧑‍💼 [Careers](https://www.causely.ai/careers)

---

> 🛠️ This organization is maintained by the team at [Causely](https://www.causely.ai).

