---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/stock/migrations/0096_auto_20230330_1121.py"
type: "rationale"
community: "Community 7"
location: "L7"
tags:
  - graphify/rationale
  - graphify/EXTRACTED
  - community/Community_7
---

# Data migration to fix a 'shortcoming' in the implementation of StockTracking his

## Connections
- [[StockHistoryCode]] - `uses` [INFERRED]
- [[update_stock_history()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/EXTRACTED #community/Community_7