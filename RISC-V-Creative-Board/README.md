# RISC-V Creative Development Board Designs
Sample Mi-V Libero project for FPGA designs for RISC-V Creative board.

This repository contains Libero projects containing an FPGA design including a RISC-V soft processor. 
The Programming bitstream(s) are also included so that you do not need to run through the full FPGA design flow 
in order to start developing software for RISC-V.

### Modify The FPGA Design 
The Modify_The_FPGA_Design folder contains Libero example designs. Libero is Microsemi's FPGA design tool. 
You will need this tool if you wish to modify the example FPGA designs. Libero is available from [here](https://www.microsemi.com/products/fpga-soc/design-resources/design-software/libero-soc#downloads).

### Programming The Target Device
The Programming_The_Target_Device folder includes FlashPro Express projects that can be used to program the 
development boards FPGA. A standalone installer for FlashPro Express is available [here](http://www.microsemi.com/products/fpga-soc/design-resources/programming/flashpro#software). 
Please note that you only need to install this standalone version of FlashPro Express if you do not have Libero tools installed.

A programming file resulting from the corresponding Libero design in "Modify_The_FPGA_Design" folder is available in "Programming The Target Device" for easy access.

### Example Software Projects
The Example_Software_Projects folder contains example projects specifically targeted at the RISC-V Creative Development Board. The TickTackToe and riscv-systic-blinky example firmware can be found in this directory.
A set of more generic RISC-V example software projects are also available for these designs from the SoftConsole [page](https://github.com/RISCV-on-Microsemi-FPGA/SoftConsole).

### Target Hardware
The RISC-V Creative Development Board includes a IGLOO2 M2GL025 FPGA. Details of the features available for this development board are available [here](https://www.microsemi.com/products/fpga-soc/design-resources/dev-kits/risc-v-creative-board).

The TickTackToe example uses a [TFT Touch Shield for Arduino, with Resistive Touch Screen](https://www.adafruit.com/product/1651)

### Target Mi-V CPU
Details of the features of Mi-V CPUs are available [here](https://github.com/RISCV-on-Microsemi-FPGA/CPUs).
