[![MCP Scorecard: 90/100](https://img.shields.io/badge/proofof.ai-90%2F100-5b21b6)](https://proofof.ai/scorecard/cisa-kev-mcp.html)

# Cisa Kev MCP
mcp-name: io.github.CSOAI-ORG/cisa-kev-mcp

# CISA KEV Known Exploited Vulnerabilities MCP

[![MEOK AI Labs](https://img.shields.io/badge/MEOK-AI%20Labs-667eea)](https://meok.ai)
[![EU AI Act](https://img.shields.io/badge/EU%20AI%20Act-Compliant-22c55e)](https://councilof.ai)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![PyPI](https://img.shields.io/badge/PyPI-Install-3775a9)](https://pypi.org/project/cisa_kev_mcp/)

> CISA Known Exploited Vulnerabilities MCP
> ## Buy Starter — £29/mo
> **Signed attestations + unlimited audits + email support.**
> 👉 **[Subscribe at meok.ai](https://buy.stripe.com/5kQ6oJ0xS3ce8sl7ew8k91j)** — instant HMAC signing key + Stripe-managed billing.
>
> Free tier remains MIT-licensed and zero-config. Upgrade only when you need signed compliance artefacts for audit.

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
- **Pro** £79/mo: unlimited + signed attestations. [Subscribe](https://buy.stripe.com/5kQ6oJ0xS3ce8sl7ew8k91j)
- **Enterprise** £1,499/mo: white-label + on-premise + SLA. hello@meok.ai

- ✅ Article 9 — Risk Management System
- ✅ Article 13 — Transparency & Instructions for Use
- ✅ Article 15 — Bias Detection & Testing
- ✅ Article 26 — FRIA Support (where applicable)
- ✅ Article 50 — AI Content Watermarking (where applicable)

Need help getting compliant? **[Book a free 15-min diagnostic →](https://cal.com/csoai/august-audit)**

## 🏢 Enterprise

Need custom development, SLA guarantees, or white-label deployment?

- **Pro:** $99/mo — Full MCP suite + EU AI Act tracking
- **Enterprise:** $499/mo — Custom dev + SLA + Dedicated support

[View Pricing →](https://councilof.ai/pricing) | [Contact Sales →](mailto:sales@csoai.org)

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

<!-- BUY-LADDER:START -->

## 💸 Try MEOK in 30 seconds — instant buy ladder

| Tier | Price | What you get | Stripe |
|---|---|---|---|
| Smoke test | **£1** | Signed sample MCP-Hardening report + Article 50 PDF | <https://buy.stripe.com/5kQ6oJ0xS3ce8sl7ew8k91j> |
| Quick Kit | **£9** | EU AI Act Article 50 implementation guide (C2PA + EU-Icon) | <https://buy.stripe.com/5kQ6oJ0xS3ce8sl7ew8k91j> |
| Founder Call | **£29** | 30-min 1-on-1 with the founder | <https://buy.stripe.com/5kQ6oJ0xS3ce8sl7ew8k91j> |

> Refundable. UK Stripe — VAT-clean. Builds on the 81-MCP MEOK fleet.
> Verify any signed report at <https://meok.ai/verify>.

<!-- BUY-LADDER:END -->


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
