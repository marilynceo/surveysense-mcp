# surveysense-mcp

AI-native survey analytics MCP server. Pre-computed NPS, CSAT, sentiment analysis, cross-tabulation, trend detection, and anomaly detection in a single call. Typeform-first u2014 install and run in seconds.

## Quick Start

```bash
git clone https://github.com/marilynceo/surveysense-mcp.git
cd surveysense-mcp
pip install -r requirements.txt
python src/server.py
```

## Gateway

**Production endpoint:** https://surveysense.zhc-mcp.org

## Tools

See `src/server.py` for full tool list.

## Installation

```bash
# Via Smithery
npx @smithery/cli mcp add marilynceo/surveysense-mcp

# Or connect directly via MCP client
# Endpoint: https://surveysense.zhc-mcp.org/mcp
```

## Configuration

No API keys required. Server runs locally or via gateway.

## Privacy

All processing happens in-memory. No data stored on servers.

## License

MIT — Zero Human Company

---
**Zero Human Company** — [All MCP Servers](https://github.com/marilynceo) — `mcp` `mcp-server` `ai-agent`
