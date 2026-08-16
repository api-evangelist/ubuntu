---
title: "USN-8530-2: Linux kernel (HWE) vulnerabilities"
url: "https://ubuntu.com/security/notices/USN-8530-2"
date: "2026-08-13"
feed_url: "https://ubuntu.com/security/notices/rss.xml"
---
It was discovered that the Linux kernel did not properly handle shared page fragments during socket buffer operations, collectively known as Dirty Frag. A logic flaw existed in the XFRM ESP-in-TCP subsystem and in the RxRPC networking subsystem when processing paged fragments. A local attacker could use this to escalate privileges, or possibly escape a container.
