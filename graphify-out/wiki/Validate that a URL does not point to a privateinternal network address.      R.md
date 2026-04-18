---
source_file: "inventree/src/backend/InvenTree/InvenTree/helpers_model.py"
type: "rationale"
community: "Data Migrations & Schema"
location: "L94"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Data_Migrations_&_Schema
---

# Validate that a URL does not point to a private/internal network address.      R

## Connections
- [[InvenTreeNotificationBodies]] - `uses` [INFERRED]
- [[NotificationBody]] - `uses` [INFERRED]
- [[validate_url_no_ssrf()]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/INFERRED #community/Data_Migrations_&_Schema