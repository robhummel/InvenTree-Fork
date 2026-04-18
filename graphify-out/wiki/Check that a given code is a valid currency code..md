---
source_file: "inventree/src/backend/InvenTree/InvenTree/validators.py"
type: "rationale"
community: "Data Migrations & Schema"
location: "L32"
tags:
  - graphify/rationale
  - graphify/EXTRACTED
  - community/Data_Migrations_&_Schema
---

# Check that a given code is a valid currency code.

## Connections
- [[PurchaseOrder]] - `uses` [INFERRED]
- [[SalesOrder]] - `uses` [INFERRED]
- [[parameter_template_model_options()]] - `rationale_for` [EXTRACTED]
- [[validate_currency_code()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/EXTRACTED #community/Data_Migrations_&_Schema