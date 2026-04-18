---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/stock/test_migrations.py"
type: "rationale"
community: "Community 7"
location: "L130"
tags:
  - graphify/rationale
  - graphify/EXTRACTED
  - community/Community_7
---

# Test that all stock items were actually removed.

## Connections
- [[.test_migration()_1]] - `rationale_for` [EXTRACTED]
- [[SalesOrderStatus]] - `uses` [INFERRED]
- [[StockHistoryCode]] - `uses` [INFERRED]
- [[TestAdditionalLineMigration]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/EXTRACTED #community/Community_7