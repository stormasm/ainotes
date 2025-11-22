Several open-source AI agent frameworks and individual agents written in Rust are available on GitHub. These projects leverage Rust's performance and safety for building robust and scalable AI systems.
Here are some notable open-source AI agents and frameworks written in Rust:

### Multi-Agent Frameworks

- [AutoAgents](https://github.com/liquidos-ai/AutoAgents) A cutting-edge multi-agent framework that uses Large Language Models (LLMs) and Ractor, designed for performance, safety, and scalability. It provides a modular architecture and supports native WASM compilation, allowing agents to be deployed directly to a web browser.
- [kwaak](https://github.com/bosun-ai/kwaak) A framework for running multiple AI agents in parallel, focused on automating code tasks and managing technical debt. Agents operate on code, use tools, and support various LLM providers (OpenAI, Ollama, etc.) with sandboxed execution.
- [livekit/agents](https://github.com/livekit/agents) A powerful framework for building real-time voice AI agents, featuring extensive WebRTC support, integrated job scheduling, and telephony integration.

### Agent Libraries and Tools

- [goose]() (codename goose) An extensible, open-source AI agent designed to automate engineering tasks from scratch. It operates locally on your machine, can build entire projects, execute code, debug failures, and integrate with any LLM.
- [AgentAI](https://github.com/AdamStrojek/rust-agentai) A Rust library that simplifies the creation of AI agents by leveraging the GenAI library to interface with a wide range of popular LLMs.
- [ai-agents](https://github.com/geminik23/ai-agents) An early-stage Rust library designed for building and managing generative AI agents, aiming to provide a robust and scalable foundation for various scenarios.
- [shai](https://github.com/ovh/shai) A simple coding agent and terminal-based pair programming assistant written in Rust.

### Related Utilities

- [indexify](https://github.com/jondot/awesome-rust-llm) A retrieval and long-term memory service for LLMs, essential for agents that need persistent knowledge and context.
- [agentgateway](https://github.com/agentgateway/agentgateway) A high-performance agentic proxy for AI agents and MCP servers, designed for security and scalability in multi-tenant deployments.
For a broader view of the ecosystem, you can explore the GitHub topics for ai-agents and [rust-ai-agent](https://github.com/topics/rust-ai-agent) filtered by the Rust language.

---

While there is no single universally recognized "most popular" standalone open-source AI agent built exclusively in Rust, several prominent projects provide frameworks and libraries for building agents in Rust, focusing on performance, safety, and scalability.

Key open-source Rust AI agent frameworks include:

- [GraphBit](https://github.com/InfinitiBit/graphbit): This project is noted as the world's first Rust core & Python-wrapped Agentic AI framework, combining Rust's efficiency with Python's ease of use. It is designed for high concurrency and low resource usage, making it suitable for large-scale development.
- [AutoAgents](https://github.com/HKUDS/AutoAgent): Described as a cutting-edge multi-agent framework, AutoAgents is built entirely in Rust and leverages the Ractor model for performance, safety, and scalability in multi-agent systems. It supports cloud-native, edge-native, and hybrid models.
- [Symbiont](https://github.com/ThirdKeyAI/Symbiont): A security-first, AI-native agent framework built entirely in Rust, focused on zero-trust principles to ensure autonomous agents can execute complex workflows securely.
- [AgentAI](https://github.com/AdamStrojek/rust-agentai): A Rust library that simplifies the creation of AI agents by providing an interface to a wide range of Large Language Models (LLMs) via the GenAI library, benefiting from Rust's strong typing and error handling.
- [Goose](https://github.com/block/goose): An open-source, extensible, on-machine AI agent capable of automating complex development tasks, including building projects, debugging, and orchestrating workflows. It is available as a desktop app and CLI and works with any LLM.

Many popular AI agents are available as general-purpose coding assistants (e.g., GitHub Copilot, Aider) that support Rust within larger, language-agnostic ecosystems. For those building AI agents or working on machine learning projects in Rust, the [awesome-rust-llm](https://github.com/jondot/awesome-rust-llm) GitHub repository provides a curated list of relevant tools and libraries
