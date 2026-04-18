---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/part/apps.py"
type: "rationale"
community: "Community 12"
location: "L39"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_12
---

# Check for any instances where a trackable part is used in the BOM for a non-trac

## Connections
- [[.update_trackable_status()]] - `rationale_for` [EXTRACTED]
- [[BomItem]] - `uses` [INFERRED]
- [[InvenTreeConfig]] - `uses` [INFERRED]
- [[PartPricing]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Community_12