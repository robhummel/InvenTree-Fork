---
source_file: "inventree/src/backend/InvenTree/InvenTree/models.py"
type: "rationale"
community: "Part Management & Archetypes"
location: "L693"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Part_Management_&_Archetypes
---

# Provides an abstracted self-referencing tree model, based on the MPTTModel class

## Connections
- [[Attachment]] - `uses` [INFERRED]
- [[InvenTreeTree]] - `rationale_for` [EXTRACTED]
- [[InvenTreeUINotifications]] - `uses` [INFERRED]
- [[NotesImage]] - `uses` [INFERRED]
- [[PluginMixinEnum]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Part_Management_&_Archetypes