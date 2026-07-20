### Hi, I’m **Aditya Karnam**  
**Senior AI Systems Engineer · AI Innovator · Researcher**

**Recent projects:**  
- **Tiny AI harness + coding agent in Rust** → [quecto](https://github.com/adityak74/quecto)  
  - a minimalist OpenAI-compatible harness and coding agent with a ~1.3 MB core and ~3.5 MB agent binary  
- **Parallel AI agent orchestration in cmux** → [antigravity-cmux-skill](https://github.com/adityak74/antigravity-cmux-skills)  
  - plugin and skill for running independent Antigravity sessions in split panes, with browser automation and coordination workflows  
- **Local coding model benchmarking** → [locobench](https://github.com/adityak74/locobench)  
  - practical Harbor + Ollama setup for running local agentic benchmarks and maintaining a leaderboard pipeline  
- **Forced-output learning skill** → [learn-anything-24h](https://github.com/adityak74/learn-anything-24h)  
  - compresses hard topics into a structured 24-hour sprint with exercises, teach-back prompts, and a final artifact  

I build intelligent AI systems that combine **strong engineering**, **modern LLM workflows**, and **real‑world usability**.  
My work focuses on **context‑aware AI**, **LLM infrastructure**, **agent tooling**, **evaluation systems**, and **products that make complex workflows feel effortless**.  

**Selected projects & research:**  
- **Universal embedding retrieval toolkit & agentic memory layer** → [embenx](https://github.com/adityak74/embenx)  
  - unified API for 15+ vector backends with MCP support for Claude and autonomous agents  
  - `pip install embenx`  
- **Interoperable AI chat contexts** → [opencontext](https://github.com/adityak74/opencontext)  
- **Academic retrieval with MCP** → [mcp-scholarly](https://github.com/adityak74/mcp-scholarly)  
- **Applied model fine‑tuning in healthcare** → [medfit-llm](https://github.com/adityak74/medfit-llm)  
- **Developer productivity automation** → [google-drive-upload-git-action](https://github.com/adityak74/google-drive-upload-git-action)  
- **Creativity‑focused Claude skills** → [cc-creativity-skills](https://github.com/adityak74/cc-creativity-skills)  

I share work and thoughts on **AI systems**, **open‑source tools**, **prompt design**, and **intelligent automation**:  
- Website: [adityakarnam.com](https://adityakarnam.com)  
- Threads: [threads.com/@aditya_karnam](https://www.threads.com/@aditya_karnam)  
- Google Scholar: [citations?user=WujCeDkAAAAJ](https://scholar.google.com/citations?user=WujCeDkAAAAJ&hl=en)  

Currently exploring how to make AI systems more interpretable without sacrificing performance.

---

## Portfolio MCP

A public, read-only [Model Context Protocol](https://modelcontextprotocol.io) server exposing this portfolio's projects, recent work, research agenda, and source links as structured data for agents and assistants.

- MCP name: `aditya-portfolio`
- Transport: `http`
- URL: `https://adityakarnam.com/mcp`
- Discovery manifest: `https://adityakarnam.com/.well-known/aditya-portfolio-mcp.json`
- Health check: `https://adityakarnam.com/mcp-health`
- Install guide: [adityakarnam.com/mcp-install](https://adityakarnam.com/mcp-install/)

It exposes only public data: projects, posts, systems, research agenda, and source links. It does not expose private files, email, analytics, personal data, availability, compensation, immigration status, or references.

### Claude Code

```bash
claude mcp add --transport http aditya-portfolio https://adityakarnam.com/mcp
```

Verify with:

```bash
claude mcp list
```

### Claude (web/desktop app)

1. Open Claude → Settings / Customize → Connectors.
2. Choose **Add custom connector**.
3. Paste `https://adityakarnam.com/mcp`.
4. Save the connector.

### Other agents (Codex, Cursor, Antigravity, or any MCP-compatible client)

Add a remote server:

- Name: `aditya-portfolio`
- Transport: `http`
- URL: `https://adityakarnam.com/mcp`

Clients that only support local/stdio MCP servers can bridge to this endpoint via [`mcp-remote`](https://www.npmjs.com/package/mcp-remote):

```bash
npx mcp-remote https://adityakarnam.com/mcp
```

### Try it

- "Use Aditya Karnam's portfolio connector. Is he a fit for this AI infrastructure role?"
- "Which projects show agent runtime or MCP experience?"
- "Give me a recruiter brief with evidence and source links."
- "Act as an engineer. Which systems should I inspect first?"
