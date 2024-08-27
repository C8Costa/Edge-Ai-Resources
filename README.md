# Edge-Ai-Resources
This is a list of useful Edge Ai information, including hardware, software, scientific literature

## Index
- [Hardware](#hardware)
- [Software](#software)
- [Benchmarking](#benchmarks)
- [Books & Other Literature](#Literature)
- [Commmunity Repositories](#repositories)
- [Usefull Tutorials](#tutorials)
- [Optimized Dl Models](#models)
- [Multimodal Datasets](#datasets)

# Hardware
### MCU + GPU
-[NVidia Jetson](https://www.nvidia.com/en-us/autonomous-machines/embedded-systems/#hardware) - The NVIDIA Jetson platform is a suite of hardware and software solutions designed for deploying AI at the edge. It provides high-performance computing capabilities in a small, energy-efficient form factor, making it ideal for AI-powered applications like robotics, autonomous machines, and IoT devices. The platform includes various modules, such as Jetson Nano, Jetson Xavier, and Jetson Orin. 

### MCU + FPGA
- [AMD Kria KV260](https://www.amd.com/en/products/system-on-modules/kria.html#portfolio)- The AMD Kria Som feature Zynq UltraScale+ MPSoC.

### MCU + ASIC
## MCUs
- [RA8M1](https://www.renesas.com/us/en/products/microcontrollers-microprocessors/ra-cortex-m-mcus/ra8m1-480-mhz-arm-cortex-m85-based-microcontroller-helium-and-trustzone) - The Renesas IC is based on the Arm® Cortex®-M85, 
- [MAX78002](https://www.analog.com/en/products/max78002.html) - Analog Devices system-on-chip featuring an Arm® Cortex®-M4 with FPU CPU for efficient system control with an ultra-low-power deep neural network accelerator.
- [STM3232H747XI](https://www.st.com/en/microcontrollers-microprocessors/stm32h747xi.html) - STMicroelectronics IC based on the high-performance Arm® Cortex®-M7 and Cortex®-M4 32-bit RISC cores.
- [STM32MP257F](https://www.st.com/en/microcontrollers-microprocessors/stm32mp257f.html) - Dual Cortex-A35, Cortex-M33, neural processing unit (NPU) with 1.35 TOPS and graphics processing unit (GPU).
- [MCX N94x/54x](https://www.nxp.com/products/processors-and-microcontrollers/arm-microcontrollers/general-purpose-mcus/mcx-arm-cortex-m/mcx-n-series-microcontrollers/mcx-n94x-54x-highly-integrated-multicore-mcus-with-on-chip-accelerators-intelligent-peripherals-and-advanced-security:MCX-N94X-N54X) - NXP IC based on dual high-performance Arm® Cortex®-M33 cores running up to 150 MHz, with 2MB of Flash with optional full ECC RAM, a DSP co-processor and an integrated eIQ Neutron NPU.
- [AM62AX](https://www.ti.com/microcontrollers-mcus-processors/arm-based-processors/products.html#1217=1%20deep%20learning%20accelerator%2C%201%20video%20encode%2Fdecode%20accelerator%2C%201%20vision%20pre-processing%20accelerator%3B1%20deep%20learning%20accelerator%2C%201%20video%20encode%2Fdecode%20accelerator%2C%201%20vision%20pre-processor%20accelerator&2115=2%20Arm%20Cortex-A53%3B4%20Arm%20Cortex-A53&) - Texas Instruments IC e integrated 64-bit Arm Cortex-A53 and 2 Deep Learning Accelerator (C7x256v).

- [GAPx](https://greenwaves-technologies.com/low-power-processor/) - GREENWAVES TECHNOLOGIES ICs 
- [Kneron AI SOCs](https://www.kneron.com/page/soc/)
- [Kendryte K210](https://maixduino.sipeed.com/en/hardware/k210.html)

- [Google Coral TPU](https://coral.ai/products/) - Google ASIC designed for Edge aplications.
- [Hailo-8 AI Accelerator](https://hailo.ai/products/ai-accelerators/) - HAILO 

## Development Boards
[Himax WE-I Plus EVB Endpoint AI Development Board](https://www.sparkfun.com/products/17256)


# Software
[Tensorflow Lite]()
[Pytorch Executorch]()
[ONNX Runtime]()

[AMD VitisAi™](https://xilinx.github.io/Vitis-AI/3.5/html/index.html) - AI inference development platform for AMD devices, boards, and Alveo™ data center acceleration cards.
[OpenVINO]()
[TensorRT]()

[STM32Cube.Ai]()
[e-AI Development Environment & Downloads](https://www.renesas.com/us/en/e-ai-development-environment-microcontrollers#overview) - The tool can convert from a trained model of “PyTorch”, “Keras”, “Tensorflow”, or an 8-bit quantized model of “TensorFlow Lite” and import it easily to e² studio, Renesas' integrated development environment.
[Reality AI Tools®](https://www.renesas.com/us/en/software-tool/reality-ai-tools)


# Benchmarking
- [AEdge AIbench V3.0](https://www.benchcouncil.org/aibench/edge-aibench/index.html)
- [AIoTBench](https://www.benchcouncil.org/aibench/aiotbench/index.html)
- [Flet-Edge](https://www.benchcouncil.org/FletEdge/, https://github.com/Jxyzzu/Flet-Edge)
- [MLMark](https://www.eembc.org/mlmark/)
- [MLPerf Tiny Benchmark](https://mlcommons.org/en/inference-tiny-10/)
- [EDLAB](https://github.com/HPInc/EDLAB)

# Books & Other Literature
- [Machine Learning Systems - Principles and Practices of Engineering Artificially Intelligent Systems](https://mlsysbook.ai/)

# Community Repositories
- [Github: AI at the edge](https://github.com/crespum/edge-ai) - A curated list of hardware,software, frameworks and other resources for Artificial Intelligence at the edge.
- [Github: awesome-edge-ai](https://github.com/rcmalli/awesome-edge-ai) - A curated list of edge devices for AI applications.
- [Github: awesome-dge-machine-learning](https://github.com/Bisonai/awesome-edge-machine-learning) - A curated list of awesome edge machine learning resources, including research papers, inference engines, challenges, books, meetups and others.
- [Github: AI-Chip-List](https://github.com/icochecker/AI-Chip-List) - AI/ML/DL ICs and IPs

# Tutorials
## Xilinx Vitis Ai:
- [Vitis Ai Overview](https://docs.amd.com/r/en-US/ug1414-vitis-ai/Vitis-AI-Overview)
- [Quick Start Guide for Zynq™ UltraScale+™](https://xilinx.github.io/Vitis-AI/3.0/html/docs/install/install.html)
- [VitisAi 3.5 Host Installation](https://xilinx.github.io/Vitis-AI/3.5/html/docs/install/install.html)
- [VitisAi 3.0 Host Installation](https://xilinx.github.io/Vitis-AI/3.0/html/docs/install/install.html)
- [YOLOv5 Quantization & Compilation with Vitis AI 3.0 for Kria](https://www.hackster.io/LogicTronix/yolov5-quantization-compilation-with-vitis-ai-3-0-for-kria-7b005d)
- [AMD Xilinx Kria KV260 Vision AI Starter Kit: License plate detection: YOLOv7](https://community.element14.com/products/roadtest/b/blog/posts/amd-xilinx-kria-kv260-vision-ai-starter-kit-license-plate-detection-yolov7)


# Optimized Dl Models

# Multimodal Datasets