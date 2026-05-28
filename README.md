# Athish Vikraman

**Hardware validation and characterization engineer.** I quantify hardware behavior at the bench — oscilloscope, DMM, bare-metal firmware, statistical methodology.

M.S. Electrical Engineering @ Case Western Reserve University

---

## What I'm Building

**STM32F446RE Platform Validation & PVT Characterization Campaign**
Systematic validation campaign following semiconductor-industry PVT methodology. GPIO timing determinism (CV = 0.054% across N=20), power-rail characterization (+0.27% accuracy on the 3.3 V LDO, 60 Hz mains EMI identified), communication-bus signal integrity across voltage corners (2.8 V–3.6 V). All firmware is register-level C — no HAL. Every measurement includes sample count, mean, and standard deviation.

**Automated Validation & Regression Framework** — *repo coming soon*
Python-on-Linux framework with Poisson failure-rate fitting, Weibull reliability modeling, chi-squared significance testing, anomaly detection, and automated HTML reporting.

---

## What I've Built

**[RV32IM Pipelined CPU + Systolic Array Coprocessor](https://github.com/athish22072003/rv32im-systolic-coprocessor)**
5-stage pipelined RISC-V processor with a custom 4×4 INT8 systolic array coprocessor in SystemVerilog. Hardware-validated on Zynq UltraScale+ — 138 MHz, 4,777 LUTs, 36/36 tests passing.

**[BitNet-Style Ternary Transformer Block on FPGA](https://github.com/athish22072003/bitnet-ternary-transformer-fpga)**
Full Transformer block (multi-head self-attention, MLP, LayerNorm, softmax) in C++ via Vitis HLS, placed-and-routed on the Avnet AUP-ZU3 (Zynq UltraScale+). BitNet-style ternary {−1, 0, +1} weights replace every weight multiply with a conditional add/subtract — DSP −38.5% (39→24), LUT −25%, FF −20.4%, BRAM −27% at identical II=1 throughput. Verified bit-faithfully against a C++ golden model and on real silicon.

**[Event-Driven Warehouse Video Surveillance](https://github.com/athish22072003/warehouse-surveillance-rpi)**
Real-time embedded surveillance on Raspberry Pi 5 in C++17 / OpenCV 4.10. A Moore finite-state machine classifies activity into four severity levels and switches recording mode accordingly — ~97% storage reduction vs. continuous capture (2.5 vs 86.5 GB/day), 15.6 ms/frame (≈64 FPS), demonstrated live on two USB cameras.

---

## Skills

**Validation & Lab:** Oscilloscopes · DMMs · Logic Analyzers · PVT Characterization · Signal Integrity · Root-Cause Analysis · Statistical Analysis
**Firmware:** C (bare-metal, register-level) · FreeRTOS · STM32 · ARM Cortex-M · ESP32
**Automation:** Python · scipy.stats · pyserial · Linux · bash
**HDL & FPGA:** SystemVerilog · Verilog · Vitis HLS · Xilinx Vivado · Zynq UltraScale+
**Protocols:** I²C · SPI · UART · CAN · AXI4-Lite

---

## Seeking

**Summer internship, Fall 2026 co-op, or full-time** → Hardware Validation · Platform Validation · Characterization Engineering

[LinkedIn](https://www.linkedin.com/in/athishvikraman) · [Portfolio](https://athish22072003.github.io)
