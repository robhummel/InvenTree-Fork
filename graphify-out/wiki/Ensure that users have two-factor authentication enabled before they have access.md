---
source_file: "inventree/src/backend/InvenTree/InvenTree/middleware.py"
type: "rationale"
community: "Community 11"
location: "L177"
tags:
  - graphify/rationale
  - graphify/EXTRACTED
  - community/Community_11
---

# Ensure that users have two-factor authentication enabled before they have access

## Connections
- [[ApiToken]] - `uses` [INFERRED]
- [[Check2FAMiddleware]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/EXTRACTED #community/Community_11