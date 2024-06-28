# Simulation 

The project mainly deals with design and performance analysis of a simple 8:1 multiplexer circuit. The circuit is simulated in Cadence,Microwind and NGspice software's.
The 8:1 MUX circuit can be generated either using NAND gates or Transmission gates(CMOS).

The Main aim of the project is to get familiar with the below software's.

Cadence provides a wide range of tools for various stages of the electronic design automation (EDA) process, from schematic capture to layout and verification. 
NGspice is an open-source circuit simulator, i.e it is freely available and can be modified as per user requirements or can be integrated into other tools.
Microwind provides an integrated environment for designing and simulating digital and analog circuits, including both CMOS and bipolar technologies.

## Cadence
In this i have used 90nm technolgy files(gdpk90).
First I have generated a 2:1 MUX circuit using Transmission gates.
![Schematic](https://github.com/SaiVarshit/Digital-circuit-Simulation-in-Cadence-Microwind-and-NGspice/assets/171639583/7f13b88e-c345-42ea-a072-5ebd196e8c7d)

Next, using the above instantiation, 8:1 MUX can be generated.
![Schematic](https://github.com/SaiVarshit/Digital-circuit-Simulation-in-Cadence-Microwind-and-NGspice/assets/171639583/7319c9ea-45b1-4ef6-a8a9-81f636c8f834)

Next, Using Analog Design Environment we can simulate our output.
![Output](https://github.com/SaiVarshit/Digital-circuit-Simulation-in-Cadence-Microwind-and-NGspice/assets/171639583/76371212-c8a8-4017-9ecf-3c670937db28)

## Microwind 

From Microwind, we obtain post layout simulation.I have generated 8to1 MUX using both nand gates and transmission gates by satisfying all the design rules.
Now, on comparing Transmission gate circuit uses less area and also generates less delay in the output.
![Final output with delay](https://github.com/SaiVarshit/Digital-circuit-Simulation-in-Cadence-Microwind-and-NGspice/assets/171639583/19ab8708-7b10-417f-ac39-bdfaf055302c)

## NGspice
For any digital circuit that is mapped in a circuit it is converted into a netlist which is then used for simulations.
![Circuit Diagram](https://github.com/SaiVarshit/Digital-circuit-Simulation-in-Cadence-Microwind-and-NGspice/assets/171639583/074a00eb-ad74-45fa-8041-2124fc0a4291)
![Vout](https://github.com/SaiVarshit/Digital-circuit-Simulation-in-Cadence-Microwind-and-NGspice/assets/171639583/4388808a-2fb6-4f19-8f8f-fa0a39894653)
