<!-- Profile README for github.com/berkeleyo -->
<div align="center">
  
# Hi, I'm Berkeley 👋

<!-- Badges Row -->
![Profile Views](https://komarev.com/ghpvc/?username=berkeleyo&color=blue&style=for-the-badge)
![Experience](https://img.shields.io/badge/Experience-6%2B%20years-1f6feb?style=for-the-badge&logo=github)
![Lines of Code](https://img.shields.io/badge/Lines%20of%20Code-100k%2B-blue?style=for-the-badge)

<!-- Tech stack badges (as provided, preserved) -->
<p align="center">
<img src="https://img.shields.io/badge/Azure-0078D4?logo=microsoftazure&logoColor=white">
<img src="https://img.shields.io/badge/AWS-232F3E?logo=amazonaws&logoColor=FF9900">
<img src="https://img.shields.io/badge/GCP-4285F4?logo=googlecloud&logoColor=white">
<img src="https://img.shields.io/badge/PowerShell-5391FE?logo=powershell&logoColor=white">
<img src="https://img.shields.io/badge/Bicep-00B4FF?logo=microsoftazure">
<img src="https://img.shields.io/badge/Terraform-7B42BC?logo=terraform&logoColor=white">
<img src="https://img.shields.io/badge/GitHub%20Actions-181717?logo=githubactions&logoColor=white">
<img src="https://img.shields.io/badge/Azure%20DevOps-0078D7?logo=azuredevops&logoColor=white">
<img src="https://img.shields.io/badge/Docker-2496ED?logo=docker">
<img src="https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes">
<img src="https://img.shields.io/badge/Microsoft%20Sentinel-003B57?logo=microsoft">
<img src="https://img.shields.io/badge/Intune-0078D4?logo=microsoftintune">
<img src="https://img.shields.io/badge/Fortinet-E60000?logo=fortinet">
<img src="https://img.shields.io/badge/Grafana-F46800?logo=grafana">
<img src="https://img.shields.io/badge/Prometheus-E6522C?logo=prometheus">
</p>

</div>

---

## 🧑‍💻 About Me

Cloud engineer focused on **access governance**, **secure network architectures**, and **pragmatic automation**.  
I like clean runbooks, reversible cutovers, and evidence-first security.  
I work primarily in **Azure**, with complementary projects in **AWS** and **GCP** where they deliver value.

- 🛡️ Identity & Access: JIT elevation, Conditional Access, PIM, external-ID federation (Azure • AWS STS • GCP WIF)  
- 🌐 Networking: Fortinet SD-WAN/IPsec in Azure, HA/BGP, MTU optimization  
- ⚙️ Automation: PowerShell/Bicep, Logic Apps, YAML pipelines, GitHub/Azure DevOps  
- 📊 Ops: Runbooks, cutover/rollback, observability, backup verification  
- ✍️ Documentation: concise, production-ready, redacted  

---

## 🏗️ Platform & Engineering Projects

Rather than isolated tooling, these repositories represent real operational problems, designed and implemented with production constraints in mind — security, rollback, observability, and long-term maintainability.

Projects are grouped by engineering domain to reflect how platforms are designed and operated in practice.

---

### ☁️ Migration & Platform Modernisation

Projects focused on moving legacy or operationally risky systems into secure, maintainable cloud architectures with controlled cutover and rollback strategies.

| Project | Description | Stack |
|---|---|---|
| [**UniFi Controller Cloud Migration**](https://github.com/berkeleyo/unifi-controller-cloud-migration) | End-to-end migration from legacy hosting to Azure with DNS cutover strategy, version pinning, Entra App Proxy integration, MFA enforcement, and operational hardening. | ☁️ Azure · 🐧 Linux · 🧰 PowerShell |
| [**Azure Public IP Migration**](https://github.com/berkeleyo/azure-public-ip-migration) | Discovery and migration framework for retiring Basic SKU public IPs safely across subscriptions with inventory export, validation, and reversible migration workflow. | 🧰 PowerShell · ☁️ Azure |
| [**Azure VPN (P2S) Runbook**](https://github.com/berkeleyo/azure-vpn-repo) | Real-world VPN deployment covering authentication models, DNS behaviour, and secure connectivity modernisation patterns. | 🌐 Networking · ☁️ Azure |

---

### 🔐 Identity & Access Platforms

Identity is treated as the primary control plane. These projects focus on removing standing privilege, enforcing least access, and making elevation auditable and time-bound.

| Project | Description | Stack |
|---|---|---|
| [**Cloud Access Broker — JIT (Multi-Cloud)**](https://github.com/berkeleyo/cloud-access-broker-jit-multicloud) | Multi-cloud just-in-time elevation across Azure, AWS and GCP with approval workflow, audit logging, and automatic revocation. | ☁️ Azure · AWS · GCP · PowerShell |
| [**AWS JIT Access**](https://github.com/berkeleyo/aws-jit-access) | Temporary privilege elevation using AWS Identity Center and Step Functions with CloudTrail-backed auditability. | ☁️ AWS · 🐍 Python · 🔐 IAM |
| [**Azure Access Automation**](https://github.com/berkeleyo/azure-access-automation) | Automated access workflows integrating Forms, Power Automate and Entra ID to provide controlled, time-bound access with policy enforcement. | ☁️ Azure · ⚡ Power Automate |

---

### 🌐 Cloud Networking & Secure Connectivity

Networking projects focused on deterministic routing, secure egress, and predictable failure modes across hybrid and cloud environments.

| Project | Description | Stack |
|---|---|---|
| [**Fortinet SD-WAN + IPsec (Azure)**](https://github.com/berkeleyo/fortinet-azure-sdwan-ipsec) | Enterprise hub-and-spoke SD-WAN architecture with HA, BGP routing, MTU optimisation, and operational validation patterns. | 🧱 Fortinet · ☁️ Azure |
| [**Cloud-Secure Egress Policy**](https://github.com/berkeleyo/cloud-secure-egress-firewall-policy) | Centralised outbound control using firewall chaining and enforced egress paths with documented cutover and rollback strategy. | 🔐 Network Security · ☁️ Azure |

---

### ⚙️ Platform Automation & Governance

Automation projects focused on scale, repeatability, and reducing operational risk across large cloud estates.

| Project | Description | Stack |
|---|---|---|
| [**Intune Kyocera Print Governance**](https://github.com/berkeleyo/intune-kyocera-only-print-governance) | Endpoint governance automation enforcing compliant printer usage and removing unmanaged drivers through Intune remediation. | 🖥️ Intune · 🧰 PowerShell |

---

### 📊 Observability & Operations

Operational tooling focused on visibility, health validation, and ensuring systems remain observable after deployment.

| Project | Description | Stack |
|---|---|---|
| [**LogicMonitor Hybrid Monitoring**](https://github.com/berkeleyo/logicmonitor-hybrid-monitoring) | Hybrid monitoring model spanning Hyper-V, AWS and GCP with unified alerting and operational dashboards. | 📊 LogicMonitor · ☁️ AWS · ☁️ GCP |

---

## 🧠 Engineering Focus

- Identity-first platform design and least-privilege access models
- Deterministic cloud networking and secure egress architecture
- Automation driven by operational need rather than tooling preference
- Governance and repeatability across multi-subscription environments
- Documentation designed for operational handover

---

## 🚀 Professional Impact

- Removed standing privilege through identity-driven elevation models across cloud environments.
- Delivered production migrations and cutovers with pre-defined rollback paths and zero-downtime strategies.
- Standardised network and access patterns reducing operational drift across environments.
- Built automation replacing manual access provisioning and configuration workflows.
- Produced operational runbooks enabling predictable support and incident response.

---

## 🧭 How I Work

- Design for rollback first.
- Prefer small, reversible changes over high-risk deployments.
- Treat identity as the primary security boundary.
- Document systems so someone else can operate them at 3am.
- Automate only after the manual process is fully understood.

---

## 🔐 Security Philosophy

- Identity over network trust.
- Short-lived access over standing privilege.
- Evidence over assumptions.
- Safe defaults over permissive convenience.
- Production systems should fail predictably.

---

## 🔍 Currently Exploring

- Workload identity federation patterns across cloud providers  
- Zero-trust network segmentation models  
- Policy-as-code for access governance and platform controls  
- Platform engineering workflows for repeatable environments  

---

## 🧩 Redaction & Security Statement
> 🧾 All documentation and code samples are **redacted for confidentiality**.  
> No secrets, IP addresses, or tenant identifiers are included.
