# Grant Evidence Pack

Turn sign-in logs and receipts into a monthly grant report. Every number links to its row.

It's a hosted MCP server, so there's nothing to install. This repo is just the listing. The server code isn't here.

## Add it

Connector URL: `https://grants.rowhousesoftware.com/mcp`

In Claude: open Settings, then Connectors, then Add custom connector. Paste the URL.

In Claude Code:

```
claude mcp add -t http grant-evidence-pack https://grants.rowhousesoftware.com/mcp
```

## Tools

- `check_report`: Works out the month's counts and costs from your CSV rows, and lists any problems.
- `build_pack`: Makes a ZIP with a draft PDF, a Word file, a checklist and the number ledger.
- `pro_status`: Says the price and limits, and checks a paid code.

## Free and paid

Free: one grant and 100 rows per file. The paid plan will be $39 a month, for five grants and 2,000 rows per file. It isn't on sale yet.

## Sign in

None. It's open. No key and no sign in.

## Help

- Site: https://grants.rowhousesoftware.com
- Email: support@rowhousesoftware.com

Made by [Rowhouse Software](https://rowhousesoftware.com).
