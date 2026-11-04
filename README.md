# Jordimp & Co.

Jordimp & Co. is the working name of one engineer in Barcelona. I build backend services and event pipelines, and more recently applied AI. Every AI feature I ship comes with the evals to check it. Java and Python are my production languages, TypeScript and Node.js turn up in modernization work, and my repos are public: CI, specs, receipts.

## Selected work

**[ggufbench](https://github.com/jordimarsal/ggufbench)**: agentic benchmark for local GGUF models. Scores speed, tool-calling, code and multi-step agent tasks under one harness, with three runs per task and the raw receipts of every call. Live scoreboard at [jordimarsal.github.io/ggufbench](https://jordimarsal.github.io/ggufbench/).

**[codebaserag](https://github.com/jordimarsal/codebaserag)**: hexagonal RAG over a codebase. Retrieval quality is a CI gate: 40+ golden Q&A pairs and a committed recall@5 baseline that fails the build on regression.

**[harness](https://github.com/jordimarsal/harness)**: multi-agent harness with spec-author, implementer and reviewer roles, and human gates between them. Installs into any project with one command, and its process ships as six standalone skills: `npx skills add jordimarsal/harness`.

**[buildwright](https://github.com/jordimarsal/buildwright)**: agent-loop runtime with per-step model routing — LangGraph orders the steps, PydanticAI runs them, LiteLLM serves the model and Langfuse traces it. The role-to-model map is configuration, so switching models touches zero lines of pipeline. On PyPI: `uvx buildwright`.

**[debrief-mcp](https://github.com/jordimarsal/debrief-mcp)**: MCP server that answers agent questions from receipts — what ggufbench measured (bench), where a buildwright run broke (run), and a role-change proposal as text. Hexagonal and read-only: every answer is findings or a structured error. On PyPI: `uvx debrief-mcp`.

**[kafka-adapter-telemetry](https://github.com/jordimarsal/kafka-adapter-telemetry)**: Kafka gateway and hub with idempotent Oracle persistence, dead-letter queues, health alerts and a live SSE dashboard. Java 25, Spring Boot 4.

Site: [jordimp.net](https://jordimp.net) · LinkedIn: [jordi-marsal-poy](https://www.linkedin.com/in/jordi-marsal-poy) · [hello@jordimp.net](mailto:hello@jordimp.net)
