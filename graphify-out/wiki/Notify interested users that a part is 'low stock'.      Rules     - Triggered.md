---
source_file: "inventree/src/backend/InvenTree/part/tasks.py"
type: "rationale"
community: "Documentation & FAQ"
location: "L32"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Documentation_&_FAQ
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
- [[is_true()]] - `rationale_for` [EXTRACTED]
- [[notify_low_stock()]] - `rationale_for` [EXTRACTED]
- [[update_group_roles()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Documentation_&_FAQ