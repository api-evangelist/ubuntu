---
title: "USN-8557-1: Authlib vulnerabilities"
url: "https://ubuntu.com/security/notices/USN-8557-1"
date: "2026-07-16"
feed_url: "https://ubuntu.com/security/notices/rss.xml"
---
Jay Neiva and Mauro Carrillo discovered that Authlib did not properly validate cryptographic keys embedded in JWT headers. An attacker could possibly use this issue to forge trusted tokens, resulting in authentication and authorization bypass. (CVE-2026-27962) Jay Neiva and Mauro Carrillo discovered that Authlib incorrectly handled RSA1_5 encrypted tokens.
