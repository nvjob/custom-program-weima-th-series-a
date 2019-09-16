# Custom program for WEIMA TH Standard Series. A

Attention!!!

This is not an official program.
For the program to function, all devices must be connected according to the inputs and outputs installed in the program.
You must understand what you are doing.
You must have knowledge of electrical engineering and technological processes.

-------------------------------------------------------------------

Features of the work.

Automatic start, no preliminary preparation required.
When the press is clogged, self-cleaning occurs, after self-cleaning, work continues.
No encoder is required at the press outlet.

https://www.youtube.com/watch?v=UAsh35nRsfA

-------------------------------------------------------------------

INPUTS:
I0.0 - Power. Starting up the hydraulic station.(Network 1)<br>
I0.1 - Start the program in automatic mode. (Network 11 - 12)
I0.2 - Stop the program in automatic mode. Manual mode. (Network 19)
I0.3 - Not involved *
I0.4 - Vertical piston, sensor, lower position.
I0.5 - Vertical piston, sensor, upper position.
I0.6 - Horizontal piston, sensor, position retracted.
I0.7 - Horizontal piston, sensor, position extended.
I1.0 - Not involved *.
I1.1 - Pressure switch.
I1.2 - Accident, stop. (Normally closed. When opened, an emergency stop occurs.)
I1.3 - Change in operating time of the screw. Min time.(Network 43 - 44) (Three position switch.)
I1.4 - Change in the operating time of the screw. Max. time.(Network 47 - 48) (Three position switch.)
When I1.3 and I1.4 are not included this corresponds to the average time.(Network 45 - 46) (Three position switch.)
I1.5 - (optional) Sensor for supplying material to the tank. It is installed at the right level in the tank, to automatically feed the material into the tank, to maintain the same amount of material in the tank.

-------------------------------------------------------------------

OUTPUTS:
Q0.0 - The engine of the hydraulic power station (star-delta).
Q0.1 - Hydroelectric power station engine (star-delta). Main valve.
Q0.2 - Fan.
Q0.3 - Auger
Q0.4 - Vertical piston, valve, up position (pushes down).
Q0.5 - Vertical piston, valve, lower position (pushes up).
Q0.6 - Horizontal piston, valve, retracts the piston.
Q0.7 - Horizontal piston, valve, extends the piston.
Q1.0 - Collet Piston.
Q1.1 - The small engine of a hydraulic power station.
Q2.1 - (optional) Auger for feeding sawdust into the tank.
