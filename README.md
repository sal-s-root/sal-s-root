# Hi, I'm Sal

My projects focus on Linux automation, cloud networking, container delivery, and
service reliability. I build small, runnable systems and document their setup,
failure modes, and recovery steps.

## Featured work

| Project | Focus | Verification |
|---|---|---|
| [AWS private network](https://github.com/sal-s-root/terraform-aws-network-lab) | Reusable Terraform/OpenTofu module with subnets in two availability zones | [Mocked plan tests](https://github.com/sal-s-root/terraform-aws-network-lab/blob/main/VALIDATION.md) |
| [Ansible Linux baseline](https://github.com/sal-s-root/ansible-server-baseline) | Reusable role, tagged tasks, and managed configuration | [Apply, idempotence, inspection](https://github.com/sal-s-root/ansible-server-baseline/blob/main/VALIDATION.md) |
| [Kubernetes platform](https://github.com/sal-s-root/kubernetes-platform-lab) | Helm, probes, resource controls, scaling, and network policy | [Chart and schema checks](https://github.com/sal-s-root/kubernetes-platform-lab/blob/main/VALIDATION.md) |
| [Compose platform](https://github.com/sal-s-root/compose-platform-lab) | Caddy proxy, private networking, and service health gating | [Outage and recovery checks](https://github.com/sal-s-root/compose-platform-lab/blob/main/VALIDATION.md) |
| [Observability stack](https://github.com/sal-s-root/observability-platform-lab) | Prometheus, Grafana, Alertmanager, and operational runbooks | [Rule tests and live scraping](https://github.com/sal-s-root/observability-platform-lab/blob/main/VALIDATION.md) |
| [Backup and restore](https://github.com/sal-s-root/backup-restore-lab) | Consistent SQLite backups and safe restore destinations | [Restore and corruption drills](https://github.com/sal-s-root/backup-restore-lab/blob/main/VALIDATION.md) |

## More projects

[Linux administration](https://github.com/sal-s-root/linux-admin-toolkit) ·
[Network diagnostics](https://github.com/sal-s-root/network-health-checks) ·
[Instrumented service](https://github.com/sal-s-root/containerized-health-api) ·
[Reliability drills](https://github.com/sal-s-root/reliability-operations-lab) ·
[Infrastructure toolbox](https://github.com/sal-s-root/infra-toolbox)

The toolbox brings small metadata checks into one maintained collection. The
standalone versions remain available as archived repositories.

## How the projects are checked

Each maintained lab includes executable checks, teardown guidance, and a
`VALIDATION.md` explaining what was exercised. GitHub Actions runs the relevant
checks on changes. Local container tests are distinguished from mocked AWS plans
and Kubernetes schema validation; the latter do not claim deployed environments.
