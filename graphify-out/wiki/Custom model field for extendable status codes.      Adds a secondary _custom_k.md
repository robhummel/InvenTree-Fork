---
source_file: "inventree/src/backend/InvenTree/generic/states/fields.py"
type: "rationale"
community: "Part Management & Archetypes"
location: "L93"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Part_Management_&_Archetypes
---

# Custom model field for extendable status codes.      Adds a secondary *_custom_k

## Connections
- [[CustomStatusCodeValidator]] - `uses` [INFERRED]
- [[InvenTreeCustomStatusModelField]] - `rationale_for` [EXTRACTED]
- [[InvenTreeCustomUserStateModel]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Part_Management_&_Archetypes