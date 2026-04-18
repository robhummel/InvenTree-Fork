---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/stock/serializers.py"
type: "rationale"
community: "Community 5"
location: "L1687"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_5
---

# Base class for managing stock adjustment actions via the API.

## Connections
- [[DataImportExportSerializerMixin_1]] - `uses` [INFERRED]
- [[InvenTreeCurrencySerializer]] - `uses` [INFERRED]
- [[InvenTreeCustomStatusSerializerMixin_1]] - `uses` [INFERRED]
- [[InvenTreeDecimalField]] - `uses` [INFERRED]
- [[OptionalField]] - `uses` [INFERRED]
- [[StockAdjustmentSerializer]] - `rationale_for` [EXTRACTED]
- [[StockItem]] - `uses` [INFERRED]
- [[StockItemTestResult]] - `uses` [INFERRED]
- [[StockItemTracking]] - `uses` [INFERRED]
- [[StockLocation]] - `uses` [INFERRED]
- [[StockLocationType]] - `uses` [INFERRED]
- [[TreePathSerializer]] - `uses` [INFERRED]
- [[UserSerializer]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Community_5