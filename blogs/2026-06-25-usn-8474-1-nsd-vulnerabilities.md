---
title: "USN-8474-1: NSD vulnerabilities"
url: "https://ubuntu.com/security/notices/USN-8474-1"
date: "2026-06-25"
feed_url: "https://ubuntu.com/security/notices/rss.xml"
---
It was discovered that NSD incorrectly handled APL resource records with an address length larger than permitted for the address family. A remote attacker could use this to cause a stack-based buffer overflow when the zone is written to disk, potentially executing arbitrary code with the privileges of the NSD server. (CVE-2026-12246) It was discovered that NSD incorrectly handled SVCB resource records.
