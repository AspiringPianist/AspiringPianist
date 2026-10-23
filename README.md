<div align="center">

# Unnath Chittimalla

### **Software · RTL & FPGA · Computer Architecture · Biomedical ML**

*4th-Year Integrated M.Tech (B.Tech + M.Tech) in Electronics & Communication Engineering @ **IIIT Bangalore** ('28)*

[![Resume (1 page)](https://img.shields.io/badge/%F0%9F%93%84_Resume-1_page_PDF-2563eb?style=for-the-badge)](./Unnath_Chittimalla_Resume.pdf)
[![CV (full)](https://img.shields.io/badge/%F0%9F%93%91_CV-full_PDF-059669?style=for-the-badge)](./Unnath_Chittimalla_CV.pdf)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Unnath_Chittimalla-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/unnath-chittimalla-08aaaa287/)
[![Email](https://img.shields.io/badge/Email-unnath.chittimalla%40iiitb.ac.in-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:unnath.chittimalla@iiitb.ac.in)
[![IEEE BHI 2026](https://img.shields.io/badge/IEEE_EMBS_BHI_'26-First_Author_(OpenReview)-8B5CF6?style=flat-square)](https://openreview.net/forum?id=ZgSLF1hkpt)
[![IEEE BHI 2025](https://img.shields.io/badge/IEEE_EMBS_BHI_'25-IEEE_Xplore_(DOI)-00629B?style=flat-square)](https://doi.org/10.1109/BHI67747.2025.11269463)
[![GoalGuard](https://img.shields.io/badge/Co--Founder-GoalGuard_(20k%2B_Downloads)-10B981?style=flat-square&logo=googleplay&logoColor=white)](https://goal-guard.vercel.app/)
[![YouTube](https://img.shields.io/badge/YouTube-%40NotDefinitelyNotMe-FF0000?style=flat-square&logo=youtube&logoColor=white)](https://www.youtube.com/@NotDefinitelyNotMe)

</div>

---

### About

I'm an undergraduate at IIIT Bangalore, still learning. I work on a mix of software (ML for biomedical signals, mobile apps, tooling) and hardware (RTL, FPGA, computer architecture), and I'm advised by [Dr. Madhav Rao](https://www.linkedin.com/in/madhavrrao/). I also make videos about what I learn on [YouTube](https://www.youtube.com/@NotDefinitelyNotMe).

- **[Resume (1 page)](./Unnath_Chittimalla_Resume.pdf)** · **[CV (full)](./Unnath_Chittimalla_CV.pdf)**
- Reach me at **unnath.chittimalla@iiitb.ac.in**

---

## Software

### Apps and tools

- **[GoalGuard](https://goal-guard.vercel.app/) (Co-Founder)** · [Website](https://goal-guard.vercel.app/) · [Google Play](https://play.google.com/store/apps/details?id=com.goalguard.app): Privacy-first Android app for blocking distractions, with **20,000+ downloads** across 20+ countries. Selected for Y Combinator Startup School India.
- **[relayBrain](https://github.com/prakrititz/relayBrain)** ([`prakrititz/relayBrain`](https://github.com/prakrititz/relayBrain), [website](https://relay-brain.vercel.app/)): Team project with [@prakrititz](https://github.com/prakrititz) (repo owner and main author) and other contributors. A coordination layer for AI coding agents (Claude Code, Cursor, Copilot, Codex, Antigravity) that shares file locks and live patches, so agents editing the same project do not overwrite each other, and keeps shared project memory in a FalkorDB graph (built for a WeMakeDevs x FalkorDB hackathon). I contributed to it as a collaborator (17 commits on GitHub).
- **[`Distance-and-Direction-Estimation-from-IMU-Sensors`](https://github.com/AspiringPianist/Distance-and-Direction-Estimation-from-IMU-Sensors):** IMU-only 2D dead reckoning. Reduces integration drift with FFT-informed Butterworth filters, Kalman filtering and a Random Forest velocity regressor (under 2.5% distance error against GPS ground truth in my tests).

### ML and biomedical signal processing

**IEEE EMBS BHI papers**

1. **[Adaptive Lead-Field Residual Learning for Sparse-to-Dense EEG Reconstruction](https://openreview.net/forum?id=ZgSLF1hkpt)** — ***First Author*, IEEE EMBS BHI 2026** · [[Code (`Sparse2Dense-EEG`)](https://github.com/AspiringPianist/Sparse2Dense-EEG)]
   - Sparse-to-dense EEG reconstruction without structural MRI: formulated EEG spatial super-resolution via a **Physics-Informed Residual Network** with learnable Boundary Element Method (BEM) conductivity calibration ($G_{\text{eff}}$) and forward-consistency regularization ($\mathcal{L}_{\text{fwd}}$).
   - Benchmarked 9 paradigms across 5-, 10-, and 15-channel layouts under LOSO cross-validation on BCI Competition IV-2a; reduced reconstruction error from $9.69\,\mu\text{V}$ (static BEM) to **2.215 µV RMSE ($R^2 = 0.955$, $r = 0.982$)**, enabling **77% wireless sensor bandwidth & power reduction** ($5 \rightarrow 22$ channels) without structural MRI.
2. **[EEG-Based Surface EMG Reconstruction Using Deep Sequence Learning for Upper Limb Motor Activity](https://ieeexplore.ieee.org/document/11269463/)** — ***Co-Author*, IEEE EMBS BHI 2025 (Georgia Tech, Atlanta)** · [[DOI: `10.1109/BHI67747.2025.11269463`](https://doi.org/10.1109/BHI67747.2025.11269463)] · [[Code (`emg-estimation`)](https://github.com/AspiringPianist/emg-estimation)]
   - Learns direct cortico-muscular mappings from non-invasive EEG (signal preprocessing + spatio-temporal modeling), replacing dual-modality EEG-EMG systems with a single EEG modality.
   - Implemented `RawSeq2SeqNet` (CNN-LSTM with 4th-order Butterworth/Hilbert DSP pipeline, Common Spatial Pattern filtering, and $\text{MSE}+\text{SoftDTW}$ alignment loss), achieving **2.11 ms real-time inference latency** ($r = 0.795$) across 204 trials.

Code: [`Sparse2Dense-EEG`](https://github.com/AspiringPianist/Sparse2Dense-EEG) · [`emg-estimation`](https://github.com/AspiringPianist/emg-estimation)

### Competitions and challenge projects

- **Stage 2 Winner, [NCIIPC & Startup India AI Grand Challenge (2026)](https://ai-grand-challenge.in/) (Team Coders@IIITB):** PS-11 Hyperspectral Anomaly Detection using Robust PCA and GAN-BWGNN pipelines ([`hyperspectral_anomaly_detection`](https://github.com/AspiringPianist/hyperspectral_anomaly_detection)).
- **1st Place, [ICDEC VDVWC Challenge (2024)](https://sites.google.com/view/vdvwc/home):** Modified YOLOv10 for adverse-weather vehicle detection ([`YOLOGANg_VehicleDetection`](https://github.com/AspiringPianist/YOLOGANg_VehicleDetection)).
- **Top 10 Finalist, [Meta Pragati AI for Impact (2025)](https://www.linkedin.com/posts/unnath-chittimalla-08aaaa287_top-10-finalists-activity-7350479787292839939-Km27):** Worked on a low-latency multilingual RAG system.
- **Top 11 Finalist, [ELCIA Tech Summit TRL-8 Sensor Challenge (2025)](https://elciatechsummit.in/hackathon):** Quantized on-device Random Forest motion-artifact filter ([`515Labs_VitalsTrack`](https://github.com/AspiringPianist/515Labs_VitalsTrack)).
- **Teaching Assistant (Signals & Systems), IIIT Bangalore:** Tutorials, labs and grading for 150+ ECE undergraduates.

---

## Hardware

### RTL, FPGA and computer architecture

| Repository | Domain & Tools | Summary |
| :--- | :--- | :--- |
| **[`tiny-gpu`](https://github.com/AspiringPianist/tiny-gpu)** | **Minimal GPU Architecture** · `SystemVerilog` · `Icarus Verilog` · `cocotb` | Studied and built a minimal GPU in **SystemVerilog**, following the public learning project [adam-maj/tiny-gpu](https://github.com/adam-maj/tiny-gpu): multi-core SIMD-style design, custom ISA, dispatcher, per-core ALU/LSU pipelines and memory controller; matrix addition & multiplication kernels simulated with **cocotb** (RTL design and simulation). Recorded a [no-code walkthrough video](https://www.youtube.com/watch?v=I2KRmAZkb30) on YouTube. |
| **[`hybrid-cmos-reram-memory`](https://github.com/AspiringPianist/hybrid-cmos-reram-memory)** | **Hybrid CMOS-ReRAM & Memristor Solver** · `SkyWater 130nm` · `Cadence Virtuoso (GPDK 180nm)` | SkyWater 130nm-targeted Hybrid CMOS-ReRAM memory controller (RTL and simulation) with a Ready/Valid interface, Program-and-Verify FSM and 1.8V-to-3.3V level shifters, plus a Virtuoso memristor crossbar matrix solver (99%+ numerical accuracy in simulation). |
| **[`obc-vector-inner-product`](https://github.com/AspiringPianist/obc-vector-inner-product)** & **[`4bit-baughwooley-multiplier`](https://github.com/AspiringPianist/4bit-baughwooley-multiplier)** | **FPGA DSP & Arithmetic** · `Verilog` · `Vivado STA` · `Artix-7` | Multiplier-less Q15 fixed-point inner-product DSP core using **Distributed Arithmetic (DA)** with **Offset Binary Coding (OBC)** for **50% LUT reduction**; plus a 4-stage pipelined **Baugh-Wooley multiplier** cutting critical-path logic delay by **2.1×** ($1.473\text{ ns} \rightarrow 0.704\text{ ns}$, $5 \rightarrow 2$ logic levels, **166.7 MHz**). |
| **[`final_nn_fpga_tanh`](https://github.com/AspiringPianist/final_nn_fpga_tanh)** | **HLS & On-Chip Debug** · `Vitis HLS` · `VHDL` · `Vivado VIO/ILA` | 16-bit fixed-point quantized neural network ($784 \times 64 \times 10$ MLP with hardware `tanh`/ReLU) built with **Vitis HLS & VHDL**, tested on-board on an **Artix-7 (Basys 3)** FPGA using **Vivado VIO and ILA** logic analyzers. |
| **[`GA-Assisted-DDR-RAM-Output-Capacitor-Decoupling-Design`](https://github.com/AspiringPianist/GA-Assisted-DDR-RAM-Output-Capacitor-Decoupling-Design)** | **PDN & Signal/Power Integrity** · `gem5` · `DRAMsim3` · `DRAMPower` · `LTspice` | **7-stage EDA automation pipeline** converting DDR4-3200 command traces (Rowhammer, streaming, random) into SPICE `.pwl` waveforms. Batch-LTspice **Genetic Algorithm** optimizing an **86-capacitor network** (51 VDDQ, 35 VTT) on an `LTM4632` buck regulator under **0.948 nH** via inductance, suppressing anti-resonance spikes up to **1.6 GHz** within JEDEC ripple specs ($\pm 60\text{ mV} / \pm 40\text{ mV}$). |
| **[`ldpc-decoder-rtl`](https://github.com/AspiringPianist/ldpc-decoder-rtl)** | **RTL Design & Simulation** · `SystemVerilog` · `Verilator/Icarus` · `C++ golden model` | SystemVerilog RTL and functional simulation of a layered min-sum decoder; work in progress. |
| **[`openenv-dcdc-rl`](https://github.com/AspiringPianist/openenv-dcdc-rl)** | **Analog/Power EDA + RL** · `Python` · `NGspice/LTspice` · `OpenEnv` | **spiceRL:** small OpenEnv RL environment for sizing buck converter MOSFETs. |

---

### Technical stack

- **HDLs & Computer Architecture:** `SystemVerilog` · `Verilog` · `VHDL` · `Vitis HLS` · `Custom GPU ISA` · `Pipelining`
- **EDA & FPGA Tools:** `Cadence Virtuoso (180nm GPDK)` · `Xilinx Vivado (OOC Synthesis, P&R, STA, VIO/ILA)` · `SkyWater 130nm PDK`
- **Simulation, Power & Verification:** `Verilator` · `Icarus Verilog` · `cocotb` · `gem5` · `DRAMsim3` · `DRAMPower` · `LTspice` · `NGspice` · `C++ Golden Models`
- **Scripting, Software & DSP/ML:** `Python` · `Tcl (EDA Batch Automation)` · `C++` · `C` · `Rust` · `Kotlin` · `Swift` · `MATLAB` · `PyTorch` · `Fixed-Point Quantization` · `Linux` · `Git`
