---
source_file: "inventree/src/backend/InvenTree/stock/test_views.py"
type: "rationale"
community: "Part Management & Archetypes"
location: "L54"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Part_Management_&_Archetypes
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

#graphify/rationale #graphify/INFERRED #community/Part_Management_&_Archetypes