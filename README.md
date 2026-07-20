# Martin Tomecka

Platform engineer. 13 years enterprise — Java, Kafka, and everything that keeps insurance, tax, and payment systems running. More recently building AI tooling: MCP servers, NL→SQL, voice dictation, multi-agent orchestration.

## AI Integration

### MCP Knowledge Infrastructure

- [turtleatlas-mcp](https://github.com/tommaone/turtleatlas-mcp) — generic MCP server that turns a folder of Markdown files and table schemas into a structured knowledge base for any LLM. Two-tier model: experts for quick context, journeys for deep process understanding. No vectors, no embeddings — just tools that pull what the LLM needs when it needs it.
- [turtleatlas-w40k-11e](https://github.com/tommaone/turtleatlas-w40k-11e) — turtleatlas-mcp applied to Warhammer 40,000 11th Edition. Merges BSData unit profiles with official MFM points data, DPP computation engine, MCP tools for LLM access. Example of the pattern on a complex, version-fractured domain. Not affiliated with Games Workshop.
- Data Artisan MCP (Allianz Technology, internal) — MCP server for Claude Code covering a large enterprise codebase and database layer. Schema context and documentation retrieval for AI-assisted development.

### Local Speech Recognition

- [opencode-voice-call](https://github.com/tommaone/opencode-voice-call) — voice dictation for opencode and VS Code. Local transcription via whisper.cpp with the [Whisper small.en](https://huggingface.co/ggerganov/whisper.cpp) model from Hugging Face (~466MB, runs fully on-device). `/call` and `/hang` slash commands, silence detection, zero API cost. It works.

### NL→SQL

- [turtleql](https://github.com/tommaone/turtleql) — natural language to SQL web UI. Pluggable LLM providers (Anthropic, Bedrock, Azure OpenAI), pluggable database adapters, turtleatlas-mcp integration for schema context.

## Agent Orchestration

Started out of necessity and interest — no AI team in the tribe, but the company provided AI access that motivated me to figure out how to structure coding agents properly. Now a personal setup I use across projects and platforms.

- [turtle-squad-core](https://github.com/tommaone/turtle-squad-core) — shared agent definitions and dojo rules, platform-agnostic source of truth
- [claude-skills](https://github.com/tommaone/claude-skills) — squad for Claude Code: Splinter orchestrator, specialist agents, adversarial review gate, evolution layer that learns from each session
- [copilot-turtle-skills](https://github.com/tommaone/copilot-turtle-skills) — same squad for GitHub Copilot CLI
- [opencode-turtle-skills](https://github.com/tommaone/opencode-turtle-skills) — same squad for opencode (local Qwen on Ollama, zero API cost)
- [kiro-turtle-skills](https://github.com/tommaone/kiro-turtle-skills) — same squad for Kiro IDE

## Backend & Infrastructure

- Java (plain Java + OSGi-based framework, now moving to Spring Boot and Quarkus)
- Kafka/Redpanda, Apache Camel, REST/event-driven architecture
- Kubernetes, Helm, ArgoCD, Terraform, HashiCorp Vault, Docker
- Insurance claim lifecycle, tax calculation (15+ countries), provider search, payment processing, DB2/SQL

## Side Projects

- [turtledeck](https://github.com/tommaone/turtledeck) — swipeable reference card viewer for wargame datasheets. Not affiliated with Games Workshop.

## Open to

AI engineering roles, or AI-first Java engineering — ideally both. Looking for companies where the engineering problem is real and the solution doesn't need six months of management buy-in before you can start.

## Connect

[LinkedIn](https://www.linkedin.com/in/martin-tome%C4%8Dka-33b58173/)
