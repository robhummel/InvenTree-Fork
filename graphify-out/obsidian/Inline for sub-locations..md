---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/stock/admin.py"
type: "rationale"
community: "Core Models & Admin"
location: "L16"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Core_Models_&_Admin
---

# Inline for sub-locations.

## Connections
- [[.has_add_permission()_2]] - `rationale_for` [EXTRACTED]
- [[LocationInline]] - `rationale_for` [EXTRACTED]
- [[StockItem]] - `uses` [INFERRED]
- [[StockItemTestResult]] - `uses` [INFERRED]
- [[StockItemTracking]] - `uses` [INFERRED]
- [[StockLocation]] - `uses` [INFERRED]
- [[StockLocationType]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Core_Models_&_Admin