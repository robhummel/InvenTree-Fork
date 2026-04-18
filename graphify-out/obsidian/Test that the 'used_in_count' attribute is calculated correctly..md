---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/part/test_bom_item.py"
type: "rationale"
community: "Community 5"
location: "L58"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_5
---

# Test that the 'used_in_count' attribute is calculated correctly.

## Connections
- [[.test_used_in()]] - `rationale_for` [EXTRACTED]
- [[BomItem]] - `uses` [INFERRED]
- [[BomItemSubstitute]] - `uses` [INFERRED]
- [[Part]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Community_5