# Azeez — AI Engineer

Building the infrastructure layer for AI agents: control surfaces, context
pipelines, and audit trails. The model is commodity — the infrastructure
around it is the product.

## What I'm building

| Project | What it is | Install |
|---|---|---|
| [agent-gatekeep](https://github.com/mlazeez/gatekeep) | Control surface for agents — vault-backed rollback, typed hooks, circuit breaker, audit log | `pip install agent-gatekeep` |
| [ctxforge](https://github.com/mlazeez/ctxforge) | Context compiler — raw documents to a queryable wiki (concepts, backlinks, search, health checks) | `pip install ctxforge-ai` |
| [tracedeck](https://github.com/mlazeez/tracedeck) | Decision logs for agents — replay, decision-point diffing, golden regression gates | `pip install tracedeck` |
| [AgentLedger](https://github.com/mlazeez/agent-ledger) | Tamper-proof audit trail + policy enforcement for AI agents, zero dependencies | — |
| [AgentLedger MCP](https://github.com/mlazeez/agent-ledger-mcp) | Audit + policy enforcement as tools for any MCP client (Claude, VS Code, custom agents) | — |
| [AgentLedger Adapters](https://github.com/mlazeez/agent-ledger-adapters) | One-liner audit for LangChain, LlamaIndex, OpenAI Agents | — |

**AgentLedger** = *what the agent did.* **gatekeep** = *what the agent is
allowed to do.* **ctxforge** = *what the agent knows.* **tracedeck** = *why
the agent decided it.*

## Stack

Python · C++ · SQLite · MCP · zero-dependency stdlib-first design

## Open to

AI engineering, agent infrastructure, and LLM tooling work — [start a
discussion](https://github.com/mlazeez/mlazeez/discussions).