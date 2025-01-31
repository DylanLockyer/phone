# phone
Simple phone powered by an STM32 for calling and texting

\*\*\*Project is still in design phase\*\*\*

Goal is to create a basic but fully functional phone using an STM32. The project is still in the schematic phase, but is almost complete. Contains the following components:



**Processor: STM32 ->** Processor to interface with all periferals and run the operating system. Uses sdram for sufficient memory for 5inch display, SD card for external file storage, nor flash for external flash memory.

**Cellular Chip: SIMCOM a7670C ->** Chip to handle low level cellular network comunication.

**Power Components ->** Combination of battery charger, power mux for selection between battery power and external power, LED backligh driver, current and voltage sensor, and voltage regulating components.
