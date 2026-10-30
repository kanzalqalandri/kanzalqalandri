# Kanzal Qalandri

**DevOps / Platform Engineer** · CNCF Kubestronaut (CKA, CKAD, CKS, KCNA, KCSA)

[kanzal.com](https://kanzal.com) · [LinkedIn](https://www.linkedin.com/in/kanzalqalandri/) · [X](https://twitter.com/KanzalQalandri) · [YouTube](https://www.youtube.com/@kanzalqalandri) · [Email](mailto:kanzalqalandri@gmail.com)

I'm a DevOps engineer at [PufferSoft](https://www.puffersoft.com/), where I build and run the Kubernetes platform behind [Apporto](https://www.apporto.com/), a browser-based virtual desktop and computer lab service. My work spans GitOps delivery, multi-cloud cluster operations, secrets management, stateful services on Kubernetes, and observability.

## What I work on

- Operate a fleet of 30+ RKE2 clusters managed through Rancher across AWS and Azure, reconciled by six regional Argo CD hubs.
- Designed and drove the move from a single GitOps monorepo with a custom renderer to a tiered, data-driven platform: 130+ cluster add-ons placed by fleet, role, cloud and cluster tiers with ring-based version promotion, and tenant stacks delivered from separate config repos.
- Centralised secrets in OpenBao with External Secrets Operator, namespace-scoped policies, and GitHub OIDC for CI secret seeding.
- Run self-hosted GitHub Actions runners on Kubernetes (ARC) and migrate pipelines from Drone CI to GitHub Actions.
- Run stateful workloads on Kubernetes: PostgreSQL (CloudNativePG, Crunchy PGO), Percona XtraDB, Strimzi Kafka (ZooKeeper to KRaft), Dragonfly, MinIO and Keycloak.
- Build observability on OpenTelemetry, VictoriaMetrics, Grafana, Tempo and Graylog, and handle incident response and RCAs.

## Tech stack

| Area | Tools |
|---|---|
| Cloud & clusters | AWS, Azure, Kubernetes, RKE2, Rancher, Helm, Kustomize, Crossplane, KEDA, Cluster Autoscaler |
| GitOps & CI/CD | Argo CD, Flux, GitHub Actions (ARC), Drone CI, Terraform, Atlantis, AWX |
| Security & identity | OpenBao / Vault, External Secrets Operator, cert-manager, Kyverno, Keycloak |
| Networking | Envoy Gateway, Gateway API, ingress-nginx, Cilium, Cloudflare |
| Data | PostgreSQL (CloudNativePG, PGO), Percona XtraDB, Kafka (Strimzi), Dragonfly / Redis, MinIO, OpenSearch |
| Observability | OpenTelemetry, Prometheus, VictoriaMetrics, Grafana, Loki, Tempo, Graylog, PagerDuty |
| Languages | Go, Bash, Python |

## Projects

| Project | Description |
|---|---|
| [gitops](https://github.com/kanzalqalandri/gitops) | Low-templating Argo CD app-of-apps layout for managing several Kubernetes clusters from one repo. |
| [system-setup](https://github.com/kanzalqalandri/system-setup) | Idempotent provisioning of a Linux workstation with DevOps tooling. |

## Writing

- [Deploy Argo CD using Helm with SSL and Ingress](https://kanzal.com/blog/argocd-gitops-deployment/)
- [Deploy Kubernetes with kubeadm 1.30 and Calico on Ubuntu 22.04](https://kanzal.com/blog/kubernetes-with-kubeadm-and-calico/)
- [More on kanzal.com/blog](https://kanzal.com/blog/)
