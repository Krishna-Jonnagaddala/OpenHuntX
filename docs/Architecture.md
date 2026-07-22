# Architecture

## Overview

OpenHuntX is designed as a modular threat hunting and detection engineering framework for Microsoft Defender XDR and Microsoft Sentinel.

The project is organised so that each component has a clear purpose. Hunting queries, investigation guides, detection rules, scripts, and documentation are kept separate to make the repository easier to navigate and maintain.

Rather than acting as a collection of standalone KQL queries, OpenHuntX is intended to document the complete investigation process. Each hunt is supported by technical documentation that explains the objective, the relevant telemetry, investigation steps, and where applicable, its mapping to the MITRE ATT&CK framework.

As the project grows, new content will follow the same structure to keep the framework consistent and easy to extend.
