---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/plugin/builtin/exporter/bom_exporter.py"
type: "rationale"
community: "Community 1"
location: "L67"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_1
---

# Builtin plugin for performing multi-level BOM exports.

## Connections
- [[BomExporterPlugin]] - `rationale_for` [EXTRACTED]
- [[BomItem]] - `uses` [INFERRED]
- [[BomItemSerializer]] - `uses` [INFERRED]
- [[InvenTreePlugin]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Community_1