## Simulation of Solar PV system under partial shaded condition.

## AIM:

To simulate solar powered system using MATLAB and obtain the I-V and P-V graph under the partial shaded condition 

## APPARATUS REQUIRED:
 MATLAB 2021 or above 
 
## Theory:

Partial shading, also known as partial shading conditions or partial shading effects, refers to a situation where only part of a solar panel or a portion of a photovoltaic (PV) array is exposed to sunlight while other parts are shaded or receive less sunlight. This condition can significantly affect the performance and efficiency of a solar panel or an entire PV system.
Bypass diodes, also known as blocking diodes or anti-reverse diodes, are essential components in photovoltaic (PV) solar panels and arrays, particularly in the context of partial shading conditions. These diodes play a crucial role in mitigating the effects of partial shading on the performance of solar panels.
Solar panels are typically constructed with multiple solar cells connected in series within a panel. When one or more cells are shaded, their electrical resistance increases, and they generate less current. This can cause the entire string of cells to operate at a lower voltage and current.
Bypass diodes are connected in parallel with sections of the solar cells. When the voltage across a bypass diode exceeds a certain threshold (typically around 0.6-0.7 volts for silicon diodes), it becomes forward-biased and conducts current.
In the presence of shading, the bypass diode(s) connected to the shaded section(s) will start conducting, allowing the current to bypass the shaded area and maintain the overall output of the panel or array.

<img width="496" height="238" alt="image" src="https://github.com/user-attachments/assets/fed4be47-8a82-42a7-b4ff-8ed5b9ba85d7" />




## CIRCUIT DIAGRAM:

<img width="1801" height="918" alt="Screenshot 2026-05-28 105726" src="https://github.com/user-attachments/assets/d687f026-1d97-4495-97b6-8e0bb038340d" />

## Procedure:
1.Open MATLAB<br>
2.From Simulink library browser, pick the following components<br>
a.Solar Panel, Controlled voltage source<br>
b.Current and voltage measurement<br>
c.Diode, Demux,<br>
d.Scope, display<br>
3.Connect the Simulink library tools as shown in the circuit diagram.<br>
4.Set the parameters as per the required design.<br>
5.Simulate the work and tabulate the maximum voltage, current and power.<br>
6.Plot the I-V, P-V graph for the values obtained.<br>

## OUTPUT:

<img width="1709" height="1102" alt="Screenshot 2026-05-28 110544" src="https://github.com/user-attachments/assets/e2875579-4d61-4e45-88c8-b485dda6cc87" />

## RESULT: 

Thus, the I-V and P-V characteristics of the Solar PV under the partial shaded condition is simulated using MATLAB.
    
