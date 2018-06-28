================================================================================
                    TickTackToe on RISC-V
================================================================================

This SoftConsole example project demonstrates using a touch screen display with
CoreRISCV_AXI4. 

--------------------------------------------------------------------------------
                            CoreRISCV_AXI4 Soft Processor
--------------------------------------------------------------------------------
This example uses CoreRISCV_AXI4 SoftProcessor (RISC-V RV32IM). This design is 
built for debugging CoreRISCV_AXI4 through the SmartFusion2 FPGA programming 
JTAG port using a FlashPro5. To achieve this the CoreJTAGDebug IP is used to 
connect to the JTAG port of the CoreRISCV_AXI4.

Optionally, The design can be build to use Olimex ARM-USB-TINY-H JTAG probe. 
For this,The JTAG pins must be routed through Fabric to the top level pins.

All the platform/design specific definitions such as peripheral base addresses,
system clock frequency etc. are included in hw_platform.h. The hw_platform.h is 
located at the root folder of this project.

The CoreRISCV_AXI4 firmware projects needs the riscv_hal and the hal firmware
(RISC-V HAL).

The RISC-V HAL is available through Firmware catalog as well as the link below:
    https://github.com/RISCV-on-Microsemi-FPGA/Mi-V-Firmware

--------------------------------------------------------------------------------
                            How to use this example
--------------------------------------------------------------------------------
The TickTackToe example uses a TFT Touch Shield for Arduino, with Resistive Touch screen
Refer https://www.adafruit.com/product/1651 for more details.

Use the touch screen to navigate and play the TickTackToe.

