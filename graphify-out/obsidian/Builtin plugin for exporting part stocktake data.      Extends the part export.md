---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/plugin/builtin/exporter/stocktake_exporter.py"
type: "rationale"
community: "Community 1"
location: "L37"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_1
---

# Builtin plugin for exporting part stocktake data.      Extends the "part" export

## Connections
- [[InvenTreePlugin]] - `uses` [INFERRED]
- [[Part]] - `uses` [INFERRED]
- [[PartSerializer]] - `uses` [INFERRED]
- [[PartStocktakeExporter]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Community_1