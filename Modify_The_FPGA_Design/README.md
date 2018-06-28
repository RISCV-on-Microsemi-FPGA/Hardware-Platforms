# RISC-V Creative Development Board RISC-V Designs
Sample Mi-V Libero project(s) for the RISC-V Creative board.

This folder contains a Libero project containing an FPGA design including a Mi-V soft processor. 

### Design Features
The FPGA designs include the following features:
* Uses MIV_RV32IMA_L1_AHB processor
* RISC-V debug block allowing on-target debug using openocd/GDB
* LSRAM for code/data
* User peripherals such as GPIO, Timers, UART
* Adafruit touch screen display
* Designs created with Libero capture 11.8.3.6

The memory map for each design is available within each Libero project.

### Libero Projects
* IGL2_RISCV_Systick_Blinky

   Contains a simple RISCV design which allows users to use basic peripherals such as GPIO, UART and Timers. Uses legacy CoreRISCV_AXI4 soft processor. 
* IGL2_CoreRISCV_AXI4_TickTackToe:

   Contains design which enables Adafruit touch screen interface using CoreSPI. To use this design a daughter board is needed from Adafruit, more information on this can be found [here](https://www.adafruit.com/product/1651).
   The design used along side of the TickTackToe example software found [here](https://github.com/RISCV-on-Microsemi-FPGA/RISC-V-Creative-Board/tree/master/Example_Software_Projects). This design uses legacy CoreRISCV_AXI4 soft processor.
* IGL2_MiV_RISCV_Systick_Blinky

   Uses MIV_RV32IMA_L1_AHB soft processor. Contains a simple RISCV design which allows users to use basic peripherals such as GPIO, UART and Timers.

### Target Hardware
The RISC-V Creative Development Board includes a IGLOO2 M2GL025 FPGA preprogrammed with a Mi-V processor design. Details of the features available for this development board are available [here](https://www.microsemi.com/products/fpga-soc/design-resources/dev-kits/smartfusion2/future-creative-board) .

### Target Mi-V CPU
Details of the features of Mi-V CPUs are available [here](https://github.com/RISCV-on-Microsemi-FPGA/CPUs).
