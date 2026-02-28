# 🔐 Cybersecurity Projects Portfolio

A collection of hands-on cybersecurity tools demonstrating core SOC analyst and security engineer competencies. Built to showcase practical skills in malware analysis, phishing detection, and network forensics.

---

## Projects

| # | Project | Description | Skills Shown |
|---|---|---|---|
| 1 | [🔬 Malware Analysis Sandbox](./Malware%20Analysis%20Sandbox/) | Static file analysis — hashes, entropy, PE headers, YARA, VirusTotal | Malware RE, YARA, Threat Intel |
| 2 | [🎣 Phishing Detector](./Phishing%20Detector/) | Email analysis — SPF/DKIM/DMARC, URL inspection, content scoring | Email Security, SOC Analysis |
| 3 | [🌐 Network Traffic Analyzer](./Network%20Traffic%20Analyzer/) | Packet capture — port scan, ARP spoofing, DNS tunneling detection | Network Forensics, IDS Logic |

---

## Quick Start

```bash
git clone https://github.com/coreyarmstrong-sec/Cybersec-Projects
cd Cybersec-Projects

# Project 1: Malware Sandbox
cd "Malware Analysis Sandbox"
pip install pefile yara-python requests
python malware_sandbox.py sample.exe

# Project 2: Phishing Detector
cd "../Phishing Detector"
python phishing_detector.py suspicious.eml

# Project 3: Network Analyzer
cd "../Network Traffic Analyzer"
pip install scapy
python network_analyzer.py --pcap capture.pcap
# OR live: sudo python network_analyzer.py --interface eth0 --duration 60
```

---

## Technical Stack

```
Python 3.8+    ─── Core language
scapy          ─── Packet capture & analysis
pefile         ─── Windows PE format parsing
yara-python    ─── Pattern-based malware detection
requests       ─── API integrations (VirusTotal)
```

---

## Certifications & Background

- CompTIA Security+ ✅
- ISC² CC ✅
- Blue Team Level 1 (BTL1)
- TryHackMe — Active Labs
- UCF — Intelligence & National Security minor
- Homelab: pfSense · Proxmox · Docker · Splunk SIEM

---

## Learning Resources Used

| Topic | Resource |
|---|---|
| Malware Analysis | Practical Malware Analysis (Sikorski & Honig) |
| YARA Rules | https://yara.readthedocs.io |
| Network Security | TCPDump/Wireshark labs |
| Email Security | RFC 7489 (DMARC), RFC 7208 (SPF), RFC 6376 (DKIM) |
| Sample PCAPs | https://www.malware-traffic-analysis.net |
| CTF Practice | TryHackMe, HackTheBox |
