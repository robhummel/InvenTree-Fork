---
source_file: "/Users/Rob/Services/inventree-source/inventree/src/backend/InvenTree/common/test_tasks.py"
type: "rationale"
community: "Community 4"
location: "L67"
tags:
  - graphify/rationale
  - graphify/INFERRED
  - community/Community_4
---

# Test that no call is made to news feed if URL setting is invalid.

## Connections
- [[.test_unset_url()]] - `rationale_for` [EXTRACTED]
- [[NewsFeedEntry]] - `uses` [INFERRED]
- [[NotificationEntry]] - `uses` [INFERRED]

#graphify/rationale #graphify/INFERRED #community/Community_4