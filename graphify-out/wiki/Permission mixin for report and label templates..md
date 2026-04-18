---
source_file: "inventree/src/backend/InvenTree/report/api.py"
type: "rationale"
community: "Stock Management & Tracking"
location: "L29"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Stock_Management_&_Tracking
---

# Permission mixin for report and label templates.

## Connections
- [[.get_serializer_class()]] - `rationale_for` [EXTRACTED]
- [[BulkDeleteMixin_1]] - `uses` [INFERRED]
- [[CreateAPI_1]] - `uses` [INFERRED]
- [[DataImporterPermissionMixin]] - `rationale_for` [EXTRACTED]
- [[DataOutput]] - `uses` [INFERRED]
- [[DataOutputSerializer]] - `uses` [INFERRED]
- [[InvenTreeLabelPlugin]] - `uses` [INFERRED]
- [[InvenTreeSearchFilter]] - `uses` [INFERRED]
- [[ListAPI_1]] - `uses` [INFERRED]
- [[ListCreateAPI_1]] - `uses` [INFERRED]
- [[LocatePluginView]] - `rationale_for` [EXTRACTED]
- [[MachineConfig]] - `uses` [INFERRED]
- [[MachineSetting]] - `uses` [INFERRED]
- [[PluginMixinEnum]] - `uses` [INFERRED]
- [[RetrieveUpdateAPI_1]] - `uses` [INFERRED]
- [[RetrieveUpdateDestroyAPI_1]] - `uses` [INFERRED]
- [[StockItem]] - `uses` [INFERRED]
- [[StockLocation]] - `uses` [INFERRED]
- [[TemplatePermissionMixin]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Stock_Management_&_Tracking