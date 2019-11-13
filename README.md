# Hardware Platforms
This repository contains a list of sample board designs for Libero. The sample designs contain Libero projects for FPGA designs including a RISC-V soft processor with programming bitstreams that can be used to program hardware using FlashPro Express. Select the hardware platform and follow instructions on it's page to implement it.
##### Notes
- Check this repository for updates on regular basis.
- Ensure you always have the latest Cores downloaded in Libero.
- Develop branch contains latest updates, master branch contains releases.
- If you have any queries be sure to jest the **[F.A.Q's](Hardware-Platforms/FAQ/)** page in the repository

## Instructions
1. Select one of the sample board designs from the list below by clicking on it's name.
2. Download or Clone the selected repository, extract it wherever you want your Libero project built.
3. Follow the instructions on the project's page to implement the design, ensure your version of Libero matches the version for which the scripts are written.

------------------------------------------
### [Future-Avalanche-Board](https://github.com/RISCV-on-Microsemi-FPGA/Future-Avalanche-Board)
This is the Future Avalanche Board for PolarFire FPGA - AVMPF300TS_01. Information like data sheets, guides and support for this board can be found by clicking here, [Microsemi's website](https://www.microsemi.com/existing-parts/parts/139680). A Libero Gold license is required to use the PolarFire part.
<p align="center"><img src="board_images/avmpf300.PNG" width="720" height="380" /></p>

- The operational clock frequency of the design is 50 MHz
- Latest cores have been implemented
- Part: MPF300TS-FCG484EES
- Cores: MiV_RV32IMA_L1_AHB or MiV_RV32IMA_L1_AXI
- Timing seed included, more information on the design's page.

---------------------------------------------
### [RISC-V-Creative-Board](https://github.com/RISCV-on-Microsemi-FPGA/RISC-V-Creative-Board)
This is a Future designed IGLOO2 RISC-V Creative Development Board for IGLOO2 FPGA - FUTUREM2GL_EVB. Information like data sheets, guides and support for this board can be found by clicking here, [Microsemi's website](https://www.microsemi.com/existing-parts/parts/143948). Below is an image of the board.
<p align="center"><img src="board_images/futurem2gl.PNG" width="720" height="380" /></p>

- The frequency of the design is 50 MHz
- Latest cores have been implemented
- This board can come in colors: red, yellow or blue
- Part: M2GLO25
- Cores: MiV_RV32IMA_L1_AHB or MiV_RV32IMA_L1_AXI
- Timing seed included, more information on the design's page.

----------------------------------------------
### [SmartFusion2-Advanced-Dev-Kit](https://github.com/RISCV-on-Microsemi-FPGA/SmartFusion2-Advanced-Dev-Kit)
This board is a SmartFusion2 Advanced Development Kit - SoC FPGA 150K LE - M2S150TS_ADV_DEV_KIT. Information like data sheets, guides and support for this board can be found by clicking here, [Microsemi's website](https://www.microsemi.com/existing-parts/parts/143709). Below is an image of the board.
<p align="center"><img src="board_images/m2s150ts.jpg" width="720" height="380" /></p>

- The frequency of the design is 50 MHz
- Latest cores have been implemented
- Contains Core SPI
- Design uses the MSS Subsystem
- Part: M2S150TS-1FC1152I or M2S150-1FC1152I
- Cores: MiV_RV32IMA_L1_AHB or MiV_RV32IMA_L1_AXI
- Timing seed included, more information on the design's page.

----------------------------------------------
### [PolarFire-FPGA-Splash-Kit](https://github.com/RISCV-on-Microsemi-FPGA/PolarFire-FPGA-Splash-Kit)
This is Microsemi's PolarFire Splash Kit board for evaluation and development. Information like data sheets, guides and support for this board can be found by clicking here, [Microsemi's website](https://www.microsemi.com/existing-parts/parts/144001). Below is an image of the board.
<p align="center"><img src="board_images/mpf300splash.PNG" width="720" height="380" /></p>

- The frequency of the design is 50 MHz
- Latest cores have been implemented
- This is project is marked 'ES' for Engineering Sample
- Part used: MPF300TS-1FCG484EES
- Cores: MiV_RV32IMA_L1_AHB or MiV_RV32IMA_L1_AXI
- Timing seed included, more information on the design's page.

----------------------------------------------
### [PolarFire-Eval-Kit](https://github.com/RISCV-on-Microsemi-FPGA/PolarFire-Eval-Kit)
This is Microsemi's PolarFire FPGA Evaluation Kit. Information like data sheets, guides and support for this board can be found by clicking here, [Microsemi's website](https://www.microsemi.com/existing-parts/parts/150789). Below is an image of the board.
<p align="center"><img src="board_images/mpf300.PNG" width="720" height="380" /></p>

- The frequency of the design is 50 MHz
- Latest cores have been implemented
- Part used: MPF300T-1FCG1152I or MPF300T_ES-1FCG1152I
- Cores: MiV_RV32IMA_L1_AHB or MiV_RV32IMA_L1_AXI
- Timing seed included, more information on the design's page.

----------------------------------------------
### [RTG4-Development-Kit](https://github.com/RISCV-on-Microsemi-FPGA/RTG4-Development-Kit)
This is a Radiation-Tolerant High-Density High-Performance Development Board with one RT4G150 FPGA. Information like data sheets, guides and support for this board can be found by clicking here, [Microsemi's website](https://www.microsemi.com/product-directory/dev-kits-solutions/3865-rtg4-kits#overview). Below is an image of the board 
<p align="center"><img src="board_images/rtg4.png" width="720" height="380" /></p>

- The frequency of the design is 50 MHz
- Latest cores have been implemented
- DDR3
- Cores: MiV_RV32IMA_L1_AHB or MiV_RV32IMA_L1_AXI
- Timing seed included, more information on the design's page.

-----------------------------------------------
### [SmartFusion2-Eval-Kit](https://github.com/RISCV-on-Microsemi-FPGA/SmartFusion2-Eval-Kit)
This is a SmartFusion2 Security Evaluation Kit - SoC FPGA 90K LE. Information like data sheets, guides and support for this board can be found by clicking here, [Microsemi's website](https://www.microsemi.com/existing-parts/parts/143988). Below is an image of the board.
<p align="center"><img src="board_images/m2s090ts.PNG" width="720" height="380" /></p>

- The frequency of the design is 50 MHz
- Contains Core SPI
- Latest cores have been implemented
- The design uses the MSS Subsystem
- Cores: MiV_RV32IMA_L1_AHB or MiV_RV32IMA_L1_AXI
- Timing seed included, more information on the design's page. 

------------------------------------------------
### [Arrow-Everest-Board](https://github.com/RISCV-on-Microsemi-FPGA/Arrow-Everest-Board)
This is an Arrow Everest Evaluation Board for PolarFire FPGA. Information like data sheets, guides and support for this board can befound by clicking here, [Microsemi's website](https://www.microsemi.com/existing-parts/parts/143998). Below is an image of the board.
<p align="center"><img src="board_images/evmpf300.PNG" width="720" height="380" /></p>

- The frequency of the design is 50 MHz
- Latest cores have been implemented
- This is project is marked 'ES' for Engineering Sample
- Cores: MiV_RV32IMA_L1_AHB or MiV_RV32IMA_L1_AXI
- Timing seed included, more information on the design's page.

-------------------------------------------------
