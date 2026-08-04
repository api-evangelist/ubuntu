---
title: "USN-8621-1: Samba vulnerabilities"
url: "https://ubuntu.com/security/notices/USN-8621-1"
date: "2026-07-28"
feed_url: "https://ubuntu.com/security/notices/rss.xml"
---
It was discovered that Samba's pam_winbind incorrectly handled home directory ownership when mkhomedir was enabled. A local attacker could possibly use this issue to cause a denial of service by triggering a change in ownership of the root directory. (CVE-2026-15779) Arjun Basnet, Douglas Bagnall, and Andrew Tridgell discovered that Samba incorrectly handled TSIG packets with name compression.
