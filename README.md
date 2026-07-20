# 🛡️ Network Traffic Analysis & Intrusion Detection using tcpdump, Wireshark, Nmap & Snort
📌 Overview
This project demonstrates the complete workflow of network traffic analysis and intrusion detection in a controlled lab environment using Kali Linux. The objective was to capture live network traffic, analyze packet behavior, simulate suspicious activity through a TCP SYN port scan, and detect malicious traffic using Snort 3 with custom detection rules.
The project provides practical experience with packet capture, protocol analysis, intrusion detection systems (IDS), and network security monitoring.
🎯 Objectives
Capture live network traffic using tcpdump
Analyze packets using Wireshark
Understand TCP/IP communication and the three-way handshake
Perform a controlled TCP SYN scan using Nmap
Detect suspicious activity using Snort 3
Create and test custom Snort detection rules
Gain hands-on experience with network security monitoring
🛠️ Tools & Technologies
Kali Linux
tcpdump
Wireshark
Nmap
Snort 3
Nano Editor
Git & GitHub
TCP/IP Networking
⚙️ Project Workflow
Step 1 – Packet Capture
Captured live network traffic using tcpdump and saved it in PCAP format for analysis.
Step 2 – Baseline Analysis
Generated normal browsing traffic to understand standard network communication.
Step 3 – Network Scanning
Performed a TCP SYN port scan using Nmap against a controlled environment.
Step 4 – Packet Analysis
Opened captured traffic in Wireshark and analyzed:
TCP Three-Way Handshake
SYN packets
DNS traffic
HTTP communication
Packet flow
Step 5 – Intrusion Detection
Configured Snort 3 and created custom detection rules to identify suspicious network activity.
Step 6 – Validation
Generated ICMP traffic and successfully verified that Snort detected the activity and generated alerts.
📷 Project Screenshots
tcpdump Packet Capture
Nmap SYN Scan
Wireshark SYN Packet Analysis
HTTP Stream Analysis
Custom Snort Rule
Snort IDS Alert Detection
📖 Technical Concepts Covered
TCP/IP Protocol Suite
Packet Capture
Packet Inspection
TCP Three-Way Handshake
TCP SYN Scan
HTTP vs HTTPS
Intrusion Detection System (IDS)
Signature-Based Detection
Network Monitoring
Packet Filtering

📊 Results
Successfully captured live network traffic using tcpdump.
Analyzed packet-level communication using Wireshark.
Performed controlled TCP SYN scans using Nmap.
Configured Snort 3 for intrusion detection.
Implemented a custom detection rule.
Successfully generated and verified IDS alerts during live monitoring.
🎓 Skills Demonstrated
Linux Administration
Cybersecurity Fundamentals
Network Security
Packet Analysis
Traffic Monitoring
Wireshark Analysis
tcpdump
Nmap
Snort IDS
Intrusion Detection
TCP/IP Networking
Problem Solving
Technical Documentation
🚀 Future Improvements
Detect SSH brute-force attacks
Create advanced Snort detection rules
Integrate Suricata IDS
Visualize alerts using Splunk
Deploy ELK Stack dashboards
Automate threat detection
Monitor cloud environments
💼 Project Outcome
This project demonstrates practical knowledge of network traffic analysis, packet inspection, and intrusion detection using industry-standard cybersecurity tools. It highlights the ability to capture, analyze, detect, and document network activity in a controlled environment while gaining hands-on experience with real-world security monitoring techniques.
👨‍💻 Author
Waris Sharma
BCA (Cybersecurity) Student
Passionate about Cybersecurity, Network Security, Threat Detection, and Ethical Hacking.
⭐ If you found this project useful, consider giving the repository a star!