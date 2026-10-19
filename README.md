<div align="center">

  <!-- Animated Typing Header -->
  <a href="https://github.com/prachurjyaghy">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=24&duration=3000&pause=1000&color=00F7FF&center=true&vCenter=true&width=800&lines=Prachurjya+Sharma+%7C+Physical+Design+Engineer;6nm+%7C+7nm+%7C+12nm+%7C+22nm+Advanced+Node+Implementation;RTL-to-GDSII+%7C+Mesh+CTS+%7C+Timing+%26+Power+Sign-off;EDA+Automation+%26+Software+Development" alt="Typing SVG" />
  </a>

  <p align="center">
    <a href="https://www.linkedin.com/in/prachurjya-sharma-04/">
      <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    <a href="https://prachurjyaghy.github.io/">
      <img src="https://img.shields.io/badge/Interactive_Portfolio-00F7FF?style=for-the-badge&logo=google-chrome&logoColor=black" alt="Portfolio" />
    </a>
    <a href="mailto:prachurjyaraj@hotmail.com">
      <img src="https://img.shields.io/badge/Contact_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
    </a>
  </p>
</div>

---

### ⚡ Executive Engineering Profile

- 🔬 **Physical Design Specialist:** Executing complete RTL-to-GDSII flows across **6nm, 7nm, 12nm, and 22nm** nodes with a focus on high-frequency (1.25 GHz) and low-power multi-domain architectures. <!--[cite: 1, 2] -->
- 🏗️ **Core Execution:** Driving floorplanning, Mesh CTS, RC-aware routing, and MCMM timing closure for multi-million instance SoCs at **Quest Global**. <!--[cite: 1] -->
- 🤖 **Software & Automation:** Leveraging a software engineering foundation from **KPIT Technologies** (C#/.NET, Azure) to engineer custom **TCL and Perl** automation scripts that slash DRC/LVS turnaround times. <!--[cite: 1, 2] -->
- 🌐 **Open-Source VLSI:** Active researcher utilizing the **SKY130 PDK** and **OpenLane** toolchain for open-source silicon implementation. <!--[cite: 2] -->

---

### 🛠️ Technical Stack & EDA Arsenal

| Domain | Technologies & Methodologies |
| :--- | :--- |
| **Physical Design** | Floorplanning, Placement, Mesh CTS, RC-Aware Routing, Sign-Off, ECO Implementation <!--[cite: 1] --> |
| **Verification & Power** | STA, Crosstalk/SI, EM/IR, CLP, DRC, LVS, Antenna Checks <!--[cite: 1] --> |
| **Commercial EDA** | Cadence Innovus, Mentor Aprisa, Synopsys PrimeTime, Calibre, Tweaker <!--[cite: 1, 2] --> |
| **Open-Source VLSI** | OpenLane, SKY130 PDK, Magic, Yosys, OpenTimer, GTKWave, Icarus Verilog <!--[cite: 2] --> |
| **Scripting & Code** | ![TCL](https://img.shields.io/badge/-TCL-FF6F00?style=flat-square) ![Perl](https://img.shields.io/badge/-Perl-39457E?style=flat-square&logo=perl&logoColor=white) ![Shell](https://img.shields.io/badge/-Shell-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white) ![Verilog](https://img.shields.io/badge/-Verilog-00599C?style=flat-square) ![C#](https://img.shields.io/badge/-C%23-239120?style=flat-square&logo=c-sharp&logoColor=white) ![Azure](https://img.shields.io/badge/-Azure-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white) <!--[cite: 1, 2] --> |

---

### 🔄 Implementation & Automation Methodology

```mermaid
graph LR
    A[RTL / Netlist] -->|Multi-Power Domain FP| B(Placement & Density Opt)
    B -->|Mesh & Standard CTS| C(Clock Tree & Latency)
    C -->|RC-Aware Routing| D(Post-Route & Optimization)
    D -->|PrimeTime / Tweaker| E{STA, EM/IR & CLP Signoff}
    E -->|Functional / Metal ECOs| C
    E -->|Calibre Clean| F[GDSII Tapeout]
    G[Custom TCL/Perl Automation] -.->|Auto DRC/LVS Fixes & Parsing| D
    style G fill:#0d1117,stroke:#00f7ff,stroke-width:2px,color:#00f7ff
    style F fill:#00c853,stroke:#ffffff,stroke-width:2px,color:#ffffff
