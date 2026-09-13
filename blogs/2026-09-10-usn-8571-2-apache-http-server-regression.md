---
title: "USN-8571-2: Apache HTTP Server regression"
url: "https://ubuntu.com/security/notices/USN-8571-2"
date: "2026-09-10"
feed_url: "https://ubuntu.com/security/notices/rss.xml"
---
USN-8571-1 fixed vulnerabilities in Apache HTTP Server. That fix was incomplete due to a missing library symbol, resulting in a regression that could cause Apache HTTP Server to fail to start when HTTP/2 proxying was enabled. This update fixes the problem.
