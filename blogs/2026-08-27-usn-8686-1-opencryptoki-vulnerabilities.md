---
title: "USN-8686-1: openCryptoki vulnerabilities"
url: "https://ubuntu.com/security/notices/USN-8686-1"
date: "2026-08-27"
feed_url: "https://ubuntu.com/security/notices/rss.xml"
---
It was discovered that primitive decoders in openCryptoki produced integer underflows when the encoded length was zero. An attacker could possibly use this issue to trigger out-of-bounds reads. (CVE-2026-40253) It was discovered that openCryptoki incorrectly handled symlinks.
