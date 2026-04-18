---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/plugin/base/barcodes/serializers.py"
type: "rationale"
community: "Community 3"
location: "L59"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_3
---

# Serializer for generating a barcode.

## Connections
- [[BarcodeGenerateSerializer]] - `rationale_for` [EXTRACTED]
- [[PurchaseOrderStatus]] - `uses` [INFERRED]
- [[PurchaseOrderStatusGroups]] - `uses` [INFERRED]
- [[SalesOrderStatusGroups]] - `uses` [INFERRED]
- [[UserSerializer]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Community_3