# TurMet (TURbidity METer)
Some of the code is autogenerated by STM32Cube Software. The remaining code was written in Keil uVision 5. 
See main.c file in Src folder. Watchdog timer is used to recover from undefined states. ADCs are set on continous mode.
Author: Haris Suhail


Main Functions

void sendLog(uint8_t* message);
Sends data/logs back to PC through UART. Data can be read using hyper terminal.


void sendBT(uint8_t* message);
Sends data through bluetooth device attached to UART peripheral of STM32.


char *itoa(int i);
Custom definition itoa - integer to character array conversion.
