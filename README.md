# Mini SAM
Mini SAM is a LEGO® minifigure-sized development board based on either the Microchip SAMD51G 48-Pin 32-Bit ARM® Cortex®-M4F MCU (Mini SAM M4) or the Microchip SAMD21G 48-Pin 32-Bit ARM® Cortex®-M0+ MCU running at 48Mhz.

## Board Features


### I/O
The boards includes a usb-micro interface for programming and power.   Around the edge are 0.050" spaced holes with castellations outside of that and the plan is to have a "breakout" board with standard .100" headers.  There is an optional board design in work that will be 4-layer and have the .100" smt header pads included.

The Mini SAM boards include two LED indicators; a standard "Built-In" LED and an APA102 RGB LED.  There are two built-in buttons as well; a RESET button and a user programmable BUTTON.

### Memory
In order to support CircuitPython, a 2MB Quad-SPI flash memory chip is included.  This provides plenty of space for the CircuitPython program as well as space for user programming.

### Other
The boards include a 600mA 3.3V regulator, more than enough to power this little board and its built-in features.  The micro-USB circuitry includes optional provisioning for case grounding and ESD protection.  Finally, The AREF input and recommended Analog and Digital power separation is present on the board.

## BOM
Please see the BOM for each board

## Arduino
Arduino FIRMWARE/BOOTLOADER is **in-work**. The goal is a bootloader that has all functions working and all on-board features usable with "Built-In" terminology in Arduino, i.e. LED_BUILTIN, MOSI, MISO, SCK, and BUTTON_BUILTIN.

## CircuitPython
CircuitPython is available for the M4 board. [Mini SAM M4](https://github.com/adafruit/circuitpython/tree/master/ports/atmel-samd/boards/mini_sam_m4)  
CircuitPython will soon be available for the M0 board.

Bootloader for Mini SAM M4 can be built from this source: [UF2-SAMDX1](https://github.com/bwshockley/uf2-samdx1) 

## Open Source
Boards can be ordered direct from [OSHPark](https://oshpark.com/profiles/bwshockley).
