---
source_file: "inventree/src/backend/InvenTree/common/settings.py"
type: "rationale"
community: "Part Management & Archetypes"
location: "L128"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Part_Management_&_Archetypes
---

# Returns True if the stock expiry feature is enabled.

## Connections
- [[InvenTreeSetting]] - `uses` [INFERRED]
- [[SystemSetId]] - `uses` [INFERRED]
- [[stock_expiry_enabled()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Part_Management_&_Archetypes