# Design and Measurement of a Gas Sensor

### Task

The aim of this project is to develop a semiconductor gas sensor to measure the concentration of methane. Metal oxide sensors are also known as chemiresistors. The detection principle of resistive sensors is based on the change of resistance of a thin film upon adsorption of the gas molecules on the surface of a semiconductor. The gas-solid interactions affect the resistance of the film because of the density of electronic species in the film.

Two substrates consisting of aluminum oxide (Al2O3) are given for this project. The development processes will be explained in the following chapters. It includes sputtering, design of the electrode structure, laser structuring, microscopy, design and layout of a printed circuit board (PCB), soldering and testing.

## Structure of the gas sensor

In order to be able to apply the principle of operation a pattern of conductors has to be created between two contact surfaces. These surfaces as well as the conductors consist of a thin layer of platinum which itself is on top of a non-conductive substrate. Above the platinum pattern there is a layer of tin oxide, but at the contacting surfaces the platinum is still exposed. In order to make the effect (change in resistance) easier to measure, the surface area of the pattern should be as high as possible. This is achieved by having small distances between the conductors in the pattern. Since the effect occurs mainly in the space charge zone, the reaction material should be applied only in a thin layer.

![board1](https://user-images.githubusercontent.com/38221793/60840818-9bc29180-a1d0-11e9-91a6-efcbbbee4227.png)       ![board2](https://user-images.githubusercontent.com/38221793/60840819-9bc29180-a1d0-11e9-8168-428a28e15f93.png)

To implement the design of the electrodes, the Easily Applicable Graphical Layout Editor (EAGLE) was used. This software is suitable for creating schematics and layouts for board designs, but also includes other features.

## Sputtering
Sputtering is one possibility of physical vapor deposition (PVD) to create a thin layer on a substrate material. Sputtering is used, because of the good edge covering, flexibility of the sputtered materials and the low temperature stress. In this project, a combination of AC- and magnetron-sputtering is used to create a thin layer of platinum on the ceramic substrate.

## Laser Structuring
The aim of laser structuring is the targeted evaporation of the platinum layer on the ceramic plate at defined geometries.

![boards](https://user-images.githubusercontent.com/38221793/60841323-d678f980-a1d1-11e9-835a-fb2ba1ccaaf0.jpg)

## Measurement
First, the sensor was fixed on a rod and the rod was inserted into a glass tube. The glass tube was then put into the oven which was heated to 400°C. During the heating process of the sensor, the PCB was connected to the power supply and multimeters. 

While the sensor reached the operating temperature, the voltmeters were connected to the board for equipotential bonding and recording of the trace. The other pins on the board like the voltage source pins were also connected. The zero-point adjustment of the wheatstone bridge was performed by adjusting the potentiometer on the PCB with the help of a voltmeter. Thereafter, the gain of the instrumentation amplifier circuit was adjusted to a factor of about 10 with the aid of the measured output and input voltages. In order to record the sensor behavior with different gas compositions, the gas mixing plant was able to conduct differently composed gas mixtures into the gas flow heating tube with the sensor element. Figure 21 shows the control panel of the gas mixing plant. 

The gas mixing plant controls the gas flow into the glass tube. It had the following settings:  
Channel 1: Nitrogen N2: 0.8 slm 
Channel 2: Oxygen O2: 0.2 slm 
Channel 3: Methane CH4: 0.0 sccm 

Note: 1 slm (standard liter per minute) = 1000 sccm (standard cubic centimeter per minute)

![ch41](https://user-images.githubusercontent.com/38221793/60841328-d8db5380-a1d1-11e9-8550-0de2e724beb0.JPG)

Nitrogen and oxygen gases were always flowing through the glass tube in order to create a mixture similar to air, but without any impurities. Methane was turned on and off periodically in different concentrations to test the sensitivity of the sensor. After the sensor was placed into the oven it took about 10 minutes until a constant temperature of 400°C was reached. With that completed, the measurement could start by using a software which automatically saves and plots the measured values. When methane gas was turned on, the voltage decreased. The voltage returned to its previous state when methane gas was turned off.



