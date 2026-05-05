---
title: "USN-8198-2: Tornado vulnerabilities"
url: "https://ubuntu.com/security/notices/USN-8198-2"
date: "Tue, 28 Apr 2026 19:27:53 +0000"
author: ""
feed_url: "https://ubuntu.com/security/notices/rss.xml"
---
USN-8198-1 fixed vulnerabilities in Tornado. This update provides the
corresponding updates for Ubuntu 26.04 LTS.

Original advisory details:

 It was discovered that Tornado incorrectly handled parsing of large
 multipart request bodies. An attacker could possibly use this issue to
 cause a denial of service. (CVE-2026-31958)

 It was discovered that Tornado did not properly validate characters in
 cookie values. An attacker could possibly use this issue to inject
 arbitrary cookie attributes. (CVE-2026-35536)
