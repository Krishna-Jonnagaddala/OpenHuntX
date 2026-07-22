# OpenHuntX

### Enterprise Threat Hunting Framework for Microsoft Defender XDR & Microsoft Sentinel

An open-source project focused on threat hunting, detection engineering, and incident investigation using Microsoft security products.

## About the Project

OpenHuntX is an open-source project that documents practical threat hunting and detection engineering techniques for Microsoft Defender XDR and Microsoft Sentinel.

The goal is to build a collection of well-documented hunting queries, investigation guides, and detection content that security analysts can understand, learn from, and use in their own environments.

This project is being built step by step, with every hunt tested, documented, and mapped to the MITRE ATT&CK framework wherever applicable.

## Why I Built OpenHuntX

While learning Microsoft Defender XDR and Microsoft Sentinel, I noticed that many examples online focus on individual KQL queries without explaining the investigation process behind them.

I wanted to build a project that brings everything together in one place. Instead of collecting queries, the aim is to document the reasoning behind each hunt, explain what the results mean, and describe how an analyst can investigate and respond to suspicious activity.

OpenHuntX is also a personal learning project, so it will continue to grow as I gain more experience and add new detection content.

## Features

Current Features

* Threat hunting queries for Microsoft Defender XDR
* Threat hunting queries for Microsoft Sentinel
* Investigation guides for common attack techniques
* MITRE ATT&CK mappings
* Detection engineering documentation
* Sample hunting scenarios
* PowerShell and Python helper scripts
* Project documentation and learning resources

## Project Structure

```text
OpenHuntX/
│
├── docs/                    # Project documentation
├── KQL/                     # Threat hunting queries
│   ├── DefenderXDR/
│   └── Sentinel/
├── Investigation-Guides/    # Investigation walkthroughs
├── Detection-Rules/         # Detection logic and analytics
├── Playbooks/               # Incident response playbooks
├── Scripts/
│   ├── Python/
│   └── PowerShell/
├── Dashboards/              # Workbook examples
├── Threat-Intel/            # Threat intelligence resources
├── Sample-Logs/             # Sample datasets
└── Images/                  # Screenshots and diagrams
```

# Sprint 1.4 - Supported Platforms

Next, add this section.

```markdown
## Supported Platforms

The current version of OpenHuntX focuses on Microsoft's security ecosystem.

### Microsoft Defender XDR

- Microsoft Defender for Endpoint
- Microsoft Defender for Office 365
- Microsoft Defender for Identity
- Microsoft Defender for Cloud Apps

### Microsoft Sentinel

- Log Analytics Workspace
- Analytics Rules
- Hunting Queries
- Workbooks

## Documentation

Project documentation is available in the `docs` directory.

The documentation explains the overall architecture, data sources, threat hunting methodology, and MITRE ATT&CK mappings used throughout the project.

As the project grows, new documentation will be added alongside each hunting query and investigation guide.

Additional platforms may be supported in future releases.
