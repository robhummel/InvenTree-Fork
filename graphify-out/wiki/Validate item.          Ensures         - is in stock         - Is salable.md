---
source_file: "inventree/src/backend/InvenTree/stock/serializers.py"
type: "rationale"
community: "Documentation & FAQ"
location: "L1353"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Documentation_&_FAQ
---

# Validate item.          Ensures:         - is in stock         - Is salable

## Connections
- [[.validate_item()]] - `rationale_for` [EXTRACTED]
- [[DataImportExportSerializerMixin_1]] - `uses` [INFERRED]
- [[InvenTreeCurrencySerializer]] - `uses` [INFERRED]
- [[InvenTreeCustomStatusSerializerMixin_1]] - `uses` [INFERRED]
- [[InvenTreeDecimalField]] - `uses` [INFERRED]
- [[OptionalField]] - `uses` [INFERRED]
- [[StockItem]] - `uses` [INFERRED]
- [[StockItemTestResult]] - `uses` [INFERRED]
- [[StockItemTracking]] - `uses` [INFERRED]
- [[StockLocation]] - `uses` [INFERRED]
- [[StockLocationType]] - `uses` [INFERRED]
- [[TreePathSerializer]] - `uses` [INFERRED]
- [[UserSerializer]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Documentation_&_FAQ