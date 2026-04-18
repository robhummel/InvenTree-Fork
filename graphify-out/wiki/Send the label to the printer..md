---
source_file: "inventree/src/backend/InvenTree/plugin/samples/machines/sample_printer.py"
type: "rationale"
community: "Community 2"
location: "L55"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_2
---

# Send the label to the printer.

## Connections
- [[.print_label()_1]] - `rationale_for` [EXTRACTED]
- [[BaseDriver]] - `uses` [INFERRED]
- [[InvenTreePlugin]] - `uses` [INFERRED]
- [[LabelTemplate]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Community_2