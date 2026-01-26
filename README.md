# Singer4452-speed-controller

This project implements PID feedback to improve control over the Singer 4452 sewing machine. The modifications are non-destructive to the sewing machine. 

As an outline:
1. A rotary encoder tracks the position of the sewing needle by mounting externally to the knob on the side of the machine. 
2. A network of optoisolated resistors emulate the potentiometer in the existing pedal. Resistance is programmed by a MCU. 
3. Motor velocity is regulated by a new pedal, connected to a potentiometer. 