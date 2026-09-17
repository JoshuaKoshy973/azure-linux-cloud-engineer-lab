# Application Unavailable Runbook

## Triage order

1. Confirm Azure VM and platform health.
2. Confirm the expected process and `systemd` service state.
3. Confirm the application is listening on the expected address and port.
4. Test the local and private health endpoints.
5. Review service and application logs.
6. Validate NGINX configuration and backend routing.
7. Validate NSG and Linux firewall paths.
8. Check CPU, memory, disk space, inodes, and mounted storage.
9. Retest the original client request.

Exact commands, expected output, and escalation criteria will be added after the healthy baseline is established.
