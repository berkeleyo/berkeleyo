<p align="center">
  <!-- Clouds -->
  <img src="https://img.shields.io/badge/Azure-0D47A1?logo=microsoftazure&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-232F3E?logo=amazonaws&logoColor=white" />
  <img src="https://img.shields.io/badge/GCP-1A73E8?logo=googlecloud&logoColor=white" />

  <!-- Azure focus -->
  <img src="https://img.shields.io/badge/Policy%20as%20Code-Bicep-2B95F0?logo=azurepipelines&logoColor=white" />
  <img src="https://img.shields.io/badge/Microsoft%20Intune-4B8BF4?logo=microsoftintune&logoColor=white" />
  <img src="https://img.shields.io/badge/Microsoft%20Sentinel-2C7BE5?logo=microsoftazure&logoColor=white" />
  <img src="https://img.shields.io/badge/Azure%20DevOps-0078D7?logo=azuredevops&logoColor=white" />

  <!-- AWS focus -->
  <img src="https://img.shields.io/badge/EC2-FF9900?logo=amazonec2&logoColor=white" />
  <img src="https://img.shields.io/badge/IAM-4053D6?logo=amazonaws&logoColor=white" />
  <img src="https://img.shields.io/badge/VPC-232F3E?logo=amazonaws&logoColor=white" />

  <!-- GCP focus -->
  <img src="https://img.shields.io/badge/Compute%20Engine-1A73E8?logo=googlecloud&logoColor=white" />
  <img src="https://img.shields.io/badge/Cloud%20Run-4285F4?logo=googlecloud&logoColor=white" />
  <img src="https://img.shields.io/badge/BigQuery-669DF6?logo=googlebigquery&logoColor=white" />

  <!-- Platform & tooling -->
  <img src="https://img.shields.io/badge/Terraform-5C4EE5?logo=terraform&logoColor=white" />
  <img src="https://img.shields.io/badge/Bicep-2B95F0?logo=azurepipelines&logoColor=white" />
  <img src="https://img.shields.io/badge/PowerShell-5391FE?logo=powershell&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-000000?logo=githubactions&logoColor=white" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Grafana-F46800?logo=grafana&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" />
</p>
<h1 align="center">Berkeley — Cloud Engineer</h1>
<p align="center">
  I build and automate on <b>Azure</b>, <b>AWS</b> and <b>GCP</b> using PowerShell and IaC — with secure-by-default patterns, CI/CD, and observability baked in.
</p>

### How I work
- 🔐 **Security-first**: least privilege, IaC guardrails, reproducible environments  
- 🧱 **Infrastructure as Code**: Bicep/Terraform templates over click-ops  
- 🔁 **Automation**: GitHub Actions / Azure DevOps for build, test, lint, deploy  
- 🔭 **Observability**: metrics, logs, and health dashboards as deliverables  
- 🧪 **Tested**: scripts & modules come with examples and linting

### Selected playbooks I’ve shipped
- **Azure governance via Policy-as-Code** — Bicep modules with MG scoping, CI-driven promotion, and real guardrails: *deny Public IP*, *audit required RG tags*, and *deployIfNotExists* scaffolding.
- **Endpoint mgmt with Intune Win32** — opinionated packaging kits: **silent install/uninstall**, robust **detection** scripts, and repeatable folder layout. Examples include New Teams and printer/scanner packages.
- **Network modernization** — discovery of legacy **Basic** Public IPs, exportable migration plan (CSV), and a safe upgrade flow to **Standard** with a change-window checklist.
- **Security automation** — Microsoft Sentinel Logic Apps to **notify Teams** with deep links, and **auto-close low-severity** after dwell time when there’s no related activity.
- **Azure Monitor → Teams** — Action Group + Logic App that posts rich Adaptive Cards, with basic **dedupe/throttling** to prevent alert storms and routing by severity.
- **Fortinet SD-WAN / IPsec references** — copy-ready configs for hub-and-spoke, HA notes, **BGP** tips, and **MTU/fragmentation** guardrails for reliable tunnels.
- **VPN DNS decision guide** — practical patterns for hybrid estates: **Azure DNS Private Resolver**, conditional forwarders, split-horizon DNS; pros/cons and when to use each.
- **Azure DevOps YAML templates** — pipelines for **.NET**, **IaC**, and **PowerShell modules** with caching, test, lint (**PSScriptAnalyzer**), semantic versioning, and publish steps.
- **Grafana backup health** — dashboard JSON plus a small **log parser** to surface failures, aging, and success trends for quick reliability checks.
- **PowerShell Az modules** — utilities like **New-SubBudget**, **Set-RequiredTags**, and **Get-ResourceSummary** to standardize subscription operations.

---

### Projects
<table><tr>
<td valign="top" width="50%">
  <b><a href="https://github.com/berkeleyo/intune-win32-packages">intune-win32-packages</a></b><br/>
  Production-ready Win32 app templates with silent install/uninstall & detection<br/>
  <img alt="Lang" src="https://img.shields.io/badge/PowerShell-informational" />
</td>
<td valign="top" width="50%">
  <b><a href="https://github.com/berkeleyo/fortinet-azure-sdwan-ipsec">fortinet-azure-sdwan-ipsec</a></b><br/>
  Reference IPsec configs and notes for Azure SD-WAN topologies<br/>
  <img alt="Lang" src="https://img.shields.io/badge/Code-informational" />
</td>
</tr>
<tr>
<td valign="top" width="50%">
  <b><a href="https://github.com/berkeleyo/sentinel-automation-playbooks">sentinel-automation-playbooks</a></b><br/>
  Logic Apps for Microsoft Sentinel alert enrichment and response<br/>
  <img alt="Lang" src="https://img.shields.io/badge/Code-informational" />
</td>
<td valign="top" width="50%">
  <b><a href="https://github.com/berkeleyo/unifi-azure-migration-runbook">unifi-azure-migration-runbook</a></b><br/>
  Step-by-step UniFi controller migration hosted on Azure<br/>
  <img alt="Lang" src="https://img.shields.io/badge/PowerShell-informational" />
</td>
</tr>
<tr>
<td valign="top" width="50%">
  <b><a href="https://github.com/berkeleyo/azure-monitor-teams-notifications">azure-monitor-teams-notifications</a></b><br/>
  Azure Monitor ÔåÆ Microsoft Teams notifications via Logic Apps<br/>
  <img alt="Lang" src="https://img.shields.io/badge/PowerShell-informational" />
</td>
<td valign="top" width="50%">
  <b><a href="https://github.com/berkeleyo/azure-devops-pipeline-templates">azure-devops-pipeline-templates</a></b><br/>
  Reusable Azure DevOps YAML templates for .NET, IaC, and PowerShell modules<br/>
  <img alt="Lang" src="https://img.shields.io/badge/Code-informational" />
</td>
</tr>
<tr>
<td valign="top" width="50%">
  <b><a href="https://github.com/berkeleyo/azure-public-ip-migration">azure-public-ip-migration</a></b><br/>
  Discover & migrate Basic Ô×£ Standard Azure Public IPs at scale<br/>
  <img alt="Lang" src="https://img.shields.io/badge/PowerShell-informational" />
</td>
<td valign="top" width="50%">
  <b><a href="https://github.com/berkeleyo/azure-governance-policy-bicep">azure-governance-policy-bicep</a></b><br/>
  Policy-as-code samples & assignment templates for Azure governance<br/>
  <img alt="Lang" src="https://img.shields.io/badge/Bicep-informational" />
</td>
</tr>
<tr>
<td valign="top" width="50%">
  <b><a href="https://github.com/berkeleyo/azure-vpn-dns-guidance">azure-vpn-dns-guidance</a></b><br/>
  DNS options that actually work with Azure VPN client scenarios<br/>
  <img alt="Lang" src="https://img.shields.io/badge/Code-informational" />
</td>
<td valign="top" width="50%">
  <b><a href="https://github.com/berkeleyo/teams-risky-users-card">teams-risky-users-card</a></b><br/>
  Adaptive Card template + Logic App for risky users/sign-ins<br/>
  <img alt="Lang" src="https://img.shields.io/badge/Code-informational" />
</td>
</tr>
<tr>
<td valign="top" width="50%">
  <b><a href="https://github.com/berkeleyo/grafana-backup-monitoring">grafana-backup-monitoring</a></b><br/>
  Dashboards + parser to verify backup health<br/>
  <img alt="Lang" src="https://img.shields.io/badge/Python-informational" />
</td>
<td valign="top" width="50%">
  <b><a href="https://github.com/berkeleyo/powershell-az-modules">powershell-az-modules</a></b><br/>
  Handy PowerShell helpers for Azure resource operations<br/>
  <img alt="Lang" src="https://img.shields.io/badge/PowerShell-informational" />
</td>
</tr>
<tr>
<td valign="top" width="50%">
  <b><a href="https://github.com/berkeleyo/azure-cost-ops-automation">azure-cost-ops-automation</a></b><br/>
  Cloud cost ops: budgets, alerting, lifecycle policies (scripts + guidance).<br/>
  <img alt="Lang" src="https://img.shields.io/badge/PowerShell-informational" />
</td>
<td valign="top" width="50%">
  <b><a href="https://github.com/berkeleyo/berkeleyo.github.io">berkeleyo.github.io</a></b><br/>
  Cloud Engineer Portfolio<br/>
  <img alt="Lang" src="https://img.shields.io/badge/HTML-informational" />
</td>
</tr></table>

---

<p align="center">
  <i>Based in London — open to interesting cloud, automation, and security work.</i>
</p>