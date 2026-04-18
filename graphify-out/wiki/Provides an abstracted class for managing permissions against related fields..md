---
source_file: "inventree/src/backend/InvenTree/InvenTree/models.py"
type: "rationale"
community: "Part Management & Archetypes"
location: "L490"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Part_Management_&_Archetypes
---

# Provides an abstracted class for managing permissions against related fields.

## Connections
- [[Attachment]] - `uses` [INFERRED]
- [[InvenTreePermissionCheckMixin]] - `rationale_for` [EXTRACTED]
- [[InvenTreeUINotifications]] - `uses` [INFERRED]
- [[NotesImage]] - `uses` [INFERRED]
- [[PluginMixinEnum]] - `uses` [INFERRED]
- [[UserProfile]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Part_Management_&_Archetypes