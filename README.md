# Square-Wave-Generators
Engineered a stable square wave oscillator, executed the complete design flow from schematic capture to PCB layout, manually assembled and soldered SMD components onto custom-fabricated boards. Successfully delivered 4 functional units  adapting designs to meet specific user requirements and providing technical support for each build especially on the PCB Layout.
# The user's requirements are to design and create a rectangular signal generator with the following characteristics:
- Oscillation frequency, fo, adjustable in the range: 20-40 [KHz]; 
- Duty cycle: 0.5; 
- Output load, RL: 10 [Kohm]; 
- Value (peak to peak) of the output oscillation, Vo, adjustable in the range: 0-2.5 [V]; 
- The output signal has no continuous component; 
- Operating temperature range: 0-70C (verifiable by testing in 
temperature); 
- Signaling the presence of input/output voltages with LED diode.
# Schematic concept:
-The electrical diagram is of a circuit that behaves like an inverting comparator with hysteresis, the inverting input containing an RC network after which it becomes a relaxation oscillator circuit. C2 and C3 form a low-pass filter and will make the shape of the rectangular signal better. The circuit frequency is set by means of the network C1, R9, P1. 
The threshold voltages of the hysteresis are set by resistors R7 and R8, that is, the values ​​between which the capacitor C1 charges and discharges. 
The circuit continues with a voltage amplifier formed by transistors Q6 and Q7, 
whose peak-to-peak amplitude is set by the voltage divider R10, P2.
