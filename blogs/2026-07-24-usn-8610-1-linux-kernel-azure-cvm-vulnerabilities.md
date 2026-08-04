---
title: "USN-8610-1: Linux kernel (Azure CVM) vulnerabilities"
url: "https://ubuntu.com/security/notices/USN-8610-1"
date: "2026-07-24"
feed_url: "https://ubuntu.com/security/notices/rss.xml"
---
Maxim Suhanov discovered that the NTFS file system implementation in the Linux kernel did not properly validate file name length in certain situations, leading to an out-of-bounds read. An attacker could use this to construct a malicious NTFS image that, when mounted and operated on, could expose sensitive information (kernel memory). (CVE-2023-45896) It was discovered that some AMD processors did not properly clear data in the floating point divider unit during speculative execution.
