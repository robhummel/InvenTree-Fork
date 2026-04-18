---
source_file: "inventree/src/backend/InvenTree/plugin/builtin/exporter/bom_exporter.py"
type: "rationale"
community: "Community 2"
location: "L79"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_2
---

# This exported only supports the BomItem model.

## Connections
- [[.supports_export()_1]] - `rationale_for` [EXTRACTED]
- [[BomItem]] - `uses` [INFERRED]
- [[BomItemSerializer]] - `uses` [INFERRED]
- [[InvenTreePlugin]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Community_2