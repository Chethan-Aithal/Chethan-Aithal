<div align="center">

<!-- Animated Header Banner -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:58a6ff,100:3fb950&height=200&section=header&text=Chethan%20Aithal&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=VLSI%20%7C%20RTL%20Design%20%7C%20FPGA%20%7C%20Design%20Verification&descAlignY=60&descColor=a8d8ea" />

<!-- Typing SVG -->
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=58A6FF&center=true&vCenter=true&width=600&lines=RTL+Design+%26+Microarchitecture;FPGA+Prototyping+%26+Bring-Up;Design+Verification+(DV);ASIC+Design+Enthusiast)](https://git.io/typing-svg)

</div>

---

## Professional Summary

```verilog
module VLSI_Engineer (
    input  wire clk,
    input  wire rst_n,
    output reg  [31:0] skill_level
);
    // Electronics & Communication Engineering Student
    // Focused on RTL Design, FPGA Implementation, and Design Verification

    always @(posedge clk or negedge rst_n) begin
        if (!rst_n)
            skill_level <= 32'h0;
        else
            skill_level <= skill_level + 1'b1; // Continuous Learning
    end
endmodule
```

> Aspiring **VLSI Engineer** with hands-on experience in **RTL Design**, **Design Verification (DV)**, and **FPGA Development**. 
> B.E. in Electronics and Communication Engineering (ECE), specializing in digital systems and hardware architecture.
> Strong foundation in writing synthesizable **Verilog**, developing robust **Testbenches**, and analyzing simulation waveforms.
> Currently expanding expertise in **ASIC Design flows**, **Physical Design**, and the intersection of hardware and **Machine Learning**.

---

## Technical Arsenal

<div align="center">

### Hardware Description & Languages
![Verilog](https://img.shields.io/badge/Verilog-FF6B35?style=for-the-badge&logo=v&logoColor=white)
![C/C++](https://img.shields.io/badge/C%2FC++-00599C?style=for-the-badge&logo=c&logoColor=white)
![Embedded C](https://img.shields.io/badge/Embedded%20C-A8B9CC?style=for-the-badge)
![Assembly](https://img.shields.io/badge/Assembly-4EAA25?style=for-the-badge)

### EDA Tools & Synthesis
![Xilinx Vivado](https://img.shields.io/badge/Xilinx%20Vivado-E01F27?style=for-the-badge&logo=xilinx&logoColor=white)
![Cadence](https://img.shields.io/badge/Cadence-E31837?style=for-the-badge)
![Keil](https://img.shields.io/badge/Keil%20µVision-000000?style=for-the-badge)
![VS Code](https://img.shields.io/badge/VS%20Code-0078D4?style=for-the-badge&logo=visual-studio-code&logoColor=white)

### Target Architectures & Hardware
![Xilinx Spartan-6 & Artix-7](https://img.shields.io/badge/Xilinx%20Spartan--6%20%26%20Artix--7-E01F27?style=for-the-badge)
![ARM Cortex-M3](https://img.shields.io/badge/ARM%20Cortex--M3-0091BD?style=for-the-badge&logo=arm&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)

</div>

---

## Industry Spotlight — Core VLSI Projects

> Highlighting projects that demonstrate industry-standard practices: **Microarchitecture Design**, **Protocol IP Implementation**, and **End-to-End Verification**.

<div align="center">

| Project | VLSI / Industry Relevance | Tech Stack | Domain |
|:---|:---|:---|:---:|
| [**MIPS32 Processor Design**](https://github.com/Chethan-Aithal/MIPS_REGISTER_BANK_DESIGN-32x32-) | **Processor Microarchitecture** — Developed a 5-stage pipelined RISC architecture (IF, ID, EX, MEM, WB). Implemented core RTL modules (ALU, Register File, CU) and verified execution via simulation. Highly relevant to CPU/SoC roles. | `Verilog` `MIPS` `Vivado` | ![CPU Design](https://img.shields.io/badge/CPU%20Architecture-6C3483?style=flat-square) |
| [**SPI ADC Controller**](https://github.com/Chethan-Aithal/spi-ltc1407a-fpga-interface) | **Hardware Bring-Up & Interfacing** — Designed an SPI Master Controller to interface a real ADC (LTC1407A) and LM35 sensor on a Spartan-3E FPGA. Proves ability to bridge RTL with physical silicon. | `Verilog` `SPI` `Spartan-3E` | ![Hardware](https://img.shields.io/badge/FPGA%20Bring--Up-FF6B35?style=flat-square) |
| [**UART Transceiver & Receiver**](https://github.com/Chethan-Aithal/uart-transceiver-receiver-verilog) | **Protocol IP Design & DV** — Architected a complete asynchronous serial communication IP with configurable baud rates. Verified end-to-end TX/RX operations using comprehensive testbenches. | `Verilog` `UART` `FSM` | ![Protocol IP](https://img.shields.io/badge/Protocol%20IP-1ABC9C?style=flat-square) |
| [**Single & Dual-Port RAM**](https://github.com/Chethan-Aithal/Single-and-Dual-port-RAM) | **Memory IP Design** — Developed synthesizable single and dual-port SRAM architectures. Memory subsystems are critical building blocks in modern ASICs and FPGAs. | `Verilog` `SRAM` `Memory` | ![Memory Design](https://img.shields.io/badge/Memory%20Subsystems-0F3460?style=flat-square) |

</div>

---

### Additional RTL & Algorithmic Projects

<div align="center">

| Project | Description | Tech Stack |
|:---|:---|:---|
| [Double Dabble Multiplier](https://github.com/Chethan-Aithal/Multiplier_Doubble_Dabble_Algorithm) | Binary-to-BCD multiplier utilizing the Double Dabble algorithm. Demonstrates ability to translate mathematical algorithms into synthesizable RTL. | `Verilog` `Algorithm` `Arithmetic` |
| [Voting Machine](https://github.com/Chethan-Aithal/Voting_Machine) | FPGA-based digital voting machine controlled by robust FSM logic design. | `Verilog` `FSM` `FPGA` |
| [RAM Verilog](https://github.com/Chethan-Aithal/RAM_VERILOG) | Parameterized RAM architecture highlighting scalable and reusable memory design practices. | `Verilog` `Memory` |
| [HDLBits Practice](https://github.com/Chethan-Aithal/HDL_bits_practice) | Documented solutions to HDLBits exercises covering advanced combinational/sequential logic and FSM verification scenarios. | `Verilog` `Practice` |

</div>

---

## GitHub Statistics

<div align="center">

<!-- Alternative GitHub Stats that are more reliable -->
<img height="180" src="https://github-readme-stats-eight-theta.vercel.app/api?username=Chethan-Aithal&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=3fb950&text_color=c9d1d9" alt="GitHub Stats" />

<img height="180" src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=Chethan-Aithal&layout=compact&langs_count=8&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9" alt="Top Languages" />

</div>

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=Chethan-Aithal&theme=github-dark-blue&hide_border=true&background=0D1117&stroke=58A6FF&ring=3FB950&fire=F78166&currStreakLabel=58A6FF)](https://git.io/streak-stats)

</div>

---

## Connect With Me

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-Chethan--Aithal-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Chethan-Aithal)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/chethan-aithal)
[![Email](https://img.shields.io/badge/Email-chethanaithal25%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:chethanaithal25@gmail.com)

</div>

---

<div align="center">

<!-- Profile Views Counter -->
![Profile Views](https://komarev.com/ghpvc/?username=Chethan-Aithal&color=58a6ff&style=flat-square&label=Profile+Views)

<!-- Snake Animation (Note: This will be a broken image link until you setup and run the GitHub Action in setup_guide.md!) -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Chethan-Aithal/Chethan-Aithal/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Chethan-Aithal/Chethan-Aithal/output/github-contribution-grid-snake.svg">
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/Chethan-Aithal/Chethan-Aithal/output/github-contribution-grid-snake.svg">
</picture>

<br>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:3fb950,50:58a6ff,100:0d1117&height=120&section=footer" />

</div>
