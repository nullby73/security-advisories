# Security Advisories

This repository contains security advisories for discovered vulnerabilities

## 2025

#### CVE-2025-0542

**Title:** G DATA Management Server Local privilege escalation  
**Severity:** Hight - 7.8 (CVSS:3.1/AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H)  
**Fixed version:** 15.8.333  
**Summary:** Local privilege escalation due to incorrect assignment of privileges of temporary files in the update mechanism of G DATA Management Server. This vulnerability allows a local, unprivileged attacker to escalate privileges on affected installations by placing a crafted ZIP archive in a globally writable directory, which gets unpacked in the context of SYSTEM and results in arbitrary file write.

[Advisory](CVE-2025-0542/README.md)

#### CVE-2025-0543

**Title:** G DATA Security Client Local privilege escalation  
**Severity:** Hight - 7.8 (CVSS:3.1/AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H)  
**Fixed version:** 15.8.333  
**Summary:** Local privilege escalation in G DATA Security Client due to incorrect assignment of privileges to directories. This vulnerability allows a local, unprivileged attacker to escalate privileges on affected installations by placing an arbitrary executable in a globally writable directory resulting in execution by the SetupSVC.exe service in the context of SYSTEM.

[Advisory](CVE-2025-0543/README.md)
