# Power Electronics Project: DC-DC Buck and Boost Converter (LTspice)

This project is about DC-DC converter design in power electronics.

The main aim is to study how Buck and Boost converters work and how they can be simulated in LTspice.  
In this project, I design simple converter circuits and observe voltage, current, switching behavior, and output ripple.

The project also includes basic design notes, simulation files, and preparation for PCB work.

## Project Goals

- Understand how DC-DC converters work
- Design a Buck converter circuit
- Design a Boost converter circuit
- Simulate the circuits in LTspice
- Observe voltage and current waveforms
- Analyze output voltage ripple
- Study the basic behavior of power electronic switching circuits

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
