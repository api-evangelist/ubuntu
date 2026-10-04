---
title: "USN-8861-1: OpenSSL vulnerabilities"
url: "https://ubuntu.com/security/notices/USN-8861-1"
date: "2026-10-01"
feed_url: "https://ubuntu.com/security/notices/rss.xml"
---
It was discovered that OpenSSL had an inefficient algorithm in its QUIC stream reassembly implementation. A remote attacker could possibly use this issue to cause OpenSSL to use excessive CPU resources, leading to a denial of service. (CVE-2026-42772) It was discovered that OpenSSL did not properly limit memory allocated for QUIC packet buffers.
