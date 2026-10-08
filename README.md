<p align="center">
<img src="logo.png" width="200">
</p>

# Computing Systems Efficiency Research (CSER)

The **Computing Systems Efficiency Research (CSER)** group is an undergraduate research group of the **Computer Science program at Universidade Federal do Tocantins (UFT)**. We study methods, tools and architectures that improve the **efficiency, performance and sustainability** of computing systems, and we publish code and data openly so experiments can be reproduced.

### Research areas
- Energy efficient and sustainable computing
- Approximate and inexact computing
- Hardware/software codesign

### Projects

| Project | Student | Repository |
|---|---|---|
| Sorting with Imprecise Comparators (undergraduate thesis) | Rafael Soares | [sort-evaluation-tolerance](https://github.com/CSER-UFT/sort-evaluation-tolerance) |
| Approximate Convolution and GEMM (undergraduate thesis) | Vinícius Arruda | [matrix_convolution](https://github.com/CSER-UFT/matrix_convolution) |
| Loop Perforation on IoT Devices (PIBIC) | Gabriel Fernandes Zamora | [Algoritmo-de-verificação-de-corrente](https://github.com/CSER-UFT/Algoritmo-de-verifica-o-de-corrente) |
| Adder Architectures on FPGA (undergraduate thesis) | Pablo Pereira Brito | [approximate_adders](https://github.com/CSER-UFT/approximate_adders) |
| Systolic Matrix Multiplication on FPGA (PIBIC) | Samuel Andrade | [systolic_matrix](https://github.com/CSER-UFT/systolic_matrix) |
| Exact and Approximate Multipliers on FPGA (undergraduate thesis) | Jeová de Sousa Barbosa (alumnus) | [approximate_multipliers](https://github.com/CSER-UFT/approximate_multipliers) |

### Teaching simulators

Four educational RISC-V simulators used in the Computer Organization course, presented on the [Simulators page](https://cser-uft.github.io/simulators.html):

| Simulator | Covers | Repository |
|---|---|---|
| Arithmetic | integers, IEEE 754 floating point, fixed point, rounding | [riscv-fp-simulator](https://github.com/CSER-UFT/riscv-fp-simulator) |
| Processors | single cycle, pipeline, Tomasulo, caches, virtual memory | [riscv-cpu-simulator](https://github.com/CSER-UFT/riscv-cpu-simulator) |
| Multiprocessing | cache coherence (MSI, MESI, MOESI) and atomic instructions | [riscv-mp-simulator](https://github.com/CSER-UFT/riscv-mp-simulator) |
| Data level parallelism | vector processor, GPU and TPU | [riscv-dlp-simulator](https://github.com/CSER-UFT/riscv-dlp-simulator) |

### About this repository
This repository holds the group website. `index.html`, `research.html`, `projects.html` and `simulators.html` are static pages that share `style.css`, with no build step, so the same files are served by GitHub Pages and by the group's own server. To add a project, copy the commented template at the top of the list in `projects.html`, add a line to the project list on the home page and a row to the table above. The figures on the Simulators page, in `img/simulators/`, are SVG exports from the simulators themselves.
