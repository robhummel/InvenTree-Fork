---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/plugin/builtin/exporter/bom_exporter.py"
type: "rationale"
community: "Community 1"
location: "L281"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_1
---

# Return supplier and manufacturer data for a BomItem.

## Connections
- [[.get_supplier_data()]] - `rationale_for` [EXTRACTED]
- [[BomItem]] - `uses` [INFERRED]
- [[BomItemSerializer]] - `uses` [INFERRED]
- [[InvenTreePlugin]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Community_1