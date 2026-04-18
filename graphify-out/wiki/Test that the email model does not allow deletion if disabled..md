---
source_file: "inventree/src/backend/InvenTree/common/test_emails.py"
type: "rationale"
community: "Part Management & Archetypes"
location: "L136"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Part_Management_&_Archetypes
---

# Test that the email model does not allow deletion if disabled.

## Connections
- [[.test_email_model_delete()]] - `rationale_for` [EXTRACTED]
- [[EmailMessage]] - `uses` [INFERRED]
- [[InvenTreeAPITestCase_1]] - `uses` [INFERRED]
- [[Priority]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Part_Management_&_Archetypes