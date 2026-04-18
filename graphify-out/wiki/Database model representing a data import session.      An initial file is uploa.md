---
source_file: "inventree/src/backend/InvenTree/importer/models.py"
type: "rationale"
community: "Community 2"
location: "L30"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_2
---

# Database model representing a data import session.      An initial file is uploa

## Connections
- [[DataImportSession]] - `rationale_for` [EXTRACTED]
- [[DataImportStatusCode]] - `uses` [INFERRED]
- [[InvenTreeMetadata]] - `uses` [INFERRED]
- [[RenderChoices_1]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Community_2