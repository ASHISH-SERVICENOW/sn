---
title: "sn_communities.enable_session_cache"
description: "Property"
---

Description: This flag is used to decide whether to use the session caching for the Community Application.
If the flag is true: The permissions of any non-admin users of the community will be stored as a part of the user's session and this value will be used to compute/determine the user's access to the various forums and community artifacts. While the user is active with that particular session, any changes to the community permissions will not take effect until the user logs out. Keep this flag set to 'true' if the system is not altered too soon in terms of permissions AND / OR there are significant performance concerns with the general load time of the various pages of the community. The cost of recomputation of the permissions is minimized here.
If the flag is false: The session cache is not utilized to store the permissions, and every request will initiate the user permission computation. However, the data will always be accurate.

Value: `false`