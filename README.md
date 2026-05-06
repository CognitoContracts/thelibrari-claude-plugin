# The Librari — Claude Code Plugin

Search and read your contract library directly from Claude Code using the [The Librari](https://www.thelibrari.com) MCP integration.

## What it does

Once installed, Claude Code can:

- **List** all your contracts
- **Search** contracts by keyword, status, or type
- **Read** full contract metadata — parties, dates, value, governing law, renewal terms
- **View** clause-level sections and full contract text

## Requirements

- An active [The Librari](https://www.thelibrari.com) subscription or beta access
- Claude Code v2.0 or later

## Installation

```bash
/plugin install https://github.com/CognitoContracts/thelibrari-claude-plugin
```

Claude Code will prompt you to connect your Librari account via OAuth the first time you use a contract tool.

## Usage

After installing, just ask Claude naturally:

```
list my contracts
search for NDAs expiring this year
get the renewal terms for my Microsoft agreement
```

Or use the namespaced tools directly via `/thelibrari:...`.

## Authentication

This plugin connects to The Librari via OAuth 2.0. Claude Code handles the auth flow automatically — you'll be redirected to The Librari to approve access, then returned to Claude Code.

To revoke access at any time, go to **Dashboard → MCP API Keys** in The Librari and delete the key.

## Support

- Website: [www.thelibrari.com](https://www.thelibrari.com)
- Issues: [github.com/CognitoContracts/thelibrari-claude-plugin/issues](https://github.com/CognitoContracts/thelibrari-claude-plugin/issues)
