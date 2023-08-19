# PDI Serial Adapter
 Add logic level RS232 to the PDI/UPDI header, with an FTDI breakout

A simple 2 layer board with 3x (U)PDI headers, and an FTDI cable header. A debug serial port is really handy, and STM debuggers have one built in.

J1 (U)PDI cable to target MCU, 2.54mm pitch<br>
J2 (U)PDI cable to target MCU, 1.27mm pitch<br>
J3 (U)PDI header for debugger/programmer
J4 FTDI cable header for TTL level RS232 and USB power
J5 Easy access to FTDI_VCC (5V or 3.3V depending on the cable)
J6 Connects FTDI_DTR to MCU's reset line via open drain
