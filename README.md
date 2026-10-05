<!-- Profile README for github.com/berkeleyo -->
<div align="center">
  
# Hi, I'm Berkeley 👋

<!-- Badges Row -->
![Profile Views](https://komarev.com/ghpvc/?username=berkeleyo&color=blue&style=for-the-badge)
![Experience](https://img.shields.io/badge/Experience-6%2B%20years-1f6feb?style=for-the-badge&logo=github)
![Lines of Code](https://img.shields.io/badge/Lines%20of%20Code-100k%2B-blue?style=for-the-badge)

<!-- Tech stack badges -->
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

Cloud engineer working across **platform infrastructure, networking, security, and automation**.

I build and operate cloud systems with an emphasis on **infrastructure as code, predictable change, operational resilience, and clear engineering boundaries**.

- 🏗️ **Cloud & Platform:** Azure, AWS, and GCP infrastructure, Kubernetes, containers, CI/CD, and repeatable platform patterns
- 🌐 **Networking:** Routing, hybrid connectivity, secure ingress/egress, load balancing, traffic engineering, and network security
- 🔐 **Security & Identity:** Least privilege, JIT access, identity federation, policy-driven controls, and workload security
- ⚙️ **Infrastructure as Code:** Terraform, Bicep, PowerShell, YAML, GitHub Actions, and Azure DevOps
- 📊 **Operations:** Observability, validation, controlled cutovers, rollback, incident readiness, and operational runbooks
- ✍️ **Engineering Practice:** Reversible change, explicit failure modes, automation, and documentation designed for handover

I also explore AI-assisted automation and event-driven systems where they provide useful interfaces to infrastructure and operational workflows.

---

## 🏗️ Cloud & Platform Engineering

Infrastructure patterns spanning cloud platforms, containers, orchestration, delivery pipelines, and infrastructure as code.

| Project | Description | Stack |
|---|---|---|
| [**Production Cloud Network Platform**](https://github.com/berkeleyo/production-cloud-network-platform) | Synthetic cloud infrastructure platform modelling secure ingress, egress, tiered segmentation, route control, and offline Terraform validation. | 🏗️ Terraform · Azure · Networking · Testing |
| [**AKS GitOps**](https://github.com/berkeleyo/azure-aks-gitops) | GitOps deployment pattern for AKS using declarative configuration and automated reconciliation across Kubernetes environments. | ☸️ Kubernetes · AKS · GitOps · YAML |
| [**GKE Production Platform**](https://github.com/berkeleyo/gcp-gke-prod) | GKE platform pattern covering workload deployment, platform controls, and operational conventions in Google Cloud. | ☸️ Kubernetes · GCP · GKE · Operations |
| [**Container Apps CI/CD Starter**](https://github.com/berkeleyo/azure-containerapps-cicd-starter) | Container deployment pattern demonstrating CI/CD wiring and a minimal cloud-native application lifecycle. | 📦 Containers · Azure · CI/CD · DevOps |

---

## 🌐 Networking & Secure Connectivity

Patterns for deterministic traffic flow, secure connectivity, explicit routing, controlled egress, and predictable failure modes across cloud and hybrid environments.

| Project | Description | Stack |
|---|---|---|
| [**Fortinet SD-WAN + IPsec**](https://github.com/berkeleyo/fortinet-azure-sdwan-ipsec) | SD-WAN and IPsec architecture covering HA, BGP routing, MTU tuning, and operational validation. | 🧱 Fortinet · Azure · SD-WAN · IPsec |
| [**Cloud-Secure Egress Policy**](https://github.com/berkeleyo/cloud-secure-egress-firewall-policy) | Centralised outbound control using policy enforcement and explicit routing to remove uncontrolled Internet egress. | 🔐 Network Security · Firewall · Azure |
| [**Azure Firewall Multi-Site Publishing**](https://github.com/berkeleyo/azure-firewall-multi-site-publishing) | Controlled ingress pattern for publishing multiple internal applications through Azure Firewall with backend isolation and reversible cutover. | 🔥 Azure Firewall · Networking · Security |
| [**Hub-Spoke Hybrid Routing**](https://github.com/berkeleyo/azure-hub-spoke-hybrid-routing-pattern) | Hybrid routing architecture using UDRs, gateway transit, and scoped prefix steering for partner connectivity. | 🌐 Routing · Azure · Hybrid |
| [**Azure VPN Patterns**](https://github.com/berkeleyo/azure-vpn-repo) | VPN deployment and troubleshooting patterns covering authentication, DNS behaviour, and connectivity hardening. | 🌐 VPN · Azure · DNS · Troubleshooting |

---

## 🔐 Identity & Security Engineering

Identity and security patterns centred on reducing standing privilege, making access time-bound, and keeping security controls auditable.

| Project | Description | Stack |
|---|---|---|
| [**Access Governance Request Platform**](https://github.com/berkeleyo/access-governance-request-platform) | Identity-driven access governance managing time-bound permissions through request workflows, approvals, expiry, and audit evidence. | 🔐 Identity · Governance · Automation |
| [**Cloud Access Broker — JIT**](https://github.com/berkeleyo/cloud-access-broker-jit-multicloud) | Multi-cloud JIT access pattern providing temporary privilege across Azure and AWS with approval, revocation, and audit controls. | ☁️ AWS · Azure · IAM · JIT |
| [**AWS JIT Access**](https://github.com/berkeleyo/aws-jit-access) | Temporary AWS privilege model using Identity Center and workflow-driven access with revocation and auditability. | ☁️ AWS · 🐍 Python · IAM · JIT |
| [**Azure Access Automation**](https://github.com/berkeleyo/azure-access-automation) | RBAC lifecycle and JIT automation for time-bound entitlement approvals and access management. | 🔐 Azure · RBAC · PowerShell |
| [**Time-Bound Geo Bypass Access**](https://github.com/berkeleyo/time-bound-geo-bypass-access) | Time-bound access-control pattern for geo-based policy exceptions with explicit expiry and operational traceability. | 🔐 Identity · Security · Automation |
| [**GCP External Security Pipelines**](https://github.com/berkeleyo/gcp-external-security-pipelines) | Security automation and pipeline controls in GCP covering identity, validation, and operational guardrails. | ☁️ GCP · Security · Pipelines |

---

## ☁️ Architecture & Modernisation

Architecture and migration work focused on controlled transitions, operational constraints, validation, and maintainable target states.

| Project | Description | Stack |
|---|---|---|
| [**AWS Modernisation Architecture**](https://github.com/berkeleyo/example-modernization-aws-architecture) | AWS architecture mapping a legacy data platform through transition states, migration sequencing, and operational controls. | ☁️ AWS · Architecture · Migration · Security |
| [**Enterprise CRM/ERP Platform Deployment**](https://github.com/berkeleyo/enterprise-crm-erp-platform-deployment) | CRM/ERP deployment pattern covering hardened Linux, NGINX reverse proxying, TLS automation, mail flow, and operational runbooks. | 🐧 Linux · NGINX · TLS · Operations |
| [**UniFi Controller Cloud Migration**](https://github.com/berkeleyo/unifi-controller-cloud-migration) | Migration playbook for moving a UniFi controller from legacy hosting to cloud infrastructure with DNS cutover, hardening, and access controls. | ☁️ Azure · Linux · DNS · Migration |
| [**Azure Public IP Migration**](https://github.com/berkeleyo/azure-public-ip-migration) | Inventory-led migration framework for moving Basic SKU public IPs to Standard SKU with validation and rollback sequencing. | ☁️ Azure · PowerShell · Validation |

---

## ⚙️ Automation, Governance & Operations

Engineering patterns for policy enforcement, repeatability, observability, operational control, and reducing manual infrastructure work.

| Project | Description | Stack |
|---|---|---|
| [**Azure Governance Baseline Framework**](https://github.com/berkeleyo/azure-governance-baseline-framework) | Governance baseline covering naming rules, tagging, policy-as-code, drift detection, and controlled remediation. | ☁️ Azure · Policy · PowerShell |
| [**Azure Cost & Tagging Governance**](https://github.com/berkeleyo/azure-cost-tagging) | Policy and automation for enforcing cost-allocation tags and repairing configuration drift across subscription estates. | ☁️ Azure · Governance · Automation |
| [**LogicMonitor Hybrid Monitoring**](https://github.com/berkeleyo/logicmonitor-hybrid-monitoring) | Hybrid observability pattern providing monitoring, alerting, and operational visibility across multiple environments. | 📊 LogicMonitor · Monitoring · Hybrid |
| [**Grafana + Kibana Observability**](https://github.com/berkeleyo/observability-grafana-kibana) | Centralised metrics and log-analysis patterns for hybrid infrastructure and operational dashboards. | 📊 Grafana · Kibana · Observability |
| [**M365 Security Alerts to Teams**](https://github.com/berkeleyo/m365-security-alerts-to-teams) | Workflow aggregating security alerts into Teams with enrichment and operational triage context. | 🔐 Security · Logic Apps · Automation |

---

## 🤖 AI & Event-Driven Systems

Exploring event-driven and AI-assisted systems as an extension of infrastructure and operational automation.

| Project | Description | Stack |
|---|---|---|
| [**AI Voice Agent Platform**](https://github.com/berkeleyo/ai-voice-agent-platform-repo) | Event-driven voice agent platform covering enquiry intake, outbound workflows, structured data capture, and operational automation. | 🤖 AI · Azure Functions · Event-Driven |

---

## 🧠 Engineering Focus

- Cloud infrastructure and platform engineering across multiple cloud environments
- Kubernetes, containers, infrastructure as code, and automated delivery
- Deterministic networking, traffic engineering, and secure ingress/egress
- Identity-first security and least-privilege access models
- Observability, operational resilience, and predictable failure modes
- Controlled change, validation, rollback, and incident readiness
- Repeatable engineering patterns designed for long-term operational ownership

---

## 🚀 Professional Impact

- Reduced standing privilege through identity-driven elevation models across cloud environments.
- Delivered production migrations and cutovers with defined validation and rollback paths.
- Standardised infrastructure, network, and access patterns to reduce operational drift.
- Built automation replacing manual provisioning and configuration workflows.
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

- Internal infrastructure platforms and reusable platform abstractions
- Kubernetes and cloud-native infrastructure patterns
- Workload identity and cross-cloud security models
- Zero-trust segmentation and cloud traffic-control patterns
- Policy-as-code and automated infrastructure governance
- AI-assisted infrastructure operations

---

## 🧩 Redaction & Security Statement

> 🧾 Public projects use **synthetic or redacted information** where appropriate.  
> No employer or customer confidential information, secrets, private tenant identifiers, or sensitive production configuration is intentionally included.
