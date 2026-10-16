---
title: "USN-8887-3: Linux kernel vulnerabilities"
url: "https://ubuntu.com/security/notices/USN-8887-3"
date: "2026-10-09"
feed_url: "https://ubuntu.com/security/notices/rss.xml"
---
It was discovered that some AMD processors did not properly perform Reverse Map Table (RMP) checks when the IOMMU accessed certain host buffers. A local attacker with hypervisor access could possibly use this to trigger an out-of-bounds condition and compromise the integrity of SEV-SNP guest memory. (CVE-2023-20585) Several security issues were discovered in the Linux kernel.
