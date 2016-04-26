For the latest Raspbian image, go to https://www.raspberrypi.org/downloads/raspbian/. 

RPI0E.sch - Eagle CAD schematic for the hat.
RPI0E.brd - Eagle CAD board for the hat.
bom.xlsx - Spreadsheet with bill of materials
datasheets - datasheets for the board components, as well as some part drawings.

For information on EEPROM configuration visit https://github.com/raspberrypi/hats .

This board implements 802.3af using the silvertel Ag9805M module to power the raspberry pi, a tpm 3.3v power regulator to power components without using the source from the pi. The ENCJ ethernet controller communicates with the PI over SPI, and the MCP3002 provides a 2 channel ADC over SPI.
