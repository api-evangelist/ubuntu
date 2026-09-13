---
title: "USN-8741-1: Flatpak vulnerabilities"
url: "https://ubuntu.com/security/notices/USN-8741-1"
date: "2026-09-10"
feed_url: "https://ubuntu.com/security/notices/rss.xml"
---
It was discovered that Flatpak did not properly validate paths in sandbox-expose options. A malicious or compromised Flatpak app could use app-controlled symlinks to access arbitrary host files and gain code execution in the host context. This issue was addressed in Ubuntu Ubuntu 20.04 LTS, Ubuntu 22.04 LTS and Ubuntu 24.04 LTS.
