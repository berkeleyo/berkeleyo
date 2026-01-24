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

## 🏗️ Featured Projects (10)

| Project | Description | Stack |
|---|---|---|
| [**Cloud Access Broker — JIT (Multi-Cloud)**](https://github.com/berkeleyo/cloud-access-broker-jit-multicloud) | Time-bound least-privilege elevation across **Azure, AWS & GCP** with approvals, audit, and auto-revocation. | ☁️ Azure · AWS · GCP · PowerShell/Bash |
| [**AWS JIT Access**](https://github.com/berkeleyo/aws-jit-access) | Identity Center + Step Functions flow for temporary AWS elevation with auto-expiry & CloudTrail logging. | ☁️ AWS · 🐍 Python · 🔐 IAM |
| [**Azure Access Automation**](https://github.com/berkeleyo/azure-access-automation) | Forms → SharePoint → Power Automate → Entra ID group → Conditional Access (time-boxed outside-country access). | ☁️ Azure · ⚡ Power Automate |
| [**Fortinet SD-WAN + IPsec (Azure)**](https://github.com/berkeleyo/fortinet-azure-sdwan-ipsec) | Hub-and-spoke SD-WAN/IPsec topology with HA/BGP, MTU hardening, and route health validation. | 🧱 Fortinet · ☁️ Azure |
| [**Azure Public IP Migration**](https://github.com/berkeleyo/azure-public-ip-migration) | Discover Basic SKU IPs, export inventory CSV, and migrate safely to Standard SKU. | 🧰 PowerShell · ☁️ Azure |
| [**Azure VPN (P2S) Runbook**](https://github.com/berkeleyo/azure-vpn-repo) | Real-world Azure P2S VPN rollout: OpenVPN/Entra ID vs IKEv2, DNS strategy, and secure defaults. | 🌐 Networking · ☁️ Azure |
| [**Cloud-Secure Egress Policy**](https://github.com/berkeleyo/cloud-secure-egress-firewall-policy) | Lock down outbound Internet egress via central firewall/NVA chain with cutover & rollback docs. | 🔐 Network Security · ☁️ Azure |
| [**LogicMonitor Hybrid (Hyper-V • AWS • GCP)**](https://github.com/berkeleyo/logicmonitor-hybrid-monitoring) | Hybrid observability with collectors/agents and cloud integrations; CPU/Memory/Uptime alerting. | 📊 LogicMonitor · ☁️ AWS · ☁️ GCP |
| [**UniFi Controller Cloud Migration**](https://github.com/berkeleyo/unifi-controller-cloud-migration) | Migration from legacy hosting to cloud VM with DNS cutover, version pinning, Entra App Proxy (MFA/CA), and SSH host key audit controls. | ☁️ Cloud · 🧰 PowerShell · 🐧 Linux |
| [**Intune Kyocera Print Governance**](https://github.com/berkeleyo/intune-kyocera-only-print-governance) | Intune automation to enforce Kyocera-only printers, removing unmanaged drivers and enforcing compliance. | 🖥️ Intune · 🧰 PowerShell |

---

## 🧠 Highlights & Focus

- **Identity & Access Governance (Multi-Cloud)** — Designing and operating secure, auditable JIT access models across Entra ID PIM, AWS STS AssumeRole, and GCP Workload Identity Federation.
- **Cloud Networking & Security** — Enterprise SD-WAN / IPsec with HA & BGP, MTU tuning, hub-and-spoke design, firewall chaining, and deterministic egress patterns.
- **Platform & Access Automation** — PowerShell-driven automation for access workflows, infrastructure provisioning, Intune remediation, and operational tooling.
- **Security Automation & SOC Integration** — Sentinel and M365 playbooks for enrichment, triage, and routing alerts into operational channels (Teams / ticketing).
- **Governance & Cost Control** — Policy enforcement, tagging hygiene, drift detection, and accountability across cloud estates.
- **Operational Resilience** — Production-grade runbooks, health checks, backup validation, controlled cutovers, and deterministic rollback procedures.

---

## 🚀 Professional Impact

- Designed and implemented identity-first access models that removed standing privileges across multi-cloud environments.
- Led multiple production migrations and cutovers (DNS, network, platform) using reversible change patterns and pre-validated rollback paths.
- Standardised cloud networking architectures (hub-and-spoke, firewall chaining, VPN / SD-WAN) to reduce operational risk and configuration drift.
- Built automation replacing manual access provisioning, onboarding flows, and environment configuration tasks.
- Authored operational runbooks used for on-call support, incident response, and long-term platform handover.

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
