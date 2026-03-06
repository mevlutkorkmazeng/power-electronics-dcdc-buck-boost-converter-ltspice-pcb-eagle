# Buck Converter Initial Design

In this step, the goal is to design a simple Buck converter circuit.

Target example:

Input Voltage: 12V  
Output Voltage: about 5V  

Basic Buck converter components:

- MOSFET (switch)
- diode
- inductor
- output capacitor
- load resistor

The output voltage of a Buck converter depends on the duty cycle of the switching signal.

Basic relation:

Vout ≈ D × Vin

Where:

Vin = input voltage  
Vout = output voltage  
D = duty cycle

Example:

Vin = 12V  
Target Vout ≈ 5V  

Estimated duty cycle:

D ≈ 5 / 12 ≈ 0.42

In the next step, this circuit will be built and simulated in LTspice.
