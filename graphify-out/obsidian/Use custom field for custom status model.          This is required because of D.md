---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/generic/states/fields.py"
type: "rationale"
community: "Community 11"
location: "L260"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_11
---

# Use custom field for custom status model.          This is required because of D

## Connections
- [[.build_standard_field()]] - `rationale_for` [EXTRACTED]
- [[CustomStatusCodeValidator]] - `uses` [INFERRED]
- [[InvenTreeCustomUserStateModel]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Community_11