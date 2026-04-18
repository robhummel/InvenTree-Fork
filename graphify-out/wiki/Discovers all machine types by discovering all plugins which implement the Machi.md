---
source_file: "inventree/src/backend/InvenTree/machine/registry.py"
type: "rationale"
community: "Community 2"
location: "L138"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_2
---

# Discovers all machine types by discovering all plugins which implement the Machi

## Connections
- [[.discover_machine_types()]] - `rationale_for` [EXTRACTED]
- [[BaseDriver]] - `uses` [INFERRED]
- [[BaseMachineType]] - `uses` [INFERRED]
- [[MachineConfig]] - `uses` [INFERRED]
- [[PluginMixinEnum]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Community_2