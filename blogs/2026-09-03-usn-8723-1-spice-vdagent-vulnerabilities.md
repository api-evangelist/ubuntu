---
title: "USN-8723-1: SPICE vdagent vulnerabilities"
url: "https://ubuntu.com/security/notices/USN-8723-1"
date: "2026-09-03"
feed_url: "https://ubuntu.com/security/notices/rss.xml"
---
It was discovered that SPICE vdagent had an integer overflow in the buffer size calculation used when writing to the daemon socket. A malicious or compromised SPICE host could possibly use this issue to cause SPICE vdagent to crash, resulting in a denial of service. (CVE-2026-57965) It was discovered that SPICE vdagent did not properly sanitize filenames provided by the SPICE host during file transfers.
