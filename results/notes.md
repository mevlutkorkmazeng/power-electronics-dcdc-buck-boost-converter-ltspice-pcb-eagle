# Results and Observations

This folder will include the results obtained from the LTspice simulations and later from the PCB design stage.

Planned results:

- output voltage waveforms
- inductor current waveforms
- output voltage ripple
- efficiency calculations
- comparison between Buck and Boost converters

These results will help to understand the behavior and performance of the DC-DC converter.

# Simulation Results

## Buck Converter Output

The LTspice simulation produced the following results for the Buck converter.

### Key Observations

- Input Voltage: 12 V
- Output Voltage: ≈ 6 V
- Switching Frequency: ≈ 2.5 kHz
- Inductor Current: triangular waveform as expected for continuous conduction mode
- Output Ripple: small ripple due to LC filtering

### Explanation

The Buck converter reduces the input voltage by controlling the duty cycle of the PWM signal applied to the MOSFET.

During the ON state, energy is stored in the inductor.

During the OFF state, the inductor releases energy to the load through the diode.

The capacitor smooths the output voltage and reduces ripple.

### Conclusion

The simulation confirms the expected operation of the Buck converter:

- stable output voltage
- controlled switching behavior
- reduced ripple due to LC filter
