---
source_file: "inventree/src/backend/InvenTree/InvenTree/models.py"
type: "rationale"
community: "Part Management & Archetypes"
location: "L260"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Part_Management_&_Archetypes
---

# Metaclass options. Abstract ensures no database table is created.

## Connections
- [[.activate()]] - `rationale_for` [EXTRACTED]
- [[Attachment]] - `uses` [INFERRED]
- [[InvenTreePlugin]] - `uses` [INFERRED]
- [[InvenTreeUINotifications]] - `uses` [INFERRED]
- [[Meta]] - `rationale_for` [EXTRACTED]
- [[NotesImage]] - `uses` [INFERRED]
- [[PluginEvents]] - `uses` [INFERRED]
- [[PluginMixinEnum]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Part_Management_&_Archetypes