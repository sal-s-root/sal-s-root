# Infrastructure engineering portfolio

Hands-on projects covering Linux operations, configuration management, cloud
networking, container delivery, Kubernetes, observability, and recovery.

## Start here

| Area | Project | What to inspect |
|---|---|---|
| Linux operations | [Linux administration toolkit](https://github.com/sal-s-root/linux-admin-toolkit) | Bash checks, failure-path tests, hardened systemd timer |
| Configuration management | [Ansible Linux baseline](https://github.com/sal-s-root/ansible-server-baseline) | Reusable role, check mode, idempotence, verification |
| Infrastructure as code | [AWS network module](https://github.com/sal-s-root/terraform-aws-network-lab) | Two-zone private networking, inputs, mocked plan tests |
| Container operations | [Compose platform](https://github.com/sal-s-root/compose-platform-lab) | Reverse proxy, private networking, health gating, limits |
| Kubernetes | [Kubernetes platform](https://github.com/sal-s-root/kubernetes-platform-lab) | Helm, probes, security contexts, scaling, disruption policy |
| Observability | [Monitoring platform](https://github.com/sal-s-root/observability-platform-lab) | Prometheus, Grafana, alert tests, dashboards, runbooks |
| Recovery | [Backup/restore lab](https://github.com/sal-s-root/backup-restore-lab) | Verified restoration, corruption detection, safe destinations |

## Supporting projects

- [Instrumented service fixture](https://github.com/sal-s-root/containerized-health-api): health, readiness, version, metrics, and container CI.
- [Network diagnostics](https://github.com/sal-s-root/network-health-checks): bounded TCP checks and explicit target manifests.
- [Reliability operations](https://github.com/sal-s-root/reliability-operations-lab): synthetic drills, acceptance policy, and SLO assumptions.
- [Infrastructure toolbox](https://github.com/sal-s-root/infra-toolbox): small metadata checks consolidated into one maintained collection.

Each lab documents setup, teardown, verification, and limitations. Local test
results and mocked plans are kept separate from real cloud or cluster deployment.
The archived standalone utilities have been consolidated into the toolbox.
