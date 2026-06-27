---
title: "USN-8476-1: xrdp vulnerabilities"
url: "https://ubuntu.com/security/notices/USN-8476-1"
date: "2026-06-25"
feed_url: "https://ubuntu.com/security/notices/rss.xml"
---
It was discovered that xrdp incorrectly handled bounds checking when processing user domain information during the connection sequence. An unauthenticated remote attacker could use this issue to cause xrdp to crash, resulting in a denial of service, or possibly execute arbitrary code. (CVE-2025-68670) It was discovered that xrdp did not correctly enforce the maximum number of login attempts configured by the MaxLoginRetry parameter.
