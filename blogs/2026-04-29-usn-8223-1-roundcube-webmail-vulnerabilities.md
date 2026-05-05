---
title: "USN-8223-1: Roundcube Webmail vulnerabilities"
url: "https://ubuntu.com/security/notices/USN-8223-1"
date: "Wed, 29 Apr 2026 13:50:15 +0000"
author: ""
feed_url: "https://ubuntu.com/security/notices/rss.xml"
---
It was discovered that Roundcube Webmail mishandled Punycode xn-- domain names.
An attacker could possibly use this issue to cause a homograph attack. (CVE-2019-15237)

It was discovered that Roundcube Webmail did not properly sanitize certain
attributes when handling CSS within HTML messages and certain SVG attributes.
An attacker could possibly use this issue to cause a cross-site scripting attack.
(CVE-2024-38356, CVE-2024-38357)

It was discovered that Roundcube Webmail did not properly sanitize certain HTML
attributes when rendering e-mail messages. An attacker could possibly use this
issue to cause a cross-site scripting attack. (CVE-2024-42008)

It was discovered that Roundcube Webmail did not properly filter certain CSS token
sequences within rendered e-mail messages. An attacker could possibly use this
issue to obtain sensitive information. (CVE-2024-42010)

It was discovered that Roundcube Webmail did not properly treat an SVG
tag as an image source within its HTML sanitizer. An attacker could possibly use
this issue to bypass remote image blocking to track email open actions or
potentially bypass access control. (CVE-2026-25916)

It was discovered that Roundcube Webmail did not properly handle comments within
Cascading Style Sheets (CSS). An attacker could possibly use this issue to perform
a CSS injection attack. (CVE-2026-26079)
