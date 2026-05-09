---
title: "USN-8246-1: Vim vulnerabilities"
url: "https://ubuntu.com/security/notices/USN-8246-1"
date: "2026-05-07"
author: ""
feed_url: "https://ubuntu.com/security/notices/rss.xml"
---
Michał Majchrowicz discovered that Vim’s zip plugin could overwrite arbitrary files. An attacker could possibly use this issue to delete sensitive data or execute arbitrary code. This issue only affected Ubuntu 26.04 LTS. (CVE-2026-35177) It was discovered that Vim’s netbeans interface did not properly sanitize certain strings. An attacker could possibly use this issue to execute arbitrary commands. This issue only affected Ubuntu 26.04 LTS. (CVE-2026-39881) It was discovered that Vim did not properly handle backticks in tag filenames.
