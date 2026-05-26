Wazuh SOC Detection Engineering Lab

This project focuses on SOC detection engineering and Windows authentication telemetry analysis using Wazuh SIEM, Sysmon, and Windows Security Events.

Current investigation includes SMB authentication reconnaissance and NTLM network logon activity simulated from a Kali Linux system against a monitored Windows 11 endpoint.

The lab demonstrates:
SMB authentication monitoring
NTLM network logon detection
Failed and successful authentication analysis
Privileged logon investigation
Wazuh alert correlation
Windows Security Event analysis
SOC investigation workflow

Technologies Used:
Wazuh SIEM
Sysmon
Windows 11
Kali Linux
VirtualBox

Key Event IDs:
4625 — Failed logon
4624 — Successful network logon
4672 — Special privileges assigned
4634 — Logoff

Key Wazuh Rules:
60122 — Failed authentication detection
92657 — Suspicious NTLM remote logon
67028 — Privileged logon detection
60137 — Windows user logoff

This repository will continue expanding with additional attack simulations, detection engineering investigations, and SIEM correlation use cases.
