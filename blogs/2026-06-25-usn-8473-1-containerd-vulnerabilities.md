---
title: "USN-8473-1: containerd vulnerabilities"
url: "https://ubuntu.com/security/notices/USN-8473-1"
date: "2026-06-25"
feed_url: "https://ubuntu.com/security/notices/rss.xml"
---
It was discovered that containerd incorrectly handled HTTP/2 SETTINGS frames. A remote attacker could possibly use this issue to cause containerd to enter an infinite loop, resulting in a denial of service. (CVE-2026-33814) Jakub Ciolek and Kyle Elliott discovered that containerd incorrectly handled group parsing when creating containers from images.
