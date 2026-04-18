---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/common/settings.py"
type: "rationale"
community: "Core Models & Admin"
location: "L128"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Core_Models_&_Admin
---

# Returns True if the stock expiry feature is enabled.

## Connections
- [[InvenTreeSetting]] - `uses` [INFERRED]
- [[SystemSetId]] - `uses` [INFERRED]
- [[stock_expiry_enabled()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Core_Models_&_Admin