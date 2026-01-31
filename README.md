# AI Agents using Model Context Protocol (MCP)

This repository is an **umbrella project** showcasing multiple 
agent workflows built using the **Model Context Protocol (MCP)**.

- Tool-based interactions
- Function calling patterns
- Multi-step workflows
- Backend service integration

---

## Tech Stack

- FastAPI
- LangChain
- Model Context Protocol (MCP)
- Gemini, Claude, OpenRouter (Qwen)
- PostgreSQL, SQLAlchemy
- Apache Kafka (Confluent-compatible)

---

## Implemented Agents

### 1. Shopping Agent
**Capabilities**
- Parses user intent (category, budget, constraints)
- Performs structured product discovery
- Ranks and surfaces relevant results

**Repo**
- [https://github.com/kinjal/<shopping-agent-repo>](https://github.com/kinjal-1007/shopping-assistant-mcp)

---

### 2. YouTube Tracker Agent
**Capabilities**
- Tracks uploads from selected creators
- Filters videos from the last N days
- Extracts topics without manual browsing

**Repo**
- [https://github.com/kinjal/<youtube-tracker-repo>](https://github.com/kinjal-1007/youtube-tracker-mcp)

---

### 3. Kafka Management Agent
**Capabilities**
- Natural-language Kafka administration
- Topic creation and configuration
- Producer / consumer group management

**Repo**
- [https://github.com/kinjal/<kafka-agent-repo>](https://github.com/kinjal-1007/confluent-mcp-server)

---

### 4. LangChain MCP Client
**Capabilities**
- MCP-based tool registration
- External API integration (Geoapify, Google Calendar)
- End-to-end task execution workflows

**Repo**
- [https://github.com/kinjal/<mcp-client-repo>](https://github.com/kinjal-1007/multi-server-MCP)

---

## What This Demonstrates

- Agent systems beyond prompt-only LLM usage
- Reliable tool execution via MCP
- Backend-first agent design
- Real-world applicability of LLMs in distributed systems

---

## Notes

This repository intentionally contains **no code**.
It exists as a **single entry point** for navigating the system.
