# Agentic Frameworks — A Visual Deep Dive

An interactive, single-page visual guide to the major agentic AI frameworks — their architectures, tradeoffs, and how to choose between them for production systems.

**[View the Live Guide](https://brendanjameslynskey.github.io/Agentic_Frameworks_guide/)**

## What's Covered

The guide walks through 12 sections covering the full agentic framework landscape:

- **Overview** — What agentic frameworks are and what they provide vs what you still build yourself
- **The Landscape** — A categorised map of the ecosystem (orchestrators, graph engines, multi-agent, enterprise, minimal, low-code) with an evolution timeline from LangChain (2022) through to MCP & A2A protocols (2025–2026)
- **Common Architecture Patterns** — The three schools of thought: graph-first (LangGraph), role-first (CrewAI), and conversation-first (AutoGen/AG2)
- **LangGraph** — Deep dive into graph-based state machines with typed state, conditional edges, durable execution, and human-in-the-loop
- **CrewAI** — Role-based agent teams, autonomous crews vs event-driven flows, task replay, and enterprise features
- **AutoGen / AG2** — Conversational multi-agent patterns, group chat, sandboxed code execution, and the Microsoft Research → AG2 community transition
- **OpenAI Agents SDK** — Minimalist agent primitives, handoff patterns, built-in tracing and guardrails
- **Emerging Frameworks** — Pydantic AI, Google ADK, Smolagents, Strands Agents, OpenAgents, MetaGPT
- **MCP & A2A Protocols** — The interoperability layer connecting agents to tools (MCP) and to each other (A2A)
- **Head-to-Head Comparison** — Interactive tabbed explorer with deep-dive panels for each framework, plus a Canvas radar chart comparing ease of use, production readiness, multi-agent support, state control, ecosystem size, and protocol support
- **Choosing a Framework** — Interactive decision tree that guides you to the right framework based on your requirements
- **Live Demo** — Animated execution traces showing how LangGraph, CrewAI, AG2, and OpenAI SDK each handle the same research task differently

## Features

- Single-file HTML — zero dependencies, zero build step
- Dark theme with animated Canvas hero (network graph)
- Sticky sidebar navigation with scroll-aware active state
- Interactive framework explorer with tabbed comparison panels
- Canvas radar chart for multi-dimensional framework comparison
- Clickable decision tree for framework selection
- Animated trace viewer demonstrating each framework's execution pattern
- Fully responsive layout for mobile and desktop
- Designed for GitHub Pages deployment

## Deployment

Push to a GitHub repository with GitHub Pages enabled on the `main` branch. The `index.html` file serves directly — no build process required.

## Built With

Pure HTML, CSS, and vanilla JavaScript. No frameworks, no bundlers, no external dependencies.

## Related Guides

- [How LLM Agents Work](https://brendanjameslynskey.github.io/LLM_Agents_guide/) — Visual deep dive into the internals of LLM-powered agents
- [LLM Transformer Decoder Internals](https://brendanjameslynskey.github.io/LLM_transformer_decoder/) — Interactive guide to transformer architecture
