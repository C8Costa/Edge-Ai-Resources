# ⚙️ Edge AI Hardware Overview

A categorized overview of available Edge AI hardware accelerators and development boards. Hardware is grouped into three main categories:

- **GPUs** and **FPGAs** – general-purpose accelerators for parallel workloads.  
- **ASICs/Custom Accelerators** – purpose-built silicon optimized for neural network inference.  

Focus is placed on stable products from reputable manufacturers to ensure long-term support and community ecosystem.

---

## 🖥️ GPU Accelerators

1. **[NVIDIA Jetson](https://www.nvidia.com/en-us/autonomous-machines/embedded-systems)**  
   High-performance modules for edge AI, combining Arm CPUs, NVIDIA GPUs, and NVDLA accelerators.  
   - Jetson platform comparison: **[Jetson Orin](https://www.seeedstudio.com/blog/nvidia-jetson-comparison-nano-tx2-nx-xavier-nx-agx-orin)**  
   - Explore hardware/software partners: **[Jetson Ecosystem](https://developer.nvidia.com/embedded/ecosystem)**

---

## 🔧 FPGA Accelerators

1. **[AMD SoMs & SoCs](https://www.amd.com/en/products/adaptive-socs-and-fpgas/soc.html)**  
   Includes Zynq UltraScale+ MPSoC platforms such as:  
   - [Kria KV260 Vision Starter Kit](https://www.amd.com/en/products/system-on-modules/kria/k26/kv260-vision-starter-kit.html)  
   - [Kria KR260 Robotics Starter Kit](https://www.amd.com/en/products/system-on-modules/kria/k26/kr260-robotics-starter-kit.html)  

2. **[Intel Altera FPGAs](https://www.intel.com/content/www/us/en/products/details/fpga.html)**  
   - AI toolchain: [FPGA AI Suite](https://www.intel.com/content/www/us/en/products/details/fpga/development-tools/fpga-ai-suite.html)

3. **[EFINIX FPGAs](https://www.efinixinc.com/index.html)**  
   - Capable of embedding RISC-V cores and neural accelerators, such as the [Edge Vision SoC](https://www.efinixinc.com/edge-vision-soc.html)

4. **[Lattice FPGAs](https://www.latticesemi.com/Products/Lattice-Intelligent-Edge-AI-and-FPGA-Solutions)**  
   - Includes the [sensAI™ Stack](https://www.latticesemi.com/en/Solutions/Solutions/SolutionsDetails02/sensAI) for AI inferencing at the edge.

5. **[Microchip PolarFire SoCs](https://www.microchip.com/en-us/products/fpgas-and-plds/system-on-chip-fpgas/polarfire-soc-fpgas)**  
   - Includes RISC-V CPU clusters; also offers [SmartFusion® 2 FPGAs](https://www.microchip.com/en-us/products/fpgas-and-plds/system-on-chip-fpgas/smartfusion-2-fpgas) with integrated Arm cores.

---

## 🧠 Custom ASIC Accelerators, MCUs & MPUs

Purpose-built accelerators such as TPUs, NPUs, VPUs, and MCUs with neural capabilities.

1. **[Google Coral TPU](https://coral.ai/products/)**  
   4 TOPS INT8 ASIC optimized for CNN inference. Available in USB, M.2, and PCIe formats.

2. **[RockChip]()** *(Missing link/description)*

3. **[Hailo](https://hailo.ai/)**  
   Offers co-processors like:  
   - [Hailo-8](https://hailo.ai/products/ai-accelerators/hailo-8-ai-accelerator/)  
   - [Hailo-10H](https://hailo.ai/products/ai-accelerators/hailo-10h-ai-accelerator/)  
   - [Hailo-15 Vision Processor](https://hailo.ai/products/ai-vision-processors/hailo-15-ai-vision-processor/)  
   - Raspberry Pi integration via [AI Kit/HAT](https://www.raspberrypi.com/products/ai-kit/)

4. **[STMicroelectronics](https://stm32ai.st.com/edge-ai-hardware/)**  
   - [STM32MP2](https://www.st.com/en/microcontrollers-microprocessors/stm32mp2-series.html) and  
   - [STM32N6](https://www.st.com/en/microcontrollers-microprocessors/stm32n6-series.html) feature NPUs for embedded AI.

5. **[Texas Instruments AM6x & TDA4](https://www.ti.com/technologies/edge-ai.html)**  
   - Arm Cortex-A processors with integrated DSPs and vision AI accelerators.

6. **[Kneron AI SoCs](https://www.kneron.com/page/soc/)**  
   - NPUs for vision-centric edge AI processing.

7. **[Espressif ESP32-S3 & ESP32-P4](https://www.espressif.com/en/products/socs)**  
   - S3: Dual-core XTensa LX7 with vector instructions  
   - P4: RISC-V CPU with AI instruction extensions

8. **[Ambiq Apollo](https://ambiq.com/apollo/)**  
   - Ultra-low power SoCs with SPOT® technology for always-on AI.

9. **[Intel® Movidius™ VPU](https://www.intel.com/content/www/us/en/developer/topic-technology/edge-5g/hardware/vision-accelerator-movidius-vpu.html)**  
   - 1–4 TOPS performance; includes 16 SHAVE cores and imaging accelerators.

10. **[NXP MCX N9x/N5x](https://www.nxp.com/applications/technologies/ai-and-machine-learning:MACHINE-LEARNING)**  
   - ARM Cortex-M MCUs with _eIQ® Neutron NPU_.

11. **[Kendryte K210/K510/K230]()**  
   - RISC-V AI SoCs with built-in KPU neural accelerators.

12. **[Renesas RZ/V MPUs](https://www.renesas.com/en/products/microcontrollers-microprocessors/rz-mpus/rzv-embedded-ai-mpus)**  
   - Embedded DRP-AI accelerator for computer vision at the edge.

13. **[Analog Devices MAX78000/78002](https://www.analog.com/en/product-category/ultralow-power-artificial-intelligence-ai-mcus.html)**  
   - Ultra-low-power MCUs with CNN hardware accelerators.

14. **[Syntiant NDP Series](https://www.syntiant.com/hardware)**  
   - Neural Decision Processors (e.g., NDP101, NDP120) for always-on sensor inference.

15. **[Infineon PSOC™ Edge](https://www.infineon.com/products/microcontroller/32-bit-psoc-arm-cortex/32-bit-psoc-edge-arm)**  
   - Combines Cortex-M55 and Ethos-U55 with ultra-low-power NNLite accelerator.

16. **[Arm Ethos-U Series](https://developer.arm.com/documentation/109267/0102/Arm-Ethos-U-NPU)**  
   - Includes: [Ethos-U55](https://developer.arm.com/Processors/Ethos-U55), [Ethos-U65](https://developer.arm.com/Processors/Ethos-U65), and [Ethos-U85](https://developer.arm.com/Processors/Ethos-U85) for embedded neural inference.

---

## 🧪 Development Boards (Reference Platforms)

Boards that combine the above chips into complete solutions for prototyping:

- **[Ultra96-V2](https://www.96boards.org/product/ultra96/)** – Xilinx-based 96Boards CE compliant platform  
- **[BeagleV®-Fire](https://www.beagleboard.org/boards/beaglev-fire)** – PolarFire SoC SBC  
- **[OpenMV Cam H7](https://www.sparkfun.com/openmv)** – MicroPython-capable vision board  
- **[SparkFun Edge (Apollo3)](https://www.sparkfun.com/products/15170)** – Ultra low-power MCU for TensorFlow Lite Micro  
- **[Khadas VIM3](https://www.khadas.com/vim3)** – Amlogic A311D SoC with 5 TOPS NPU  
- **[JEVOIS-PRO](https://www.jevoisinc.com/)** – Quad-core AI camera module

---

## 🚫 Outdated or Deprecated Hardware

These products are either obsolete or no longer actively supported:

- **Himax WE-I Plus EVB** – Arm Cortex-M + CNN accelerator. Supports TFLite Micro; used in Himax AI competitions.  
- **GreenWaves GAP Processors** – RISC-V IoT processors for ultra-low power AI, with limited ecosystem support.
