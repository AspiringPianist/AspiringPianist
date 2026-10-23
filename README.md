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

## Software & Hardware

<table>
<tr>
<th width="50%" align="left">Software</th>
<th width="50%" align="left">Hardware</th>
</tr>
<tr>
<td valign="top" width="50%">
<b><i>Apps and tools</i></b><br>
<b><a href="https://goal-guard.vercel.app/">GoalGuard</a> (Co-Founder)</b><br>
Privacy-first Android app for blocking distractions, with <b>20,000+ downloads</b> across 20+ countries. Selected for Y Combinator Startup School India.<br>
<sub><a href="https://goal-guard.vercel.app/">Website</a> · <a href="https://play.google.com/store/apps/details?id=com.goalguard.app">Google Play</a></sub><br>
<br>
<b><a href="https://github.com/prakrititz/relayBrain">relayBrain</a></b><br>
Team project with <a href="https://github.com/prakrititz">@prakrititz</a> (repo owner and main author) and other contributors. A coordination layer for AI coding agents (Claude Code, Cursor, Copilot, Codex, Antigravity) that shares file locks and live patches, so agents editing the same project do not overwrite each other, and keeps shared project memory in a FalkorDB graph (built for a WeMakeDevs x FalkorDB hackathon). I contributed as a collaborator (17 commits on GitHub).<br>
<sub><a href="https://github.com/prakrititz/relayBrain"><code>prakrititz/relayBrain</code></a> · <a href="https://relay-brain.vercel.app/">website</a></sub><br>
<br>
<b><a href="https://github.com/AspiringPianist/Distance-and-Direction-Estimation-from-IMU-Sensors"><code>Distance-and-Direction-Estimation-from-IMU-Sensors</code></a></b><br>
IMU-only 2D dead reckoning. Reduces integration drift with FFT-informed Butterworth filters, Kalman filtering and a Random Forest velocity regressor (under 2.5% distance error against GPS ground truth in my tests).<br>
<br>
<b><i>ML and biomedical signal processing</i></b><br>
<i>IEEE EMBS BHI papers</i><br><br>
<b><a href="https://openreview.net/forum?id=ZgSLF1hkpt">Adaptive Lead-Field Residual Learning for Sparse-to-Dense EEG Reconstruction</a></b><br>
<i>First Author</i>, IEEE EMBS BHI 2026. Sparse-to-dense EEG reconstruction without structural MRI via a <b>Physics-Informed Residual Network</b> with learnable BEM conductivity calibration and forward-consistency regularization. Benchmarked 9 paradigms across 5-, 10- and 15-channel layouts under LOSO cross-validation on BCI Competition IV-2a; reduced reconstruction error from 9.69 µV (static BEM) to <b>2.215 µV RMSE (R² = 0.955, r = 0.982)</b>, enabling <b>77% wireless sensor bandwidth &amp; power reduction</b> (5 → 22 channels).<br>
<sub><a href="https://github.com/AspiringPianist/Sparse2Dense-EEG">Code (<code>Sparse2Dense-EEG</code>)</a></sub><br>
<br>
<b><a href="https://ieeexplore.ieee.org/document/11269463/">EEG-Based Surface EMG Reconstruction Using Deep Sequence Learning for Upper Limb Motor Activity</a></b><br>
<i>Co-Author</i>, IEEE EMBS BHI 2025 (Georgia Tech, Atlanta). Learns direct cortico-muscular mappings from non-invasive EEG, replacing dual-modality EEG-EMG systems with a single EEG modality. Implemented <code>RawSeq2SeqNet</code> (CNN-LSTM with 4th-order Butterworth/Hilbert DSP pipeline, Common Spatial Pattern filtering, MSE+SoftDTW alignment loss), achieving <b>2.11 ms real-time inference latency</b> (r = 0.795) across 204 trials.<br>
<sub><a href="https://doi.org/10.1109/BHI67747.2025.11269463">DOI: <code>10.1109/BHI67747.2025.11269463</code></a> · <a href="https://github.com/AspiringPianist/emg-estimation">Code (<code>emg-estimation</code>)</a></sub><br>
<br>
<b><i>Competitions and challenge projects</i></b><br>
<b>Stage 2 Winner, <a href="https://ai-grand-challenge.in/">NCIIPC &amp; Startup India AI Grand Challenge (2026)</a></b><br>
(Team Coders@IIITB) PS-11 Hyperspectral Anomaly Detection using Robust PCA and GAN-BWGNN pipelines.<br>
<sub><a href="https://github.com/AspiringPianist/hyperspectral_anomaly_detection"><code>hyperspectral_anomaly_detection</code></a></sub><br>
<br>
<b>1st Place, <a href="https://sites.google.com/view/vdvwc/home">ICDEC VDVWC Challenge (2024)</a></b><br>
Modified YOLOv10 for adverse-weather vehicle detection.<br>
<sub><a href="https://github.com/AspiringPianist/YOLOGANg_VehicleDetection"><code>YOLOGANg_VehicleDetection</code></a></sub><br>
<br>
<b>Top 10 Finalist, <a href="https://www.linkedin.com/posts/unnath-chittimalla-08aaaa287_top-10-finalists-activity-7350479787292839939-Km27">Meta Pragati AI for Impact (2025)</a></b><br>
Worked on a low-latency multilingual RAG system.<br>
<br>
<b>Top 11 Finalist, <a href="https://elciatechsummit.in/hackathon">ELCIA Tech Summit TRL-8 Sensor Challenge (2025)</a></b><br>
Quantized on-device Random Forest motion-artifact filter.<br>
<sub><a href="https://github.com/AspiringPianist/515Labs_VitalsTrack"><code>515Labs_VitalsTrack</code></a></sub><br>
<br>
<b>Teaching Assistant (Signals &amp; Systems), IIIT Bangalore</b><br>
Tutorials, labs and grading for 150+ ECE undergraduates.<br>
</td>
<td valign="top" width="50%">
<b><i>RTL, FPGA and computer architecture</i></b><br>
<b><a href="https://github.com/AspiringPianist/tiny-gpu"><code>tiny-gpu</code></a></b><br>
Studied and built a minimal GPU in <b>SystemVerilog</b>, following the public learning project <a href="https://github.com/adam-maj/tiny-gpu">adam-maj/tiny-gpu</a>: multi-core SIMD-style design, custom ISA, dispatcher, per-core ALU/LSU pipelines and memory controller; matrix addition &amp; multiplication kernels simulated with <b>cocotb</b> (RTL design and simulation).<br>
<sub><code>SystemVerilog</code> · <code>Icarus Verilog</code> · <code>cocotb</code> · <a href="https://www.youtube.com/watch?v=I2KRmAZkb30">no-code walkthrough video</a></sub><br>
<br>
<b><a href="https://github.com/AspiringPianist/hybrid-cmos-reram-memory"><code>hybrid-cmos-reram-memory</code></a></b><br>
SkyWater 130nm-targeted Hybrid CMOS-ReRAM memory controller (RTL and simulation) with a Ready/Valid interface, Program-and-Verify FSM and 1.8V-to-3.3V level shifters, plus a Virtuoso memristor crossbar matrix solver (99%+ numerical accuracy in simulation).<br>
<sub><code>SkyWater 130nm</code> · <code>Cadence Virtuoso (GPDK 180nm)</code></sub><br>
<br>
<b><a href="https://github.com/AspiringPianist/obc-vector-inner-product"><code>obc-vector-inner-product</code></a> &amp; <a href="https://github.com/AspiringPianist/4bit-baughwooley-multiplier"><code>4bit-baughwooley-multiplier</code></a></b><br>
Multiplier-less Q15 fixed-point inner-product DSP core using <b>Distributed Arithmetic (DA)</b> with <b>Offset Binary Coding (OBC)</b> for <b>50% LUT reduction</b>; plus a 4-stage pipelined <b>Baugh-Wooley multiplier</b> cutting critical-path logic delay by <b>2.1×</b> (1.473 ns → 0.704 ns, 5 → 2 logic levels, <b>166.7 MHz</b>).<br>
<sub><code>Verilog</code> · <code>Vivado STA</code> · <code>Artix-7</code></sub><br>
<br>
<b><a href="https://github.com/AspiringPianist/final_nn_fpga_tanh"><code>final_nn_fpga_tanh</code></a></b><br>
16-bit fixed-point quantized neural network (784×64×10 MLP with hardware <code>tanh</code>/ReLU) built with <b>Vitis HLS &amp; VHDL</b>, tested on-board on an <b>Artix-7 (Basys 3)</b> FPGA using <b>Vivado VIO and ILA</b> logic analyzers.<br>
<sub><code>Vitis HLS</code> · <code>VHDL</code> · <code>Vivado VIO/ILA</code></sub><br>
<br>
<b><a href="https://github.com/AspiringPianist/GA-Assisted-DDR-RAM-Output-Capacitor-Decoupling-Design"><code>GA-Assisted-DDR-RAM-Output-Capacitor-Decoupling-Design</code></a></b><br>
<b>7-stage EDA automation pipeline</b> converting DDR4-3200 command traces (Rowhammer, streaming, random) into SPICE <code>.pwl</code> waveforms. Batch-LTspice <b>Genetic Algorithm</b> optimizing an <b>86-capacitor network</b> (51 VDDQ, 35 VTT) on an <code>LTM4632</code> buck regulator under <b>0.948 nH</b> via inductance, suppressing anti-resonance spikes up to <b>1.6 GHz</b> within JEDEC ripple specs (±60 mV / ±40 mV).<br>
<sub><code>gem5</code> · <code>DRAMsim3</code> · <code>DRAMPower</code> · <code>LTspice</code></sub><br>
<br>
<b><a href="https://github.com/AspiringPianist/ldpc-decoder-rtl"><code>ldpc-decoder-rtl</code></a></b><br>
SystemVerilog RTL and functional simulation of a layered min-sum decoder; work in progress.<br>
<sub><code>SystemVerilog</code> · <code>Verilator/Icarus</code> · <code>C++ golden model</code></sub><br>
<br>
<b><a href="https://github.com/AspiringPianist/openenv-dcdc-rl"><code>openenv-dcdc-rl</code></a> (spiceRL)</b><br>
Small OpenEnv RL environment for sizing buck converter MOSFETs.<br>
<sub><code>Python</code> · <code>NGspice/LTspice</code> · <code>OpenEnv</code></sub><br>
</td>
</tr>
</table>

---

### Technical stack

- **HDLs & Computer Architecture:** `SystemVerilog` · `Verilog` · `VHDL` · `Vitis HLS` · `Custom GPU ISA` · `Pipelining`
- **EDA & FPGA Tools:** `Cadence Virtuoso (180nm GPDK)` · `Xilinx Vivado (OOC Synthesis, P&R, STA, VIO/ILA)` · `SkyWater 130nm PDK`
- **Simulation, Power & Verification:** `Verilator` · `Icarus Verilog` · `cocotb` · `gem5` · `DRAMsim3` · `DRAMPower` · `LTspice` · `NGspice` · `C++ Golden Models`
- **Scripting, Software & DSP/ML:** `Python` · `Tcl (EDA Batch Automation)` · `C++` · `C` · `Rust` · `Kotlin` · `Swift` · `MATLAB` · `PyTorch` · `Fixed-Point Quantization` · `Linux` · `Git`
