# Athish Vikraman

Hardware validation and characterization engineer. I quantify hardware behavior at the bench — oscilloscope, DMM, bare-metal firmware, statistical methodology.

## What I'm Building

**STM32F446RE Platform Validation & PVT Characterization Campaign**
Systematic validation campaign following semiconductor-industry PVT methodology. GPIO timing determinism (CV = 0.054% across N=20), power rail characterization (+0.27% accuracy on 3.3V LDO, 60 Hz mains EMI identified), communication bus signal integrity across voltage corners (2.8V–3.6V). All firmware is register-level C — no HAL. All measurements include sample count, mean, and standard deviation.

**Automated Validation & Regression Framework** — Repo coming soon
Python-on-Linux framework with Poisson failure rate fitting, Weibull reliability modeling, chi-squared significance testing, anomaly detection, and automated HTML reporting.

## What I've Built

**[RV32IM Pipelined CPU + Systolic Array Coprocessor](https://github.com/athish22072003/rv32im-systolic-coprocessor)**
5-stage pipelined RISC-V processor with a custom 4×4 INT8 systolic array coprocessor in SystemVerilog. Hardware validated on Zynq UltraScale+ — 138 MHz, 4,777 LUTs, 36/36 tests passing.

## Skills

**Validation & Lab:** Oscilloscopes · DMMs · Logic Analyzers · PVT Characterization · Signal Integrity · Root-Cause Analysis · Statistical Analysis
**Firmware:** C (bare-metal, register-level) · FreeRTOS · STM32 · ARM Cortex-M · ESP32
**Automation:** Python · scipy.stats · pyserial · Linux · bash
**HDL & FPGA:** SystemVerilog · Verilog · Xilinx Vivado · Zynq UltraScale+
**Protocols:** I2C · SPI · UART · CAN · AXI4-Lite

## Seeking

Fall 2026 co-op or full-time → Hardware Validation · Platform Validation · Characterization Engineering

[LinkedIn](https://www.linkedin.com/in/athishvikraman) · [Portfolio](https://athishvikraman.com)
