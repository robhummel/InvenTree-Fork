---
source_file: "inventree/src/backend/InvenTree/plugin/base/supplier/api.py"
type: "rationale"
community: "Community 2"
location: "L125"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_2
---

# Import a part by supplier.      - POST: Attempt to import part by sku

## Connections
- [[ImportPart]] - `rationale_for` [EXTRACTED]
- [[ImportRequestSerializer]] - `uses` [INFERRED]
- [[ImportResultSerializer]] - `uses` [INFERRED]
- [[PartCategoryParameterTemplate]] - `uses` [INFERRED]
- [[PluginMixinEnum]] - `uses` [INFERRED]
- [[SearchResultSerializer]] - `uses` [INFERRED]
- [[SupplierListSerializer]] - `uses` [INFERRED]
- [[SupplierMixin_1]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Community_2