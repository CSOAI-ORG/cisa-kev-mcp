[![MCP Scorecard: 90/100](https://img.shields.io/badge/proofof.ai-90%2F100-5b21b6)](https://proofof.ai/scorecard/cisa-kev-mcp.html)

# Cisa Kev MCP
mcp-name: io.github.CSOAI-ORG/cisa-kev-mcp

# CISA KEV Known Exploited Vulnerabilities MCP

[![MEOK AI Labs](https://img.shields.io/badge/MEOK-AI%20Labs-667eea)](https://meok.ai)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![PyPI](https://img.shields.io/badge/PyPI-Install-3775a9)](https://pypi.org/project/cisa_kev_mcp/)

> CISA Known Exploited Vulnerabilities MCP
> **Signed attestations + unlimited audits + email support.**
> 👉 **[Subscribe at meok.ai](https://meok.ai/pricing)** — instant HMAC signing key + Stripe-managed billing.
>

CISA Known Exploited Vulnerabilities MCP. BOD 22-01 + EPSS overlay. MIT

---

## 🚀 Quick Start

```bash
# Install via pip
pip install cisa_kev_mcp

# Or install via Smithery
npx -y @smithery/cli@latest install cisa-kev-mcp --client claude
```

## ✨ Features

- MCP protocol compliant
- Easy installation
- Well-documented API
- Production-ready
- Active maintenance

## 📖 Documentation

- [Full Documentation](https://docs.meok.ai/cisa-kev-mcp)
- [API Reference](https://api.meok.ai)
- [EU AI Act Compliance Guide](https://councilof.ai/compliance)

## 🛡️ Compliance

This MCP server is built with **EU AI Act compliance** built-in:
- **Free**: 10 calls/day. No API key required.

- ✅ Article 9 — Risk Management System
- ✅ Article 13 — Transparency & Instructions for Use
- ✅ Article 15 — Bias Detection & Testing
- ✅ Article 26 — FRIA Support (where applicable)
- ✅ Article 50 — AI Content Watermarking (where applicable)

Need help getting compliant? **[Book a free 15-min diagnostic →](https://cal.com/csoai/august-audit)**

## How MEOK charges

MEOK has no subscriptions and no tiers. You pay per job, and only when the agreed artifact has been delivered to you. There is no public price list. See <https://meok.ai/pricing>.

This repository's source is MIT-licensed and free to self-host.

## 🤝 Part of the MEOK Ecosystem

This server is part of the **[MEOK AI Labs](https://meok.ai)** ecosystem — 300+ MCP servers for sovereign AI governance.

| Domain | Purpose |
|--------|---------|
| [councilof.ai](https://councilof.ai) | EU AI Act compliance marketplace |
| [safetyof.ai](https://safetyof.ai) | AI safety & monitoring |
| [meok.ai](https://meok.ai) | Sovereign AI platform |
| [cobolbridge.ai](https://cobolbridge.ai) | Legacy modernization |

## 📜 License

MIT © [CSOAI-ORG](https://github.com/CSOAI-ORG)

---

<p align="center">
  <sub>Built with 💜 by <a href="https://meok.ai">MEOK AI Labs</a> · UK Companies House 16939677</sub>
</p>
<!-- mcp-name: io.github.CSOAI-ORG/cisa-kev-mcp -->



## Configuration

Add to your `claude_desktop_config.json` (Claude Desktop) or your MCP client config:

```json
{
  "mcpServers": {
    "cisa-kev-mcp": {
      "command": "uvx",
      "args": ["cisa-kev-mcp"]
    }
  }
}
```

Or: `pip install cisa-kev-mcp` then run the `cisa-kev-mcp` command (stdio transport).

## Examples

Once configured, ask your assistant, for example:
- "Use `query_kev_catalog` to …"
- "Use `check_remediation_deadline` to …"
- "Use `export_kev_sbom` to …"
