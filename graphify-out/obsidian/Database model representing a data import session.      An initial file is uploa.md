---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/importer/models.py"
type: "rationale"
community: "Community 4"
location: "L30"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_4
---

# Database model representing a data import session.      An initial file is uploa

## Connections
- [[DataImportSession]] - `rationale_for` [EXTRACTED]
- [[DataImportStatusCode]] - `uses` [INFERRED]
- [[InvenTreeMetadata]] - `uses` [INFERRED]
- [[RenderChoices_1]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Community_4