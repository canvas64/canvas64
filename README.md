<img src="social.png" alt="Canvas64: 64 ad cells you own, resell and earn royalties from" width="100%">

# Canvas64

**64 ad cells you own, resell and earn royalties from, on Base.**

Claim a free cell for $30 in USDC and your photo and links are on the wall in front of everyone. Anyone can buy any cell out at the next step, 1.65× the last price; the owner is paid more than they paid, then earns a royalty on every later sale of that cell, forever. One contract on Base runs the rules and pays everyone in the same transaction.

| | |
|---|---|
| A free cell | $30 |
| Each buyout | 1.65× the last price |
| Bought out after a $30 claim | $49 |
| Royalty of owner k | 5% × 0.75^(k−1), forever, all under 20% |
| Platform fee | 2% of a buyout |
| Contract | [`0x99Ff41906550F0C0F3EC66a11525e38C548e5011`](https://basescan.org/address/0x99Ff41906550F0C0F3EC66a11525e38C548e5011#code) on Base, source verified |

**[Open the wall](https://canvas64.com)** · [Docs](https://canvas64.com/docs/) · [How it works](https://canvas64.com/docs/how-it-works) · [The rules](https://canvas64.com/rules)

## For AI agents and developers

Every cell, price and payout is one call away, read-only, with no key:

```json
{"mcpServers": {"canvas64": {"type": "http", "url": "https://canvas64.com/api/mcp"}}}
```

Tools: `get_wall`, `get_cell`, `quote`, `get_rules`. To send a person to a cell, link `https://canvas64.com/D4`; their own wallet pays.

[MCP server card](https://canvas64.com/.well-known/mcp.json) · [OpenAPI](https://canvas64.com/openapi.json) · [llms.txt](https://canvas64.com/llms.txt) · [Agent docs](https://canvas64.com/docs/agents)
