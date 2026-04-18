---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/stock/test_views.py"
type: "rationale"
community: "Core Models & Admin"
location: "L54"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Core_Models_&_Admin
---

# Check without ownership control enabled. Should always return True.

## Connections
- [[.test_owner_no_ownership()]] - `rationale_for` [EXTRACTED]
- [[InvenTreeSetting]] - `uses` [INFERRED]
- [[InvenTreeTestCase_1]] - `uses` [INFERRED]
- [[Owner]] - `uses` [INFERRED]
- [[StockItem]] - `uses` [INFERRED]
- [[StockLocation]] - `uses` [INFERRED]
- [[StockStatus]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Core_Models_&_Admin