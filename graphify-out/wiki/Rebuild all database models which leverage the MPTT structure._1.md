---
source_file: "inventree/src/backend/InvenTree/InvenTree/management/commands/rebuild_models.py"
type: "rationale"
community: "Documentation & FAQ"
location: "L18"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Documentation_&_FAQ
---

# Rebuild all database models which leverage the MPTT structure.

## Connections
- [[.handle()_8]] - `rationale_for` [EXTRACTED]
- [[Part]] - `uses` [INFERRED]
- [[PartCategory]] - `uses` [INFERRED]
- [[StockItem]] - `uses` [INFERRED]
- [[StockLocation]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Documentation_&_FAQ