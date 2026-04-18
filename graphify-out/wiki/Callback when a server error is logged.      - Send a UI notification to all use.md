---
source_file: "inventree/src/backend/InvenTree/InvenTree/models.py"
type: "rationale"
community: "Part Management & Archetypes"
location: "L1434"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Part_Management_&_Archetypes
---

# Callback when a server error is logged.      - Send a UI notification to all use

## Connections
- [[Attachment]] - `uses` [INFERRED]
- [[InvenTreeUINotifications]] - `uses` [INFERRED]
- [[NotesImage]] - `uses` [INFERRED]
- [[PluginMixinEnum]] - `uses` [INFERRED]
- [[after_error_logged()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Part_Management_&_Archetypes