# Martin Tomecka

AI systems engineer. 12 years enterprise platform engineering — insurance, tax, payments, provider search.

Building AI tooling that actually gets used: MCP servers, NL→SQL, voice dictation, multi-agent orchestration. Validate on myself first, scale to production.

## AI Integration

### MCP Knowledge Infrastructure

- [turtleatlas-mcp](https://github.com/tommaone/turtleatlas-mcp) — generic MCP server that turns a folder of Markdown files and table schemas into a structured knowledge base for any LLM. Two-tier model: experts for quick context, journeys for deep process understanding. No vectors, no embeddings — just tools that pull what the LLM needs when it needs it.
- [turtleatlas-w40k-11e](https://github.com/tommaone/turtleatlas-w40k-11e) — turtleatlas-mcp applied to Warhammer 40,000 11th Edition. Merges BSData unit profiles with official MFM points data, DPP computation engine, MCP tools for LLM access (WIP). A real-world test of the pattern on a complex, version-fractured domain. Not affiliated with Games Workshop.

### Local Speech Recognition

- [opencode-voice-call](https://github.com/tommaone/opencode-voice-call) — voice dictation for opencode and VS Code. Local transcription via whisper.cpp with the [Whisper small.en](https://huggingface.co/ggerganov/whisper.cpp) model from Hugging Face (~466MB, runs fully on-device). `/call` and `/hang` slash commands, silence detection, zero API cost. It works.

### NL→SQL

- [turtleql](https://github.com/tommaone/turtleql) — natural language to SQL web UI. Pluggable LLM providers (Anthropic, Bedrock, Azure OpenAI), pluggable database adapters, turtleatlas-mcp integration for schema context.

## Agent Orchestration

A pattern for structuring AI coding agents as a team of specialists — ported across platforms so the squad works wherever you are.

- [turtle-squad-core](https://github.com/tommaone/turtle-squad-core) — shared agent definitions and dojo rules, platform-agnostic source of truth
- [claude-skills](https://github.com/tommaone/claude-skills) — squad for Claude Code: Splinter orchestrator, specialists, adversarial Shredder review gate, evolution layer that learns from each session
- [copilot-turtle-skills](https://github.com/tommaone/copilot-turtle-skills) — same squad for GitHub Copilot CLI
- [opencode-turtle-skills](https://github.com/tommaone/opencode-turtle-skills) — same squad for opencode (local Qwen on Ollama, zero API cost)
- [kiro-turtle-skills](https://github.com/tommaone/kiro-turtle-skills) — same squad for Kiro IDE

## Backend & Infrastructure

- Java (OSGi, Spring Boot 3.x, Quarkus), Kafka/Redpanda, Apache Camel, REST/event-driven architecture
- Kubernetes, Helm, ArgoCD, Terraform, HashiCorp Vault, Docker
- Insurance claim lifecycle, tax calculation (15+ countries), provider search, payment processing, DB2/SQL

## Side Projects

- [turtledeck](https://github.com/tommaone/turtledeck) — swipeable reference card viewer for wargame datasheets. Not affiliated with Games Workshop.

## Open to

AI engineering roles. Preference for companies where the engineering problem is real and the solution doesn't need six months of management buy-in before you can start.

## Connect

[LinkedIn](https://www.linkedin.com/in/martin-tome%C4%8Dka-33b58173/)
