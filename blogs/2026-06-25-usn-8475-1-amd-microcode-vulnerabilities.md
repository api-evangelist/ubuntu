---
title: "USN-8475-1: AMD Microcode vulnerabilities"
url: "https://ubuntu.com/security/notices/USN-8475-1"
date: "2026-06-25"
feed_url: "https://ubuntu.com/security/notices/rss.xml"
---
Oleksii Oleksenko, Cedric Fournet, Jana Hofmann, Boris Köpf, Stavros Volos, and Flavien Solt discovered that some AMD processors may allow an attacker to infer data from previous stores, potentially resulting in the leakage of privileged information. A local attacker could possibly use this to expose sensitive information. (CVE-2024-36350, CVE-2024-36357) It was discovered that some AMD Zen 5 processors supporting RDSEED instruction did not properly handle entropy, potentially resulting in the consumption of insufficiently random values.
