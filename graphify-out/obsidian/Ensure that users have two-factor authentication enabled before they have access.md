---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/InvenTree/middleware.py"
type: "rationale"
community: "Community 24"
location: "L177"
tags:
  - graphify/rationale
  - graphify/EXTRACTED
  - community/Community_24
---

# Ensure that users have two-factor authentication enabled before they have access

## Connections
- [[ApiToken]] - `uses` [INFERRED]
- [[Check2FAMiddleware]] - `rationale_for` [EXTRACTED]

#graphify/rationale #graphify/EXTRACTED #community/Community_24