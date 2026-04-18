---
source_file: "inventree/src/backend/InvenTree/company/test_migrations.py"
type: "rationale"
community: "Data Migrations & Schema"
location: "L188"
tags:
  - graphify/rationale
  - graphify/EXTRACTED
  - community/Data_Migrations_&_Schema
---

# Test that the new companies have been created successfully.

## Connections
- [[.test_manufacturer_part_objects()]] - `rationale_for` [EXTRACTED]
- [[.test_po_migration()]] - `rationale_for` [EXTRACTED]
- [[SalesOrderStatus]] - `uses` [INFERRED]

#graphify/rationale #graphify/EXTRACTED #community/Data_Migrations_&_Schema