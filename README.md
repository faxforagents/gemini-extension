# Fax for Agents for Gemini CLI

A Gemini CLI extension that adds the Fax for Agents MCP server. Fax for Agents is a fax API, a hosted MCP server and SDKs built so AI agents can send and receive faxes. It is made by JSB Holdings LLC.

## Install

```bash
gemini extensions install https://github.com/faxforagents/gemini-extension
```

Gemini CLI asks for your API key on install and keeps it in the system keychain. A sandbox key (`ffa_test_...`) is free and comes from https://faxforagents.com. A live key (`ffa_live_...`) sends through the carrier and is prepaid per page.

The extension runs `npx -y faxforagents-mcp`, so you need Node.js 20 or newer.

## What you get

15 tools, plus resources and prompts, for sending and receiving faxes: quotes, human review, delegated policies and delivery evidence. The hosted endpoint at `https://mcp.faxforagents.com/mcp/` offers the same tools over Streamable HTTP if you prefer not to run a local process.

## Links

- Website: https://faxforagents.com
- Docs: https://faxforagents.com/docs/
- Pricing: https://faxforagents.com/pricing/
- OpenAPI: https://faxforagents.com/openapi.json
- MCP server source: https://github.com/faxforagents/mcp
- npm: https://www.npmjs.com/package/faxforagents-mcp
- Contact: hello@faxforagents.com

## Licence

MIT. See [LICENSE](LICENSE).
