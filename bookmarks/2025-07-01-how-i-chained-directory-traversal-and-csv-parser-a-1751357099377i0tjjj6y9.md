---
id: 1751357099377i0tjjj6y9
title: "How I Chained Directory Traversal and CSV Parser Abuse for RCE in a Django App"
url: https://jineeshak.github.io/posts/Chaining-Directory-Traversal-and-CSV-Parser-Abuse-for-RCE-in-Django/
tags: ["bugbounty", "writeup", "security"]
created: 2025-07-01T08:04:59.365Z
updated: 2025-07-01T08:05:01.631Z
---
While testing a web application as part of a bug bounty program, I uncovered a critical RCE vulnerability by chaining directory traversal with a subtle CSV parsing abuse. The exploit chain involved a combination of directory traversal and subtle abuse of how the application used the pandas CSV parser, ultimately allowing me to overwrite the wsgi.py file and execute arbitrary code server-side.
