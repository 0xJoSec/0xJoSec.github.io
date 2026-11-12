---
title: "HTB Forest – AS-REP Roasting to Domain Admin"
date: 2026-11-12 18:00:00 +0100
categories: [HackTheBox, Active Directory]
tags: [htb, asrep-roasting, bloodhound, dcsync]
image:
  path: /assets/img/posts/forest/banner.png
---

## Recon

```bash
nmap -sC -sV -oN forest.nmap 10.10.10.161
```

> Found Kerberos on port 88, so this is a domain controller.
{: .prompt-tip }
