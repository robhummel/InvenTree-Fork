---
source_file: "inventree/src/backend/InvenTree/part/test_category.py"
type: "rationale"
community: "Data Migrations & Schema"
location: "L158"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Data_Migrations_&_Schema
---

# Test that the Category parameters are correctly fetched.

## Connections
- [[.test_parameters()]] - `rationale_for` [EXTRACTED]
- [[InvenTreeSetting]] - `uses` [INFERRED]
- [[Parameter]] - `uses` [INFERRED]
- [[ParameterTemplate]] - `uses` [INFERRED]
- [[Part]] - `uses` [INFERRED]
- [[PartCategory]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Data_Migrations_&_Schema