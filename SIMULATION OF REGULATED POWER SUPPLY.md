# SIMULATION OF REGULATED POWER SUPPLY

## AIM:
To design and simulate the a complete AC to DC power supply using LTspice consisting of a transformer, bridge rectifier, smoothing capacitor, Zener diode voltage regulator and load, and to observe the output waveform at each stage.

## SOFTWARE REQUIRED:
LT-Spice

## PROCEDURE:
1.Double click on LT-Spice icon.

2.New schematic window open.

3.Pick and paste the required component from the library and draw the transformer circuit using AC source, L1, L2 and coupling.

4.Run the simulation and observe the transformer secondary output.

5.Pick and place four diodes and draw the bridge rectifier circuit.
 
6.Run the simulation to obtain the rectified waveform.
 
7.Place the smoothing capacitor across the rectifier output.

8.Run the simulation again to view the filtered DC waveform

9.CAdd the Zener diode regulator with a series resistor and connect the load resistor.

10.Right-click each component and set the required values.

11.Save the file with a suitable name.

12.Click Run → Advanced→ Transient Analysis and set the stop time (e.g.,60 ms).

13.Click Run, and place the probe at each stage to observe: Transformer output, Rectifier output, Filtered output, Regulated output, Load voltage.



## CIRCUIT DIAGRAM:
<img width="983" height="410" alt="image" src="https://github.com/user-attachments/assets/688b9110-12d5-4341-9e7c-5e574bfdb4c5" />


## AC INPUT WAVEFORM:
<img width="945" height="481" alt="Screenshot 2025-11-25 194130" src="https://github.com/user-attachments/assets/5ab91611-56b1-4b9d-b7e0-3dd2da4748f7" />


## OUTPUT GRAPH:
## SIGNAL OUTPUT(WITHOUT FILTER)
<img width="944" height="483" alt="Screenshot 2025-11-25 194142" src="https://github.com/user-attachments/assets/f9aa2222-e7b2-46f5-af02-b520ea2ca416" />

## SIGNAL OUTPUT(WITH FILTER)
<img width="943" height="480" alt="Screenshot 2025-11-25 194157" src="https://github.com/user-attachments/assets/463cd15b-b725-45ab-b9b8-bfda01ce7022" />



## RESULT:
Thus the output waveform at each stage was observed and analyzed. A stable regulated DC output was obtained at the load of RPS using LT-spice is simulated and verified. 
