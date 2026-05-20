---
title: "USN-8268-1: Dnsmasq vulnerabilities"
url: "https://ubuntu.com/security/notices/USN-8268-1"
date: "Tue, 12 May 2026 09:23:25 +0000"
author: ""
feed_url: "https://ubuntu.com/security/notices/rss.xml"
---
Andrew S. Fasano, Royce M, and Hugo Martinez Ray discovered that Dnsmasq did not allocate the necessary space to store domain names in some contexts. An attacker could possibly use this issue to write out-of-bounds, and could cause a denial of service or execute arbitrary code. (CVE-2026-2291) Royce M discovered that Dnsmasq could loop infinitely due to erroneously missing the window header.
