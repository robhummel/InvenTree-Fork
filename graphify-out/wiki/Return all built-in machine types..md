---
source_file: "inventree/src/backend/InvenTree/plugin/builtin/integration/machine_types.py"
type: "rationale"
community: "Community 2"
location: "L21"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_2
---

# Return all built-in machine types.

## Connections
- [[.get_machine_types()]] - `rationale_for` [EXTRACTED]
- [[BaseDriver]] - `uses` [INFERRED]
- [[BaseMachineType]] - `uses` [INFERRED]
- [[InvenTreePlugin]] - `uses` [INFERRED]
- [[LabelPrinterMachine]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Community_2