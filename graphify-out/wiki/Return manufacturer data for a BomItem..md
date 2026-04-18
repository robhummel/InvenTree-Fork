---
source_file: "inventree/src/backend/InvenTree/plugin/builtin/exporter/bom_exporter.py"
type: "rationale"
community: "Community 2"
location: "L305"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_2
---

# Return manufacturer data for a BomItem.

## Connections
- [[.get_manufacturer_data()]] - `rationale_for` [EXTRACTED]
- [[BomItem]] - `uses` [INFERRED]
- [[BomItemSerializer]] - `uses` [INFERRED]
- [[InvenTreePlugin]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Community_2