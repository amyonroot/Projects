# Security Operations Center Home Lab

This project is my fully built SOC-style home lab designed to simulate real-world enterprise security operations.
It includes a firewall, Active Directory domain, endpoint telemetry, SIEM monitoring, and attacker simulations to analyze security events and develop practical blue-team skills.

The goal of this lab is to understand how attacks unfold, how defenders detect them, and how logs flow across systems to support incident investigation and threat hunting.

## Lab Architecture Overview

The environment consists of:

- pfSense Firewall – traffic filtering, NAT, and logging

- Windows Server 2022 (AD DS) – Active Directory domain controller

- Windows 10 Client – domain-joined workstation

- Ubuntu Server (Splunk Enterprise) – SIEM for log ingestion and analysis

- Sysmon – detailed Windows endpoint telemetry

- Kali Linux – attacker machine for recon and exploitation testing

All systems run inside VirtualBox on my host machine using an isolated internal network.

## Skills Demonstrated

- SIEM deployment & configuration (Splunk)

- Log forwarding using Splunk Universal Forwarder

- Windows event log analysis

- Sysmon installation, configuration, and event interpretation

- Network segmentation & firewall rule creation (pfSense)

- Active Directory setup and management

- Incident response fundamentals

- Attack simulation using Kali Linux

- Query building and dashboard creation in Splunk
