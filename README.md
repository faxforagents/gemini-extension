<p align="center">
  <a href="https://faxforagents.com"><img src="https://faxforagents.com/brand/logo-512.png" width="88" alt="Fax for Agents"></a>
</p>

<h1 align="center">Fax for Agents for Gemini CLI</h1>

<p align="center">A Gemini CLI extension that adds the <a href="https://faxforagents.com">Fax for Agents</a> MCP server.</p>

<p align="center">
  <a href="https://faxforagents.com">Website</a> ·
  <a href="https://faxforagents.com/docs/quickstart/">Quickstart</a> ·
  <a href="https://faxforagents.com/docs/api/">API reference</a> ·
  <a href="https://faxforagents.com/docs/sdks/">SDKs</a> ·
  <a href="https://faxforagents.com/mcp/">MCP</a> ·
  <a href="https://app.faxforagents.com">Dashboard</a> ·
  <a href="https://faxforagents.com/pricing/">Pricing</a> ·
  <a href="https://faxforagents.com/changelog/">Changelog</a>
</p>

<p align="center">
  <a href="https://github.com/faxforagents/gemini-extension/blob/main/LICENSE"><img src="https://img.shields.io/badge/licence-MIT-1f6feb" alt="MIT licence"></a>
  <a href="https://www.npmjs.com/package/faxforagents-mcp"><img src="https://img.shields.io/npm/v/faxforagents-mcp?label=faxforagents-mcp" alt="faxforagents-mcp on npm"></a>
  <a href="https://nodejs.org"><img src="https://img.shields.io/badge/node-20%2B-339933" alt="Node 20+"></a>
</p>

Fax for Agents is a fax API, a hosted MCP server and SDKs built so AI agents can send and receive faxes. It is made by JSB Holdings LLC and built by [Synapse](https://synapsereality.io/).

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
- Dashboard: https://app.faxforagents.com
- Changelog: https://faxforagents.com/changelog/
- OpenAPI: https://faxforagents.com/openapi.json
- MCP server source: https://github.com/faxforagents/mcp
- npm: https://www.npmjs.com/package/faxforagents-mcp
- Contact: hello@faxforagents.com

## Licence

MIT. See [LICENSE](LICENSE).
