# SoftConsole Example Projects
This folder contains a example firmware projects for the Mi-V processors.
Projects included: miv-rv32im-systick-blinky and miv-rv32im-ticktacktoe.

### Using this Workspace in SoftConsole
You must first clone or download the entire SoftConsole GitHub repository. The easiest approach is to click the green "Clone or download" button on this [page](https://github.com/RISCV-on-Microsemi-FPGA/RISC-V-Creative-board) then click "Download ZIP".
Alternatively you can clone the GitHub repository using the following command:

   $ git clone https://github.com/RISCV-on-Microsemi-FPGA/RISC-V-Creative-board

Once the GitHub repository is on your local machine.
* Open SoftConsole
* Select menu items: "File" -> "Import" -> "General" -> "Existing Project into Workspace"
* In the Import Projects dialog box click "Browse"
* Select the RISC-V-Creative-board/Example_Software_Projects folder of the RISC-V-Creative-board GitHub repository you cloned or downloaded.
* Select systic-blinky and/or TickTackToe example code.
* Select "Copy projects into workspace" then select "Finish".
* You will now see the systic-blink and/or TickTackToe project in the "Project Explorer" pane.
* Note that these SpfotConsole projects can be used on any of the Mi-V hardware platform. You need to make sure that the clock at which your Libero design is running must match the value SYS_CLK_FREQ in the hw_platform.h. The base addresses of the peripherals must also be crosschecked.

