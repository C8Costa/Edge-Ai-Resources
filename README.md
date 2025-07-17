# Edge-AI-Resources

[![Last Updated](https://img.shields.io/github/last-commit/yourusername/edge-ai-resources?style=flat-square)](https://github.com/C8Costa/Edge-Ai-Resources/commits/main/) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](LICENSE)

A curated collection of **hardware**, **software**, **benchmarks**, **literature**, and **community projects** for deploying AI models on edge devices. This repository focuses on computer vision and audio applications, aggregating information from manufacturers, research papers, and open‑source communities.

## Table of Contents

1. [Hardware](#hardware)
   - [GPU Accelerators](#gpu-accelerators)
   - [FPGA Accelerators](#fpga-accelerators)
   - [ASIC & Microcontroller Accelerators](#asic--microcontroller-accelerators)
   - [Development Boards](#development-boards)
2. [Software Frameworks](#software-frameworks)
3. [Benchmarking](#benchmarking)
4. [Books & Literature](#books--literature)
5. [Community Repositories](#community-repositories)
6. [Useful Tutorials](#useful-tutorials)
7. [Contributing](#contributing)
8. [License](#license)

---

## Hardware
A categorized overview of available edge AI hardware accelerators and development boards.

### GPU Accelerators

1. **[NVIDIA Jetson](https://www.nvidia.com/en-us/autonomous-machines/embedded-systems/#hardware)**
   - Suite of modules (Nano, Xavier, Orin) for high-performance AI at the edge. See [Jetson Partner Hardware Products](https://developer.nvidia.com/embedded/jetson-partner-products).
2. **[AAEON Platforms](https://www.aaeon.com/en/c/aaeon-nvidia-ai-solutions)**
   - Embedded AI systems leveraging NVIDIA SoMs, from Jetson Nano to AGX Orin (up to 200 TOPS).
3. **[Artificial Intelligence Radio - Transceiver (AIR-T)](https://www.crowdsupply.com/deepwave-digital/air-t)**
   - High-performance SDR with integrated deep-learning inference hardware.
4. **[FZ3 Card](https://www.myirtech.com/list.asp?id=630)**
   - Xilinx Zynq UltraScale+ ZU3EG MPSoC-based accelerator card with ARM Cortex-A53/A53 and FPGA fabric.

### FPGA Accelerators

1. **[AMD (Xilinx) Kria SOMs](https://www.amd.com/en/products/system-on-modules/kria.html#portfolio)**
   - Features Zynq UltraScale+ MPSoC.  
   - **[Kria KV260](https://www.amd.com/en/products/system-on-modules/kria/k26/kv260-vision-starter-kit.html)** — Vision starter kit.  
   - **[Ultra96-V2](https://www.96boards.org/product/ultra96/)** — 96Boards CE compliant board.
2. **Intel FPGA AI Suite**  
   - AI inference on Altera FPGAs.  
   - **[Agilex](https://www.intel.com/content/www/us/en/products/docs/programmable/agilex-5-d-series-fpga.html)** — Enhanced DSP + AI Tensor Blocks.  
   - **[Arria 10 GX](https://www.intel.com/content/www/us/en/products/details/fpga/development-kits/cyclone/10-gx.html)** — Ideal for embedded vision and automation.
3. **[EFINIX Titanium FPGAs](https://www.efinixinc.com/products-titanium.html)**
   - 16 nm process, 35 K–1 M LE densities, RISC-V SoC compatible.
4. **[Lattice sensAI](https://www.latticesemi.com/en/Solutions/Solutions/SolutionsDetails02/sensAI)**
   - End-to-end FPGA ML stack (IP cores, tools, reference designs).
5. **[Microchip PolarFire® SoC](https://www.microchip.com/en-us/products/fpgas-and-plds/system-on-chip-fpgas/polarfire-soc-fpgas)**
   - RISC-V CPU cluster + FPGA.  
   - **[BeagleV®-Fire](https://www.beagleboard.org/boards/beaglev-fire)** — PolarFire SoC SBC.

### ASIC & Microcontroller Accelerators

- **[Arm Ethos NPUs](https://www.arm.com/products/silicon-ip-cpu?families=ethos%20npus)** — Scalable inference up to 4 TOPS.
- **[Google Coral TPU](https://coral.ai/products/)** — Edge TPU ASIC.
- **[Syntiant NDPs](https://www.syntiant.com/hardware)** — M0 cores + deep-learning architecture for always-on audio.
- **[MAX78002](https://www.analog.com/en/products/max78002.html)** — Cortex-M4 + ultra-low-power DNN accelerator.
- **[ESP32-S3](https://www.espressif.com/en/products/socs/esp32-s3)**
  - Vector instructions for NN workloads.  
  - **[ESP32-S3-EYE](https://www.espressif.com/en/products/devkits/esp-eye/overview)** — AI development board.
- **[RA8M1](https://www.renesas.com/us/en/products/microcontrollers-microprocessors/ra-cortex-m-mcus/ra8m1-480-mhz-arm-cortex-m85-based-microcontroller-helium-and-trustzone)** — Cortex-M85 MCU.
- **[STM32H747XI](https://www.st.com/en/microcontrollers-microprocessors/stm32h747xi.html)** — Cortex-M7 + M4 cores.  
  - **[OpenMV Cam H7](https://www.sparkfun.com/openmv)** — MicroPython vision board.
- **[STM32MP257F](https://www.st.com/en/microcontrollers-microprocessors/stm32mp257f.html)** — Dual A35 + M33 + 1.35 TOPS NPU.
- **[NXP MCX N9x](https://www.nxp.com/products/processors-and-microcontrollers/arm-microcontrollers/general-purpose-mcus/mcx-arm-cortex-m/mcx-n-series-microcontrollers/mcx-n94x-54x-highly-integrated-multicore-mcus-with-on-chip-accelerators-intelligent-peripherals-and-advanced-security:MCX-N94X-N54X)** — Dual M33 + eIQ Neutron NPU.
- **[TI AM6xxX](https://www.ti.com/microcontrollers-mcus-processors/arm-based-processors/products.html#1217=1%20deep%20learning%20accelerator%2C%201%20video%20encode%2Fdecode%20accelerator%2C%201%20vision%20pre-processing%20accelerator%3B1%20deep%20learning%20accelerator%2C%201%20video%20encode%2Fdecode%20accelerator%2C%201%20vision%20pre-processor%20accelerator&2115=2%20Arm%20Cortex-A53%3B4%20Arm%20Cortex-A53&) — Cortex-A53 + C7x256v DL accelerator.  
  - **[BeagleY®-AI](https://www.beagleboard.org/boards/beagley-ai)** — AM67A-based SBC.
- **[GreenWaves GAPx](https://greenwaves-technologies.com/low-power-processor/)** — RISC-V for low-power AI.
- **[Kneron AI SoCs](https://www.kneron.com/page/soc/)** — Proprietary NPU for smart devices.
- **[Kendryte K2xx Series](https://developer.canaan-creative.com/resource)** — RISC-V NPUs.  
  - **[Grove AI HAT](https://wiki.sipeed.com/soft/maixpy/en/develop_kit_board/grove_ai_hat.html)** — Kendryte K210 module.
  - **[Canaan CanMV-K230](https://developer.canaan-creative.com/k230/dev/zh/CanMV_K230_%E6%95%99%E7%A8%8B.html)** — K230 AIoT board.
- **[Intel Movidius Myriad X VPU](https://www.intel.com/content/www/us/en/products/details/processors/movidius-vpu.html)**
  - **[Neural Compute Stick 2](https://www.intel.com/content/www/us/en/developer/articles/tool/neural-compute-stick.html)**
  - **[UP Xtreme Edge Compute Kit](https://up-board.org/up-xtreme-edge-compute-enabling-kit/)**
- **[Hailo-8 AI Accelerator](https://hailo.ai/products/ai-accelerators/)** — Up to 26 TOPS.  
  - **[Raspberry Pi AI Kit](https://www.raspberrypi.com/products/ai-kit/)**
- **[Ambiq Apollo](https://ambiq.com/products/)** — Cortex-M4F.  
  - **[SparkFun Edge - Apollo3 Blue](https://www.sparkfun.com/products/15170)**
- **[Himax WE-I Plus EVB](https://www.sparkfun.com/products/17256)** — ARC EM9D DSP + AI accelerator.

### Development Boards

- **[OpenMV Cam H7](https://www.sparkfun.com/openmv)** — MicroPython-powered vision board.
- **[SparkFun Edge - Apollo3 Blue](https://www.sparkfun.com/products/15170)** — Apollo3 MCU for TensorFlow Lite.
- **[Khadas VIM3](https://www.khadas.com/vim3)** — Amlogic A311D (5 TOPS NPU).
- **[JEVOIS-PRO](https://www.jevoisinc.com/)** — Quad-core AI camera.

## Software Frameworks

- [TensorFlow Lite]()
- [PyTorch Mobile / TorchScript]()
- [ONNX Runtime]()
- [AMD Vitis AI™](https://xilinx.github.io/Vitis-AI/3.5/html/index.html)
- [OpenVINO]()
- [TensorRT]()
- [STM32Cube.AI]()
- [e-AI Development Environment](https://www.renesas.com/us/en/e-ai-development-environment-microcontrollers#overview)
- [Reality AI Tools®](https://www.renesas.com/us/en/software-tool/reality-ai-tools)

## Benchmarking

- [Edge AIBench V3.0](https://www.benchcouncil.org/aibench/edge-aibench/index.html)
- [AIoTBench](https://www.benchcouncil.org/aibench/aiotbench/index.html)
- [MLMark](https://www.eembc.org/mlmark/)
- [MLPerf Tiny Inference](https://mlcommons.org/en/inference-tiny-10/)
- [EDLAB (Edge Deep Learning Accelerator Benchmark)](https://github.com/HPInc/EDLAB)

## Books & Literature

- [Machine Learning Systems](https://mlsysbook.ai/) — Principles and practices of engineering AI systems.
- [TinyML]() — Machine learning on resource-constrained devices.
- [Efficient Processing of Deep Neural Networks]()

## Community Repositories

- [crespum/edge-ai](https://github.com/crespum/edge-ai)
- [rcmalli/awesome-edge-ai](https://github.com/rcmalli/awesome-edge-ai)
- [Bisonai/awesome-edge-machine-learning](https://github.com/Bisonai/awesome-edge-machine-learning)
- [basicmi/AI-Chip](https://github.com/basicmi/AI-Chip)
- [icochecker/AI-Chip-List](https://github.com/icochecker/AI-Chip-List)

## Useful Tutorials

### Xilinx Vitis AI
- [Overview](https://docs.amd.com/r/en-US/ug1414-vitis-ai/Vitis-AI-Overview)
- [Quick Start (UltraScale+)](https://xilinx.github.io/Vitis-AI/3.0/html/docs/install/install.html)
- [YOLOv5 Quantization on Kria](https://www.hackster.io/LogicTronix/yolov5-quantization-compilation-with-vitis-ai-3-0-for-kria-7b005d)

### Coral Edge TPU
- [Getting Started](https://coral.ai/docs/accelerator/get-started/)
- [Model Optimization](https://coral.ai/docs/edgetpu/models-intro/)

## Contributing

Contributions welcome!  
1. Fork the repo.  
2. Create a branch (`git checkout -b feature-name`).  
3. Commit changes (`git commit -m "Add resource"`).  
4. Push (`git push origin feature-name`).  
5. Open a PR.

## License

MIT License. See [LICENSE](LICENSE).
