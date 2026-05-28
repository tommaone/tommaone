# Martin Tomecka

AI systems engineer. 12 years enterprise platform engineering — insurance, tax, payments, provider search.

Building reliable AI infrastructure through **multi-agent orchestration** and **evolution layers**. Validate approaches on myself first, then scale to production. Focus: structured knowledge grounding (no RAG), local cost-efficient inference, and teams of specialist agents that improve through learning.

  ## What I build

  - **AI systems** — multi-agent orchestration, adversarial review gates, self-correcting agent pipelines, MCP server development (Node.js, HTTP/SSE)
  - **Backend services** — Java (OSGi, Spring Boot 3.x, Quarkus), Kafka/Redpanda, Apache Camel, REST/event-driven architecture
  - **Infrastructure** — Kubernetes, Helm, ArgoCD, Terraform, ACM Cloud, HashiCorp Vault, Docker
  - **Domain depth** — insurance claim lifecycle, tax calculation (15+ countries), provider search, EDA payment processing, DB2/SQL

  ## Things I own publicly

  ### Multi-Agent Orchestration (Siege Specialist Pattern)
  
  - [claude-skills](https://github.com/tommaone/claude-skills) — squad methodology: Splinter orchestrator, specialist agents (Leonardo/Donatello/Raphael/Michelangelo), adversarial Shredder review gate, evolution layer that learns from each session
  - [opencode-turtle-skills](https://github.com/tommaone/opencode-turtle-skills) — same squad ported to opencode for cost efficiency (local Qwen 7B on Ollama instead of API bills), with permanent turtle-dojo skill loaded on every session
  
  ### Knowledge Infrastructure (No RAG)
  
  - [turtleatlas-mcp](https://github.com/tommaone/turtleatlas-mcp) — MCP server that serves structured Markdown knowledge to any LLM. Two-tier model: experts for quick context, journeys for deep understanding. No vectors, no embeddings, just tools that pull what you need.
  - [turtleql](https://github.com/tommaone/turtleql) — natural language to SQL web UI that uses turtleatlas-mcp as its knowledge backend. Pluggable LLM providers (Anthropic, Bedrock, Azure OpenAI), pluggable database adapters.
  
  ### Workflow Optimization
  
  - [opencode-voice-call](https://github.com/tommaone/opencode-voice-call) — voice dictation for opencode and VS Code with local whisper.cpp transcription. Zero API cost, works in TUI and editor. Built to free hands for parallel activities (Warhammer hobby, other work).

  ## Open to

  AI engineering roles. Preference for companies where the engineering problem is real and the solution doesn't need to be explained to management for six months before you can start.

  ## Connect

  [LinkedIn](https://www.linkedin.com/in/martin-tome%C4%8Dka-33b58173/)
