#Arduino Force Reset  
This board has been connected between SWP1 of the RPi_SoftSwitch and Reset Pin of the Arduino (need soldering).  
The Foldarap-chimera is full controlled by OctoPrint, ATX power distribute control included. So, the Marlin firmware set up power off the initial,  and send M80 by Octoprint when connected.  
And, I added small program which send the M81 (Turn off Power Supply) after stopping of the Octoprint. But, sometime, it didn't work because connection failure of the /dev/ttyACM0.  
  
This board send reset signal to the arduino simultaneously without any side effect.   

##License Information

These files are free; you can redistribute them and/or modify them under the
terms of the Creative Commons Attribution-ShareAlike 4.0 International
License only, as published by the Creative Commons organization.  

These files are distributed in the hope that they will be useful, but
WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY
or FITNESS FOR A PARTICULAR PURPOSE.  See the Creative Commons Attribution-
ShareAlike 4.0 International License for more details.  

Please contact Aynik technology Co., Ltd. at kkishita@aynik-tech.jp if you need additional information or have any questions.
