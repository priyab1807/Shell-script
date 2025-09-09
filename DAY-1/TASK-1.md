# Basic
### Task: Write a script that checks if a given service (e.g., nginx, mysql) is running. If running, return exit code 0; otherwise return 1.
Purpose: Introduces process status checks, crucial for SRE monitoring probes.


# Intermediate:
### Task: Script to ping a critical endpoint (e.g., google.com) and log latency values to latency.log. If response time exceeds 200ms, print a warning.
Purpose: Basic observability for network performance.


# Advanced:
### Task: Implement a health check probe script that verifies:
1. A given process is running
2. Required TCP port is open
3. Disk usage is below 80%
Purpose: Mimics Kubernetes-style liveness/readiness probes.

