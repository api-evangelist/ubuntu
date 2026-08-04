---
title: "USN-8556-1: Ruby vulnerabilities"
url: "https://ubuntu.com/security/notices/USN-8556-1"
date: "2026-07-16"
feed_url: "https://ubuntu.com/security/notices/rss.xml"
---
It was discovered that the Net::IMAP client in Ruby did not properly sanitize Symbol arguments passed to IMAP commands. A remote attacker controlling a malicious IMAP server, or able to influence command arguments, could use this to inject arbitrary IMAP commands via CRLF sequences. (CVE-2026-42258) It was discovered that the Zlib::GzipReader in Ruby did not correctly ensure sufficient buffer capacity in the zstream_buffer_ungets function.
