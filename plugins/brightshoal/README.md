# Brightshoal plugins

Connect your AI assistant to your [Brightshoal](https://brightshoal.si) account. The `brightshoal` plugin adds the Brightshoal MCP server (`https://api.brightshoal.si/mcp`) to Claude Code, Claude, Codex and ChatGPT, so you can ask about your leads, conversations, assistants, analytics and Search work in plain language.

It contains the server connection and nothing else: no skills, commands, hooks or local code.

## Install

**Claude Code**

```sh
claude plugin marketplace add piyush-gambhir/brightshoal-plugins
claude plugin install brightshoal@brightshoal
```

**Codex**

```sh
codex plugin marketplace add piyush-gambhir/brightshoal-plugins
```

Then open `/plugins` in Codex and install **Brightshoal**.

**Any other MCP client:** add `https://api.brightshoal.si/mcp` as a remote (streamable HTTP) MCP server.

## Signing in

The first time a tool runs, your client opens Brightshoal in the browser. Sign in, choose the organization, and untick any permission you do not want the client to have. Disconnect it any time under **Settings > Account > MCP connections** in the console.

## What it can do

- **Read** with your own role: leads, conversations, assistants, knowledge, bookings, chat analytics and Search (sites, findings, drafts, AI answer visibility and To do items).
- **Propose changes**, such as editing an assistant draft or updating a lead. A change never runs on its own: it opens a review in your Brightshoal console and runs only after you approve it there.
- Keys, users, payments and outbound sending are not available through the plugin.

## Support

hello@brightshoal.si · [Privacy](https://brightshoal.si/privacy) · [Terms](https://brightshoal.si/terms) · [Developers](https://brightshoal.si/developers)
