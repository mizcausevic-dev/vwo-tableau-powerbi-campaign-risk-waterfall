# VWO Tableau Power BI Campaign Risk Waterfall

Campaign risk waterfall for VWO rollout risk, Tableau source trust, and Power BI revenue exposure.

![ci](https://github.com/mizcausevic-dev/vwo-tableau-powerbi-campaign-risk-waterfall/actions/workflows/ci.yml/badge.svg)

## What this ships

This repo is a static Kinetic Gain evidence surface, not a placeholder page. It packages VWO, Tableau, Power BI signals into a board-readable operating view:

- Exposure: where workflow, platform, or communications risk can become visible.
- Savings: where duplicate effort, drift, or manual coordination can be reduced.
- Investment: which next action deserves funding, ownership, or escalation.
- Story: how the evidence should be explained to executives or investors.

## Live surface

- Product page: https://mizcausevic-dev.github.io/vwo-tableau-powerbi-campaign-risk-waterfall/
- Repository: https://github.com/mizcausevic-dev/vwo-tableau-powerbi-campaign-risk-waterfall
- Portfolio atlas: https://portfolio.kineticgain.com/

## Evidence lanes

- experiment integrity
- holdout trust
- dashboard lineage
- semantic model confidence
- revenue lift evidence
- board readout readiness

## Related surfaces

- [VWO Tableau Power BI Decision Evidence Room](https://mizcausevic-dev.github.io/vwo-tableau-powerbi-decision-evidence-room/)

## Local verification

```bash
npm test
```

The validation script checks the data payload, generated page, interactive evidence table, related links, and footer links.
