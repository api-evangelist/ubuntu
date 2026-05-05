---
title: "USN-8225-1: Python marshmallow vulnerabilities"
url: "https://ubuntu.com/security/notices/USN-8225-1"
date: "Thu, 30 Apr 2026 02:19:38 +0000"
author: ""
feed_url: "https://ubuntu.com/security/notices/rss.xml"
---
Jared Deckard discovered that Python marshmallow did not correctly
handle hiding certain fields. An attacker could possibly use this issue
to leak sensitive information. This issue only affected Ubuntu 18.04 LTS.
(CVE-2018-17175)

It was discovered that Python marshmallow did not efficiently handle
merging certain objects. An attacker could possibly use this issue to
cause a denial of service. This issue only affected Ubuntu 20.04 LTS,
Ubuntu 22.04 LTS, Ubuntu 24.04 LTS and Ubuntu 26.04 LTS. (CVE-2025-68480)
