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

Cloud engineer focused on building **reliable infrastructure across platform, network, security, and automation layers**.  
My work spans **cloud architecture, infrastructure as code, networking, identity, observability, and production operations**, with an emphasis on predictable change and operational resilience.

- 🏗️ **Cloud & Platform:** Infrastructure engineering across Azure, AWS, and GCP with repeatable platform patterns and infrastructure as code  
- 🌐 **Networking:** Cloud networking, routing, secure ingress/egress, hybrid connectivity, load balancing, and deterministic traffic flows  
- 🔐 **Security & Identity:** Least privilege, JIT elevation, identity federation, policy-driven access, and secure infrastructure patterns  
- ⚙️ **Automation & IaC:** Terraform, Bicep, PowerShell, CI/CD, GitHub Actions, Azure DevOps, and API-driven workflows  
- 📊 **Operations & Observability:** Monitoring, operational validation, controlled cutovers, rollback, and incident readiness  
- ✍️ **Documentation:** Clear technical documentation and runbooks designed for operational handover  

I also explore AI-assisted automation and event-driven systems where they provide useful interfaces to infrastructure and operational workflows.

---

### 🤖 AI Systems & Event-Driven Platforms

Exploring AI-assisted automation and event-driven architectures as extensions to traditional platform engineering and operational workflows.

| Project | Description | Stack |
|---|---|---|
| [**AI Voice Agent Platform**](https://github.com/berkeleyo/ai-voice-agent-platform-repo) | Event-driven voice agent platform handling enquiry intake, outbound workflows, structured data capture, and downstream automation. | 🤖 AI · Azure Functions · Event-Driven |

---

## ⭐ Flagship Engineering Project

### [Production Cloud Network Platform](https://github.com/berkeleyo/production-cloud-network-platform)

Production-oriented cloud infrastructure reference modelling **segmented application tiers, application delivery and WAF controls, deterministic routing, backend TLS, diagnostics, and offline Terraform regression testing**.

Implemented in Azure as a synthetic engineering environment, with an emphasis on infrastructure boundaries, controlled change, validation, and failure-aware design.

<p>
<img src="https://img.shields.io/badge/Terraform-7B42BC?logo=terraform&logoColor=white">
<img src="https://img.shields.io/badge/Azure-0078D4?logo=microsoftazure&logoColor=white">
<img src="https://img.shields.io/badge/Cloud%20Networking-1f6feb">
<img src="https://img.shields.io/badge/Security-2ea44f">
<img src="https://img.shields.io/badge/Testing-6f42c1">
</p>

> Synthetic/offline engineering reference — no live production infrastructure, customer data, or employer architecture.

---

## 🏗️ Platform & Engineering Projects

These repositories address practical infrastructure and operational problems, with an emphasis on **security, controlled change, rollback, observability, and maintainability**.

Projects are grouped by engineering domain to reflect how cloud platforms are designed and operated in practice.

---

### ☁️ Migration & Platform Modernisation

Migration patterns for moving legacy or operationally risky systems toward maintainable cloud architectures with explicit validation, cutover, and rollback strategies.

| Project | Description | Stack |
|---|---|---|
| [**UniFi Controller Cloud Migration**](https://github.com/berkeleyo/unifi-controller-cloud-migration) | End-to-end migration from legacy hosting to Azure with DNS cutover strategy, version pinning, Entra App Proxy integration, MFA enforcement, and operational hardening. | ☁️ Azure · 🐧 Linux · 🧰 PowerShell |
| [**Azure Public IP Migration**](https://github.com/berkeleyo/azure-public-ip-migration) | Discovery and migration framework for retiring Basic SKU public IPs safely across subscriptions with inventory export, validation, and reversible migration workflow. | 🧰 PowerShell · ☁️ Azure |
| [**Azure VPN (P2S) Runbook**](https://github.com/berkeleyo/azure-vpn-repo) | VPN deployment covering authentication models, DNS behaviour, and secure connectivity modernisation patterns. | 🌐 Networking · ☁️ Azure |
| [**CSAT Remote Access Pattern (LB + NAT Gateway)**](https://github.com/berkeleyo/azure-csat-remote-access-standard-lb-nat-natgw) | Policy-compliant remote access pattern using Standard Load Balancer inbound NAT with controlled outbound egress through NAT Gateway. | ☁️ Azure · Networking · Operations |

---

### 🔐 Identity & Access Platforms

Identity is treated as a primary control plane. These projects focus on reducing standing privilege, enforcing least access, and making elevation auditable and time-bound.

| Project | Description | Stack |
|---|---|---|
| [**Cloud Access Broker — JIT (Multi-Cloud)**](https://github.com/berkeleyo/cloud-access-broker-jit-multicloud) | Multi-cloud just-in-time elevation across Azure, AWS, and GCP with approval workflows, audit logging, and automatic revocation. | ☁️ Azure · AWS · GCP · PowerShell |
| [**AWS JIT Access**](https://github.com/berkeleyo/aws-jit-access) | Temporary privilege elevation using AWS Identity Center and Step Functions with CloudTrail-backed auditability. | ☁️ AWS · 🐍 Python · 🔐 IAM |
| [**Azure Access Automation**](https://github.com/berkeleyo/azure-access-automation) | Automated access workflows integrating Forms, Power Automate, and Entra ID for controlled, time-bound access with policy enforcement. | ☁️ Azure · ⚡ Power Automate |
| [**Access Governance Request Platform**](https://github.com/berkeleyo/access-governance-request-platform) | Request, approval, expiry, and audit workflows for time-bound group membership and access governance. | ☁️ Azure · Identity · Automation |

---

### 🌐 Cloud Networking & Secure Connectivity

Networking patterns focused on **deterministic traffic flow, secure connectivity, explicit routing, controlled egress, and predictable failure modes** across cloud and hybrid environments.

| Project | Description | Stack |
|---|---|---|
| [**Fortinet SD-WAN + IPsec (Azure)**](https://github.com/berkeleyo/fortinet-azure-sdwan-ipsec) | Hub-and-spoke SD-WAN architecture with HA, BGP routing, MTU optimisation, and operational validation patterns. | 🧱 Fortinet · ☁️ Azure |
| [**Cloud-Secure Egress Policy**](https://github.com/berkeleyo/cloud-secure-egress-firewall-policy) | Centralised outbound control using firewall chaining and enforced egress paths with documented cutover and rollback strategy. | 🔐 Network Security · ☁️ Azure |
| [**Azure Firewall Multi-Site Publishing**](https://github.com/berkeleyo/azure-firewall-multi-site-publishing) | Ingress architecture publishing multiple internal applications through Azure Firewall using DNAT and isolated backend patterns. | 🔥 Azure Firewall · ☁️ Azure |
| [**Azure Hub-Spoke Hybrid Routing Pattern**](https://github.com/berkeleyo/azure-hub-spoke-hybrid-routing-pattern) | Hybrid routing design steering partner traffic over VPN using explicit UDR prefix routing and gateway transit. | 🌐 Networking · ☁️ Azure |

---

### ⚙️ Platform Automation & Governance

Automation patterns for improving repeatability, policy enforcement, and operational control across cloud environments.

| Project | Description | Stack |
|---|---|---|
| [**Azure Governance Baseline Framework**](https://github.com/berkeleyo/azure-governance-baseline-framework) | Governance baseline implementing naming standards, tag enforcement, policy-as-code scaffolding, drift detection, and controlled remediation workflows. | ☁️ Azure · Policy · PowerShell |
| [**Azure Cost & Tagging Governance**](https://github.com/berkeleyo/azure-cost-tagging) | Automation enforcing tagging standards and cost attribution across subscriptions with reporting and remediation workflows. | ☁️ Azure · Governance · Automation |
| [**Azure Budget Governance**](https://github.com/berkeleyo/azure-budget-governance) | Budget enforcement and alerting automation using cost management APIs and operational reporting patterns. | ☁️ Azure · FinOps · Automation |
| [**Intune Kyocera Print Governance**](https://github.com/berkeleyo/intune-kyocera-only-print-governance) | Endpoint governance automation enforcing compliant printer usage and removing unmanaged drivers through Intune remediation. | 🖥️ Intune · 🧰 PowerShell |

---

### 📊 Observability & Operations

Operational tooling focused on visibility, health validation, and maintaining useful telemetry across infrastructure environments.

| Project | Description | Stack |
|---|---|---|
| [**LogicMonitor Hybrid Monitoring**](https://github.com/berkeleyo/logicmonitor-hybrid-monitoring) | Hybrid monitoring model spanning Hyper-V, AWS, and GCP with unified alerting and operational dashboards. | 📊 LogicMonitor · ☁️ AWS · ☁️ GCP |
| [**Observability (Grafana + Kibana)**](https://github.com/berkeleyo/observability-grafana-kibana) | Centralised observability stack for metrics and log analysis across hybrid environments. | 📊 Grafana · Kibana · Monitoring |
| [**M365 Security Alerts to Teams**](https://github.com/berkeleyo/m365-security-alerts-to-teams) | Logic App workflow aggregating security alerts and publishing operational summaries to Teams using adaptive cards. | ☁️ Azure · Security · Automation |
| [**Datto Grafana Monitoring**](https://github.com/berkeleyo/datto-grafana-presales) | Monitoring dashboards and alerting patterns for operational visibility and infrastructure validation. | 📊 Grafana · Monitoring |

---

## 🧠 Engineering Focus

- Cloud infrastructure and platform engineering across multi-cloud environments
- Deterministic networking, traffic engineering, and secure ingress/egress
- Infrastructure as code, automated delivery, and repeatable engineering patterns
- Identity-first security and least-privilege access models
- Observability, operational resilience, and failure-aware design
- Controlled change, rollback, and incident readiness
- Documentation designed for operational ownership and handover

---

## 🚀 Professional Impact

- Reduced standing privilege through identity-driven elevation models across cloud environments.
- Delivered production migrations and cutovers with defined validation and rollback paths.
- Standardised network, access, and infrastructure patterns to reduce operational drift.
- Built automation replacing manual access provisioning and configuration workflows.
- Produced operational runbooks supporting predictable handover, support, and incident response.

---

## 🧭 How I Work

- Design for rollback first.
- Prefer small, reversible changes over high-risk deployments.
- Treat identity as a primary security boundary.
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

- Internal infrastructure platforms and repeatable platform engineering patterns
- Workload identity and cross-cloud security models
- Zero-trust segmentation and cloud traffic-control patterns
- Policy-as-code and automated infrastructure governance
- AI-assisted infrastructure operations and operational interfaces

---

## 🧩 Redaction & Security Statement

> 🧾 Public projects use **synthetic or redacted information** where appropriate.  
> No employer or customer confidential information, secrets, private tenant identifiers, or sensitive production configuration is intentionally included.
