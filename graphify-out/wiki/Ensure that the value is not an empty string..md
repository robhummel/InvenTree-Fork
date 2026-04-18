---
source_file: "inventree/src/backend/InvenTree/generic/states/fields.py"
type: "rationale"
community: "Part Management & Archetypes"
location: "L131"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Part_Management_&_Archetypes
---

# Ensure that the value is not an empty string.

## Connections
- [[.clean()_12]] - `rationale_for` [EXTRACTED]
- [[CustomStatusCodeValidator]] - `uses` [INFERRED]
- [[InvenTreeCustomUserStateModel]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Part_Management_&_Archetypes