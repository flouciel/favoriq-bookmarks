---
id: 1751423830826xemo7t6pc
title: Guest Post: How I Scanned all of GitHub’s “Oops Commits” for Leaked Secrets ◆
  Truffle Security Co.
url: https://trufflesecurity.com/blog/guest-post-how-i-scanned-all-of-github-s-oops-commits-for-leaked-secrets
tags: ["blog", "articles", "security", "secret"]
created: 2025-07-02T02:37:10.813Z
updated: 2025-07-02T02:37:12.245Z
previewImagePath: assets/previews/1751423830826xemo7t6pc.webp
---
GitHub Archive logs every public commit, even the ones developers try to delete. Force pushes often cover up mistakes like leaked credentials by rewriting Git history. GitHub keeps these dangling commits, from what we can tell, forever. In the archive, they show up as “zero-commit” PushEvents.
