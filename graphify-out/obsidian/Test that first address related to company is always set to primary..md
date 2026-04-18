---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/company/tests.py"
type: "rationale"
community: "Community 3"
location: "L219"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_3
---

# Test that first address related to company is always set to primary.

## Connections
- [[.test_first_address_is_primary()]] - `rationale_for` [EXTRACTED]
- [[Company]] - `uses` [INFERRED]
- [[Contact]] - `uses` [INFERRED]
- [[ManufacturerPart]] - `uses` [INFERRED]
- [[Part]] - `uses` [INFERRED]
- [[SupplierPart]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Community_3