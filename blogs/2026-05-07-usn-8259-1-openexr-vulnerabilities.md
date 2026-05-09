---
title: "USN-8259-1: OpenEXR vulnerabilities"
url: "https://ubuntu.com/security/notices/USN-8259-1"
date: "2026-05-07"
author: ""
feed_url: "https://ubuntu.com/security/notices/rss.xml"
---
Quang Luong discovered that OpenEXR incorrectly handled sample count accumulation when processing deep scan line image files. An attacker could possibly use this issue to cause OpenEXR to crash, resulting in a denial of service, or execute arbitrary code. (CVE-2026-27622) It was discovered that OpenEXR had an integer overflow in the PXR24 decoder. An attacker could possibly use this issue to cause OpenEXR to crash, resulting in a denial of service, or execute arbitrary code. This issue only affected Ubuntu 24.04 LTS and Ubuntu 26.04 LTS.
