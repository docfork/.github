# Docfork 👋

**Up-to-date code documentation for your AI agents. Stop hunting for docs, start building.**

---

### Why Docfork?

We've all been there: you ask your AI for the latest Next.js syntax, but it gives you code from 2023. AI models are powerful, but their "knowledge" is often out of date.

**Docfork** fixes this by pulling the latest documentation directly into your AI’s context. No more hallucinations, no more stale APIs—just working code.

* **Always Current:** Daily updates for 10,000+ libraries.
* **Fast:** Sub-second retrieval so you don't lose your flow.
* **Ready for AI:** Content is formatted specifically for LLMs to understand and use instantly.

---

### 🚀 Featured Repositories

* **[docfork-mcp](https://github.com/docfork/docfork-mcp)**: The core MCP server. Works with **Cursor, Claude Code, Windsurf, VS Code**, and more.
* **[docs](https://github.com/docfork/docs)**: Guides, SDK documentation, and community resources.

---

### 🛠️ Quick Start

Connect Docfork to your favorite editor in seconds.

**Option 1: Add to your MCP config**

```json
{
  "mcpServers": {
    "docfork": {
      "url": "https://mcp.docfork.com/mcp"
    }
  }
}

```

**Option 2: Run it locally**

```bash
npx -y docfork

```

Once connected, just ask your AI:

> *"Create a basic Next.js app with the App Router. use docfork"*

---

**Happy coding!** [docfork.com](https://docfork.com) • [Follow us on X](https://x.com/docfork_ai)
