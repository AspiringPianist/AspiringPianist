<div align="center">

# Unnath Chittimalla

### **ASIC Implementation · Computer Architecture · VLSI & FPGA Design · Hardware-Aware ML**

*4th-Year Integrated M.Tech (B.Tech + M.Tech) in Electronics & Communication Engineering @ **IIIT Bangalore** ('28)*

[![1-Page ASIC Resume](https://img.shields.io/badge/%F0%9F%93%84_1--Page_Resume-ASIC_%2F_VLSI_%2F_Computer_Arch-2563eb?style=for-the-badge)](./Unnath_Chittimalla_Resume.pdf)
[![2-Page Master CV](https://img.shields.io/badge/%F0%9F%93%91_2--Page_Master_CV-Research_%2B_Hardware_%2B_Product-059669?style=for-the-badge)](./Unnath_Chittimalla_CV.pdf)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Unnath_Chittimalla-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/unnath-chittimalla-08aaaa287/)
[![Email](https://img.shields.io/badge/Email-unnath.chittimalla%40iiitb.ac.in-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:unnath.chittimalla@iiitb.ac.in)
[![IEEE BHI 2026](https://img.shields.io/badge/IEEE_EMBS_BHI_'26-First_Author_(OpenReview)-8B5CF6?style=flat-square)](https://openreview.net/forum?id=ZgSLF1hkpt)
[![IEEE BHI 2025](https://img.shields.io/badge/IEEE_EMBS_BHI_'25-IEEE_Xplore_(DOI)-00629B?style=flat-square)](https://doi.org/10.1109/bhi67747.2025.11269463)
[![GoalGuard](https://img.shields.io/badge/Co--Founder-GoalGuard_(20k%2B_Downloads)-10B981?style=flat-square&logo=googleplay&logoColor=white)](https://goal-guard.vercel.app/)
[![YouTube](https://img.shields.io/badge/YouTube-%40NotDefinitelyNotMe-FF0000?style=flat-square&logo=youtube&logoColor=white)](https://www.youtube.com/@NotDefinitelyNotMe)

</div>

---

### ⚡ About Me

- 🔬 **Hardware & Systems Researcher @ IIIT Bangalore:** Working on **RTL-to-GDSII ASIC implementation**, **Out-of-Order RISC-V microarchitecture power/current shaping (`di/dt`)**, **PDN & DC-DC EDA automation**, **post-quantum lattice FPGA accelerators**, and **physics-informed neural signal processing** (advised by [Dr. Madhav Rao](https://www.linkedin.com/in/madhavrrao/)).
- 📄 **Quick Resume Links:**
  - **[📄 View 1-Page Resume (ASIC / VLSI / Computer Architecture)](./Unnath_Chittimalla_Resume.pdf)** *(LaTeX source: [`Unnath_Chittimalla_Resume.tex`](./Unnath_Chittimalla_Resume.tex))*
  - **[📑 View 2-Page Master CV (Full Research, Hardware & Product)](./Unnath_Chittimalla_CV.pdf)** *(LaTeX source: [`Unnath_Chittimalla_CV.tex`](./Unnath_Chittimalla_CV.tex))*
- 🚀 **Co-Founder @ [GoalGuard](https://goal-guard.vercel.app/) ([Google Play](https://play.google.com/store/apps/details?id=com.goalguard.app)):** Scaled a privacy-first distraction-blocking platform to **20,000+ downloads across 20+ countries**; selected for **Y Combinator Startup School India** (top 2,000 of 20,000+ applicants) and [making YouTube videos on whatever I learn](https://www.youtube.com/@NotDefinitelyNotMe)!
- 📬 **Reach me at:** **unnath.chittimalla@iiitb.ac.in**

---

### 📚 Peer-Reviewed IEEE Publications (IEEE EMBS BHI)

1. **[Adaptive Lead-Field Residual Learning for Sparse-to-Dense EEG Reconstruction](https://openreview.net/forum?id=ZgSLF1hkpt)** — ***First Author*, IEEE EMBS BHI 2026** · [[Code (`Sparse2Dense-EEG`)](https://github.com/AspiringPianist/Sparse2Dense-EEG)]
   - Formulated EEG spatial super-resolution via a **Physics-Informed Residual Network** with learnable Boundary Element Method (BEM) conductivity calibration ($G_{\text{eff}}$) and forward-consistency regularization ($\mathcal{L}_{\text{fwd}}$).
   - Benchmarked 9 paradigms across 5-, 10-, and 15-channel layouts under LOSO cross-validation on BCI Competition IV-2a; reduced reconstruction error from $9.69\,\mu\text{V}$ (static BEM) to **2.215 µV RMSE ($R^2 = 0.955$, $r = 0.982$)**, enabling **77% wireless sensor bandwidth & power reduction** ($5 \rightarrow 22$ channels) without structural MRI.
2. **[EEG-Based Surface EMG Reconstruction Using Deep Sequence Learning for Upper Limb Motor Activity](https://ieeexplore.ieee.org/document/11269463/)** — ***Co-Author*, IEEE EMBS BHI 2025 (Georgia Tech, Atlanta)** · [[DOI: `10.1109/BHI67747.2025.11269463`](https://doi.org/10.1109/bhi67747.2025.11269463)] · [[Code (`emg-estimation`)](https://github.com/AspiringPianist/emg-estimation)]
   - Engineered `RawSeq2SeqNet` (CNN-LSTM with 4th-order Butterworth/Hilbert DSP pipeline, Common Spatial Pattern filtering, and $\text{MSE}+\text{SoftDTW}$ alignment loss), achieving **2.11 ms real-time inference latency** ($r = 0.795$) across 204 trials.

---

### 🛠️ Featured ASIC, Computer Architecture, EDA & FPGA Repositories

| Repository | Domain & Tools | Key Engineering & PPA Highlights |
| :--- | :--- | :--- |
| **[`hybrid-cmos-reram-memory`](https://github.com/AspiringPianist/hybrid-cmos-reram-memory)** | **Hybrid CMOS-ReRAM & Memristor Solver** · `SkyWater 130nm` · `Cadence Virtuoso (GPDK 180nm)` | SkyWater 130nm Hybrid CMOS-ReRAM non-volatile memory controller with a Ready/Valid interface, RTL Program-and-Verify FSM and 1.8V-to-3.3V level shifters, plus a Virtuoso memristor crossbar matrix solver with 99%+ numerical accuracy. |
| **[`GA-Assisted-DDR-RAM-Output-Capacitor-Decoupling-Design`](https://github.com/AspiringPianist/GA-Assisted-DDR-RAM-Output-Capacitor-Decoupling-Design)** | **PDN & Signal/Power Integrity** · `gem5` · `DRAMsim3` · `DRAMPower` · `LTspice` | **7-stage EDA automation pipeline** synthesizing DDR4-3200 command traces (Rowhammer, streaming, random) into SPICE `.pwl` waveforms. Batch-LTspice **Genetic Algorithm** optimizing an **86-capacitor network** (51 VDDQ, 35 VTT) on an `LTM4632` buck regulator under **0.948 nH** via inductance, suppressing anti-resonance spikes up to **1.6 GHz** within JEDEC ripple specs ($\pm 60\text{ mV} / \pm 40\text{ mV}$). |
| **[`openenv-dcdc-rl`](https://github.com/AspiringPianist/openenv-dcdc-rl)** | **Analog/Power EDA + RL** · `Python` · `NGspice/LTspice` · `OpenEnv` | **spiceRL:** Closed-loop SPICE reinforcement learning environment for automated DC-DC buck converter MOSFET sizing ($W_{\text{hi}}, W_{\text{lo}}$), switching frequency, and passive BOM optimization with Murata/Coilcraft parasitics. |
| **[`hawk-12289-ntt-fpga`](https://github.com/AspiringPianist/hawk-12289-ntt-fpga)** & **[`fermat-conv-hardware`](https://github.com/AspiringPianist/fermat-conv-hardware)** | **PQC Lattice Accelerators** · `Verilog` · `Vivado Tcl OOC P&R` · `Kintex-7` | Designed & timed **11 modular-multiplication PEs** (Montgomery, Barrett, K-RED, Proth-fold, Karatsuba) and **8 full $N=64$ negacyclic NTT/INTT/PWM pipelines** ($q=12289$) via automated Vivado Out-of-Context synthesis & Place-and-Route on **Kintex-7 (`XC7K325T-2`)**, achieving **116.1 MHz $F_{\max}$** and **17.6 µs** polynomial multiply latency; plus a radix-2 Fermat ($q=65537$) accelerator. |
| **[`obc-vector-inner-product`](https://github.com/AspiringPianist/obc-vector-inner-product)** & **[`4bit-baughwooley-multiplier`](https://github.com/AspiringPianist/4bit-baughwooley-multiplier)** | **FPGA DSP & Arithmetic** · `Verilog` · `Vivado STA` · `Artix-7` | Multiplier-less Q15 fixed-point inner-product DSP core using **Distributed Arithmetic (DA)** with **Offset Binary Coding (OBC)** for **50% LUT reduction**; plus a 4-stage pipelined **Baugh-Wooley multiplier** cutting critical-path logic delay by **2.1×** ($1.473\text{ ns} \rightarrow 0.704\text{ ns}$, $5 \rightarrow 2$ logic levels, **166.7 MHz**). |
| **[`final_nn_fpga_tanh`](https://github.com/AspiringPianist/final_nn_fpga_tanh)** | **HLS & On-Chip Debug** · `Vitis HLS` · `VHDL` · `Vivado VIO/ILA` | 16-bit fixed-point quantized neural network ($784 \times 64 \times 10$ MLP with hardware `tanh`/ReLU) synthesized in **Vitis HLS & VHDL**, validated at-speed on an **Artix-7 (Basys 3)** FPGA using **Vivado VIO and ILA** logic analyzers. |
| **[`hybrid-cmos-reram-memory`](https://github.com/AspiringPianist/hybrid-cmos-reram-memory)** | **NVM & Mixed-Signal** · `SkyWater 130nm` · `Cadence Virtuoso 180nm` | **SkyWater 130nm** Hybrid CMOS-ReRAM controller with AXI-Lite-style Ready/Valid interface, RTL Program-and-Verify FSM, 1.8V-to-3.3V level shifters, and 1T1R pulse shaping; paired with an $\mathcal{O}(1)$ analog **Memristor Crossbar Matrix Solver** in **Cadence Virtuoso (GPDK 180nm)** (**99%+ accuracy**). |
| **[`tiny-gpu`](https://github.com/AspiringPianist/tiny-gpu)** | **Minimal GPU Architecture** · `SystemVerilog` · `Icarus Verilog` · `cocotb` | Minimal SIMD GPU in **SystemVerilog** (built & extended while learning GPU architecture) with a custom 16-bit ISA, dispatcher, per-core ALU/LSU pipelines, and memory controller; verified matrix addition & multiplication kernels with **cocotb**. |

---

### 🏆 Product Engineering, Embedded Systems & National Honors

- 📱 **[GoalGuard — Co-Founder](https://goal-guard.vercel.app/) ([Play Store](https://play.google.com/store/apps/details?id=com.goalguard.app)):** Scaled a privacy-first Android distraction-blocking platform to **20,000+ downloads across 20+ countries**; selected for **Y Combinator Startup School India** (top 2,000 of 20,000+ applicants).
- 🧭 **[`Distance-and-Direction-Estimation-from-IMU-Sensors`](https://github.com/AspiringPianist/Distance-and-Direction-Estimation-from-IMU-Sensors):** Solved IMU double-integration drift for 2D dead reckoning using FFT-informed **Butterworth filters**, **Kalman filtering**, and a Random Forest velocity regressor (**<2.5% distance error** vs GPS ground truth).
- 🥇 **1st Place (Among 5,000+ Participants), [ICDEC VDVWC Challenge (2024)](https://sites.google.com/view/vdvwc/home):** Ranked #1 at Jadavpur University by architecturally modifying YOLOv10 for adverse-weather vehicle detection.
- 🏅 **Top 10 Finalist (Among 10,000+ Teams), [Meta Pragati AI for Impact (2025, New Delhi)](https://www.linkedin.com/posts/unnath-chittimalla-08aaaa287_top-10-finalists-activity-7350479787292839939-Km27):** Selected nationwide by Meta for architecting a low-latency multilingual RAG system.
- 🏅 **Top 11 Finalist, [ELCIA Tech Summit TRL-8 Sensor Challenge (2025)](https://elciatechsummit.in/hackathon-2025/):** Deployed a quantized on-device Random Forest motion artifact filter for real-time wireless vital monitoring.
- 🏅 **Top 3 Nationwide (Stage 2), [NCIIPC & Startup India AI Grand Challenge](https://ai-grand-challenge.in/):** Built Robust PCA and GAN-BWGNN pipelines for hyperspectral & thermal anomaly detection.
- 🎓 **Teaching Assistant (Signals & Systems), IIIT Bangalore:** Led tutorials, lab sessions, and grading for 150+ ECE undergraduates.

---

### 🧰 Technical Stack

- **HDLs & Computer Architecture:** `SystemVerilog` · `Verilog` · `VHDL` · `Vitis HLS` · `Custom GPU ISA` · `Pipelining` · `Active Clock Gating`
- **EDA, ASIC & FPGA Implementation:** `Cadence Genus (RTL Synthesis)` · `Cadence Virtuoso (180nm GPDK)` · `Xilinx Vivado (OOC Synthesis, P&R, STA, VIO/ILA)` · `SkyWater 130nm PDK`
- **Simulation, Power & Verification:** `Verilator` · `Icarus Verilog` · `cocotb` · `gem5` · `DRAMsim3` · `DRAMPower` · `LTspice` · `NGspice` · `C++ Golden Models`
- **Scripting, Software & DSP/ML:** `Python` · `Tcl (EDA Batch Automation)` · `C++` · `C` · `Rust` · `Kotlin` · `Swift` · `MATLAB` · `PyTorch` · `Fixed-Point Quantization` · `Linux` · `Git`
