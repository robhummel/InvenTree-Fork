---
source_file: "inventree/src/backend/InvenTree/stock/test_migrations.py"
type: "rationale"
community: "Data Migrations & Schema"
location: "L130"
tags:
  - graphify/rationale
  - graphify/EXTRACTED
  - community/Data_Migrations_&_Schema
---

# Test that all stock items were actually removed.

## Connections
- [[.test_migration()_1]] - `rationale_for` [EXTRACTED]
- [[SalesOrderStatus]] - `uses` [INFERRED]
- [[StockHistoryCode]] - `uses` [INFERRED]
- [[TestAdditionalLineMigration]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/EXTRACTED #community/Data_Migrations_&_Schema