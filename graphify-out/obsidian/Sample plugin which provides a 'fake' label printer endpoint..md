---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/plugin/samples/integration/label_sample.py"
type: "rationale"
community: "Community 1"
location: "L14"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_1
---

# Sample plugin which provides a 'fake' label printer endpoint.

## Connections
- [[InvenTreePlugin]] - `uses` [INFERRED]
- [[LabelPrintingMixin_1]] - `uses` [INFERRED]
- [[SampleLabelPrinter]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Community_1