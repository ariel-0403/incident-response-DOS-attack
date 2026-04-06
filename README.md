# Incident Response Report - DoS Attack (NIST CSF)

This project presents an incident response analysis based on a Denial of Service (DoS) attack scenario. The analysis follows the NIST Cybersecurity Framework (CSF) to evaluate the incident and propose security improvements.

## Objective

To analyze a network-based DoS attack and develop a structured incident response plan using the five core functions of the NIST CSF: Identify, Protect, Detect, Respond, and Recover.

## Scenario Overview

A multimedia company experienced a network outage caused by a flood of ICMP packets. The attack overwhelmed the internal network due to an unconfigured firewall, making services unavailable for approximately two hours.

## Incident Summary

- **Attack Type:** Denial of Service (DoS) – ICMP Flood  
- **Impact:** Network services unavailable for 2 hours  
- **Cause:** Misconfigured firewall allowing ICMP traffic  
- **Response:** Blocked ICMP traffic, disabled non-critical services, restored critical systems  

## NIST CSF Analysis

### Identify
- Detected a DoS attack affecting internal network services  
- Identified firewall misconfiguration as the root cause  

### Protect
- Implemented firewall rules and ICMP rate limiting  
- Recommended network segmentation and stronger access controls  

### Detect
- Deployed network monitoring tools  
- Implemented IDS/IPS for traffic analysis  
- Established alerting for abnormal traffic patterns  

### Respond
- Contained the attack by blocking malicious traffic  
- Isolated affected systems  
- Documented the incident and improved response procedures  

### Recover
- Restored network functionality  
- Verified system integrity  
- Implemented improvements to prevent future incidents  

## Skills Demonstrated

- Incident analysis  
- Network security fundamentals  
- NIST Cybersecurity Framework (CSF)  
- Threat detection and response  
- Security recommendations  

## Files

- Incident_report_analysis.docx  
