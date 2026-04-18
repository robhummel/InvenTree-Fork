---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/part/tasks.py"
type: "rationale"
community: "Community 5"
location: "L32"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_5
---

# Notify interested users that a part is 'low stock'.      Rules:     - Triggered

## Connections
- [[Part]] - `uses` [INFERRED]
- [[PartPricing]] - `uses` [INFERRED]
- [[PartStocktake]] - `uses` [INFERRED]
- [[RuleSet]] - `uses` [INFERRED]
- [[ScheduledTask]] - `uses` [INFERRED]
- [[StockItem]] - `uses` [INFERRED]
- [[SupplierPart]] - `uses` [INFERRED]
- [[notify_low_stock()]] - `rationale_for` [EXTRACTED]
- [[update_group_roles()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Community_5