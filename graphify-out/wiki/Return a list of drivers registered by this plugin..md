---
source_file: "inventree/src/backend/InvenTree/plugin/samples/machines/sample_printer.py"
type: "rationale"
community: "Community 2"
location: "L82"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_2
---

# Return a list of drivers registered by this plugin.

## Connections
- [[.get_machine_drivers()]] - `rationale_for` [EXTRACTED]
- [[BaseDriver]] - `uses` [INFERRED]
- [[InvenTreePlugin]] - `uses` [INFERRED]
- [[LabelTemplate]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Community_2