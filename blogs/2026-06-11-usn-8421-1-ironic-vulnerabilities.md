---
title: "USN-8421-1: Ironic vulnerabilities"
url: "https://ubuntu.com/security/notices/USN-8421-1"
date: "2026-06-11"
feed_url: "https://ubuntu.com/security/notices/rss.xml"
---
Dmitry Tantsur and Tuomo Tanskanen discovered that Ironic did not properly validate file paths when handling ISO images. A privileged authenticated remote user could use this issue to perform path traversal via a crafted ISO image and overwrite arbitrary files on the Ironic conductor. (CVE-2026-48681) Dmitry Tantsur and Tuomo Tanskanen discovered that Ironic did not properly validate kernel command line parameters.
