# MITRE ATT&CK Attack Lifecycle Detection Lab
### *Wazuh SIEM + Sysmon + Atomic Red Team*
This project is based on [Wazuh: Emulation of ATT&CK Techniques](https://wazuh.com/blog/emulation-of-attck-techniques-and-detection-with-wazuh/).
I demonstrate the components of basic network configuration and using Wazuh to ingest logs generated from Atomic Red Team Tests. Everything performed was completed on my homelab stack.

## Objective
The main objective is to create custom rules that detect and log attack vectors generated from the Atomic Tests. Other objectives involved understanding sysmon, event viewer, xml configuration files, creating custom rules, and fixing errors or using workarounds when encountering errors.

### Lab Topology
[Basic Network Diagram](https://github.com/ProjectTapioca/Wazuh-ART-Tests/blob/main/Network/Network%20Diagram.png)
of the infrastructure utilized. Two VLANs were utilized. One is for managing the proxmox server, the second is for wazuh and the target VM.

## List of Equipment
Edgerouter-x-sfp<br>Cisco Catalyst 2960-C<br>Proxmox Server (PC)<br>Management PC<br>Wazuh Virtual Machine<br>Windows 11 Virtual Machine

## Tools & Versions
Wazuh v:4.14.x
Sysmon: Olaf config
Proxmox: Version

## Project Goals
bullet list

### Challenges & Solutions
Troubleshooting shines here, take note of this

## Detection Workflow
Select a test - run and fix if possible (add to troubleshoots) - verify in Event Viewer - verify in Wazuh - Write Rule - Validate Rule - Document. Repeat

### Tests & Rules
List of Tests<br>Inside the folders will contain screenshots of eventviewer, raw log in Wazuh, custom rule created, dashboard of the log after rule created

### Learning Lessons
Errors that occured and what I learned
