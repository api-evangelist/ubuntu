---
title: "USN-8222-1: OpenSSH vulnerabilities"
url: "https://ubuntu.com/security/notices/USN-8222-1"
date: "Wed, 29 Apr 2026 12:10:19 +0000"
author: ""
feed_url: "https://ubuntu.com/security/notices/rss.xml"
---
Christos Papakonstantinou discovered that the OpenSSH scp tool incorrectly
handled the legacy scp protocol (-O) option. This could result in certain
files being installed setuid or setgid, contrary to expectations.
(CVE-2026-35385)

Florian Kohnhäuser discovered that OpenSSH incorrectly handled shell
metacharacters in usernames within a command line. When untrusted usernames
and non-default configurations using % in ssh_config are being used, an
attacker could possibly use this issue to execute arbitrary code.
(CVE-2026-35386)

Christos Papakonstantinou discovered that OpenSSH incorrectly handled
parsing the PubkeyAcceptedAlgorithms and HostbasedAcceptedAlgorithms
options. This could result in unintended ECDSA algorithms being used,
contrary to expectations. (CVE-2026-35387)

Michalis Vasileiadis discovered that OpenSSH incorrectly handled
proxy-mode multiplexing sessions. This could result in no confirmation
being asked, contrary to expectations. (CVE-2026-35388)

Vladimir Tokarev discovered that OpenSSH incorrectly handled certificates
with the principal name containing a comma character when using user-trusted
CA keys in authorized_keys and an authorized_keys principals="" option
that lists more than one principal. This could result in inappropriate
principal matching, contrary to expectations. (CVE-2026-35414)
