---
source_file: "inventree/src/backend/InvenTree/plugin/builtin/exporter/bom_exporter.py"
type: "rationale"
community: "Community 2"
location: "L179"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_2
---

# Export BOM data from the queryset.

## Connections
- [[.export_data()]] - `rationale_for` [EXTRACTED]
- [[BomItem]] - `uses` [INFERRED]
- [[BomItemSerializer]] - `uses` [INFERRED]
- [[InvenTreePlugin]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Community_2