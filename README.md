# 🧾 invoiceOracle

**Consumer MCP Server** — 10 tools | Part of [ToolOracle](https://tooloracle.io)

![Tools](https://img.shields.io/badge/MCP_Tools-10-10B898?style=flat-square)
![Status](https://img.shields.io/badge/Status-Live-00C853?style=flat-square)
![Tier](https://img.shields.io/badge/Tier-Free-2196F3?style=flat-square)

## Quick Connect

```bash
# Claude Desktop / Cursor / Windsurf
npx -y mcp-remote https://tooloracle.io/invoice/mcp/
```

```json
// claude_desktop_config.json
{
  "mcpServers": {
    "invoiceoracle": {
      "command": "npx",
      "args": ["-y", "mcp-remote", "https://tooloracle.io/invoice/mcp/"]
    }
  }
}
```

## Tools (10)

| Tool | Description |
|------|-------------|
| `invoice_parse_text` | Extract all text from a PDF invoice. Returns text per page and full combined tex |
| `invoice_extract` | Smart field extraction from invoice: Rechnungsnummer, Datum, Fälligkeit, Gesamtb |
| `invoice_tables` | Extract tables and line items (Positionen) from invoice. Returns structured rows |
| `invoice_ocr` | OCR extraction for scanned or image-based PDF invoices using Tesseract (German + |
| `invoice_zugferd` | Parse ZUGFeRD or XRechnung XML data embedded in PDF. Returns structured invoice  |
| `invoice_validate` | Validate invoice against German §14 UStG legal requirements. Returns compliance  |
| `invoice_summary` | Complete invoice analysis in one call: all extracted fields, line items, ZUGFeRD |
| `invoice_from_url` | Download PDF from URL and run complete invoice analysis. |
| `invoice_batch_urls` | Process multiple invoice PDFs from URLs in one call. Returns analysis for each. |
| `health_check` | InvoiceOracle server status and available library versions. |

## Pricing

| Tier | Rate Limit | Price |
|------|-----------|-------|
| Free | 100 calls/day | €0 |
| Pro | 10,000 calls/day | €29/month |
| Enterprise | Unlimited | Custom |

> Free tier includes all tools with rate limiting. Upgrade for higher limits and priority support.

## Part of ToolOracle

invoiceOracle is one of **42 specialized MCP servers** in the [ToolOracle](https://tooloracle.io) ecosystem — the largest collection of production-ready MCP tools for AI agents.



**Related Oracles:**
- [FeedOracle](https://feedoracle.io) — Evidence-grade compliance data infrastructure
- [ToolOracle](https://tooloracle.io) — 42 Oracles, 390+ MCP Tools

## Links

- 🌐 Live: `https://tooloracle.io/invoice/mcp/`
- 📚 Docs: [tooloracle.io/docs](https://tooloracle.io/docs)
- 🏠 Platform: [tooloracle.io](https://tooloracle.io)

---

*Built by [FeedOracle](https://feedoracle.io) — Evidence by Design*
