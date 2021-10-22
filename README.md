# [PCB for the Air Bearing](https://online.huskysatellitelab.com/wiki/index.php/2021_Intro_Projects#Design_PCB_for_the_Air_Bearing)

As a project developed over the course of a summer, our air bearing test stand's electrical system needed to be quickly assembled onto a perfboard Arduino shield. Now that we have time, we'd like to replace that janky jury-rigged board with a PCB to make the system more robust and reduce the number of loose wires holding the electronics together. Currently, the circuit is responsible for connecting the I2C lines of the Arduino Uno to several sensors and an external system through a logic level shifter, communicating with a Bluetooth module over UART, receiving power from a battery, and providing reset functionality in software.

In this intro project, you will design a PCB to act as a shield over an Arduino Uno that replaces the functionality of the current perfboard. You will translate a circuit from a breadboard schematic into a PCB design and manufacture it.

**Tasks involved:** PCB design, electronics manufacturing

**Background knowledge:** Electronics/ECAD knowledge will be helpful, but not required.

**What you'll learn:** The process of translating a breadboard circuit into a PCB, manufacturing, and assembly.

**Point of Contact:** Sebastian Soetomo or Andrew Buckingham 
