---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/plugin/samples/locate/locate_sample.py"
type: "rationale"
community: "Core Models & Admin"
location: "L27"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Core_Models_&_Admin
---

# Locate a StockItem.          Args:             item_pk: primary key for item

## Connections
- [[.locate_stock_item()]] - `rationale_for` [EXTRACTED]
- [[InvenTreePlugin]] - `uses` [INFERRED]
- [[LocateMixin_1]] - `uses` [INFERRED]
- [[StockItem]] - `uses` [INFERRED]
- [[StockLocation]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Core_Models_&_Admin