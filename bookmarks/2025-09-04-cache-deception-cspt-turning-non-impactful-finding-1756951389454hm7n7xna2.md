---
id: 1756951389454hm7n7xna2
title: "Cache Deception + CSPT: Turning Non Impactful Findings into Account Takeover"
url: https://zere.es/posts/cache-deception-cspt-account-takeover/?utm_source=blog.criticalthinkingpodcast.io&utm_medium=newsletter&utm_campaign=hackernotes-ep-137-how-we-do-ai-assisted-whitebox-review-new-cspt
tags: ["cspt", "cache-deception", "account-takeover", "bug-bounty"]
createdAt: 2025-09-04T02:03:09.443Z
updatedAt: 2025-09-04T02:03:11.335Z
---Recently, while auditing the main application of a private bug bounty program, I discovered a Client-Side Path Traversal (CSPT) and a Cache Deception vulnerability. Individually, these issues were unexploitable and had no real impact. However, when chained together, I was able to demonstrate Account Takeover.
