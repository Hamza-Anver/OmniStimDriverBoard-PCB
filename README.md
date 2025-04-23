# OmniStim Eval Board

This is an evaluation board to test operating principles of the OptiStim head unit. 

Fabricated with JLCPCB in April 2025, designed with KiCAD.

It is designed to use the ESP32 Audio PLL to create a signal between approximately 5MHz to 80MHz. This signal is then conditioned and used to drive an LC tank, where the capacitance can be varied digitally and by the DIP switches.

Future designs will have their capacitance entirely digitally controlled, and be miniaturized.

This board is intended only to test if the ESP32 with this conditioning can successfully drive the LC tank and if the resonance of the tank can be subsequently measured by the ESP32. 


## Resolved Errata Rev 2
[x] - USB to Serial RX TX swapped
[x] - Typo JTAG connector (TDI instead of 3V3)
[x] - Missing EN and IO0 on UART breakout