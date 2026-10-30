# Fax for Agents

This extension connects Gemini CLI to Fax for Agents. Fax for Agents is a fax API, a hosted MCP server and SDKs built so AI agents can send and receive faxes. It is made by JSB Holdings LLC.

The MCP server runs locally with `npx -y faxforagents-mcp` and reads the key from `FAXFORAGENTS_API_KEY`.

How the keys work:

- A key that starts with `ffa_test_` is a sandbox key. Nothing leaves the sandbox and nothing is billed.
- A key that starts with `ffa_live_` sends real faxes through the carrier. Live sends are prepaid per page.

Before a live send, quote it first and show the user the price and the destination number. Ask before sending when the user has not named the number and the document in this session. Use the delivery evidence tools to confirm what happened instead of guessing.

Docs: https://faxforagents.com/docs/
Pricing: https://faxforagents.com/pricing/
Source: https://github.com/faxforagents/mcp
