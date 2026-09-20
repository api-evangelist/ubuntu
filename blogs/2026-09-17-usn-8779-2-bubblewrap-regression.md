---
title: "USN-8779-2: Bubblewrap regression"
url: "https://ubuntu.com/security/notices/USN-8779-2"
date: "2026-09-17"
feed_url: "https://ubuntu.com/security/notices/rss.xml"
---
USN-8779-1 fixed vulnerabilities in Bubblewrap. Unfortunately, the fix for CVE-2026-87766 introduced a regression in symlink resolution, preventing certain Flatpak applications from launching. This update reverts that fix until a complete fix is available.
