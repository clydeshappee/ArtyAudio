This is an audio shiled for the Digilent Arty board.

It should be usable with an Arduino, but I have not tested it.

This has line and mic inputs, supporting dynamic and electret microphones.

I designed this to do DSP processing of audio in the Artix 7 FPGA.

The FPGA code is still a work in progress.  

I recently added the push button as a "start recording" feature and an LED
to show that audio is being sampled.

I hope this is of use to someone else and would love to have someone try it on 
an Arduino.  The boards cost $28 and the BOM cost is $35.72

I do not recommend making a substitution on the operational amplifiers.  Initially
I had trouble with the minus supply sagging and the amplifier specified does not
bring down the supply

Clyde R. Shappee
Walpole, MA
