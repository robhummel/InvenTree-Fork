---
source_file: "inventree/src/backend/InvenTree/part/test_bom_item.py"
type: "rationale"
community: "Documentation & FAQ"
location: "L58"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Documentation_&_FAQ
---

# Test that the 'used_in_count' attribute is calculated correctly.

## Connections
- [[.test_used_in()]] - `rationale_for` [EXTRACTED]
- [[BomItem]] - `uses` [INFERRED]
- [[BomItemSubstitute]] - `uses` [INFERRED]
- [[Part]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Documentation_&_FAQ