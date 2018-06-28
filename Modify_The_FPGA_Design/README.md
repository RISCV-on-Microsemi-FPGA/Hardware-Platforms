# SmartFusion2 Advanced development Kit RISC-V Sample FPGA Designs 
Sample RISC-V Libero projects for the SmartFusion2 (M2S150) Advanced Development Kit.

This folder contains Libero projects containing FPGA designs including a RISC-V soft processor. 
Programming bit-streams are also included so you don't have to run through the full FPGA design flow in order to start developing software for RISC-V.

### Design Feature
The FPGA Designs include the following features
* Mi-V RISC-V processor 
* RISC-V debug block allowing on-target debug using openocd/GDB
* On-chip NVM used as boot/execution memory
* DDR3 memory for code/data
* User peripherals such as GPIO, Timers, UART
* Designs created with Libero capture 11.8.3.6

The memory map for each design is available within each Libero project.

### Libero Projects

* MIV_RV32IMA_AHB_BaseDesign:

   Uses MIV_RV32IMA_L1_AHB soft processor. Contains a sample RISCV design which allows users to use basic peripherals such as GPIO, UART and Timers.

* CoreRISCV_AXI4_BaseDesign:

   Uses legacy CoreRISCV_AXI4 soft processor. Contains a sample RISCV design which allows users to use basic peripherals such as GPIO, UART and Timers.

### Target Hardware
The SmartFusion2 Advanced development Board includes a SmartFusion2 M2S150 FPGA. Details of the features of this development board are available [here](https://www.microsemi.com/products/fpga-soc/design-resources/dev-kits/smartfusion2/smartfusion2-advanced-development-kit).

### Target Mi-V CPU
Details of the features of Mi-V CPUs are available [here](https://github.com/RISCV-on-Microsemi-FPGA/CPUs).

### Modifying the Libero projects
Some of the Libero projects use IP packages may not be  directly available from the Microsemi IP Catalog. These IP packages were created to speed up design creation by wrapping simple logic into reusable user IP packages.
These user IP packages are available [here](https://github.com/RISCV-on-Microsemi-FPGA/CPUs/tree/master/Supporting-IPs).

If you are using a design with CoreRISCV_AXI4 soft processor based design, please note that you may need to uncomment "`define USE_REGISTERS" in file coreriscv_axi4_defines.v in order to reduce RAM blocks usage. 
You will need to do this anytime you regenerate the top level SmartDesign in Libero.
