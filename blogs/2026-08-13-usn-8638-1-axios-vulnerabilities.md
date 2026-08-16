---
title: "USN-8638-1: Axios vulnerabilities"
url: "https://ubuntu.com/security/notices/USN-8638-1"
date: "2026-08-13"
feed_url: "https://ubuntu.com/security/notices/rss.xml"
---
Ameer Assadi discovered that Axios did not properly handle certain hostnames when applying NO_PROXY rules. An attacker could possibly use this issue to bypass proxy restrictions and access internal services, resulting in server-side request forgery. (CVE-2025-62718) It was discovered that Axios did not properly protect certain HTTP header values from prototype pollution.
