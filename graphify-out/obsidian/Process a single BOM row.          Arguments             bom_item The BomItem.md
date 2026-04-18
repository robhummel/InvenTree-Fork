---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/plugin/builtin/exporter/bom_exporter.py"
type: "rationale"
community: "Community 1"
location: "L214"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_1
---

# Process a single BOM row.          Arguments:             bom_item: The BomItem

## Connections
- [[.process_bom_row()]] - `rationale_for` [EXTRACTED]
- [[BomItem]] - `uses` [INFERRED]
- [[BomItemSerializer]] - `uses` [INFERRED]
- [[InvenTreePlugin]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Community_1