---
source_file: "inventree/src/backend/InvenTree/company/test_migrations.py"
type: "rationale"
community: "Data Migrations & Schema"
location: "L70"
tags:
  - graphify/rationale
  - graphify/EXTRACTED
  - community/Data_Migrations_&_Schema
---

# Test that the new companies have been created successfully.

## Connections
- [[.test_company_objects()]] - `rationale_for` [EXTRACTED]
- [[StockHistoryCode]] - `uses` [INFERRED]
- [[TestScheduledForDeletionMigration]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/EXTRACTED #community/Data_Migrations_&_Schema