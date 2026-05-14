# CISA KEV Known Exploited Vulnerabilities MCP

[![PyPI](https://img.shields.io/pypi/v/cisa-kev-mcp)](https://pypi.org/project/cisa-kev-mcp/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![MEOK AI Labs](https://img.shields.io/badge/MEOK_AI_Labs-governance--mcp-purple)](https://meok.ai)

CISA Known Exploited Vulnerabilities feed + remediation deadlines for US federal + critical infrastructure operators.

## Install

```bash
pip install cisa-kev-mcp
```

## Tools

| Tool | Purpose |
|------|---------|
| `query_kev_catalog` | Query CISA KEV catalog by CVE, vendor, product, date |
| `check_remediation_deadline` | BOD 22-01 remediation deadline + days remaining |
| `export_kev_sbom` | Cross-reference KEV with provided SBOM (CycloneDX) |
| `subscribe_alerts` | Recent additions to KEV catalog (last 7 days) |
| `epss_overlay` | EPSS Exploit Prediction Scoring overlay for prioritization |

## Pairs with

- `meok-attestation-api` — POST results to https://meok-attestation-api.vercel.app/sign for cryptographically signed compliance certs
- `meok-attestation-verify` — public verification of any MEOK-signed cert
- Other MEOK governance MCPs via SOV3 `mcp_bridge_call`

## Pricing

- **Free**: 10 calls/day. No API key required.
- **Pro** £79/mo: unlimited + signed attestations. [Subscribe](https://buy.stripe.com/14A4gB3K4eUWgYR56o8k836)
- **Enterprise** £1,499/mo: white-label + on-premise + SLA. hello@meok.ai

## Status

Scaffold v1.0.0 ships the MCP framework + 5 tool stubs. v1.1.0 will add real regulation data ingestion.

If your team needs this MCP fully-loaded faster, ping hello@meok.ai for sponsored development.

## License

MIT © MEOK AI Labs

<!-- mcp-name: io.github.CSOAI-ORG/cisa-kev-mcp -->
