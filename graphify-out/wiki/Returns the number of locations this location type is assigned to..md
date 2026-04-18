---
source_file: "inventree/src/backend/InvenTree/stock/admin.py"
type: "rationale"
community: "Documentation & FAQ"
location: "L50"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Documentation_&_FAQ
---

# Returns the number of locations this location type is assigned to.

## Connections
- [[.location_count()]] - `rationale_for` [EXTRACTED]
- [[PluginUserSettingInline]] - `rationale_for` [EXTRACTED]
- [[StockItem]] - `uses` [INFERRED]
- [[StockItemTestResult]] - `uses` [INFERRED]
- [[StockItemTracking]] - `uses` [INFERRED]
- [[StockLocation]] - `uses` [INFERRED]
- [[StockLocationType]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Documentation_&_FAQ