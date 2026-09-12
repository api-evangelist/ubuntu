---
title: "USN-8721-1: OpenSSH vulnerabilities"
url: "https://ubuntu.com/security/notices/USN-8721-1"
date: "2026-09-03"
feed_url: "https://ubuntu.com/security/notices/rss.xml"
---
It was discovered that OpenSSH's ssh-agent incorrectly handled interactions between agent locking and the session-bind@openssh.com extension. A remote attacker with access to a forwarded agent connection could possibly use this issue to perform operations that should only be available locally, such as adding tokens or using keys. (CVE-2026-73281) It was discovered that OpenSSH's ssh client incorrectly handled concurrent remote-forwarding operations.
