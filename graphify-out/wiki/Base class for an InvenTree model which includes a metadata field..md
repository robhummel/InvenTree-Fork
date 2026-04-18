---
source_file: "inventree/src/backend/InvenTree/InvenTree/models.py"
type: "rationale"
community: "Part Management & Archetypes"
location: "L481"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Part_Management_&_Archetypes
---

# Base class for an InvenTree model which includes a metadata field.

## Connections
- [[Attachment]] - `uses` [INFERRED]
- [[InvenTreeMetadataModel]] - `rationale_for` [EXTRACTED]
- [[InvenTreeUINotifications]] - `uses` [INFERRED]
- [[NotesImage]] - `uses` [INFERRED]
- [[PluginMixinEnum]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Part_Management_&_Archetypes