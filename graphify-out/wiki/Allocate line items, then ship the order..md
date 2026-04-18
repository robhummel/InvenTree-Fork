---
source_file: "inventree/src/backend/InvenTree/order/test_sales_order.py"
type: "rationale"
community: "System Configuration & Settings"
location: "L251"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/System_Configuration_&_Settings
---

# Allocate line items, then ship the order.

## Connections
- [[.test_complete_order()]] - `rationale_for` [EXTRACTED]
- [[Company]] - `uses` [INFERRED]
- [[InvenTreeSetting]] - `uses` [INFERRED]
- [[InvenTreeTestCase_1]] - `uses` [INFERRED]
- [[NotificationMessage]] - `uses` [INFERRED]
- [[Owner]] - `uses` [INFERRED]
- [[Part]] - `uses` [INFERRED]
- [[SalesOrder]] - `uses` [INFERRED]
- [[SalesOrderAllocation]] - `uses` [INFERRED]
- [[SalesOrderExtraLine]] - `uses` [INFERRED]
- [[SalesOrderLineItem]] - `uses` [INFERRED]
- [[SalesOrderShipment]] - `uses` [INFERRED]
- [[StockItem]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/System_Configuration_&_Settings