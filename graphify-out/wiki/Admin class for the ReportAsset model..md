---
source_file: "inventree/src/backend/InvenTree/report/admin.py"
type: "rationale"
community: "Stock Management & Tracking"
location: "L35"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Stock_Management_&_Tracking
---

# Admin class for the ReportAsset model.

## Connections
- [[.get_fields()]] - `rationale_for` [EXTRACTED]
- [[ApiToken]] - `uses` [INFERRED]
- [[DataImportSessionAdmin]] - `rationale_for` [EXTRACTED]
- [[LabelTemplate]] - `uses` [INFERRED]
- [[Owner]] - `uses` [INFERRED]
- [[ReportAsset]] - `uses` [INFERRED]
- [[ReportAssetAdmin]] - `rationale_for` [EXTRACTED]
- [[ReportSnippet]] - `uses` [INFERRED]
- [[ReportTemplate]] - `uses` [INFERRED]
- [[RuleSet]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Stock_Management_&_Tracking