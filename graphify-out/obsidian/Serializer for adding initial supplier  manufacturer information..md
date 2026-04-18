---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/part/serializers.py"
type: "rationale"
community: "Community 5"
location: "L466"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_5
---

# Serializer for adding initial supplier / manufacturer information.

## Connections
- [[BomItem]] - `uses` [INFERRED]
- [[BomItemSubstitute]] - `uses` [INFERRED]
- [[ContentTypeField]] - `uses` [INFERRED]
- [[ContentTypeSerializer]] - `rationale_for` [EXTRACTED]
- [[DataExportSerializerMixin]] - `uses` [INFERRED]
- [[DataImportExportSerializerMixin_1]] - `uses` [INFERRED]
- [[FilterableSerializerMixin_1]] - `uses` [INFERRED]
- [[InitialSupplierSerializer]] - `rationale_for` [EXTRACTED]
- [[InvenTreeAttachmentMixin]] - `uses` [INFERRED]
- [[InvenTreeAttachmentSerializerField]] - `uses` [INFERRED]
- [[InvenTreeImageSerializerField]] - `uses` [INFERRED]
- [[InvenTreeModelSerializer_1]] - `uses` [INFERRED]
- [[InvenTreeParameterMixin]] - `uses` [INFERRED]
- [[OptionalField]] - `uses` [INFERRED]
- [[OwnerSerializer]] - `uses` [INFERRED]
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