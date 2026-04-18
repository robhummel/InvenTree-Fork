---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/part/apps.py"
type: "rationale"
community: "Community 12"
location: "L60"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_12
---

# Performed on startup, to ensure that all pricing objects are in a "good" state.

## Connections
- [[.reset_part_pricing_flags()]] - `rationale_for` [EXTRACTED]
- [[BomItem]] - `uses` [INFERRED]
- [[InvenTreeConfig]] - `uses` [INFERRED]
- [[PartPricing]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Community_12