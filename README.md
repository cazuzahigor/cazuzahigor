<div align="center">
```
╔══════════════════════════════════════════════════════════╗
║          HIGOR CAZUZA — DEVOPS ENGINEER                  ║
║          Cloud Infrastructure & Platform Engineering     ║
╚══════════════════════════════════════════════════════════╝
```

[![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)](https://aws.amazon.com/)
[![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)](https://kubernetes.io/)
[![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)](https://www.terraform.io/)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)](https://www.docker.com/)
[![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)](https://www.ansible.com/)
[![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)](https://www.kernel.org/)

</div>

---

## `$ whoami`

DevOps Engineer focused on cloud-native infrastructure, automation, and continuous delivery. I design and operate environments where provisioning is code, deployments are automated, and observability is built in from day one.

My foundation is in **infrastructure engineering fundamentals**: how systems actually run, how networks communicate, how workloads fail under real conditions. That foundation drives how I approach automation decisions — choosing the right orchestration model, the right abstraction layer, the right tradeoff between flexibility and reliability.

I operate a bare-metal Kubernetes cluster as my primary engineering environment, where I apply production-grade practices across the full infrastructure lifecycle: from OS provisioning to GitOps-driven deployments.

> _"Infrastructure that you cannot reason about will eventually fail in ways you cannot predict."_

---

## Core Competencies

### Cloud & Infrastructure

| Area | Detail |
|---|---|
| **Cloud Platform** | AWS: EC2, S3, IAM, VPC, EKS, CloudWatch |
| **Infrastructure as Code** | Terraform: resource provisioning, state management, module design |
| **Container Orchestration** | Kubernetes: workload scheduling, networking, storage, RBAC |
| **Configuration Management** | Ansible: idempotent provisioning, roles, inventory management |
| **Containerization** | Docker: image design, multi-stage builds, Compose environments |

### CI/CD & GitOps

| Area | Detail |
|---|---|
| **Pipelines** | GitHub Actions: build, test, and deploy workflows |
| **GitOps** | Infrastructure versioning, pull-based deployments, drift detection |
| **Version Control** | Git: branching strategies, commit conventions, repository structure |

### Observability & Systems

| Area | Detail |
|---|---|
| **Monitoring** | Prometheus: metrics collection, alerting rules, service discovery |
| **Visualization** | Grafana: infrastructure dashboards, SLO tracking |
| **Systems** | Linux administration: systemd, networking, storage, security hardening |
| **Scripting** | Bash: automation scripts, system tooling |

---

## Selected Projects

### Bare-Metal Kubernetes Cluster

**Context:** Provisioning and operating a multi-node Kubernetes cluster on physical hardware, without managed cloud abstractions.

**Engineering decisions:**

Chose K3s as the Kubernetes distribution for its production-grade feature set with reduced operational overhead on bare-metal nodes. Designed the cluster with a dedicated control plane node and separate worker nodes, reflecting real production topology. Applied Ansible to fully automate node provisioning and cluster configuration, ensuring reproducible and idempotent infrastructure state across all machines.

**Outcome:** A fully operational Kubernetes cluster on bare-metal, managed as code, with automated provisioning from a clean OS install to running workloads.

---

### Infrastructure Automation with Ansible

**Context:** Eliminating manual configuration drift across Linux servers in a multi-machine environment.

**Engineering decisions:**

Structured playbooks around roles to enforce separation of concerns and enable reuse across different inventory groups. Applied idempotency as a design constraint: every task is safe to run repeatedly without side effects. Used inventory groups to model the real environment, separating control plane, worker, and workstation nodes.

**Outcome:** Full infrastructure configuration expressed as version-controlled Ansible code, with zero manual steps required from OS installation to production-ready state.

---

## Infrastructure Radar
```
Adopted        →  Linux, Docker, Kubernetes (K3s), Ansible, Git, GitHub Actions
Expanding      →  Terraform, AWS (EKS, EC2, IAM, VPC), Prometheus, Grafana
Watching       →  OpenTelemetry, ArgoCD, Cilium, Crossplane
```

---

## Connect

<div align="center">

| | |
|---|---|
| 💼 LinkedIn | [linkedin.com/in/higorcazuza](https://linkedin.com/in/higorcazuza) |
| 🌐 Web | [asymptora.dev](https://asymptora.dev) |
| ✍️ Technical Writing | [dev.to/asymptora](https://dev.to/asymptora) |
| 📬 Email | [higorcazuza@protonmail.com](mailto:higorcazuza@protonmail.com) |

</div>

---

<div align="center">
<sub>Infrastructure as code. Reliability by design. Delivered continuously.</sub>
</div>
