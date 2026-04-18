---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/machine/registry.py"
type: "rationale"
community: "Community 1"
location: "L188"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_1
---

# Discovers all machine drivers by discovering all plugins which implement the Mac

## Connections
- [[.discover_drivers()]] - `rationale_for` [EXTRACTED]
- [[BaseDriver]] - `uses` [INFERRED]
- [[BaseMachineType]] - `uses` [INFERRED]
- [[MachineConfig]] - `uses` [INFERRED]
- [[PluginMixinEnum]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Community_1