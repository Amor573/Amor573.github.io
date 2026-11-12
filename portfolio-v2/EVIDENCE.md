# Public portfolio evidence index

These URLs identify independently checkable **GitHub Actions jobs** that ran for the connected GitHub account on November 12, 2026. They prove narrow automated validation only.

| Project | Verified public evidence | Limits |
| --- | --- | --- |
| Ansible / Flask / NGINX | [Compose build and reverse-proxy HTTP smoke test](https://github.com/Amor573/ansible_flask_vm_deploy/actions/runs/43138526349) | Does not verify production HA, TLS, or traffic distribution |
| Prometheus / Grafana | [Monitoring Bash syntax and ShellCheck](https://github.com/Amor573/Monitor_Grafana-Prometheus/actions/runs/43138453834) | Does not verify a live installation, dashboard, or alert delivery |
| Azure AKS / Terraform | [Terraform init and static validate](https://github.com/Amor573/Terraform-Aks/actions/runs/43139006016) | Does not prove a cloud apply or Datadog agent operation |
| OpenShift platform lab | [Kubernetes YAML structure validation](https://github.com/Amor573/openshift-platform-engineering-lab/actions/runs/43138856595) | Does not prove the manifests have been applied successfully to a cluster |

## Required human-reviewed proof

- **Web:** sanitized browsing flow, independent frontend/backend checks and error-handling evidence.
- **Cloud/DevOps:** deployment pipeline, rollout, metrics, rollback, cost and exact commit.
- **Networking:** IPsec/VTI lab topology, IKEv2 policy negotiation, reversible cutover and incident response; no real private keys or peers.
- **Enterprise:** anonymized SAN/VIOS/OpenShift troubleshooting and independently checkable test outcomes.
- **Product:** synthetic cargo reconciliation dashboard and decision-impact explanation.

**Do not upload raw images from personal devices, client systems or clinical/financial records without verifying they contain no confidential information.**