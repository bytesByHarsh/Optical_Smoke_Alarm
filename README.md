# Optical Smoke Alarm
A project on optical smoke alarm 


**An Optical Smoke Detector is a device that senses smoke, typically as an indicator of fire.**

## Components Used
* 10K potentiometer.
* IC MOC7811.
* IC LM358.
* Resistors: 100 ohms, 680 ohms, 33K, 10K and 220 ohms.
* Two transistors BC547A.
* 1 LED.
* 1 electric buzzer.
* 1 Capacitor 100 microfarad, 25 volts.

## Description
Optical smoke alarm uses MOC 7811 which is an *optocoupler*.The sensor designed for this device is based on the principle of scattering of *infrared rays*.The light coming from the light source passes through the air being tested and reaches the photosensor. In case of smoke, the received light intensity will be reduced by absorption due to smoke. It can be easily observed while simulating the circuit. This change in light intensity again causes change in the resistance and hence results in the voltage drop. As this happens, the transistor T1 (as shown in the schematic) stops working and transistor T2 starts working and starts off the buzzer. Sensitivity of the sensor can be set by changing the variable resistence of 4.7kΩ. Capacitor C1 is used in case the power cuts off the circuit will still work.

## Schematic of the whole circuit

![Analog Circuit](Schematic/Sch1.png)

## Schematic of circuit in NI Multisim

![Circuit in NI Multisim](Schematic/Sch2.PNG)


## Schematic of PCB Design

![PCB Design](Schematic/Sch3.PNG)
