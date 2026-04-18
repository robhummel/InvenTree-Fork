---
source_file: "inventree/src/backend/InvenTree/data_exporter/mixins.py"
type: "rationale"
community: "Stock Management & Tracking"
location: "L226"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Stock_Management_&_Tracking
---

# Determine if the view is currently exporting data.

## Connections
- [[.is_exporting()]] - `rationale_for` [EXTRACTED]
- [[DataOutput]] - `uses` [INFERRED]
- [[DataOutputSerializer]] - `uses` [INFERRED]
- [[PluginMixinEnum]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Stock_Management_&_Tracking