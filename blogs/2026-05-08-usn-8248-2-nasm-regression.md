---
title: "USN-8248-2: NASM regression"
url: "https://ubuntu.com/security/notices/USN-8248-2"
date: "2026-05-08"
author: ""
feed_url: "https://ubuntu.com/security/notices/rss.xml"
---
USN-8248-1 fixed vulnerabilities in NASM. Unfortunately the update introduced a regression which could cause NASM to crash. This update fixes the problem by reverting the fix for CVE-2021-33450 and CVE-2021-33452 in Ubuntu 24.04 LTS. We apologize for the inconvenience. Original advisory details: Daisy Chen discovered that NASM was vulnerable to a heap buffer overflow when handling certain input. An attacker could possibly use this issue to cause NASM to crash, resulting in a denial of service, or possibly execute arbitrary code.
