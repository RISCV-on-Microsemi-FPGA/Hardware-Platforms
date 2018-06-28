# PolarFire Evaluation Kit RISC-V Designs
Sample Mi-V Libero projects for the PolarFire (MPF300T) Evaluation Kit.

This folder contains a Libero project for the FPGA designs including a Mi-V soft processor. 

### Design Features
The FPGA designs include the following features:
* Uses MI-V soft processor
* RISC-V debug block allowing on-target debug using openocd/GDB
* LSRAM for code/data
* User peripherals such as GPIO, Timers, UART
* Designs created with Libero capture 12.200.10.15

The memory map for each design is available within each Libero project.

### Libero Projects
* PF_MIV_RV32IMA_L1_AHB_BaseDesign:

   Allows software debugging using FlashPro5. The same JTAG port is used for programming the FPGA and debugging RISC-V software. Uses MIV_RV32IMA_L1_AHB soft processor.
* PF_CoreRISCV_AXI4_BaseDesign:

   Allows software debugging using FlashPro5. The same JTAG port is used for programming the FPGA and debugging RISC-V software. Uses legacy CoreRISCV_AXI4 soft processor.
* PF_CoreRISCV_AXI4_CoreBootStrap:

   Allows software debugging using FlashPro5. This also allows for booting from SPI Flash.The same JTAG port is used for programming the FPGA and debugging RISC-V software. Uses legacy CoreRISCV_AXI4 soft processor.

### Example Software Projects
A set of RISC-V example software projects are also available for these designs from the SoftConsole [page](https://github.com/RISCV-on-Microsemi-FPGA/SoftConsole).

### Target Hardware
The PolarFire Evaluation Kit includes an MPF300T FPGA. Details of the features of PolarFire Evaluation kit are available [here](https://www.microsemi.com/products/fpga-soc/design-resources/dev-kits/polarfire/polarfire-eval-kit).

### Target Mi-V CPU
Details of the features of Mi-V CPUs are available [here](https://github.com/RISCV-on-Microsemi-FPGA/CPUs).
