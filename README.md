# Cybersecurity & Network Testing Toolkit

A curated collection of offensive security, network traffic generation, vulnerability assessment, and system analysis tools organized by functional category.

---

## 📂 Repository Structure & Included Tools

The toolkit is organized into the following directories:

| Directory | Included Tools | Description |
| :--- | :--- | :--- |
| **`DDoS generator`** | Hping3, Stress, Apache Benchmark, Slowhttptest, GoldenEye | Tools for stress-testing network resilience and simulating Distributed Denial-of-Service traffic. |
| **`Dictionary and brute force attack tool`** | Medusa Tool, Hydra, Ncrack, John the Ripper | Utilities for credential auditing and password strength testing. |
| **`Firmware Analysis`** | Binwalk, EMBA, Fact, HEXDUMP, Ghidra | Tools for extracting, reverse-engineering, and inspecting embedded device firmware. |
| **`Malware detection tool`** | ClamAV, EMBA, Secops | Scanners and utilities for identifying malicious binaries and suspicious system behavior. |
| **`Network Level Application Level Attack Generators (L4 to L7)`** | Scapy, Metasploit, TRex | High-throughput (1Gbps–10Gbps+) traffic and attack simulators targeting OSI Layers 4 through 7. |
| **`Packet assembler and crafting Manipulation Tool`** | Hping3, IPv6Toolkit, Tenoto, Tcpreplay, Scapy | Utilities for building, modifying, and injecting custom network packets. |
| **`Port scanner`** | Nmap | Network discovery tool for identifying open ports, active services, and OS fingerprints. |
| **`Protocol Fuzzer`** | BeFUZZ, Boofuzz, FFUF, Peachfuzzer, WFUZZ | Automated fuzzing tools for discovering protocol implementation flaws and vulnerabilities. |
| **`Source code Analysis`** | SonarQube (Sonar Cube), Terrascan (Terra Scan), Lizard | Static Application Security Testing (SAST) and IaC analysis tools for auditing source code. |
| **`Syslog Server`** | Rsyslog, Synology NAS, Visual Syslog Server, PS Syslog | Centralized logging utilities for collecting and monitoring system and network event logs. |
| **`Terminal Emulation Software`** | CLI - PuTTY | Clients and utilities for SSH, Telnet, and serial console connections. |
| **`Traffic analysis tool`** | Wireshark, Tcpdump | Packet sniffers and network analyzers for inspecting live or captured (PCAP) traffic. |
| **`Vulnerability scanner`** | Vulscan NSE, OpenVAS, Testssl, Nikto | Automated scanners for detecting known CVEs, SSL/TLS issues, and misconfigurations. |
| **`Web application Vulnerability scanner and Testing`** | OpenSSL, Burp Suite, OWASP-ZAP, Nikto, DirBuster, Skipfish | Tools tailored for testing web apps, directories, and encryption configurations. |
| **`Other`** | AAA Server, FreeRADIUS, UERANSIM, OpenLDAP, cURL, RAN Simulator | Telecom/5G simulators, authentication servers, and standalone network utilities. |
| **`Zipped File with tools list`** | *Archived reference files* | Archived bundles and reference documentation of included utilities. |

---

## 🚀 Getting Started

### Prerequisites
* A dedicated lab environment (e.g., Kali Linux, Ubuntu, Windows for GUI utilities, or isolated Virtual Machines)
* Administrative / `root` privileges (required for raw socket access, packet crafting, and network sniffing tools like `Scapy`, `Hping3`, and `Wireshark`)
* Python 3.x / Go / Java (depending on the specific tool you intend to run)

### Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/](https://github.com/)<your-username>/<repo-name>.git
   cd <repo-name>
