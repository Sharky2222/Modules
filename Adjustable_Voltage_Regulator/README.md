Adjustable Regulator Circuit With Improved Ripple Rejection

SnapEDA Link for component .eli file:
https://www.snapeda.com/parts/LM317T/Texas%20Instruments/view-part/?ref=search&t=lm317

Datasheet Link used: 
https://www.ti.com/lit/ds/symlink/lm317.pdf?ts=1644127164654&ref_url=https%253A%252F%252Fwww.google.com%252F 

To add the .eli file into diptrace, add the downloaded .eli file to the Diptrace Lib directory. 

To import this design into a new diptrace schematic, the exported Adj_voltage_reg.asc file can be downloaded and used with the hierachial block by copy and pasting it 
into the current project. To generate the export file go to the file and export as a DipTrace Ascii. To import a file, go to the file and import a downloaded .asc file. Another approach can be done by downloading the Adjustable_Voltage_Regulator.dch file and using the hierachial block by copy and pasting into the current project.

This circuit is useful because it provides noise rejection and stabilizes the voltage at the adjustment pin. The resistors in the system determine the output voltage and the capacitors smooth the voltage wave.  

Output voltage is listed below, where IADJ is the current coming out of the adjust pin and is usually negligible in most applications.
VO = VREF (1 + R2 / R1) + (IADJ × R2)

Bill of Materials:
-LM317T
-240 ohm resistor
-.1uF capacitor
-10uF capacitor
-1uF capacitor
-1N4002 diode
-5k resistor
