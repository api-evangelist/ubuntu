---
title: "USN-8726-2: Linux kernel (Raspberry Pi) vulnerabilities"
url: "https://ubuntu.com/security/notices/USN-8726-2"
date: "2026-09-18"
feed_url: "https://ubuntu.com/security/notices/rss.xml"
---
It was discovered that some Arm processors could complete a broadcast translation lookaside buffer (TLB) invalidation before memory writes made through the invalidated translation were globally observed. A local attacker could possibly use this to write to memory after permission to do so had been revoked, bypassing memory protections or escalating privileges. (CVE-2025-10263) Several security issues were discovered in the Linux kernel.
