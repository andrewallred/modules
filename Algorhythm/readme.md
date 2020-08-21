Algorhythm
=======

Algorhythm is an 8-channel trigger/gate sequencer for Eurorack synthesizer systems.

The schematic is provided as a technical reference and to assist with repairs if needed.

Visit [http://grayscale.info/algorhythm](http://grayscale.info/algorhythm) for more information.

## Building firmware version 2.2

To build firmware version 2.2 download the XC8 compiler (found here: https://www.microchip.com/mplab/compilers). Navigate to the modules\Algorhythm\firmware folder and run the following command:

```
xc8 --chip=18f66k22 Algorhythm_v2.2.c
```