NES-I/O 1.5
===========


From original Borti's project: https://github.com/borti4938/NES_IGR_for_NESRGB/tree/master/NES-IO

an idea by Arcade-TV from circuit-board.de :) Thank you very much!!!

The board replaces the silver box in NES frontloader. On this PCB the following components are included:

- AC input jack
- AC to DC conversion
- MultiAV (SNES and GC(*) are supported) 
- PIC16F684 microcontroller to control the NESRGB color palette and reset the console using your controller :D

All components you need are stated on the silkscreen. An complete overview as well as an English installation guide is coming soon ;)

Grab the firmware for the PIC16F684 here: https://github.com/borti4938/NES_IGR_for_NESRGB/tree/master/fw/IGR_for_NESRGB/
- current version: use the 'normal version' and flash the nesrgb_igr_684_var_led.hex
- oldest PCB version (with three 10k resistors next to the 74*125): use the 'risky version' and flash nesrgb_igr_684_risky_var_led.hex

(*) 3d-printed Helder/Buffalowing connector on assemblergames (http://assemblergames.com/l/threads/f-s-nes-top-loader-snes-style-multi-a-v-socket.50494/) also fits  
    thanks for figuring out, splits (shmups forum)


================
The Rev 1.5 add the audio module, and there is now a NO CUT version where a miniDIN 9pin and a miniDIN 4pin replace the SNES/GC Multiout.
--
--> YOU'LL NEED TO REMOVE THE 3 RESISTORS ON THE RGB LINES OF THE NESRGB BOARD IF YOU ARE USING THE NOCUT BOARD
--

