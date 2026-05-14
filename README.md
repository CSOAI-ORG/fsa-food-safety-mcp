# Food Safety Compliance (UK FSA + EU) MCP

[![PyPI](https://img.shields.io/pypi/v/fsa-food-safety-mcp)](https://pypi.org/project/fsa-food-safety-mcp/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![MEOK AI Labs](https://img.shields.io/badge/MEOK_AI_Labs-governance--mcp-purple)](https://meok.ai)

UK Food Standards Agency + EU Reg 178/2002 + HACCP + allergen labelling compliance for food producers, retailers, and caterers.

## Install

```bash
pip install fsa-food-safety-mcp
```

## Tools

| Tool | Purpose |
|------|---------|
| `classify_food_business` | Determine FSA registration tier (low/medium/high risk) |
| `haccp_audit` | HACCP 7 principles + 12 steps compliance check |
| `allergen_labelling_check` | EU Reg 1169/2011 + Natasha's Law allergen disclosure |
| `traceability_one_up_one_down` | EU Reg 178/2002 Article 18 traceability |
| `recall_procedure_template` | Food recall + withdrawal procedure generator |

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
