************************************
Author:  Tianyun Du
Date:    March 15 2025
************************************
Discription:
This circuit is designed for precise current measurement.
For me is to measure the intensity of scintillator under X-ray radiation.
The photodiode I used is an HAMAMATSU S1227-1010BR.
The feedback resistance and capacitor used in these two Op Amp are calculated from the online design tool "Photodiode Circuit Design Wizard".
Website: https://tools.analog.com/en/photodiode/
ATTENTION:
IF YOU USE ANOTHER PHOTODIODE, RE-DESIGN THIS CIRCUIT WITH THIS TOOL.
THE PACKAGE OF THESE RESISTANCE AND CAPACITOR ARE "0805".
*************************************


************************************
************POWER SUPPLY************
************************************
USE INTERNAL POWER SUPPLY

The power supply of these Op Amps are ±5V (from 12V), you can also find this design in my other repository.
Use two jumper cap to enable the power supply on board ("H1"&"H2"). You can introduce 12V input from "DC1" OR "P1".

OR....

USE EXTERNAL POWER SUPPLY

External linear power supply can be used for power supply, to obtain a power with lower ripple.
Connect the +5V/AGND/-5V to "P2".
Other voltage can be used like ±10V and ±15V based on the data sheet of ADA4530-1, but I have not test yet.
The website of datasheet:
https://www.analog.com/media/en/technical-documentation/user-guides/ada4530-1r-ebz_ug-865.pdf

*************************************
*********ANOTHER INFORMATION*********
*************************************
DO NOT WELDING THE 0R RESISTANCE IN R2!
DO NOT WELDING THE 0R RESISTANCE IN R2!
DO NOT WELDING THE 0R RESISTANCE IN R2!

