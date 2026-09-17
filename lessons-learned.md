# Lessons Learned

This document will capture the strongest technical and operational takeaways as the lab is completed.

The final review will focus on:

- separating Azure platform controls from Linux guest configuration
- using dedicated service identities and least-privilege permissions
- understanding listeners, interfaces, ports, and private request routing
- treating `systemd` and logs as core workload-operating tools
- distinguishing disk attachment from filesystem creation and persistent mounting
- troubleshooting by layer and evidence instead of changing multiple settings at once
- converting proven manual checks into safe, repeatable Bash automation
