 # Network Traffic Capture and Analysis with Wireshark
  # Overview

This project demonstrates practical network traffic capture and analysis using Wireshark. The goal is to understand how network communications work at packet level and identify useful information from captured traffic.

  # Objectives
Capture network traffic in an authorized environment
Identify common network protocols
Analyze TCP and UDP communications
Investigate DNS queries and responses
Analyze IP addresses and network conversations
Use Wireshark filters to isolate specific traffic
Identify unusual or noteworthy traffic patterns
🛠️ Tools Used
Wireshark
Windows/Linux
TCP/IP
   # Analysis

The captured traffic was examined using Wireshark's packet inspection and filtering capabilities.

Examples of filters used:

dns
tcp
udp
tls
http
ip.addr == 192.168.1.10
tcp.flags.syn == 1
   Key Areas Investigated
DNS Analysis

Examined DNS queries to understand how domain names are resolved into IP addresses.

# TCP Analysis

Analyzed TCP communication, including connection establishment and packet exchanges.

# Protocol Analysis

Used Wireshark statistics and packet details to identify protocols present in the capture.

# IP Analysis

Investigated communication between different hosts and examined network conversations.

  # Screenshots

Screenshots of the analysis are included in the screenshots/ directory.

# 📁 Project Structure
network-traffic-capture-analysis/
├── README.md
├── captures/
├── analysis/
├── screenshots/
└── report/
 # Skills Demonstrated
Network traffic analysis
Packet capture and inspection
TCP/IP fundamentals
DNS analysis
Wireshark filtering
Network troubleshooting
Basic security investigation
# ⚠️ Disclaimer

All traffic analyzed in this project was captured from an authorized environment for educational and cybersecurity learning purposes.

  # Future Improvements
Analyze larger packet captures
Investigate additional protocols
Automate parts of the analysis using Python
Develop more advanced network anomaly detection techniques

## 📸 Packet Analysis

![Wireshark Packet Analysis](screenshots/packet-analysis.png)
