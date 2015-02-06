# Arduino-Ethernet-W5200

Those modifications allow to use a Wiz820io module or a  W5200 chip with an Arduino Due

How to use:
Overwrite libraries/Ethernet/Ethernet.h
Overwrite libraries/Ethernet/utility/w5100.h
Overwrite libraries/Ethernet/utility/w5100.cpp

To use a W5100 based shield, comment line 16 of file w5100.h
