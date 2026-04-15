# DottedSign MCP

Connect your AI assistant (Claude or ChatGPT) to DottedSign — create signing tasks, track document status, manage templates, and more using natural language.

---

## Setup on Claude

Works on free accounts. Steps are the same for both Claude Desktop and claude.ai.

1. Click your account icon → **Settings**
2. Select **Connectors** → **Add Connector**
3. Paste the following URL:
   ```
   https://mcp.dottedsign.com/dottedsign-api/mcp
   ```
4. Claude will walk you through signing in to DottedSign to authorize access

Once connected, just tell Claude what you want — for example: *"Show me my recent signing tasks in DottedSign."*

---

## Setup on Claude Code

Run the following command in your terminal:

```bash
claude mcp add --transport http dottedsign https://mcp.dottedsign.com/dottedsign-api/mcp
```

Claude Code will prompt you to authorize via DottedSign on first use.

---

## Setup on ChatGPT

May require a paid plan.

1. Go to [chatgpt.com](https://chatgpt.com), click your account icon → **Settings**
2. Select **Connectors** → **Add Connector**
3. Paste the following URL:
   ```
   https://mcp.dottedsign.com/dottedsign-api/mcp
   ```
4. Sign in to DottedSign to complete authorization

---

## What You Can Do

Once connected, try asking your AI assistant:

- "List all my pending signing tasks"
- "Create a new signing task from the Sales Contract template and send it to xxx@example.com"
- "What's the signing status of my latest document?"
- "Get the download link for a completed contract"
