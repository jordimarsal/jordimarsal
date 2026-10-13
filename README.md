# Jordimp & Co.

Jordimp & Co. is the working name of one engineer in Barcelona. I build backend services and event pipelines, and more recently applied AI. Every AI feature I ship comes with the evals to check it. Java and Python are my production languages, TypeScript and Node.js turn up in modernization work, and my repos are public: CI, specs, receipts.

## Selected work

**[ggufbench](https://github.com/jordimarsal/ggufbench)**: agentic benchmark for local GGUF models. Scores speed, tool-calling, code and multi-step agent tasks under one harness, with three runs per task and the raw receipts of every call. Live scoreboard at [jordimarsal.github.io/ggufbench](https://jordimarsal.github.io/ggufbench/).

**[codebaserag](https://github.com/jordimarsal/codebaserag)**: hexagonal RAG over a codebase. Retrieval quality is a CI gate: 40+ golden Q&A pairs and a committed recall@5 baseline that fails the build on regression.

**[harness-standard](https://github.com/jordimarsal/harness-standard)**: multi-agent harness with spec-author, implementer and reviewer roles, and human gates between them. Installs into any project with one command.

**[kafka-adapter-telemetry](https://github.com/jordimarsal/kafka-adapter-telemetry)**: Kafka gateway and hub with idempotent Oracle persistence, dead-letter queues, health alerts and a live SSE dashboard. Java 25, Spring Boot 4.

**[mcp-transparent-png](https://github.com/jordimarsal/mcp-transparent-png)**: MCP server in Python for PNG transparency, with three modes (rgb, auto, greenscreen).

**[redis-toolkit](https://github.com/jordimarsal/redis-toolkit)**: rate limiting for LLM gateways. Atomic per-client token buckets that degrade gracefully when Redis fails. Java.

Site: [jordimp.net](https://jordimp.net) · LinkedIn: [jordi-marsal-poy](https://www.linkedin.com/in/jordi-marsal-poy) · [hello@jordimp.net](mailto:hello@jordimp.net)
