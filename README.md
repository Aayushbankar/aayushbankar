<div align="center">

# ⚡ Aayush Bankar
### Systems Security Researcher & AI-Augmented Systems Architect

[![Cybersecurity Analyst](https://img.shields.io/badge/Role-Cybersecurity_Analyst_%40_CypherMatrix-0052CC?style=flat-square&logo=securityscorecard&logoColor=white)](https://cyphermatrix.io/)
[![SIH 2026](https://img.shields.io/badge/Hackathon-SIH_2026_Screening_Round-FF9900?style=flat-square&logo=target&logoColor=white)](https://github.com/Aayushbankar/spectre-prism)
[![Location](https://img.shields.io/badge/Location-Gandhinagar%2C_India-107C41?style=flat-square&logo=google-maps&logoColor=white)](https://en.wikipedia.org/wiki/Gandhinagar)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aayushbankar/)
[![Webfolio](https://img.shields.io/badge/Webfolio-Explore-181717?style=flat-square&logo=firefox&logoColor=white)](https://aayushbankar.github.io/webfolio/)

<p align="center">
  <em>Engineering at the confluence of kernel internals, low-level vulnerability research, and sovereign AI architectures.</em>
</p>

```
[ ARCHITECTURE & VULN RESEARCH ] ────► [ SLUB HEAP GROOMING ] ────► [ VERIFIABLE EVIDENCE PROVENANCE ]
```

---

</div>

## 📌 Executive Summary

I am a security researcher and software engineer operating across **low-level systems security**, **exploit chain reproduction**, and **architectural orchestration**:
- **Exploit & Vulnerability Research:** Deep-dive Linux kernel memory corruption (SLUB UAF, cross-cache sprays, ROP gadget synthesis under retpoline) and Android platform security flaws.
- **Sovereign Systems Design:** Architecting high-throughput data pipelines with SIMD parsing, OCSF normalization, and multi-signature cryptographic provenance.
- **AI-Augmented Engineering:** Designing autonomous research agents, local multimodal voice companions, and mathematically verifiable test ledgers.

---

## 🔬 Flagship Research & Systems Engineering

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🔐 Vulnerability & Exploit Research</h3>
      <ul>
        <li>
          <a href="https://github.com/Aayushbankar/cve-2026-28576"><b>CVE-2026-28576: Android Contacts SQLi</b></a><br/>
          <sub>Zero-permission boolean-oracle SQL Injection in <code>ContactsProvider</code> via <code>targetSdk</code>-gated strict SQL checks. Complete PoC, Red Team verification app, YARA & Suricata signatures.</sub><br/>
          <img src="https://img.shields.io/badge/Android-Vulnerability-3DDC84?style=flat-square&logo=android&logoColor=white" />
          <img src="https://img.shields.io/badge/Zero--Permission-Exploit-red?style=flat-square" />
        </li>
        <br/>
        <li>
          <a href="https://github.com/Aayushbankar/bad_epoll_ab_tier2"><b>CVE-2026-46242: Linux Kernel "Bad Epoll"</b></a><br/>
          <sub>x86_64 root exploit reproduction on Linux 6.12.67 via kernelCTF/QEMU (two-stage ROP pivot + <code>msg_msg</code> cross-cache reclamation) + novel research porting to Android ARM64 GKI under kCFI & PAC.</sub><br/>
          <img src="https://img.shields.io/badge/Linux_Kernel-Exploit-FCC624?style=flat-square&logo=linux&logoColor=black" />
          <img src="https://img.shields.io/badge/Whitepaper-26_Pages-blue?style=flat-square" />
        </li>
        <br/>
        <li>
          <a href="https://github.com/Aayushbankar/cve_aggregator"><b>CVE Intelligence Aggregator</b></a><br/>
          <sub>Self-hosted cybersecurity intelligence engine aggregating feeds from NVD API v2.0, CISA KEV, and GitHub Advisories with composite risk scoring and rate-limit recovery buffers.</sub><br/>
          <img src="https://img.shields.io/badge/Threat_Intel-Automation-blueviolet?style=flat-square" />
        </li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>⚡ Systems, Architecture & AI</h3>
      <ul>
        <li>
          <a href="https://github.com/Aayushbankar/spectre-prism"><b>SPECTRE-PRISM (SIH 2026)</b></a><br/>
          <sub><b>Cleared College Internal Round (Screening).</b> 5-Plane sovereign log processing engine capable of 13,290 EPS with ~13.47 µs latency, Dynamic OCSF mapping, and Section 65B Indian Evidence Act Ed25519 quorum signing.</sub><br/>
          <img src="https://img.shields.io/badge/SIH_2026-Screening-orange?style=flat-square" />
          <img src="https://img.shields.io/badge/13K_EPS-SIMD_Pipeline-critical?style=flat-square" />
        </li>
        <br/>
        <li>
          <a href="https://github.com/Aayushbankar/wolvie"><b>Wolvie: Local Voice-First Companion</b></a><br/>
          <sub>My original concept for an ultra-low latency real-time voice companion running 100% locally on consumer hardware without cloud audio dependencies.</sub><br/>
          <img src="https://img.shields.io/badge/WebRTC-llama.cpp-yellow?style=flat-square" />
          <img src="https://img.shields.io/badge/Whisper-Piper_TTS-green?style=flat-square" />
        </li>
        <br/>
        <li>
          <a href="https://github.com/Aayushbankar/Quantlab"><b>QuantLab: Trading Backtesting Engine</b></a><br/>
          <sub>Realistic event-driven algorithmic trading engine explicitly modeling transaction slippage, execution fees, and out-of-sample decay. <i>(Minor Project)</i></sub><br/>
          <img src="https://img.shields.io/badge/Fintech-Simulation-9cf?style=flat-square" />
        </li>
      </ul>
    </td>
  </tr>
</table>

---

## 🛠️ Technical Arsenal

<div align="center">

### Systems & Low-Level Security
![Linux](https://img.shields.io/badge/Linux_Kernel-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![Android](https://img.shields.io/badge/Android_Internals-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![QEMU](https://img.shields.io/badge/QEMU%2FKVM-FF6600?style=for-the-badge&logo=qemu&logoColor=white)
![GDB](https://img.shields.io/badge/GDB_Scripting-8B0000?style=for-the-badge&logo=gnu&logoColor=white)
![eBPF](https://img.shields.io/badge/eBPF_Telemetry-FF4500?style=for-the-badge&logoColor=white)

### Languages & Backend
![Python](https://img.shields.io/badge/Python_3-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite_3-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

### Security Tooling & Protocols
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=for-the-badge&logo=burp-suite&logoColor=white)
![YARA](https://img.shields.io/badge/YARA_Rules-006699?style=for-the-badge&logoColor=white)
![Suricata](https://img.shields.io/badge/Suricata_IDS-EF3B24?style=for-the-badge&logoColor=white)
![Cryptography](https://img.shields.io/badge/Ed25519_%2F_BLAKE3-2E8B57?style=for-the-badge&logo=letsencrypt&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

### Applied AI & Client-Side
![llama.cpp](https://img.shields.io/badge/llama.cpp-4B0082?style=for-the-badge&logo=meta&logoColor=white)
![Whisper](https://img.shields.io/badge/faster--whisper-00A67E?style=for-the-badge&logo=openai&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6F00?style=for-the-badge&logoColor=white)
![React](https://img.shields.io/badge/React_19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![GSAP](https://img.shields.io/badge/GSAP_Animations-88CE02?style=for-the-badge&logo=greensock&logoColor=black)

</div>

---

## 🏆 Verified Credentials & Recognition

- 🛡️ **Certified AppSec Practitioner v2 (CAP)** — *The SecOps Group (June 2026)*
- 🛡️ **Certified Network Security Practitioner (CNSP)** — *The SecOps Group (June 2026)*
- 🏅 **IBM SkillsBuild Cybersecurity Credential** — *CSRBOX & BharatCares (Evaluated: 48/50)*
- 🎯 **Smart India Hackathon 2026 (SIH)** — *Cleared College Internal Hackathon Round with Team SPECTRE*
- 🏢 **CypherMatrix** — *Formally Designated Cybersecurity Analyst (Research Collaboration)*

---

## 📊 Telemetry & Contribution Stream

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Aayushbankar&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=58A6FF&text_color=C9D1D9" height="175" alt="GitHub Stats" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=Aayushbankar&theme=tokyonight&hide_border=true&background=0D1117&ring=58A6FF&fire=FF9900&currStreakNum=58A6FF" height="175" alt="GitHub Streak" />

</div>

---

<div align="center">

### 📬 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Aayush_Bankar-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aayushbankar/)
[![Webfolio](https://img.shields.io/badge/Personal_Site-Explore-181717?style=for-the-badge&logo=firefox&logoColor=white)](https://aayushbankar.github.io/webfolio/)
[![Email](https://img.shields.io/badge/Email-Contact_Directly-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:aayushbankar42@gmail.com)

<sub>© 2026 Aayush Bankar • Gandhinagar, Gujarat, India</sub>

</div>
