---
title: "glide.db.soft_join_cap"
description: "Property"
---

Description: Maximum number of database joins per query. Smaller values cause the system to issue a larger number of less complex queries. Larger values reduce the number of queries at the cost of additional complexity per query. In the absence of known database issues stemming from large join counts, this property should remain unchanged.

Value: `10`