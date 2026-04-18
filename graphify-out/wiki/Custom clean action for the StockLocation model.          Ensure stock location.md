---
source_file: "inventree/src/backend/InvenTree/stock/models.py"
type: "rationale"
community: "System Configuration & Settings"
location: "L289"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/System_Configuration_&_Settings
---

# Custom clean action for the StockLocation model.          Ensure stock location

## Connections
- [[.clean()_20]] - `rationale_for` [EXTRACTED]
- [[.trigger_data_import()]] - `rationale_for` [EXTRACTED]
- [[DataImportStatusCode]] - `uses` [INFERRED]
- [[InvenTreeCustomStatusModelField]] - `uses` [INFERRED]
- [[InvenTreeMetadata]] - `uses` [INFERRED]
- [[InvenTreeModelMoneyField]] - `uses` [INFERRED]
- [[InvenTreePlugin]] - `uses` [INFERRED]
- [[InvenTreeURLField]] - `uses` [INFERRED]
- [[Meta]] - `rationale_for` [EXTRACTED]
- [[Owner]] - `uses` [INFERRED]
- [[PluginEvents]] - `uses` [INFERRED]
- [[PluginMixinEnum]] - `uses` [INFERRED]
- [[RenderChoices_1]] - `uses` [INFERRED]
- [[SalesOrderStatusGroups]] - `uses` [INFERRED]
- [[StatusCodeMixin_1]] - `uses` [INFERRED]
- [[StockEvents]] - `uses` [INFERRED]
- [[StockHistoryCode]] - `uses` [INFERRED]
- [[StockStatus]] - `uses` [INFERRED]
- [[StockStatusGroups]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/System_Configuration_&_Settings