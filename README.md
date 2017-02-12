# FKL25Z-firmware
Frdm-KL25Z firmware using MATLAB Simulink


Author: Vasutorn Siriyakorn, kasetsart university , 2017

#Require
  
   * XP FRDM-KL25Z Microcontroller Support from Simulink Coder
   
   Download link : https://www.mathworks.com/hardware-support/frdm-kl25z.html
   
   * OpenSDA
   
   Download link : https://www.mathworks.com/help/supportpkg/freedomboard/ug/install-firmware.html
   
#Main File:

  * Frdm_KL25Z.slx : main file, recive input form raspberrry pi 3 by using Serial Recive box and sent output to motor and servo.
  
#Include file
  * serial_vector_to_frdm : Decode signal
  * PWMlenght : recive pulse and find lenght of pulse
  * controller : get data form speedsenser and control motor using PI contoller

#How to

  * open file ``Frdm_KL25Z.slx``
  * setting ``Model Configuration Parameter`` following [This link](https://www.mathworks.com/help/supportpkg/freedomboard/examples/getting-started-with-simulink-coder-support-package-for-nxp-frdm-kl25z-board.html#zmw57dd0e186 "Setting Parameter")
  * Click `` Deploy to Hardware ``
  

Thank you.
