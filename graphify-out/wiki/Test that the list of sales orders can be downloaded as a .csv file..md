---
source_file: "inventree/src/backend/InvenTree/order/test_api.py"
type: "rationale"
community: "System Configuration & Settings"
location: "L2073"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/System_Configuration_&_Settings
---

# Test that the list of sales orders can be downloaded as a .csv file.

## Connections
- [[.test_download_csv()_1]] - `rationale_for` [EXTRACTED]
- [[Company]] - `uses` [INFERRED]
- [[InvenTreeAPITestCase_1]] - `uses` [INFERRED]
- [[InvenTreeSetting]] - `uses` [INFERRED]
- [[Owner]] - `uses` [INFERRED]
- [[Parameter]] - `uses` [INFERRED]
- [[ParameterTemplate]] - `uses` [INFERRED]
- [[Part]] - `uses` [INFERRED]
- [[PurchaseOrderStatus]] - `uses` [INFERRED]
- [[ReturnOrderLineStatus]] - `uses` [INFERRED]
- [[ReturnOrderStatus]] - `uses` [INFERRED]
- [[SalesOrderStatus]] - `uses` [INFERRED]
- [[SalesOrderStatusGroups]] - `uses` [INFERRED]
- [[StockItem]] - `uses` [INFERRED]
- [[StockLocation]] - `uses` [INFERRED]
- [[StockStatus]] - `uses` [INFERRED]
- [[SupplierPart]] - `uses` [INFERRED]
- [[SupplierPriceBreak]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/System_Configuration_&_Settings