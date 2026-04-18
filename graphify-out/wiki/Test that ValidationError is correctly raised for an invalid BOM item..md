---
source_file: "inventree/src/backend/InvenTree/part/test_bom_item.py"
type: "rationale"
community: "Documentation & FAQ"
location: "L297"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Documentation_&_FAQ
---

# Test that ValidationError is correctly raised for an invalid BOM item.

## Connections
- [[.test_invalid_bom()]] - `rationale_for` [EXTRACTED]
- [[BomItem]] - `uses` [INFERRED]
- [[BomItemSubstitute]] - `uses` [INFERRED]
- [[Part]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Documentation_&_FAQ