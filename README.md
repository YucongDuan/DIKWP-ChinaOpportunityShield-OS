# DIKWP ChinaOpportunityShield OS

**DIKWP ChinaOpportunityShield OS** is an offline-first, GitHub-ready strategy system for protecting and converting Yucong Duan / DIKWP's open-source portfolio into China-market opportunities.

It analyzes a DIKWP GitHub repository portfolio, classifies repositories into strategic lanes, scores China-market opportunity, estimates protection need, screens partner requests, and generates a benefit-capture action plan.

## Core idea

Open source code can be copied. Opportunity capture must therefore move upward into:

- attribution integrity;
- official registry;
- TrustPassport / signed badge;
- pilot review report;
- training certification;
- industry adapter pack;
- partner routing;
- opportunity ledger;
- copycat-to-partner conversion path.

## Quick start

```bash
pip install -e .
oppshield analyze examples/sample_yucongduan_portfolio.json --out outputs/demo
oppshield static-audit src --out outputs/demo/static_boundary_audit_report.json
```

## Output files

- `github_portfolio_assessment.json`
- `repo_lane_map.csv`
- `china_opportunity_matrix.csv`
- `open_core_release_policy.csv`
- `partner_screening_report.json`
- `official_registry_seed.json`
- `opportunity_ledger.json`
- `protection_action_plan.md`
- `priority_90_day_action_plan.md`
- `benefit_capture_brief.md`

## Boundary

This project is for strategy, partner screening, opportunity logging, and open-source ecosystem governance. It is not legal advice, not investment advice, not official certification, and not a replacement for counsel, contracts, or governmental approval.
