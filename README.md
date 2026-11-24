![MasterHead](https://i.pinimg.com/originals/c0/61/8a/c0618aa786979739db4c6c643abdb1f3.gif)

<div align="center">

# Gabriel Lira

### SOC Analyst · Detection Engineering · Security Research

**From security telemetry to reproducible evidence.**

[![Portfolio](https://img.shields.io/badge/PORTFOLIO-Explore-256D5A?style=for-the-badge&logo=firefoxbrowser&logoColor=white)](https://liragbr.github.io)
[![LinkedIn](https://img.shields.io/badge/LINKEDIN-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/Liragbr)
[![Repositories](https://img.shields.io/badge/GITHUB-Projects-24292F?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Liragbr?tab=repositories)

</div>

---

### About

I work in **Security Operations**, investigating suspicious activity across network, endpoint, and identity environments. My focus is on correlating telemetry, assessing evidence, and supporting incident response with clear technical findings.

Outside day-to-day SOC operations, I build independent security labs to explore **detection logic, network protocols, and embedded systems**. I value controlled experiments, automated validation, and documentation that distinguishes observations from assumptions.

### Selected projects

#### 01 · [Identity & Network Correlation Lab](https://github.com/Liragbr/Identity-Network-Correlation-Lab)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Sigma](https://img.shields.io/badge/Sigma-Detection_Rules-30363D?style=flat-square)
![MITRE ATT&CK](https://img.shields.io/badge/MITRE-ATT%26CK-30363D?style=flat-square)
[![CI](https://github.com/Liragbr/Identity-Network-Correlation-Lab/actions/workflows/ci.yml/badge.svg)](https://github.com/Liragbr/Identity-Network-Correlation-Lab/actions/workflows/ci.yml)

A **loopback-only detection lab** that generates authentication, DNS PTR, and TCP activity from local services, then correlates suspicious patterns in defined time windows.

**Evidence:** structured event logs, correlated findings, investigation timelines, case reports, Sigma rules, and automated tests with reproducible replay.

[**Explore the lab →**](https://github.com/Liragbr/Identity-Network-Correlation-Lab)

#### 02 · [WebRTC STUN Analyzer](https://github.com/Liragbr/WebRTC)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TShark](https://img.shields.io/badge/TShark-Packet_Analysis-30363D?style=flat-square)
![PCAP](https://img.shields.io/badge/PCAP-Replay-30363D?style=flat-square)
[![CI](https://github.com/Liragbr/WebRTC/actions/workflows/ci.yml/badge.svg)](https://github.com/Liragbr/WebRTC/actions/workflows/ci.yml)

A network analysis tool for inspecting **STUN responses and observed IP mappings** through live capture or offline PCAP replay.

**Evidence:** controlled-network validation, automated tests, and comparison against expected egress addresses. An observed mapping is **not automatically treated as a confirmed privacy leak**.

[**Inspect the analyzer →**](https://github.com/Liragbr/WebRTC)

#### 03 · [HIDra](https://github.com/Liragbr/HIDra)

![C](https://img.shields.io/badge/C-Firmware-A8B9CC?style=flat-square&logo=c&logoColor=black)
![RP2040](https://img.shields.io/badge/Raspberry_Pi-Pico_W-C51A4A?style=flat-square&logo=raspberrypi&logoColor=white)
![USB HID](https://img.shields.io/badge/USB-HID-30363D?style=flat-square)
[![CI](https://github.com/Liragbr/HIDra/actions/workflows/validation.yml/badge.svg)](https://github.com/Liragbr/HIDra/actions/workflows/validation.yml)

An **embedded security research lab** combining Pico firmware, USB HID, a Python server, and an authenticated communication protocol.

**Evidence:** protocol documentation, host-side tests, simulator-based validation, firmware build checks, and a security audit. **Physical device behavior remains a separate validation requirement.**

[**Review the research →**](https://github.com/Liragbr/HIDra)

---

### Technical focus

| Area | Focus |
| :-- | :-- |
| **Security Operations** | Alert triage, threat detection, incident investigation, incident response |
| **Detection & Analysis** | Network telemetry, evidence correlation, MITRE ATT&CK, Sigma, PCAP analysis |
| **Engineering** | Python, C/C++, Bash, Linux, Git, automated testing, CI/CD |
| **Research** | Network protocols, embedded systems, controlled security experimentation |

<sub>All featured projects are independent research conducted in controlled environments. No employer or client infrastructure is represented.</sub>
