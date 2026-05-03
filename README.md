# SIEM-Based Network Threat Detection System using Splunk and Snort

## Overview
This project implements a real-time Security Information and Event Management (SIEM) system for network threat detection by integrating Snort Intrusion Detection System (IDS) with Splunk Enterprise. The system captures, analyzes, and visualizes network security events generated from simulated cyber attacks in a controlled environment.

The solution demonstrates how modern SOC (Security Operations Center) workflows operate using log aggregation, intrusion detection, and real-time security analytics.

## Objectives
- Deploy and configure Snort as a Network Intrusion Detection System (NIDS)
- Develop custom Snort rules for detecting network-based attacks
- Simulate real-world cyber attacks in a controlled lab environment
- Integrate Snort with Splunk for centralized log analysis
- Enable real-time log forwarding using Splunk Universal Forwarder
- Build dashboards for security event visualization and monitoring

## System Architecture
- Attacker Machine → Generates malicious traffic (simulation)
- Target Machine → Runs Snort IDS + Apache2 (vulnerable services)
- Splunk Forwarder → Collects and forwards logs
- Splunk Enterprise (SIEM) → Analyzes and visualizes security events

## Tools & Technologies
- Snort IDS (Intrusion Detection System)
- Splunk Enterprise Security (SIEM)
- Splunk Universal Forwarder
- Ubuntu 22.04 (Target System)
- Apache2 Web Server
- Linode Cloud (Splunk Hosting)

## Attack Scenarios Simulated
- ICMP Ping Detection
- SSH Authentication Attempts
- FTP Login Attempts
- Port Scanning Detection
- SYN Flood Attack Simulation

## Key Features
- Real-time intrusion detection and alerting
- Custom Snort rule development
- Centralized log aggregation and indexing
- Splunk-based security dashboards
- Attack visualization and trend analysis
- Scalable SIEM pipeline architecture

## Outcomes
- Successfully detected multiple simulated attack vectors
- Achieved real-time log forwarding from Snort to Splunk
- Built interactive dashboards for security monitoring
- Demonstrated SOC-style threat detection workflow
- Improved visibility into network-level security events

## Key Learning Outcomes
- Intrusion Detection System (IDS) configuration and tuning
- SIEM architecture and log analysis
- Network traffic monitoring and security event correlation
- Cyber attack simulation and detection strategies
- Splunk SPL query usage and dashboard design

## Conclusion
This project demonstrates a functional SIEM pipeline combining Snort IDS and Splunk Enterprise to detect, analyze, and visualize network-based cyber threats in real time. It provides a strong foundation for understanding SOC operations and modern cybersecurity monitoring systems.
