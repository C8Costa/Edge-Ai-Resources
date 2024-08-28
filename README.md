# Edge-Ai-Resources
This is a list of useful Edge Ai information, including hardware, software, scientific literature.
With this repository with pretend to provide a extensive overview of current edge ai resources, focusing on vision and audio applications. We try to gather the most important information including current hardware from the major IC manufactures and some from vaiable startups.

## Index
- [Hardware](#hardware)
- [Software](#software)
- [Benchmarking](#benchmarking)
- [Books & Other Literature](#books-other-literature)
- [Community Repositories](#community-repositories)
- [Useful Tutorials](#useful-tutorials)
- [Optimized DL Models](#optimized-dl-models)
- [Multimodal Datasets](#multimodal-datasets)

# Hardware
We look to present the various types of hardware available for Edge AI, devided by diferent categories of hardware accelerators.
  1. GPU Accelerators[]()
  2. FPGA Accelerators
  3. ASICS Accelerators & Generic Controllers ( NPU, VPU, TPU, MCU ( ARM, RISC-V, ARC ) )

### GPU
- [NVIDIA Jetson](https://www.nvidia.com/en-us/autonomous-machines/embedded-systems/#hardware) - The NVIDIA Jetson platform is a suite of hardware and software solutions designed for deploying AI at the edge. It provides high-performance computing capabilities in a small, energy-efficient form factor, making it ideal for AI-powered applications like robotics, autonomous machines, and IoT devices. The platform includes various modules, such as Jetson Nano, Jetson Xavier, and Jetson Orin. To review the full suite of jetson developmeent systems pls refer to [Jetson Partner Hardware Products](https://developer.nvidia.com/embedded/jetson-partner-products)
  - [AAEONN Platforms](https://www.aaeon.com/en/c/aaeon-nvidia-ai-solutions) - AAEON’s embedded AI systems utilize the entire range of NVIDIA SoMs, from the budget-friendly Jetson Nano to the highly powerful Jetson AGX Orin, which delivers up to 200 TOPS of inferencing performance.
  - [Artificial Intelligence Radio - Transceiver (AIR-T)](https://www.crowdsupply.com/deepwave-digital/air-t) - The Artificial Intelligence Radio Transceiver (AIR-T) is a high-performance software-defined radio (SDR) seamlessly integrated with state-of-the-art processing and deep learning inference hardware.
  - [FZ3 Card](https://www.myirtech.com/list.asp?id=630) - The FZ3 Card is a powerful deep learning accelerator card based on Xilinx Zynq UltraScale+ ZU3EG MPSoC which features a 1.2 GHz quad-core ARM Cortex-A53 64-bit application processor, a 600MHz dual-core real-time ARM Cortex-R5 processor, a Mali400 embedded GPU and rich FPGA fabric.

### FPGA
- [AMD (previous Xilinx) Kria SOMs](https://www.amd.com/en/products/system-on-modules/kria.html#portfolio)- The AMD Kria SOMs feature Zynq UltraScale+ MPSoC.
  - [AMD Kria KV260](https://www.amd.com/en/products/system-on-modules/kria/k26/kv260-vision-starter-kit.html) - The KV260 is built for advanced vision application development without requiring complex hardware design knowledge.
  - [Ultra96-V2](https://www.96boards.org/product/ultra96/) - Ultra96-V2 is an Arm-based, Xilinx Zynq UltraScale+ ™ MPSoC development board based on the Linaro 96Boards Consumer Edition (CE) specification.
  - []()
- [Intel  FPGA]() - s''''''''''''
  - [Agilex](https://www.intel.com/content/www/us/en/products/docs/programmable/agilex-5-d-series-fpga.html) - FPGAs integrating Enhanced DSP with AI Tensor Blocks.
  - [Arria](https://www.intel.com/content/www/us/en/products/details/fpga/development-kits/cyclone/10-gx.html) - Intel® Cyclone® 10 GX FPGA Development Kit is an ideal starting point for applications, such as embedded vision, factory automation, video connectivity evaluation, or concept proving.
- [EFINIX]() - 
- [Lattice]() - 
- [Microchip PolarFire® SoC FPGAs](https://www.microchip.com/en-us/products/fpgas-and-plds/system-on-chip-fpgas/polarfire-soc-fpgas) - The PolarFire®  is the first System-on-Chip (SoC) FPGA to feature a deterministic, coherent RISC-V CPU cluster.
  - [BeagleV®-Fire](https://www.beagleboard.org/boards/beaglev-fire) - BeagleV®-Fire is a revolutionary single-board computer (SBC) powered by the Microchip’s PolarFire® MPFS025T 5x core RISC-V System on Chip (SoC) with FPGA fabric.

### Generic Controllers & ASIC Accelerators
- [RA8M1](https://www.renesas.com/us/en/products/microcontrollers-microprocessors/ra-cortex-m-mcus/ra8m1-480-mhz-arm-cortex-m85-based-microcontroller-helium-and-trustzone) -  The Renesas IC is based on the Arm® Cortex®-M85.
- [MAX78002](https://www.analog.com/en/products/max78002.html) - Analog Devices system-on-chip featuring an Arm® Cortex®-M4 with FPU CPU for efficient system control with an ultra-low-power deep neural network accelerator.
- [STM3232H747XI](https://www.st.com/en/microcontrollers-microprocessors/stm32h747xi.html) - STMicroelectronics IC based on the high-performance Arm® Cortex®-M7 and Cortex®-M4 32-bit RISC cores.
   - [OpenMV Cam H7](https://www.sparkfun.com/openmv) - The OpenMV H7 Camera is a small, low power, microcontroller board which allows you to easily implement applications using machine vision in the real-world. Out of the box, it comes loaded with the MicroPython interpreter, so you don't need to load anything to get it up and running!
   - [OpenMV Cam H7](https://www.sparkfun.com/openmv) - The OpenMV H7 Camera is a small, low power, microcontroller board which allows you to easily implement applications using machine vision in the real-world. Out of the box, it comes loaded with the MicroPython interpreter, so you don't need to load anything to get it up and running!
- [STM32MP257F](https://www.st.com/en/microcontrollers-microprocessors/stm32mp257f.html) - Dual Cortex-A35, Cortex-M33, neural processing unit (NPU) with 1.35 TOPS and graphics processing unit (GPU).
- [MCX N94x/54x](https://www.nxp.com/products/processors-and-microcontrollers/arm-microcontrollers/general-purpose-mcus/mcx-arm-cortex-m/mcx-n-series-microcontrollers/mcx-n94x-54x-highly-integrated-multicore-mcus-with-on-chip-accelerators-intelligent-peripherals-and-advanced-security:MCX-N94X-N54X) - NXP IC based on dual high-performance Arm® Cortex®-M33 cores running up to 150 MHz, with 2MB of Flash with optional full ECC RAM, a DSP co-processor and an integrated eIQ Neutron NPU.
- [AM6xxX](https://www.ti.com/microcontrollers-mcus-processors/arm-based-processors/products.html#1217=1%20deep%20learning%20accelerator%2C%201%20video%20encode%2Fdecode%20accelerator%2C%201%20vision%20pre-processing%20accelerator%3B1%20deep%20learning%20accelerator%2C%201%20video%20encode%2Fdecode%20accelerator%2C%201%20vision%20pre-processor%20accelerator&2115=2%20Arm%20Cortex-A53%3B4%20Arm%20Cortex-A53&) - Texas Instruments IC e integrated 64-bit Arm Cortex-A53 and 2 Deep Learning Accelerator (C7x256v).
  - [BeagleY®-AI](https://www.beagleboard.org/boards/beagley-ai) - 
- [GAPx](https://greenwaves-technologies.com/low-power-processor/) - GREENWAVES TECHNOLOGIES GAP8/GAP9 ICs are based on ultra-low-power RISC-V processors.
- [Kneron AI SOCs](https://www.kneron.com/page/soc/) - Equipped with Kneron’s proprietary NPU, which accelerates neural network models, Kneron SoCs enable a wide range of AI applications for smart devices.
- [Kendryte Kxxx IC](https://developer.canaan-creative.com/resource) - Kendryte offers the KV210, KV230 and KV510 ICs, based on RISC-V architecture 
  - [Grove AI HAT](https://wiki.sipeed.com/soft/maixpy/en/develop_kit_board/grove_ai_hat.html) - Built around Sipeed MAix M1 AI MODULE with Kendryte K210 processor inside.
  - [Cannan CanMV-K230](https://developer.canaan-creative.com/k230/dev/zh/CanMV_K230_%E6%95%99%E7%A8%8B.html) - 
The CanMV-K230 development board uses the latest generation SoC chip K230 in Canaan Technology’s Kendryte® series AIoT chips.
- [Syntiant NDPs](https://www.syntiant.com/hardware) - The Syntiant family of Neural Decision Processors are based on  ARM Cortex-M0 cores and Syntiant Core programmable deep learning architecture.
- [Kendryte Kxxx IC](https://developer.canaan-creative.com/resource) - Kendryte offers the KV210, KV230 and KV510 ICs, based on RISC-V architecture 
  - [Grove AI HAT](https://wiki.sipeed.com/soft/maixpy/en/develop_kit_board/grove_ai_hat.html) - Built around Sipeed MAix M1 AI MODULE with Kendryte K210 processor inside.
  - [Cannan CanMV-K230](https://developer.canaan-creative.com/k230/dev/zh/CanMV_K230_%E6%95%99%E7%A8%8B.html) - 
The CanMV-K230 development board uses the latest generation SoC chip K230 in Canaan Technology’s Kendryte® series AIoT chips.
- [Syntiant NDPs](https://www.syntiant.com/hardware) - The Syntiant family of Neural Decision Processors are based on  ARM Cortex-M0 cores and Syntiant Core programmable deep learning architecture.
- [Google Coral TPU](https://coral.ai/products/) - Google ASIC designed for Edge aplications.
- [Intel Movidius Myriad x VPU](https://www.intel.com/content/www/us/en/products/details/processors/movidius-vpu.html) - 
  - [ntel Neural Compute Stick 2](https://www.intel.com/content/www/us/en/developer/articles/tool/neural-compute-stick.html) - [UP Xtreme Edge Compute Enabling Kit](https://up-board.org/up-xtreme-edge-compute-enabling-kit/) - UP Xtreme Edge Compute Enabling Kit, powered by the 8th Generation Ultra-Low Power Intel® Core™ i3/i5/i7/Celeron CPU, is designed to boost your AI on-the-Edge. Offload AI workloads from Intel® Core™ CPU and integrated GPU to the optional VPU by selecting the kit configuration with the UP AI Core XM2280, powered by 2 Intel® Movidius™ Myriad™ X.
- [Hailo-8 AI Accelerator](https://hailo.ai/products/ai-accelerators/) - The Hailo-8 edge AI processor, features up to 26 tera-operations per second (TOPS)
  - [Raspberry Pi AI Kit](https://www.raspberrypi.com/products/ai-kit/) - The Raspberry Pi AI Kit bundles the Raspberry Pi M.2 HAT+ with a Hailo AI acceleration module for use with Raspberry Pi 5.
- [ESP32-S3](https://www.espressif.com/en/products/socs/esp32-s3) - ESP32-S3 is a dual-core XTensa LX7 MCU, capable of running at 240 MHz. It has additional support for vector instructions in the MCU, which provides acceleration for neural network computing and signal processing workloads.
   - [ESP32-S3-EYE](https://www.espressif.com/en/products/devkits/esp-eye/overview) - The ESP32-S3-EYE is a small-sized AI development board based on the ESP32-S3 SoC
- [Amlogic Axx]() - 
  - [KHADAS VIM3](https://www.khadas.com/vim3) - The VIM3 SBC includes a Amlogic A311D with a 5.0 TOPS NPU.
  - [JEVOIS-PRO](https://www.jevoisinc.com/) - Open-source quad-core camera with the A311D IC.
- [Ambiq Apollo](https://ambiq.com/products/) - 
  - [SparkFun Edge Development Board - Apollo3 Blue](https://www.sparkfun.com/products/15170) - 
- [ARM Ethos NPUs](https://www.arm.com/products/silicon-ip-cpu?families=ethos%20npus) - Arm has a ethos family of machine learning inference processor oferring up to 4 TOPs scalable ML performance

### Development Boards
- [Himax WE-I Plus EVB Endpoint AI Development Board](https://www.sparkfun.com/products/17256) -
- [Himax WE-I Plus EVB Endpoint AI Development Board](https://www.sparkfun.com/products/17256) -

# Software
- [Tensorflow Lite]()
- [Pytorch Executorch]()
- [ONNX Runtime]()
- [AMD VitisAi™](https://xilinx.github.io/Vitis-AI/3.5/html/index.html) - AI inference development platform for AMD devices, boards, and Alveo™ data center acceleration cards.
- [OpenVINO]()
- [TensorRT]()
- [STM32Cube.Ai]()
- [e-AI Development Environment](https://www.renesas.com/us/en/e-ai-development-environment-microcontrollers#overview) - The tool can convert from a trained model of “PyTorch”, “Keras”, “Tensorflow”, or an 8-bit quantized model of “TensorFlow Lite” and import it easily to e² studio, Renesas' integrated development environment.
- [e-AI Development Environment](https://www.renesas.com/us/en/e-ai-development-environment-microcontrollers#overview) - The tool can convert from a trained model of “PyTorch”, “Keras”, “Tensorflow”, or an 8-bit quantized model of “TensorFlow Lite” and import it easily to e² studio, Renesas' integrated development environment.
- [Reality AI Tools®](https://www.renesas.com/us/en/software-tool/reality-ai-tools)

# Benchmarking
- [AEdge AIbench V3.0](https://www.benchcouncil.org/aibench/edge-aibench/index.html)
- [AIoTBench](https://www.benchcouncil.org/aibench/aiotbench/index.html)
- [Flet-Edge](https://www.benchcouncil.org/FletEdge/)
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

# Useful Tutorials
### Xilinx Vitis Ai:
- [Vitis Ai Overview](https://docs.amd.com/r/en-US/ug1414-vitis-ai/Vitis-AI-Overview)
- [Quick Start Guide for Zynq™ UltraScale+™](https://xilinx.github.io/Vitis-AI/3.0/html/docs/install/install.html)
- [VitisAi 3.5 Host Installation](https://xilinx.github.io/Vitis-AI/3.5/html/docs/install/install.html)
- [VitisAi 3.0 Host Installation](https://xilinx.github.io/Vitis-AI/3.0/html/docs/install/install.html)
- [YOLOv5 Quantization & Compilation with Vitis AI 3.0 for Kria](https://www.hackster.io/LogicTronix/yolov5-quantization-compilation-with-vitis-ai-3-0-for-kria-7b005d)
- [AMD Xilinx Kria KV260 Vision AI Starter Kit: License plate detection: YOLOv7](https://community.element14.com/products/roadtest/b/blog/posts/amd-xilinx-kria-kv260-vision-ai-starter-kit-license-plate-detection-yolov7)

# Optimized Dl Models

# Multimodal Datasets