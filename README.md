# LucidLink AI

Give your AI agents secure, real-time access to the data in your
[LucidLink](https://www.lucidlink.com) filespace. This is the index of
LucidLink's AI integrations - each lives in its own repo so you can clone
just what you need.

## Building blocks

- **[Python SDK](https://pypi.org/project/lucidlink/)** - wire filespace
  `list` / `read` / `write` in as agent tools, in any framework.
- **[MCP server](https://pypi.org/project/lucidlink-mcp/)** - drop in ~35
  filespace tools (navigation, safe multi-writer editing, locking, audit)
  into any MCP-capable agent or IDE.

## Integrations

### [lucidlink-agentic-examples](https://github.com/LucidLink/lucidlink-agentic-examples)

Code samples connecting popular Python agentic frameworks to LucidLink -
LangChain, LlamaIndex, CrewAI, Pydantic AI, smolagents, OpenAI Agents, the
Anthropic SDK, and the Claude Agent SDK. Tiny, self-contained files per
framework: hand-wired SDK tools and MCP bridging, side by side.

### [Scoped agents](https://github.com/LucidLink/lucidlink-agentic-examples/tree/master/scoped-agents)

Least-privilege service accounts, minted by agents: your admin agent creates
**collaborator service accounts** that see nothing until granted, hands a
worker agent exactly one folder, and optionally makes the credential
single-use so it self-destructs after its one mount. A natural-language
walkthrough through the MCP.

### [Terminal agents (claws)](https://github.com/LucidLink/lucidlink-agentic-examples/tree/master/claws)

One-page setup for wiring terminal agents - **OpenClaw**, **Hermes**, and **NVIDIA NemoClaw**
sandboxes - to the LucidLink MCP server.

### [lucidlink-kiro-power](https://github.com/LucidLink/lucidlink-kiro-power)

A custom **[Kiro](https://kiro.dev)** Power that activates on demand when you
mention your LucidLink filespace - giving Kiro the filespace tools and the
safe multi-writer workflow without bloating its context the rest of the time.

### [lucidlink-bob-mode](https://github.com/LucidLink/lucidlink-bob-mode)

A custom **[IBM Bob](https://bob.ibm.com)** mode that lets Bob work with
files in your LucidLink filespace - navigate, preview edits, and edit safely
alongside your teammates and other agents.

## Links

- [LucidLink Python SDK on PyPI](https://pypi.org/project/lucidlink/)
- [LucidLink MCP server on PyPI](https://pypi.org/project/lucidlink-mcp/)
- [LucidLink Developer Platform KB](https://support.lucidlink.com/hc/en-us/articles/44957651982989-LucidLink-Developer-Platform)
- [LucidLink Support](https://support.lucidlink.com/)
