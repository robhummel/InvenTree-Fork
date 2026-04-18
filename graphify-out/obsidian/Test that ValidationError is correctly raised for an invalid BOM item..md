---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/part/test_bom_item.py"
type: "rationale"
community: "Community 5"
location: "L297"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_5
---

# Test that ValidationError is correctly raised for an invalid BOM item.

## Connections
- [[.test_invalid_bom()]] - `rationale_for` [EXTRACTED]
- [[BomItem]] - `uses` [INFERRED]
- [[BomItemSubstitute]] - `uses` [INFERRED]
- [[Part]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Community_5