# SLICE-OPL-Firmware-Upgrade
Repository for the latest released firmware for the SLICE-OPL.


## Requires 
  Vescent SLICE_Firmware_Upgrade_Utility available at:
  
  https://github.com/Vescent/SLICE-FFC_Firmware_Upgrade_Utility
## Instructions
 
  Connect your SLICE-OPL to your PC via USB cable.  Ensure that all serial interface programs (TeraTerm, Putty, Python scripts, etc.) that may attempt to communicate with the SLICE-OPL's COM port are closed, as these may disrupt communication with the device during upgrade.

  Download and run the SLICE Firmware Upgrade Utility from the link above.  Follow the on-screen instructions.

  The firmware upgrader automatically retrieves the upgrade files from this repository.
  However, if your system does not allow this, you may need to perform the following steps:  
  
  - Left click on the upgrade package (**SLICE_OPL_Sx.xxx-OPLx.xx.zip**) and then click 'Download' to download the firmware package to your hard drive.
  - Extract the 2 ".hex" files from the .zip file and place them in the following location on your hard drive (**DO NOT RENAME THEM!** 
    **AND MAKE SURE THERE ARE NO OTHER FILES IN THE UPGRADE DIRECTORY!!!**):

        C:\Vescent\SLICE\UPGRADE\
		
	       

## Configuration S1.244_OPL1.29	 
1. Fixes missing default settings of some PFD values
2. Makes improvements that reduce the noise on the ramping output
3. Fixes the PLL output shift when changing between the graph page and the home page
4. Fixes hangup of the tenths digit when using the rotary dial to adjust Range[V]
5. Fixes the missing Servo Enable/Disable choice on the Input Trigger menu
6. Adds visible feedback to the Servo OFF/ON buttons to indicate control of the Servo state
   is being controlled by the Input Trigger signal.
7. Fixes missing color Servo Lock status on the home page when viewed after a power cycle
   and before the Graph Page has been displayed
8. Fixes Ramp to Limit and Rollover of PLL output that would occur after ramp had been enabled
   and then disabled prior to enabling Servo control.
   
## Configuration S1.242_OPL1.27	 
Adds CE safety excess internal temperature power shutdown feature.

## Configuration S1.240_OPL1.27	 
Adds support for new Rotary Encoders.

## Configuration S1.239_OPL1.27
Original Production Release


