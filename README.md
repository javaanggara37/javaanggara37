# Hi, I'm Java Chrisand Hecka Anggara 👾

**Vulnerability Researcher | Kernel, Firmware & Silicon Security**

I break and build across the entire execution stack—from web applications and Linux kernel space down to UEFI, Intel CSME, System Management Mode (SMM), and bare-metal RTL/silicon.

- 🔭 Current Focus: **Hardware Trojans (RTL), Ring -2 / SMM Internals & Kernel Exploitation**
- 🛡️ Track Record: **Linux Kernel Upstream Contributor, CWE Analysis & Major Vendor Bug Bounties**
- ⚙️ Engineering: **Custom RTL anti-tamper PoCs, boot-level instrumentation, and fault-injection setups**
- 📫 Reach me at: **javaanggara37@gmail.com**

---

### 💻 Languages & HDL

<p align="left">
  <img src="https://shields.io" alt="SystemVerilog" />
  <img src="https://shields.io" alt="C" />
  <img src="https://shields.io" alt="Assembly" />
  <img src="https://shields.io" alt="Python" />
</p>

---

### 🧰 Arsenal & Tooling

| Domain | Tools & Frameworks |
| :--- | :--- |
| **⚡ Hardware & Silicon** | `ChipWhisperer`, `FPGA & Synthesis Tools`, `JTAG / SWD`, `OpenOCD` |
| **🧬 Firmware & Kernel** | `UEFITool`, `EDK II`, `me_cleaner`, `CHIPSEC`, `Syzkaller`, `WinDbg` |
| **🌐 Web Exploitation** | `Burp Suite`, `Nuclei`, `Subfinder`, `Wapiti`, `OWASP Methodology` |

---

### 🏆 Track Record & Low-Level Engineering

- **🔌 Hardware Trojan & Anti-Tamper PoC (SystemVerilog):** Designed an ultra-compact RTL Hardware Trojan (~hundreds of gates/LUTs footprint) engineered to evade static analysis, logic testing, and physical probing:
  - *Stealth & Obfuscation:* Deeply embedded **Finite State Machine (FSM)** fortified with **Opaque Predicates** and gate-level **camouflaging** techniques.
  - *Activation Mechanism:* Multi-stage cryptographic/bus **handshake** gated by rare, non-standard trigger conditions to bypass functional verification.
  - *Active Defense / Anti-Probing:* Hardware-level **self-destruct / zeroization logic** triggered upon detecting anomalous current/voltage impedance on standard **JTAG** pinouts.
- **🔬 Ring -2 & Boot-Level Architecture:** Engineered advanced low-level PoCs involving bootloader mechanics, **HECI** hooking for **Intel CSME** interaction, and triggering **SMI (System Management Interrupts)** via I/O ports (`0xB2`/`0xB3`).
- **🐧 Linux Kernel Contributions:** Authored upstream patches addressing memory corruption and subsystem vulnerabilities.
- **🛡️ Enterprise Bug Bounty & CWE:** Discovered and reported high-impact web vulnerabilities across major global tech vendors.

---

### 📌 Featured Repositories
- **[Repo 1: RTL Hardware Trojan & Anti-Tamper PoC](https://github.com)** — *SystemVerilog implementation demonstrating obfuscated FSM triggers, low-footprint synthesis, and JTAG probe detection.*
- **[Repo 2: UEFI & SMM Inspection Scripts](https://github.com)** — *CHIPSEC modules and EDK II utilities for auditing firmware interfaces.*
- **[Repo 3: Kernel Fuzzing & Patch Notes](https://github.com)** — *Custom Syzkaller harnesses and notes on Linux kernel vulnerability remediation.*

---

### 📊 GitHub Telemetry

<p align="left">
  <img src="https://vercel.app" alt="GitHub Stats" height="165" />
  <img src="https://vercel.app" alt="Top Languages" height="165" />
</p>

---

### 🔗 Connect & Advisories

[![LinkedIn](https://shields.io)](https://linkedin.com)
[![X / Twitter](https://shields.io)](https://x.com)
[![PGP Key](https://shields.io)](https://link-pgp-kamu.com)
