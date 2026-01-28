# DAY 02 - Connecting Devices

## What was conducted in this lab?
In this lab, I connected endpoint devices as well as various network devices using the appropriate cables.
Assuming devices did not support Auto MDI-X, I had to be sure to use the correct cables so that devices and networks can properly communicate with one another. 
- PC1 and PC2 connect to SW3 and SW4 respectively via copper straight through cable
  - PCs data transmit on pins 1 and 2 and receive on pins 3 and 6
  - Switches data transmit on pins 3 and 6 and receieve on pins 1 and 2
- SW3 and SW4 connect to SW1 and SW2 respectively via copper cross-over cable
  - Crossover is required for devices that transmit/receive on the same pins and Auto MDI-X is not used
- SW1 and SW2 connect to R2 via copper straight through
- R2 connects to R1 via copper cross-over since they are the same device
- R1 connects to R3 via single mode fiber optic since they are separated 3 kilometers
- R3 connects to R4 via multi mode fiber optic since they are separated 250 meters
- SW5, SW6, SW7, SW8 connect via copper cross-over and copper straight through to PC3 and SRV1 respectively
## Lessons learned?
In this lab, I learned how to properly connect cables across endpoints and network devices. Not relying on Auto MDI-X allowed me to think critically about when to use straight through, cross-over, single mode, and multi mode cables, as well as taking into account information such as distancing between devices. Overall, it helped solidify some concepts surrounding cabling.
