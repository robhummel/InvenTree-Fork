---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/InvenTree/management/commands/rebuild_models.py"
type: "rationale"
community: "Core Models & Admin"
location: "L15"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Core_Models_&_Admin
---

# Rebuild all database models which leverage the MPTT structure.

## Connections
- [[Command_8]] - `rationale_for` [EXTRACTED]
- [[Part]] - `uses` [INFERRED]
- [[PartCategory]] - `uses` [INFERRED]
- [[StockItem]] - `uses` [INFERRED]
- [[StockLocation]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Core_Models_&_Admin