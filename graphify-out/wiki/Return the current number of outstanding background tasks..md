---
source_file: "inventree/src/backend/InvenTree/InvenTree/api.py"
type: "rationale"
community: "Stock Management & Tracking"
location: "L276"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Stock_Management_&_Tracking
---

# Return the current number of outstanding background tasks.

## Connections
- [[.handle_barcode()_2]] - `rationale_for` [EXTRACTED]
- [[.print()_3]] - `rationale_for` [EXTRACTED]
- [[.worker_pending_tasks()]] - `rationale_for` [EXTRACTED]
- [[ApiToken]] - `uses` [INFERRED]
- [[BarcodeScanResult]] - `uses` [INFERRED]
- [[BulkDeleteMixin_1]] - `uses` [INFERRED]
- [[DataOutput]] - `uses` [INFERRED]
- [[DataOutputSerializer]] - `uses` [INFERRED]
- [[InvenTreeLabelPlugin]] - `uses` [INFERRED]
- [[InvenTreeSearchFilter]] - `uses` [INFERRED]
- [[ListAPI_1]] - `uses` [INFERRED]
- [[ListCreateAPI_1]] - `uses` [INFERRED]
- [[MetadataSerializer]] - `uses` [INFERRED]
- [[PluginMixinEnum]] - `uses` [INFERRED]
- [[RetrieveDestroyAPI_1]] - `uses` [INFERRED]
- [[RetrieveUpdateAPI_1]] - `uses` [INFERRED]
- [[RetrieveUpdateDestroyAPI_1]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Stock_Management_&_Tracking