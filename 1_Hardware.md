# ⚙️ Edge AI Hardware Overview

A categorized overview of available Edge AI hardware accelerators and development boards. Hardware is grouped into three main categories:
- **GPUs** and **FPGAs** – general-purpose accelerators for parallel workloads.  
- **ASICs/Custom Accelerators** – purpose-built silicon optimized for neural network inference.  
Focus is placed on stable products from reputable manufacturers to ensure long-term support and a large community ecosystem.

## Table of Contents

- [GPU Accelerators](#gpu-accelerators)
- [FPGA Accelerators](#fpga-accelerators)
- [Custom ASICs and Edge SoCs](#custom-asics-and-edge-socs)
- [Development Boards](#development-boards)
- [Outdated or Deprecated](#outdated-or-deprecated)

## GPU Accelerators

1. **[NVIDIA Jetson](https://www.nvidia.com/en-us/autonomous-machines/embedded-systems)** -  High-performance modules for edge AI, combining Arm CPUs, NVIDIA GPUs, and NVDLA accelerators.  
   - Jetson platform comparison: **[Jetson Orin](https://www.seeedstudio.com/blog/nvidia-jetson-comparison-nano-tx2-nx-xavier-nx-agx-orin)**  
   - Explore hardware/software partners: **[Jetson Ecosystem](https://developer.nvidia.com/embedded/ecosystem)**

## FPGA Accelerators

1. **[AMD SoMs & SoCs](https://www.amd.com/en/products/adaptive-socs-and-fpgas/soc.html)** -  Includes Zynq UltraScale+ MPSoC platforms such as: [Kria KV260 Vision Starter Kit](https://www.amd.com/en/products/system-on-modules/kria/k26/kv260-vision-starter-kit.html) , [Kria KR260 Robotics Starter Kit](https://www.amd.com/en/products/system-on-modules/kria/k26/kr260-robotics-starter-kit.html)
2. **[Intel Altera FPGAs](https://www.intel.com/content/www/us/en/products/details/fpga.html)** - AI toolchain: [FPGA AI Suite](https://www.intel.com/content/www/us/en/products/details/fpga/development-tools/fpga-ai-suite.html)
3. **[EFINIX Trion & Titanium FPGAs](https://www.efinixinc.com/index.html)** - Capable of embedding RISC-V cores and neural accelerators, such as the [Edge Vision SoC](https://www.efinixinc.com/edge-vision-soc.html)
4. **[Lattice FPGAs](https://www.latticesemi.com/Products/Lattice-Intelligent-Edge-AI-and-FPGA-Solutions)** - Includes the [sensAI™ Stack](https://www.latticesemi.com/en/Solutions/Solutions/SolutionsDetails02/sensAI) for AI inferencing at the edge.
5. **[Microchip PolarFire SoCs](https://www.microchip.com/en-us/products/fpgas-and-plds/system-on-chip-fpgas/polarfire-soc-fpgas)** - Includes RISC-V CPU clusters; also offer [SmartFusion® 2 FPGAs](https://www.microchip.com/en-us/products/fpgas-and-plds/system-on-chip-fpgas/smartfusion-2-fpgas) with integrated Arm cores.

## Custom ASIC Accelerators, NPUs, MCUs & MPUs

Purpose-built accelerators such as TPUs, NPUs, VPUs, and MCUs with neural capabilities.

1. **[Google Coral TPU](https://coral.ai/products/)** - 4 TOPS INT8 ASIC optimized for CNN inference. Available in USB, M.2, and PCIe formats.
2. **[Qualcomm]()** - Dragonwing processor offer edge solution combining a NPU with a DSP, such is the case of the QCS6490 in the [**RB3 Gen 2 Development Kit**](https://www.qualcomm.com/developer/hardware/rb3-gen-2-development-kit)
3. **[RockChip Kiwi Pi5](https://www.rockchips.net/case/)** -  Uses Rockchip RK3588 CPU, with a 6.0 TOPs NPU.
4. **[Hailo](https://hailo.ai/)** Offers co-processors like:  
	- [Hailo-8](https://hailo.ai/products/ai-accelerators/hailo-8-ai-accelerator/)  
	- [Hailo-10H](https://hailo.ai/products/ai-accelerators/hailo-10h-ai-accelerator/)  
	- [Hailo-15 Vision Processor](https://hailo.ai/products/ai-vision-processors/hailo-15-ai-vision-processor/)  
	- Raspberry Pi integration via [AI Kit/HAT](https://www.raspberrypi.com/products/ai-kit/)
5. **[STMicroelectronics MCU and MPUs](https://stm32ai.st.com/edge-ai-hardware/)**  
	- [STM32MP2](https://www.st.com/en/microcontrollers-microprocessors/stm32mp2-series.html) and  
	- [STM32N6](https://www.st.com/en/microcontrollers-microprocessors/stm32n6-series.html) feature NPUs for embedded AI.
6. **[Texas Instruments AM6x & TDA4 Family ](https://www.ti.com/technologies/edge-ai.html)** - Arm Cortex-A processors with integrated DSPs and vision AI accelerators.
7. **[Kneron AI SoCs](https://www.kneron.com/page/soc/)** - NPUs for vision-centric edge AI processing.
8. **[Espressif*](https://www.espressif.com/en/products/socs)** - 
	 - [ESP32-P4](https://www.espressif.com/en/products/socs/esp32-p4) is powered by a dual-core RISC-V CPU featuring AI instruction extensions. 
	 - [ESP32-S3](https://www.espressif.com/en/products/socs/esp32-s3)  is a dual-core XTensa LX7 MCU with  support for vector instructions.
9. **[Ambiq  Apollo SoC](https://ambiq.com/apollo/)** - Ultra-low power SoCs with SPOT® technology for always-on AI.
10. **[Intel® Movidius™ VPU](https://www.intel.com/content/www/us/en/developer/topic-technology/edge-5g/hardware/vision-accelerator-movidius-vpu.html)** - 1–4 TOPS performance; includes 16 SHAVE cores and imaging accelerators.
11. **[NXP i.MX Series](https://www.nxp.com/applications/technologies/ai-and-machine-learning:MACHINE-LEARNING)** - ARM Cortex-M MCUs with _eIQ® Neutron NPU_.
12. **[Kendryte K210/K510/K230]()** - RISC-V AI SoCs with built-in KPU neural accelerators.
13. **[Renesas RZ/V MPUs](https://www.renesas.com/en/products/microcontrollers-microprocessors/rz-mpus/rzv-embedded-ai-mpus)** - Embedded DRP-AI accelerator for computer vision at the edge.
14. **[Analog Devices MAX78000/78002](https://www.analog.com/en/product-category/ultralow-power-artificial-intelligence-ai-mcus.html)** - Ultra-low-power MCUs with CNN hardware accelerators.
15. **[Syntiant NDP Series](https://www.syntiant.com/hardware)** - Neural Decision Processors (e.g., NDP101, NDP120) for always-on sensor inference.
16. **[Infineon PSOC™ Edge](https://www.infineon.com/products/microcontroller/32-bit-psoc-arm-cortex/32-bit-psoc-edge-arm)** - Combines Cortex-M55 and Ethos-U55 with ultra-low-power NNLite accelerator.
17. **[Arm Ethos-U Series](https://developer.arm.com/documentation/109267/0102/Arm-Ethos-U-NPU)** - Includes: [Ethos-U55](https://developer.arm.com/Processors/Ethos-U55), [Ethos-U65](https://developer.arm.com/Processors/Ethos-U65), and [Ethos-U85](https://developer.arm.com/Processors/Ethos-U85) for embedded neural inference.
18. **[BrainChip Akida](https://brainchip.com/ip/)** - In the **Edge AI Box** Brainchip combine a NXP i.MX 8M Plus Quad SOC host CPU with 2* AKD1000 (Akida AI/ML Accelerator).
19. **[SiMa MLSoC™ Modalix ](https://sima.ai/hardware/)** - The SOC integrates a Arm APU, alongside the DSP to deliver 50 TOPS.

### Development Boards (Reference Platforms):

Third-Party development platforms that combine the above chips into complete solutions for prototyping:
- **[Ultra96-V2](https://www.96boards.org/product/ultra96/)** - Arm-based controller with AMD Zynq UltraScale+ ™ MPSoC development board based on the Linaro 96Boards Consumer Edition (CE) specification. 
- **[FZ5 EdgeBoard AI Box](https://www.myirtech.com/list.asp?id=639)** - The FZ5 EdgeBoard AI Box uses [**Xilinx Zynq UltraScale+ ZU5EV MPSoC**](https://www.xilinx.com/products/silicon-devices/soc/zynq-ultrascale-mpsoc.html) solution.
- **[BeagleV®-Fire](https://www.beagleboard.org/boards/beaglev-fire)** - leverages Microchip's PolarFire® MPFS025T SoC.
- **[OrangePi RV2](http://www.orangepi.org/html/hardWare/computerAndMicrocontrollers/details/Orange-Pi-RV2.html)** - OrangePi board with the Ky X1 8-core RISC-V AI CPU, providing 2TOPS CPU. 
- **[OrangePi AIpro](http://www.orangepi.org/html/hardWare/computerAndMicrocontrollers/details/Orange-Pi-AIpro(20t).html)** - The board has a 20TOPS version and one with just 8TOPS.
- **[Sipeed Maix](https://wiki.sipeed.com/hardware/en/maix/index.html)** - Sipeed Maix Boards are complete solutions from hardware to software to run AI inference on the edge.
- **[Vision AI-KIT 6490](https://www.tria-technologies.com/product/vision-ai-kit-6490/)** - Qualcomm Dragonwing™ QCS6490 Development Kit
- **[RASynBoard](https://www.tria-technologies.com/product/rasynboard/)** -  Board based on a Syntiant NDP120 Neural Decision Processor, a Renesas RA6M4 host MCU
- **[SparkFun Artemis](https://www.sparkfun.com/products/15170)** –  Artemis module is spec’d to run TensorFlow Lite, with the support of [Ambiq](https://ambiq.com/) Apollo3 processor
- **[Khadas VIM 3](https://www.khadas.com/vim3)** – uses an Amlogic SoC with 5 TOPS NPU.
- **[UP Squared AI BOX](https://up-shop.org/default/solution-kit/ai-dev-kit.html)** - UP offers a suit of development boards, based on Hailo and NVIDIA solutions
- **[OpenMV Cam H7 Plus](https://openmv.io/products/openmv-cam-h7-plus)** - OpenMV Cameras are vision solutions, programmed in MicroPython.
- **[JEVOIS-PRO](https://www.jevoisinc.com/)** - Open-source quad-core camera based on an Allwinner A33 processor.

---
### Outdated or Deprecated Hardware
These products are either obsolete or no longer actively supported:

- **[Intel Movidius Neural Compute Stick](https://www.intel.com/content/www/us/en/developer/tools/neural-compute-stick/overview.html)** - A USB-based neural compute accelerator for running AI models at the edge.
- **[Himax WE-I Plus EVB](https://www.sparkfun.com/himax-we-i-plus-evb-endpoint-ai-development-board.html)** – Arm Cortex-M + CNN accelerator. Supports TFLite Micro; used in Himax AI competitions.
- **GreenWaves GAP Processors** – RISC-V IoT processors for ultra-low power AI, with limited ecosystem support.
