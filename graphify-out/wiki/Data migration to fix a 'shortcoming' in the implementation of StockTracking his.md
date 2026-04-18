---
source_file: "inventree/src/backend/InvenTree/stock/migrations/0096_auto_20230330_1121.py"
type: "rationale"
community: "Data Migrations & Schema"
location: "L7"
tags:
  - graphify/rationale
  - graphify/EXTRACTED
  - community/Data_Migrations_&_Schema
---

# Data migration to fix a 'shortcoming' in the implementation of StockTracking his

## Connections
- [[StockHistoryCode]] - `uses` [INFERRED]
- [[update_stock_history()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/EXTRACTED #community/Data_Migrations_&_Schema