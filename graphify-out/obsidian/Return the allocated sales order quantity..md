---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/part/serializers.py"
type: "rationale"
community: "Community 5"
location: "L1231"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_5
---

# Return the allocated sales order quantity.

## Connections
- [[.get_allocated_to_sales_orders()]] - `rationale_for` [EXTRACTED]
- [[BomItem]] - `uses` [INFERRED]
- [[BomItemSubstitute]] - `uses` [INFERRED]
- [[DataExportSerializerMixin]] - `uses` [INFERRED]
- [[DataImportExportSerializerMixin_1]] - `uses` [INFERRED]
- [[OptionalField]] - `uses` [INFERRED]
- [[Part]] - `uses` [INFERRED]
- [[PartCategory]] - `uses` [INFERRED]
- [[PartCategoryParameterTemplate]] - `uses` [INFERRED]
- [[PartInternalPriceBreak]] - `uses` [INFERRED]
- [[PartPricing]] - `uses` [INFERRED]
- [[PartRelated]] - `uses` [INFERRED]
- [[PartSellPriceBreak]] - `uses` [INFERRED]
- [[PartStar]] - `uses` [INFERRED]
- [[PartStocktake]] - `uses` [INFERRED]
- [[PartTestTemplate]] - `uses` [INFERRED]
- [[TreePathSerializer]] - `uses` [INFERRED]
- [[UserSerializer]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Community_5