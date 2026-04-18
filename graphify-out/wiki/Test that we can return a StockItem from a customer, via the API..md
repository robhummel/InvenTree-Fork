---
source_file: "inventree/src/backend/InvenTree/stock/test_api.py"
type: "rationale"
community: "Documentation & FAQ"
location: "L1804"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Documentation_&_FAQ
---

# Test that we can return a StockItem from a customer, via the API.

## Connections
- [[.test_duplicates()]] - `rationale_for` [EXTRACTED]
- [[.test_return_from_customer()]] - `rationale_for` [EXTRACTED]
- [[BomItem]] - `uses` [INFERRED]
- [[BomItemSubstitute]] - `uses` [INFERRED]
- [[Company]] - `uses` [INFERRED]
- [[InvenTreeAPIPerformanceTestCase_1]] - `uses` [INFERRED]
- [[InvenTreeAPITestCase_1]] - `uses` [INFERRED]
- [[InvenTreeCustomUserStateModel]] - `uses` [INFERRED]
- [[InvenTreeSetting]] - `uses` [INFERRED]
- [[ParameterTemplate]] - `uses` [INFERRED]
- [[Part]] - `uses` [INFERRED]
- [[PartCategory]] - `uses` [INFERRED]
- [[PartCategoryParameterTemplate]] - `uses` [INFERRED]
- [[PartRelated]] - `uses` [INFERRED]
- [[PartSellPriceBreak]] - `uses` [INFERRED]
- [[PartTestTemplate]] - `uses` [INFERRED]
- [[PurchaseOrderStatusGroups]] - `uses` [INFERRED]
- [[StockHistoryCode]] - `uses` [INFERRED]
- [[StockItem]] - `uses` [INFERRED]
- [[StockItemTestResult]] - `uses` [INFERRED]
- [[StockItemTracking]] - `uses` [INFERRED]
- [[StockLocation]] - `uses` [INFERRED]
- [[StockLocationType]] - `uses` [INFERRED]
- [[StockStatus]] - `uses` [INFERRED]
- [[SupplierPart]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Documentation_&_FAQ