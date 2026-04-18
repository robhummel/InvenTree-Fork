---
source_file: "inventree/src/backend/InvenTree/order/models.py"
type: "code"
community: "System Configuration & Settings"
location: "L1749"
tags:
  - graphify/code
  - graphify/INFERRED
  - community/System_Configuration_&_Settings
---

# OrderLineItem

## Connections
- [[.delete()]] - `method` [EXTRACTED]
- [[.save()_2]] - `method` [EXTRACTED]
- [[Abstract model for an order line item.      Attributes         quantity Number]] - `rationale_for` [EXTRACTED]
- [[Company]] - `uses` [INFERRED]
- [[Contact]] - `uses` [INFERRED]
- [[InvenTreeCustomStatusModelField]] - `uses` [INFERRED]
- [[InvenTreeModelMoneyField]] - `uses` [INFERRED]
- [[InvenTreeNotificationBodies]] - `uses` [INFERRED]
- [[InvenTreeURLField]] - `uses` [INFERRED]
- [[OrderExtraLine]] - `inherits` [EXTRACTED]
- [[PurchaseOrderEvents]] - `uses` [INFERRED]
- [[PurchaseOrderLineItem]] - `inherits` [EXTRACTED]
- [[PurchaseOrderStatus]] - `uses` [INFERRED]
- [[PurchaseOrderStatusGroups]] - `uses` [INFERRED]
- [[ReturnOrderEvents]] - `uses` [INFERRED]
- [[ReturnOrderLineItem]] - `inherits` [EXTRACTED]
- [[ReturnOrderLineStatus]] - `uses` [INFERRED]
- [[ReturnOrderStatus]] - `uses` [INFERRED]
- [[ReturnOrderStatusGroups]] - `uses` [INFERRED]
- [[RoundingDecimalField]] - `uses` [INFERRED]
- [[SalesOrderEvents]] - `uses` [INFERRED]
- [[SalesOrderLineItem]] - `inherits` [EXTRACTED]
- [[SalesOrderStatus]] - `uses` [INFERRED]
- [[SalesOrderStatusGroups]] - `uses` [INFERRED]
- [[StatusCodeMixin_1]] - `uses` [INFERRED]
- [[StockHistoryCode]] - `uses` [INFERRED]
- [[StockStatus]] - `uses` [INFERRED]
- [[SupplierPart]] - `uses` [INFERRED]
- [[models.py]] - `contains` [EXTRACTED]

#graphify/code #graphify/INFERRED #community/System_Configuration_&_Settings