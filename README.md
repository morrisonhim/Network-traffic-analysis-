# Network Traffic Analysis Using Wireshark
# Project Overview
This project demonstrates practical network traffic analysis using Wireshark. The goal was to capture, inspect, and interpret network packets to identify communication patterns, detect anomalies, and strengthen situational awareness- key skills in Security Operations Center (SOC) environments.
Through this analysis, I examined different network protocols, applied custom filters, and documented key findings supported by screenshots.
# Tools used
~ Wireshark
~ Windows
# Methodology
1. **Environment Setup**
   - Installed Wireshark on my personal laptop
   - Verified permission to capture packets on network interfaces
2. **Traffic Capture**
   - Selected active network interfaces
   - Captured live traffic for a set duration
   - Saved captured packets in '.pcap' format
3. **Traffic Filtering & Analysis**
   - Applied protocol filters such as:
    - 'hhtp' to view HTTP request traffic
    - 'dns' to analyze DNS queries and responses
    - 'tcp.flags.syn==1' to detect SYN packets
   - Inspected TCP handshakes, DNS lookups and ARP requests
   - Noted patterns that could indicate scanning or abnormal behavior
4. **Documentation**
   - Captured key findings through annotated screenshots
   - Recorded protocol-level details and timestamps for analysis traceability
## Key Findings
- Observed normal TCP 3-way handshakes and DNS resolution behavior
- Identified several HTTP GET requests to external IPs
- Confirmed expected ARP broadcasts and local subnet activity
## Insights and Impact
- Enhanced unnderstanding of OSI layers and packet structures
- Strengthened ability to filter, dissect, and interpret network communications
- Developed a structured approach to document and report network behavior
- Reinforced skills applicable to SOC analysis, incident detection, and network forensics

## Contact
For questions, feature requests, please contact me via email @newlordkm123gmail.com

