---
source_file: "inventree/src/backend/InvenTree/stock/migrations/0061_auto_20210511_0911.py"
type: "rationale"
community: "Data Migrations & Schema"
location: "L11"
tags:
  - graphify/rationale
  - graphify/EXTRACTED
  - community/Data_Migrations_&_Schema
---

# Update each existing StockItemTracking object,     convert the recorded "quantit

## Connections
- [[StockHistoryCode]] - `uses` [INFERRED]
- [[update_history()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/EXTRACTED #community/Data_Migrations_&_Schema