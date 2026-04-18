---
source_file: "inventree/src/backend/InvenTree/generic/states/fields.py"
type: "rationale"
community: "Part Management & Archetypes"
location: "L260"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Part_Management_&_Archetypes
---

# Use custom field for custom status model.          This is required because of D

## Connections
- [[.build_standard_field()]] - `rationale_for` [EXTRACTED]
- [[CustomStatusCodeValidator]] - `uses` [INFERRED]
- [[InvenTreeCustomUserStateModel]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Part_Management_&_Archetypes