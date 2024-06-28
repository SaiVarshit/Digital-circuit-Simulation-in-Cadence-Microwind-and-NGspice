# Simulation 

The project mainly deals with design and performance analysis of a simple 8:1 multiplexer circuit. The circuit is simulated in Cadence,Microwind and NGspice softwares.
The 8:1 MUX circuit can be generated either using NAND gates or Transmission gates(CMOS).
The Main aim of the project is to get familiar with the above softwares.
Cadence provides a wide range of tools for various stages of the electronic design automation (EDA) process, from schematic capture to layout and verification. 
NGspice is an open-source circuit simulator, i.e it is freely available and can be modified as per user requirements or can be integrated into other tools.
Microwind provides an integrated environment for designing and simulating digital and analog circuits, including both CMOS and bipolar technologies.

## Cadence
In this i have used 90nm technolgy files(gdpk90).
First I have generated a 2:1 MUX circuit using Transmission gates.
Next, using the above instantiation, 8:1 MUX can be generated.

Next, Using Analog Design Environment we can simulate our output.

## Microwind 

From Microwind, we obtain post layout simulation.I have generated 8to1 using both nand gates and transmission gates and by comparing Transmission gate circuit uses less area and also generates less delay in the output.


## NGspice
For any digital circuit that is mapped in a circuit it is converted into a netlist which is then used for simulations.
![enter image description here](https://imgur.com/IpVWqBz.png)
