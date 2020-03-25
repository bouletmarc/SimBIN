# SimBIN
Codes Removal Tool on Honda/Acura Baseroms for the Engine Simulator

# Description
This tool remove Codes listed as best as possible
from any OBD1 Honda baserom in order
to avoid the codes with an Engine ECU Simulator

# Codes available for disabling
- Code4 (CKP - Crank Position Sensor)
- Code8 (TDC - Top Dead Center Sensor)
- Code9 (CYL - Cylinder Position Sensor)
- Code14 (IACV - Idle Air Control Valve)

# Notes
The remade version of the baserom .bin that has the Codes disabled
cannot be used on the car as normal
(the tool create a copy of the .bin that has the code disabled, it doesn't overwrite your opened file!)

# Requirements
- .Net Framework 3.5 installed (most computer already have that installed by default)
- Windows XP, Vista, 7, 8, 10 (32 and 64 bits)
