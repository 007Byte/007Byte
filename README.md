<p align="center">
  <img src="assets/header.svg" width="100%" alt="Walker Yturbides. Cybersecurity, M.S. at Northeastern University, U.S. Army Veteran." />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/walker-yturbides-8bba011b4"><img src="https://img.shields.io/badge/LinkedIn-Walker_Yturbides-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <img src="https://img.shields.io/badge/Boston,_MA-1B354F?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Boston, MA" />
  <img src="https://img.shields.io/badge/Open_to-Cybersecurity_Co--op-2EA44F?style=for-the-badge" alt="Open to a cybersecurity co-op" />
</p>

```console
walker@shield:~$ whoami
Walker Yturbides · M.S. Cybersecurity @ Northeastern (Dec 2027)

walker@shield:~$ cat background.txt
U.S. Army veteran · former P&G OT/ICS engineer · MBA

walker@shield:~$ cat focus.txt
offensive security · secure architecture · post-quantum crypto · GRC for finance

walker@shield:~$ ./next --role
cybersecurity co-op · fintech & financial services
```

## 🧭 About me

- 🎓 **M.S. Cybersecurity** candidate at **Northeastern University** (Khoury College), graduating December 2027. I also hold an MBA (UMGC) and a B.S. in Electronic Engineering Technology (Wentworth).
- 🏭 **Former OT/ICS engineer at Procter & Gamble.** I hardened 400+ plant computers to an Active Directory standard, wrote allow-list firewall rules from traffic analysis, and led HMI upgrades across 9 production lines.
- 🪖 **U.S. Army veteran.** I led a 16-soldier combat engineer team in South Korea.
- 🐞 **Responsible disclosure.** I found and privately reported two vulnerabilities in my course's grading infrastructure, including an insecure-deserialization risk (CWE-502) that I assessed as Critical. I proved it on an isolated mock and never touched the live system.
- 🔬 **Research.** I'm leading a pre-registered study of whether separate Solana wallets reveal common control, across 218M trades and 7M wallets.
- 🎯 **Goal:** secure the systems that move money, as a security engineer in fintech and financial services.
- 🌎 Bilingual in English and Spanish.

## 🛡️ Featured work

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/007Byte/Quantum_Shield">🔐 Quantum Shield</a></h3>
      Zero-knowledge, post-quantum encrypted file vault for USB, web, mobile and desktop. All crypto runs on the client, so the server never sees plaintext.
      <br/><br/>
      <b>Crypto:</b> hybrid X25519 + ML-KEM-1024, AES-256-GCM-SIV, Argon2id, SRP-6a, Shamir recovery<br/>
      <b>Pipeline:</b> 10 GitHub Actions workflows gating 4,300+ tests, with Semgrep, gosec, gitleaks, Snyk, Trivy, OWASP ZAP, cargo-fuzz, SBOMs and cosign signing
      <br/><br/>
      <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust" />
      <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" />
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/007Byte/web-recon">🌐 web-recon</a></h3>
      Python toolkit for <b>authorized</b> web testing: HTTP request smuggling (CL.TE / TE.CL), cache poisoning and deception, CPDoS, header splitting and multi-stage chains. It grew out of course-lab work where I demonstrated denial-of-service impact in an isolated environment.
      <br/><br/>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
      <img src="https://img.shields.io/badge/zero_dependencies-555555?style=flat-square" alt="Zero dependencies" />
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/007Byte/password-policy">🔑 password-policy</a></h3>
      Password-strength policy module that implements NIST SP 800-63B Rev. 4 and the OWASP Authentication Cheat Sheet. It scores length first, checks against breached-password lists, and detects personal information in passwords.
      <br/><br/>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
      <img src="https://img.shields.io/badge/NIST_SP_800--63B-1B354F?style=flat-square" alt="NIST SP 800-63B" />
      <img src="https://img.shields.io/badge/OWASP-000000?style=flat-square&logo=owasp&logoColor=white" alt="OWASP" />
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/007Byte/ctf-hackathon-kit">🚩 ctf-hackathon-kit</a></h3>
      Offline-ready CTF kit with checklists, cheatsheets and custom tooling for PCAP triage, nmap parsing, binary triage and headless Ghidra. It also includes a malware write-up that maps a typosquat npm dropper to 11 MITRE ATT&amp;CK techniques, with IOCs and a Sigma rule.
      <br/><br/>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
      <img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white" alt="Bash" />
      <img src="https://img.shields.io/badge/MITRE_ATT%26CK-C8102E?style=flat-square" alt="MITRE ATT&CK" />
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🏠 CIA_Home_Shield <sub><i>(private)</i></sub></h3>
      My home network, run like a small enterprise: 6 segmented VLANs under default-deny, IPS with honeypots, DNS locked to the gateway, WPA3-only Wi-Fi, a WireGuard tunnel with a tested kill switch, and off-host logging to a Raspberry Pi 5. Python checks on the UniFi API verify 100+ settings every day and flag drift, and every change goes through approval, rollback and evidence.
      <br/><br/>
      <img src="https://img.shields.io/badge/UniFi-0559C9?style=flat-square&logo=ubiquiti&logoColor=white" alt="UniFi" />
      <img src="https://img.shields.io/badge/WireGuard-88171A?style=flat-square&logo=wireguard&logoColor=white" alt="WireGuard" />
      <img src="https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white" alt="Raspberry Pi" />
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/007Byte/finance-tracker-dashboard">💹 WealthUp</a></h3>
      Full-stack personal-finance platform with budgeting, mortgage planning, investment analysis and an AI coach. It runs on React 19 and Expo with an Express and Supabase back end, Postgres row-level security, AES-256-GCM and Argon2id, and a documented security audit.
      <br/><br/>
      <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
      <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white" alt="Supabase" />
    </td>
  </tr>
</table>

## 🧰 Tech arsenal

| | |
|---|---|
| **Offensive** | ![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=for-the-badge&logo=burpsuite&logoColor=white) ![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kalilinux&logoColor=white) ![nmap](https://img.shields.io/badge/nmap-0E83CD?style=for-the-badge) ![Ghidra](https://img.shields.io/badge/Ghidra-C3171D?style=for-the-badge) ![gdb](https://img.shields.io/badge/gdb-A42E2B?style=for-the-badge&logo=gnu&logoColor=white) |
| **Defense** | ![UniFi](https://img.shields.io/badge/UniFi-0559C9?style=for-the-badge&logo=ubiquiti&logoColor=white) ![WireGuard](https://img.shields.io/badge/WireGuard-88171A?style=for-the-badge&logo=wireguard&logoColor=white) ![iptables](https://img.shields.io/badge/iptables-333333?style=for-the-badge&logo=linux&logoColor=white) ![tcpdump](https://img.shields.io/badge/tcpdump-2C3E50?style=for-the-badge) ![MITRE ATT&CK](https://img.shields.io/badge/MITRE_ATT%26CK-C8102E?style=for-the-badge) ![Sigma](https://img.shields.io/badge/Sigma_rules-5A3E9B?style=for-the-badge) |
| **Crypto & DevSecOps** | ![OpenSSL](https://img.shields.io/badge/OpenSSL-721412?style=for-the-badge&logo=openssl&logoColor=white) ![GnuPG](https://img.shields.io/badge/GnuPG-0093DD?style=for-the-badge&logo=gnuprivacyguard&logoColor=white) ![Semgrep](https://img.shields.io/badge/Semgrep-2B6CB0?style=for-the-badge&logo=semgrep&logoColor=white) ![Snyk](https://img.shields.io/badge/Snyk-4C4A73?style=for-the-badge&logo=snyk&logoColor=white) ![Trivy](https://img.shields.io/badge/Trivy-1904DA?style=for-the-badge&logo=trivy&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white) |
| **Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white) ![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white) ![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white) ![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge) ![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge) ![Julia](https://img.shields.io/badge/Julia-9558B2?style=for-the-badge&logo=julia&logoColor=white) |
| **Platforms** | ![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black) ![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white) ![VirtualBox](https://img.shields.io/badge/VirtualBox-183A61?style=for-the-badge&logo=virtualbox&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white) ![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=for-the-badge&logo=duckdb&logoColor=black) |
| **GRC** | ![NIST CSF 2.0](https://img.shields.io/badge/NIST_CSF_2.0-1B354F?style=for-the-badge) ![NIST SP 800-63B](https://img.shields.io/badge/NIST_SP_800--63B-1B354F?style=for-the-badge) ![PCI DSS](https://img.shields.io/badge/PCI_DSS-1B354F?style=for-the-badge) ![STRIDE](https://img.shields.io/badge/STRIDE-1B354F?style=for-the-badge) ![CVSS](https://img.shields.io/badge/CVSS-1B354F?style=for-the-badge) |

## 🗺️ Path so far

| | Role | Where | When |
|:---:|---|---|---|
| 🎓 | M.S. Cybersecurity | Northeastern University, Khoury College | 2025 – Dec 2027 |
| 🪖 | Combat Engineer Team Leader | U.S. Army, 11th Engineer Battalion | 2021 – 2024 |
| 🎓 | MBA, GPA 3.83 | University of Maryland Global Campus | 2023 |
| 🏭 | Power Controls & Information Systems Engineer (OT/ICS) | Procter & Gamble | 2014 – 2018 |
| 🎓 | B.S. Electronic Engineering Technology | Wentworth Institute of Technology | 2014 |

## 🔭 Right now

- 🔬 Wrapping up the Solana wallet-linkability study for CS 6983
- 🏠 Hardening CIA_Home_Shield: assurance, recovery drills and controlled admin access
- 📚 CY 5010, Foundations of Information Assurance: post-quantum file sharing and network security labs

## 🤝 Let's connect

<p align="left">
  <a href="https://www.linkedin.com/in/walker-yturbides-8bba011b4"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="Connect on LinkedIn" /></a>
</p>

<p align="center">
  <i>"Read More, Learn More, Change the Globe."</i><br/>
  <sub>Last updated November 2026</sub>
</p>
