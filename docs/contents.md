[Home](../README.md) |
|--------------------|

# Contents

## Widgets

| Widget Name      | Description                                                                                                                                                        |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| FortiRecon Theme | This widget is designed to serve files essential for applying a custom theme to FortiRecon.                                                                        |
| Playbook List    | Selects and execute playbook from the FortiRecon Screen                                                                                                            |
| Playbook Config  | This widget lists available playbooks, allows to select a specific playbook for execution, show list of required connectors from playbooks and install/config them |
| Create Agent     | Agents act as the execution environment for your connectors. Once created, you can install, configure, and monitor connectors seamlessly through this agent.       |


## Playbook Collections


APT Intelligence

This collection of playbooks is focused towards gathering intelligence about APT groups from FortiRecon ACI reporting.

| Playbook Name                            | Description                                                                            |
| ---------------------------------------- | -------------------------------------------------------------------------------------- |
| Get Intelligence Reportings on APT Group | This playbook retrieves FortiRecon Intelligence reporting on particular APT group.     |
| Get IOCs of APT group                    | This playbook retrieves Indicators of Compromise associated with particular APT group. |


2. **CERT Advisories** - This collection of playbook is focused towards gathering advisories from different CERT (Computer Emergency Response Team) alerts that are published as a part of FortiRecon ACI OSINT reporting.

| Playbook Name                     | Description                                                                                               |
| --------------------------------- | --------------------------------------------------------------------------------------------------------- |
| Get Advisories of Particular CERT | This playbook retrieves advisories by CERT that are released by FortiRecon as a part of OSINT collection. |

3. **Malware Intelligence** - This collection of playbooks is focused towards gathering intelligence about malwares from FortiRecon ACI reporting.

| Playbook Name                               | Description                                                                                                 |
| ------------------------------------------- | ----------------------------------------------------------------------------------------------------------- |
| Get Intelligence Reportings on Infostealers | This playbook retrieves FortiRecon Intelligence reporting on Credential Stealer malwares.                   |
| Get Intelligence Reportings on Malware      | This playbook retrieves FortiRecon Intelligence reportings which includes malware used in threat campaigns. |
| Get Infostealers IOCs                       | This playbook retrieves Indicators of Compromise of Infostealer malware reported by FortiRecon.             |

4. **Ransomware Intelligence** - This collection of playbooks is focused towards gathering intelligence about Ransomware Groups from FortiRecon ACI module.

| Playbook Name                                   | Description                                                                                                                                          |
| ----------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- |
| Supply Chain Ransomware Incident                | This playbook checks if any vendor monitored under FortiRecon's Ransomware Intelligence suffered a ransomware incident.                              |
| Ransomware Group Profile                        | This playbook retrieves intelligence on a specific ransomware group, including targeted industries and countries based on the ransomware group name. |
| Get Intelligence Reportings on Ransomware Group | This playbook retrieves FortiRecon Intelligence reporting on Ransomware group.                                                                       |
| Get IOCs of Ransomware Group                    | This playbook retrieves Indicators of Compromise associated with particular Ransomware group.                                                        |
| Exploited Vulnerabilities by Ransomware Group   | This playbook retrieves Vulnerabilities Exploited by Ransomware Group.                                                                               |

5. **Strategic Threat Intelligence** - This collection of playbook is focused towards FortiRecon Intelligence Trends Reporting. It includes Adversary Profile, Global Threat Landscape Report that is published Monthly, Quarterly and Half-yearly.

| Playbook Name                         | Description                                                                                                                                                                           |
| ------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Get Strategic Intelligence Reportings | This playbook retrieves FortiRecon Intelligence Trends Reporting. It includes Adversary Profile, Global Threat Landscape Report that is published Monthly, Quarterly and Half-yearly. |

6. **Ticketing Automation** - This collection of playbooks is focused towards creating ticket for alerts that are created for various threats which are reported by FortiRecon.

| Playbook Name                                       | Description                                                                                                                                                                                            |
| --------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Create Ticket for Typosquat Domain Threat Alerts    | This playbook helps Analyst to create custom tickets in respective ticketing platform for threats that are reported by FortiRecon Brand Protection > Domain Threats module.                            |
| Create Ticket for Stealer Infection On Sale Alerts  | This playbook helps analyst to create custom tickets in respective ticketing platform for High-risk issues found in Brand Protection > Code Repo Exposure.                                             |
| Create Ticket for Stealer Infection Leaked Alerts   | This playbook helps Analyst to create custom tickets in respective ticketing platform for threats that are reported by FortiRecon Adversary Centric Intelligence > Stealer Infections (Leaked) module. |
| Create Ticket for Social Media Impersonation Alerts | This playbook helps Analyst to create custom tickets in respective ticketing platform for threats that are reported by FortiRecon Brand Protection > Social Media Impersonation module.                |
| Create Ticket for Rogue Mobile Application Alerts   | This playbook helps Analyst to create custom tickets in respective ticketing platform for threats that are reported by FortiRecon Brand Protection > Rogue Mobile Apps module.                         |
| Create Ticket for Open Bucket Exposure Alerts       | This playbook helps Analyst to create custom tickets in respective ticketing platform for threats that are reported by FortiRecon Brand Protection > Open Bucket Exposure module.                      |
| Create Ticket for Leaked Credential Alerts          | This playbook helps Analyst to create custom tickets in respective ticketing platform for threats that are reported by FortiRecon EASM > Leaked Credentials module.                                    |
| Create Ticket for EASM Security Issues              | This playbook helps Analyst to create custom tickets in respective ticketing platform for security issues that are reported by FortiRecon EASM module.                                                 |
| Create Ticket for Code Repo Exposure Alerts         | This playbook helps analyst to create custom tickets in respective ticketing platform for High-risk issues found in Brand Protection > Code Repo Exposure.                                             |

7. **Utilities** - This collection of playbooks contains supporting playbooks for all the other playbooks such as sending an emails or creates a JIRA Ticket

| Playbook Name           | Description                                                                                                                                                                                          |
| ----------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Send Email Notification | This is generic playbook that is used by all the playbook that generates the reports, it converts the report data JSON received from the parent playbooks to CSV and sends to the desired recipients |
| Create JIRA Ticket      | This is generic playbook that generates the JIRA ticket FortiRecon Alerts                                                                                                                            |


8. **Vulnerability Intelligence** - This collection of playbooks is focused towards gathering Vulnerability Intelligence from FortiRecon.

| Playbook Name                                 | Description                                                                                                              |
| --------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------ |
| Get Intelligence Reportings on Exploited CVEs | This playbook retrieves FortiRecon Intelligence reporting on exploited CVEs                                              |
| Get IOCs of Exploited CVE                     | This playbook retrieves Indicators of Compromise associated with CVE exploitation.                                       |
| Get FortiRecon Context of Vulnerability       | This playbook retrieves the context of the vulnerability in terms of Darknet chatter, Available Exploits, Exploited, etc |
| Get FortiRecon Severity of the CVE            | This playbook retrieves FortiRecon scoring of the vulnerability.                                                         |

# Next Steps

| [Installation](./setup.md#installation) | [Configuration](./setup.md#configuration) | [Usage](./usage.md) |
| --------------------------------------- | ----------------------------------------- | ------------------- |
