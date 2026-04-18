---
source_file: "inventree/src/backend/InvenTree/part/test_notification_stale.py"
type: "rationale"
community: "Part Management & Archetypes"
location: "L160"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Part_Management_&_Archetypes
---

# Test check_stale_stock when STOCK_STALE_DAYS is 0.

## Connections
- [[.test_check_stale_stock_zero_stale_days()]] - `rationale_for` [EXTRACTED]
- [[InvenTreeTestCase_1]] - `uses` [INFERRED]
- [[NotificationEntry]] - `uses` [INFERRED]
- [[NotificationMessage]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Part_Management_&_Archetypes