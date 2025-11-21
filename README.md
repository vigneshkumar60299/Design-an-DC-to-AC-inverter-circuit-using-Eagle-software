# Design-an-DC-to-AC-inverter-circuit-using-Eagle-software
## Exp 2: Design an DC to AC inverter circuit using Eagle software
# AIM:
To design the schematic and PCB layout diagram of a DC to AC inverter circuit using Eagle software.
# EQUIPMENT REQUIRED:
● Hardware: Personal Computer (PC) <br>
● Software: Eagle <br>
# PROCEDURE:
### Create a New Project: <br>
o Launch EAGLE and start a new project for your PCB design. <br>
o Within the project, create a new schematic file. <br>

### Add Components: <br>
o Utilize the built-in libraries in EAGLE or create custom libraries if needed. <br>
o Use the 'Add' tool to place the required components onto the schematic sheet. <br>

### Make Connections: <br>
o Connect the components using the 'Net' tool. <br>
o Label the nets clearly to maintain clarity and organization in your design. <br>

### Check for Errors: <br>
o Once the schematic design is complete, perform an Electrical Rule Check (ERC) to identify and correct any errors. <br>
o Save the schematic after confirming that no errors are present. <br>

### Switch to Board Layout: <br>
o Click on the 'Generate/Switch to Board' button to create the PCB layout from the schematic.

 ### Arrange Components and Route Traces: <br>
o In the board layout editor, arrange the components to optimize space and reduce signal interference. <br>
o Use the 'Route' tool to connect the components based on the schematic design. <br>
o Ensure proper routing by utilizing the available editing tools in EAGLE to avoid design rule violations.

 ### Design Rule Check (DRC): <br>
o Perform a Design Rule Check (DRC) to ensure that the routing and layout comply with design standards and that there are no issues. <br>
o Save the board layout after resolving any errors. <br>

 ### Generate Gerber Files: <br>
o Go to File > CAM Processor and configure the CAM jobs to generate Gerber files for all PCB layers, such as copper layers, silkscreen, solder mask, and drill files. <br>
o Verify the generated files to ensure they contain all necessary information for manufacturing. <br>
 Save Manufacturing Files: <br>
o Save the Gerber files and any other required manufacturing files to send to your PCB manufacturer for fabrication. <br>

# THEORY:
An inverter is an electronic device that converts direct current (DC) into alternating current (AC). A transformer-based inverter makes use of a transformer to step up the voltage level of the AC waveform generated from a low-voltage DC supply. The basic need for such an inverter arises from the fact that most electrical appliances and utility power systems operate on high-voltage AC (110V/230V, 50Hz/60Hz), while common energy storage units like batteries or photovoltaic (PV) cells provide only low-voltage DC (12V, 24V, or 48V). Hence, the inverter bridges this gap by producing a usable AC supply from a DC source.The construction of a transformer-based inverter consists of three key sections: the DC source, the switching or oscillator stage, and the step-up transformer. The DC source may be a battery bank, a rectifier, or solar panels. The switching stage typically uses semiconductor devices like bipolar junction transistors (BJTs), metal-oxide semiconductor field-effect transistors (MOSFETs), or insulated gate bipolar transistors (IGBTs) to create an alternating signal from the DC input. These switches are controlled in a push-pull or H-bridge arrangement to produce alternating current pulses across the transformer’s primary winding.

The transformer is the heart of the circuit. It not only steps up the low-voltage alternating signal but also provides electrical isolation between the input DC source and the AC load. Depending on the turn ratio of the transformer, a 12V or 24V AC at the primary winding can be converted into 110V or 230V AC at the secondary winding. The waveform produced can vary depending on the design—from square waves in simple models to pure sine waves in advanced models. Such inverters are widely applied in uninterruptible power supplies (UPS), renewable energy systems, and emergency backup power.

# Working:
The working of a transformer-based inverter begins with the DC supply provided by a battery or solar panel. Since DC cannot be directly fed to a transformer, it must first be converted into an alternating signal. This task is accomplished by a switching circuit composed of semiconductor devices such as MOSFETs or IGBTs. These switches are arranged in pairs, usually in a push-pull configuration. A control signal or oscillator circuit alternately turns the switches ON and OFF, thereby applying the DC voltage to the transformer’s primary winding in opposite directions during each cycle.As one switch conducts, current flows through one half of the transformer primary, producing a magnetic flux. When the switch turns off and the other switch turns on, the current flows in the opposite direction through the other half of the primary, thus reversing the polarity of the flux. This alternating magnetic field induces an alternating voltage across the transformer’s secondary winding according to Faraday’s law of electromagnetic induction. By appropriately choosing the turns ratio, the transformer steps up the low-voltage AC to the required high-voltage AC output, such as 220V at 50Hz.

The quality of the output waveform depends on the switching method used. If the switches simply turn ON and OFF without modulation, the result is a square wave. For improved performance, pulse-width modulation (PWM) techniques are employed, which generate modified or pure sine wave outputs. In high-quality inverters, filters consisting of capacitors and inductors are used at the output stage to smoothen the waveform.Thus, the inverter provides a high-voltage AC supply capable of running household appliances, industrial machines, or communication equipment. Transformer-based inverters are reliable, provide electrical isolation, and are especially useful in applications where stable AC power is required from low-voltage DC sources.

# CIRCUIT DIAGRAM:

<img width="744" height="547" alt="image" src="https://github.com/user-attachments/assets/d7d74d2e-322f-4cae-a94a-2cb9ac7186a8" />

 
# Schematic diagram
<img width="1291" height="643" alt="Screenshot 2025-10-10 063045" src="https://github.com/user-attachments/assets/b39cd16e-c25d-4ad2-8ee1-080d67649366" />


# Layout diagram
<img width="1273" height="641" alt="Screenshot 2025-10-10 063057" src="https://github.com/user-attachments/assets/b6a15ba6-906b-4fe8-864c-92441f8234c4" />


# RESULT:
Thus, the schematic and PCB layout for the DC to AC inverter circuit has been successfully designed using Eagle software.
