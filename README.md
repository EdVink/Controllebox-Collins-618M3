# Controllebox-Collins-618M3
This is a control box to set the frequency of an airborne Collins 618 M3 VHF Comm transceiver

At the moment it is still a work in progress 

The system has two rotary encoders, two I2C OLED 1.54" displays and most importantly a Arduino MEGA 2560

Parts of the software that are functional at the moment:

*-Read the encoders and represent the selected Frequency via the Oled's. Pushbuttons select 25KHz or 1MHz increments

*-Translate the selected frequency to "2 out of 5 code" that the 618 M3 work withand sent to a serie of outputs of the MEGA (34 to 49

*-A transfere switch between the two selected frequeties

Final process is to combine these parts in one working program
THis process will start around the beginning of May
