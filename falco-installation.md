# Phase 2 - Falco Runtime Security

- Installed Falco using Helm in `falco` namespace.
- Verified Falco is running (`kubectl get pods -n falco`).
- Tested Falco by accessing /etc/shadow inside a pod.
- Falco correctly generated alerts.
