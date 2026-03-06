# Power Electronics Project: DC-DC Buck and Boost Converter (LTspice)

This project is about DC-DC converter design in power electronics.

The main aim is to study how Buck and Boost converters work and how they can be simulated in LTspice.  
In this project, I design simple converter circuits and observe voltage, current, switching behavior, and output ripple.

The project also includes basic design notes, simulation files, and preparation for PCB work.

## Project Overview

This project demonstrates the design and simulation of a **DC-DC Buck Converter** using LTspice.  
The converter steps down a **12V input voltage** to a lower output voltage using PWM switching control.

Key features analyzed in this project:

- PWM switching behavior
- Inductor current waveform
- Output voltage ripple
- Basic converter performance

  
## Project Goals

- Understand how DC-DC converters work
- Design a Buck converter circuit
- Design a Boost converter circuit
- Simulate the circuits in LTspice
- Observe voltage and current waveforms
- Analyze output voltage ripple
- Study the basic behavior of power electronic switching circuits


## Buck Converter Circuit

![Buck Circuit](images/buck_converter_circuit.png)

## Converter Specifications

| Parameter | Value |
|-----------|------|
| Input Voltage | 12 V |
| Inductor | 100 µH |
| Capacitor | 100 µF |
| Load Resistance | 10 Ω |
| Switching Frequency | 2.5 kHz |
| Duty Cycle | ~35% |

## Buck Converter Simulation Results

### PWM Gate Signal and Output Voltage

![Buck PWM Output](images/buck_pwm_vout_waveform.png)

This waveform shows the PWM gate signal and the output voltage response of the buck converter.

### Inductor Current

![Inductor Current](images/buck_inductor_current.png)

This waveform shows the inductor current during converter operation.

### Output Voltage Ripple

![Output Ripple](images/buck_output_ripple.png)

This waveform shows the output voltage ripple in steady-state operation.

## Project Structure

- `docs/` → theory notes and design explanations
- `simulations/` → LTspice simulation notes and files
- `results/` → result notes and observations
- `pcb/` → PCB preparation notes
- `images/` → simulation screenshots used in the README

## Tools Used

- LTspice
- Power Electronics concepts
- Basic PCB design tools
- GitHub for project documentation
