# N-CHANNEL MOSFET OUTPUT AND TRANSFER CHARACTERISTICS
# AIM:
To study transfer and output characteristics of an n-channel Metal Oxide Semiconductor field
effect Transistor (MOSFET) in Common-source configuration

# APPARATUS REQUIRED:
<img width="974" height="466" alt="image" src="https://github.com/user-attachments/assets/1dc29c04-d2d1-443a-ab84-e21bdd308d01" />

# CIRCUIT DIAGRAM: 
<img width="932" height="600" alt="image" src="https://github.com/user-attachments/assets/fac3ebd0-a055-4a01-8192-18b14a9901aa" />

# THEORY:
The MOSFET is actually a four-terminal device, whose substrate, or body terminal must be
always held at one of the extreme voltage in the circuit, either the most positive for the PMOS or
the most negative for the NMOS. One unique property of the MOSFET is that the gate draws no
measurable current.

# PROCEDURE:
# OUTPUT/DRAIN CHARACTERISTICS:
1. Connect the circuit as per given diagram properly.
2. Keep V GS constant at some value say 1.1 V by varying V GG
3. Vary V DS in step of 1V up to 10 volts and measure the drain current I D . Tabulate all the
readings.
4. Repeat the above procedure for V GS as 1.2V, 1.3V, 1.4V, 1.5V etc
   
# TRANSFER CHARACTERISTICS:
1. Connect the circuit as per given diagram properly.
2. Set the voltage V DS constant at 10 V.
3. Vary V GS by varying V GG in the step of 0.1 up to 1.55V and note down value of drain
current I D . Tabulate all the readings.
4. Plot the output characteristics V DS vs I D and transfer characteristics VGS vs ID
5. Calculate V T ,gm, rd or ro from the graphs and verify it from the data sheet.

# TABULATION:
# DRAIN CHARACTERISTICS:

<img width="699" height="407" alt="Screenshot 2026-03-28 174138" src="https://github.com/user-attachments/assets/6e3945dc-7aea-4168-8e8a-3e0ba22a89e7" />


# TRANSFER CHARACTERISTICS:

<img width="742" height="452" alt="Screenshot 2026-03-28 174220" src="https://github.com/user-attachments/assets/92ca5b3f-03c1-46a6-9805-69e08b477c33" />


# MODEL GRAPH:

# TRANSFER CHARACTERISTICS DRAIN CHARACTERISTICS:
<img width="1098" height="460" alt="image" src="https://github.com/user-attachments/assets/f2570b25-b339-4a9c-9c90-19e9a59b5051" />

# GRAPH:

<img width="1200" height="1600" alt="image" src="https://github.com/user-attachments/assets/dcc6e4dc-5339-480d-99a2-25dce1ab0232" />


# CALCULATION:
1. Threshold voltage V T : Gate to source voltage at which, drain current starts flowing.
2. Transconductancegm : Ratio of small change in drain current (Δ I D ) to the corresponding
change in gate to source voltage (ΔV GS ) for a constant V DS .
gm = Δ I D / ΔV GS at constant V DS
3. Output drain resistance : It is given by the relation of small change in drain to source voltage
(Δ V DS ) to the corresponding change in Drain Current (Δ I D ) for a constant V GS .
rd or ro = ΔVDS/ΔID at a constant VGS

# RESULTS:
1. V T : 0.50 kilo ohms
2. gm : 1.5 x 10^-3 ohm
3. ro : 0.75

