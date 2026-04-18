---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/part/test_migrations.py"
type: "rationale"
community: "Community 7"
location: "L120"
tags:
  - graphify/rationale
  - graphify/EXTRACTED
  - community/Community_7
---

# Test that the template units and values have been updated correctly.

## Connections
- [[.test_data_migration()]] - `rationale_for` [EXTRACTED]
- [[.test_shipment_creation()]] - `rationale_for` [EXTRACTED]
- [[SalesOrderStatus]] - `uses` [INFERRED]

#graphify/rationale #graphify/EXTRACTED #community/Community_7