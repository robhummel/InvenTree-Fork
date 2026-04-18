---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/part/test_bom_item.py"
type: "rationale"
community: "Community 5"
location: "L83"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_5
---

# Test that BOM line attrition values are calculated correctly.

## Connections
- [[.test_attrition()]] - `rationale_for` [EXTRACTED]
- [[BomItem]] - `uses` [INFERRED]
- [[BomItemSubstitute]] - `uses` [INFERRED]
- [[Part]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Community_5