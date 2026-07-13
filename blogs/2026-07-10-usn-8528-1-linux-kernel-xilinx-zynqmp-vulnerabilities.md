---
title: "USN-8528-1: Linux kernel (Xilinx ZynqMP) vulnerabilities"
url: "https://ubuntu.com/security/notices/USN-8528-1"
date: "2026-07-10"
feed_url: "https://ubuntu.com/security/notices/rss.xml"
---
It was discovered that the Linux kernel algif_aead module did not properly handle in-place cryptographic operations. This flaw is known as Copy Fail. A local attacker could use this to escalate privileges, or possibly escape a container.
