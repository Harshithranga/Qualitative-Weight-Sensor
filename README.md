# Qualitative-Weight-Sensor
# Weight Sensor using BJTs and Force Sensitive Resistor (FSR)

This repository contains the documentation and circuit diagrams for building a weight sensor using Bipolar Junction Transistors (BJTs) in a voltage divider bias configuration along with a Force Sensitive Resistor (FSR). Additionally, it includes information on designing a power supply circuit using a 12V step-down transformer to convert 220V AC to 12V DC.

## Weight Sensor Circuit

The weight sensor circuit presented here combines the characteristics of BJTs and FSR to create a simple yet effective weight measurement system. The BJT voltage divider bias configuration provides a stable voltage reference, and the FSR changes its resistance based on the applied force (weight). This change in resistance modulates the voltage across the FSR, leading to a detectable voltage change at the output.

### Components Needed

- NPN Bipolar Junction Transistors (BJTs)
- Force Sensitive Resistor (FSR)
- Resistors (various values)
- Capacitors (for noise filtering, optional)
- Breadboard or PCB for prototyping
- Connecting wires

## Power Supply Circuit with 12V Step-Down Transformer

To power the weight sensor circuit, a power supply circuit is required. This repository also provides information on designing a power supply circuit using a 12V step-down transformer to convert the standard 220V AC mains voltage to a safer and usable 12V DC voltage.

### Components Needed

- 12V Step-Down Transformer
- Bridge Rectifier
- Capacitors (for smoothing)
- Voltage Regulator (e.g., LM7805) for stable 12V DC output
- Heat Sink (for the voltage regulator, if necessary)
- Diodes
- Filtering Capacitors
- Connecting wires

## Usage

1. Clone this repository to your local machine.
2. Refer to the circuit diagrams in the PDF directory for both the weight sensor and power supply circuits.
3. Gather the required components mentioned in the documentation.
4. Assemble the circuits on a breadboard or design and fabricate a PCB.
5. Follow best practices for circuit assembly, wiring, and safety precautions when dealing with electrical circuits.
6. Power up the circuits and observe the weight sensor's output as you apply different forces to the FSR.
7. Monitor the power supply circuit to ensure a stable and safe 12V DC output.

**Disclaimer:** This project involves working with electrical components and circuits, which can be potentially hazardous. Always follow proper safety precautions, work in a controlled environment, and seek professional guidance if needed. The authors of this repository are not responsible for any damage, injury, or loss caused by the use of the provided information.
