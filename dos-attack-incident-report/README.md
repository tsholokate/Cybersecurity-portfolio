# DoS Attack Incident Report — NIST CSF Analysis

## Scenario
A multimedia company offering web design, graphic design, and social media 
marketing services experienced a Denial of Service (DoS) attack that disabled 
internal network access for two hours. An unconfigured firewall allowed a 
malicious actor to flood the network with ICMP packets, overwhelming network 
resources and blocking legitimate traffic.

## Task
Analyzed the incident and developed a network security improvement plan using 
the NIST Cybersecurity Framework (CSF) — covering Identify, Protect, Detect, 
and Respond functions.

## NIST CSF Analysis

### Identify
Conducted a review of network assets, firewall configuration, and access 
controls to determine how the vulnerability (unconfigured firewall) allowed 
the attack to succeed.

### Protect
Recommended implementing a new firewall rule to rate-limit incoming ICMP 
traffic, along with source IP address verification to detect spoofed 
addresses — reducing the attack surface for future ICMP-based floods.

### Detect
Recommended deploying network monitoring software to identify abnormal 
traffic patterns early, alongside an IDS/IPS system to filter suspicious 
ICMP traffic based on defined characteristics.

### Respond
Documented the incident response steps taken: blocking incoming ICMP packets, 
taking non-critical services offline to contain the incident, and restoring 
critical services — then outlined process improvements to reduce response 
time for future incidents.

## Key Skills Demonstrated
- Incident documentation and analysis
- NIST CSF framework application
- Network security fundamentals (ICMP, firewalls, IDS/IPS)
- DoS attack mitigation strategy
