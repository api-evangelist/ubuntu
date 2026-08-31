---
title: "LSN-0121-1: Kernel Live Patch Security Notice"
url: "https://ubuntu.com/security/notices/LSN-0121-1"
date: "2026-08-27"
feed_url: "https://ubuntu.com/security/notices/rss.xml"
---
In the Linux kernel, the following vulnerability has been resolved: ksmbd: ipc: fix use-after-free in ipc_msg_send_request ipc_msg_send_request() waits for a generic netlink reply using an ipc_msg_table_entry on the stack. In the Linux kernel, the following vulnerability has been resolved: ksmbd: fix use-after-free of share_conf in compound request smb2_get_ksmbd_tcon() reuses work->tcon in compound requests without validating tcon->t_state. In the Linux kernel, the following vulnerability has been resolved: netfilter: nf_conntrack_h323: check for zero length in DecodeQ931() In DecodeQ931(), t
