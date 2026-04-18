---
source_file: "inventree/src/backend/InvenTree/order/test_sales_order.py"
type: "rationale"
community: "System Configuration & Settings"
location: "L340"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/System_Configuration_&_Settings
---

# Test completion of a shipment with many items.          Here, we create a shipme

## Connections
- [[.test_shipment_many_items()]] - `rationale_for` [EXTRACTED]
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