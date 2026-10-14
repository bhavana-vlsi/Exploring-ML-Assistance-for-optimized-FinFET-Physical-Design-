# 🔬 ML-Assisted Congestion & Self-Heating Prediction in FinFET Physical Design

<p align="center">
  <img src="https://img.shields.io/badge/TEEP-Research-2457A6?style=for-the-badge" alt="TEEP Research"/>
  <img src="https://img.shields.io/badge/Domain-VLSI%20%7C%20EDA-101827?style=for-the-badge" alt="VLSI and EDA"/>
  <img src="https://img.shields.io/badge/Simulation-NGSPICE-60A5FA?style=for-the-badge" alt="NGSPICE"/>
  <img src="https://img.shields.io/badge/Status-Ongoing-64748B?style=for-the-badge" alt="Ongoing research"/>
</p>

<p align="center">
  <b>Exploring early prediction of routing congestion and self-heating hotspots in FinFET physical design.</b>
</p>

---

## 🎓 Research Details

| | Details |
|---|---|
| 👩‍💻 Researcher | Bhavana Karanam |
| 🎓 Programme | Taiwan Experience Education Program (TEEP) |
| 🏛️ University | Feng Chia University |
| 🔬 Department | Department of Electronics |
| 🧪 Laboratory | Reliable Integrated Circuit Development Laboratory |
| 📍 Location | Taichung, Taiwan |
| 📅 Duration | September – December 2026 |

---

## 🌟 About the Project

This research investigates the potential for **machine-learning-assisted early prediction of routing congestion and self-heating (SHE) hotspots** in FinFET physical design.

The long-term objective is to explore physical-design information and develop a spatially aligned dataset for studying congestion and self-heating hotspots before routing.

The work combines semiconductor device simulation, physical-design analysis and machine-learning-oriented dataset development.

## 🧪 Current Research: Self-Heating Characterization

NGSPICE simulations are used to study self-heating-enabled BSIM-CMG transistor models under different operating conditions.

### 🔍 Parameters under investigation

- ⚡ Gate-to-source voltage (VGS)
- ⚡ Drain-to-source voltage (VDS)
- 🔢 Number of fins (NFIN)
- 🌡️ Ambient temperature
- 📈 Model-reported temperature rise (`T_DELTA_SH`)

### 📊 Dataset Snapshot

<p align="center">
  <img src="https://img.shields.io/badge/Total%20Samples-336-2457A6?style=for-the-badge" alt="336 samples"/>
  <img src="https://img.shields.io/badge/NMOS-168-60A5FA?style=for-the-badge" alt="168 NMOS samples"/>
  <img src="https://img.shields.io/badge/PMOS-168-101827?style=for-the-badge" alt="168 PMOS samples"/>
</p>

The current dataset contains **336 device-level operating-condition samples**, consisting of 168 NMOS and 168 PMOS samples, excluding the CSV header.

> 📌 These are simulation-derived device-level characterization samples, not spatial hotspot maps or measured silicon temperatures.

---

## 🛠️ Tools & Technologies

<p align="center">
  <img src="https://img.shields.io/badge/NGSPICE-Circuit%20Simulation-2457A6?style=flat-square" alt="NGSPICE"/>
  <img src="https://img.shields.io/badge/BSIM--CMG-Transistor%20Models-101827?style=flat-square" alt="BSIM-CMG"/>
  <img src="https://img.shields.io/badge/ASAP7-Technology%20Platform-60A5FA?style=flat-square" alt="ASAP7"/>
  <img src="https://img.shields.io/badge/Yosys-Synthesis-2457A6?style=flat-square" alt="Yosys"/>
  <img src="https://img.shields.io/badge/OpenROAD-Physical%20Design-101827?style=flat-square" alt="OpenROAD"/>
  <img src="https://img.shields.io/badge/KLayout-Layout%20Analysis-60A5FA?style=flat-square" alt="KLayout"/>
</p>

- **Circuit simulation:** NGSPICE
- **Device modeling:** BSIM-CMG with self-heating support
- **Technology platform:** ASAP7, subject to applicable access and redistribution terms
- **Digital implementation:** Yosys
- **Physical design:** OpenROAD
- **Layout visualization:** KLayout

## 🚀 Research Roadmap

### ✅ Completed

- Initial NGSPICE-based self-heating characterization.
- NMOS and PMOS operating-condition sweeps.
- Generation of a combined 336-sample device-level dataset.

### 🔄 In Progress

- Analysis and validation of transistor characterization results.
- Investigation of suitable design-level reference data for self-heating analysis.
- Exploration of the relationship between electrical and physical-design information.

### 🎯 Planned

- ⚡ Investigate power-grid and IR-drop analysis on a representative design.
- 🗺️ Develop spatially aligned physical-design features and defensible hotspot reference labels.
- 📦 Expand the dataset across multiple designs.
- 🤖 Investigate machine-learning models for congestion and self-heating prediction.
- 📊 Evaluate models using held-out designs.

*Planned activities are research objectives, not completed results.*

---

## 📂 Repository Structure

```text
finfet-congestion-self-heating-research/
│
├── README.md
├── docs/
│   └── methodology.md
├── scripts/
│   └── simulation_and_analysis_scripts
├── data/
│   └── sanitized_characterization_data.csv
└── results/
    └── characterization_plots/
```

*The structure above is the intended organization. Files will be added as they are prepared and verified.*

## 🔐 Research Integrity

- Results will be documented based on actual simulations and experiments.
- Device-level characterization will be distinguished from design-level spatial hotspot labels.
- Licensed PDKs, restricted transistor-model files and confidential university materials will not be redistributed.
- Scripts and datasets will be shared only where permitted.

---

## 🎯 Research Interests

`VLSI` · `Digital IC Design` · `FinFET` · `Physical Design` · `RTL-to-GDSII` · `EDA` · `Machine Learning for EDA` · `Semiconductor Devices`

## 🤝 Connect With Me

<p align="center">
  <a href="https://www.linkedin.com/in/bhavanakaranam-ece">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-2457A6?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://github.com/bhavana-vlsi">
    <img src="https://img.shields.io/badge/GitHub-Portfolio-101827?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  <a href="mailto:karanambhavana275@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-60A5FA?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
</p>

<p align="center">
  💙 Building knowledge at the intersection of semiconductor devices, digital design and intelligent physical-design automation.
</p>
