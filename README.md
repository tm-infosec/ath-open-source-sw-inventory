# Cybersecurity & Network Testing Toolkit

A curated collection of offensive security, network traffic generation, vulnerability assessment, and system analysis tools organized by functional category[cite: 1, 2].


---

## 📂 Repository Structure & Included Tools

The toolkit is organized into the following directories:

| Directory | Included Tools | Description |
| :--- | :--- | :--- |
| **`DDoS generator`**[cite: 1, 2] | Hping3, Stress, Apache Benchmark, Slowhttptest, GoldenEye | Tools for stress-testing network resilience and simulating Distributed Denial-of-Service traffic[cite: 1, 2]. |
| **`Dictionary and brute force attack tool`**[cite: 1, 2] | Medusa Tool, Hydra, Ncrack, John the Ripper[cite: 2] | Utilities for credential auditing and password strength testing[cite: 1, 2]. |
| **`Firmware Analysis`**[cite: 1, 2] | Binwalk, EMBA, Fact, HEXDUMP, Ghidra[cite: 2] | Tools for extracting, reverse-engineering, and inspecting embedded device firmware[cite: 1, 2]. |
| **`Malware detection tool`**[cite: 1, 2] | ClamAV, EMBA, Secops[cite: 2] | Scanners and utilities for identifying malicious binaries and suspicious system behavior[cite: 1, 2]. |
| **`Network Level Application Level Attack Generators (L4 to L7)`**[cite: 1, 2] | Scapy, Metasploit, TRex[cite: 2] | High-throughput (1Gbps–10Gbps+) traffic and attack simulators targeting OSI Layers 4 through 7[cite: 1, 2]. |
| **`Packet assembler and crafting Manipulation Tool`**[cite: 1, 2] | Hping3, IPv6Toolkit, Tenoto, Tcpreplay, Scapy[cite: 2] | Utilities for building, modifying, and injecting custom network packets[cite: 1, 2]. |
| **`Port scanner`**[cite: 1, 2] | Nmap[cite: 2] | Network discovery tool for identifying open ports, active services, and OS fingerprints[cite: 1, 2]. |
| **`Protocol Fuzzer`**[cite: 1, 2] | BeFUZZ, Boofuzz, FFUF, Peachfuzzer, WFUZZ[cite: 2] | Automated fuzzing tools for discovering protocol implementation flaws and vulnerabilities[cite: 1, 2]. |
| **`Source code Analysis`**[cite: 1, 2] | SonarQube (Sonar Cube), Terrascan (Terra Scan), Lizard[cite: 2] | Static Application Security Testing (SAST) and IaC analysis tools for auditing source code[cite: 1, 2]. |
| **`Syslog Server`**[cite: 1, 2] | Rsyslog, Synology NAS, Visual Syslog Server, PS Syslog[cite: 2] | Centralized logging utilities for collecting and monitoring system and network event logs[cite: 1, 2]. |
| **`Terminal Emulation Software`**[cite: 1, 2] | CLI - PuTTY[cite: 2] | Clients and utilities for SSH, Telnet, and serial console connections[cite: 1, 2]. |
| **`Traffic analysis tool`**[cite: 1, 2] | Wireshark, Tcpdump[cite: 2] | Packet sniffers and network analyzers for inspecting live or captured (PCAP) traffic[cite: 1, 2]. |
| **`Vulnerability scanner`**[cite: 1, 2] | Vulscan NSE, OpenVAS, Testssl, Nikto[cite: 2] | Automated scanners for detecting known CVEs, SSL/TLS issues, and misconfigurations[cite: 1, 2]. |
| **`Web application Vulnerability scanner and Testing`**[cite: 1, 2] | OpenSSL, Burp Suite, OWASP-ZAP, Nikto, DirBuster, Skipfish[cite: 2] | Tools tailored for testing web apps, directories, and encryption configurations[cite: 1, 2]. |
| **`Other`**[cite: 1, 2] | AAA Server, FreeRADIUS, UERANSIM, OpenLDAP, cURL, RAN Simulator[cite: 2] | Telecom/5G simulators, authentication servers, and standalone network utilities[cite: 1, 2]. |
| **`Zipped File with tools list`**[cite: 1] | *Archived reference files* | Archived bundles and reference documentation of included utilities[cite: 1]. |

---

## 🚀 Getting Started

### Prerequisites
* A dedicated lab environment (e.g., Kali Linux, Ubuntu, Windows for GUI utilities, or isolated Virtual Machines)
* Administrative / `root` privileges (required for raw socket access, packet crafting, and network sniffing tools like `Scapy`, `Hping3`, and `Wireshark`)[cite: 2]
* Python 3.x / Go / Java (depending on the specific tool you intend to run)

### Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/](https://github.com/)<your-username>/<repo-name>.git
   cd <repo-name>
