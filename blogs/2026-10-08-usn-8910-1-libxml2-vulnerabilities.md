---
title: "USN-8910-1: libxml2 vulnerabilities"
url: "https://ubuntu.com/security/notices/USN-8910-1"
date: "2026-10-08"
feed_url: "https://ubuntu.com/security/notices/rss.xml"
---
Yirou Yang discovered that libxml2 incorrectly handled certain XML catalogs. If a user or automated system was tricked into processing a specially crafted XML catalog, an attacker could possibly use this issue to cause libxml2 to crash, resulting in a denial of service. (CVE-2026-76781) It was discovered that libxml2 incorrectly handled certain large qualified names, leading to a heap-based buffer overflow.
