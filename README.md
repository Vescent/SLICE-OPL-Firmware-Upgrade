# SLICE-OPL-Firmware-Upgrade
Repository for the latest released firmware for the SLICE-OPL.


## Requires 
  Vescent SLICE_Firmware_Upgrade_Utility available at:
  
  https://github.com/Vescent/SLICE-FFC_Firmware_Upgrade_Utility
## Instructions
 
  Connect your SLICE-OPL to your PC via USB cable.  Ensure that all serial interface programs (TeraTerm, Putty, Python scripts, etc.) that may attempt to communicate with the SLICE-OPL's COM port are closed, as these may disrupt communication with the device during upgrade.

  Download and run the SLICE Firmware Upgrade Utility from the link above.  Follow the on-screen instructions.

  The V1.42 firmware upgrader automatically retrieves the upgrade files from this repository.
  However, if your system does not allow this, you may need to perform the following steps:  
  
  - Left click on the upgrade package (**SLICE_OPL_Sx.xxx-OPLx.xx.zip**) and then click 'Download' to download the firmware package to your hard drive.
  - Extract the 2 ".hex" files from the .zip file and place them in the following location on your hard drive (DO NOT RENAME THEM!):

        C:\Vescent\SLICE\UPGRADE\
       
	   
## Configuration S1.239_OPL1.27
Original Production Release


