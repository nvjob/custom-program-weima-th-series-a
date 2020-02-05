# Custom program for WEIMA TH Standard Series (Briquette Press). A 2.8
#### [nvjob.github.io/sources/custom-program-weima-th-series-a](https://nvjob.github.io/sources/custom-program-weima-th-series-a)

![GitHub Logo](https://raw.githubusercontent.com/nvjob/nvjob.github.io/master/repo/other%20sources/weima%20th%20a/28/pic/2.jpg)

### Attention!!!
This is not an official program.
For the program to function, all devices must be connected according to the inputs and outputs installed in the program.<br>
You must understand what you are doing.<br>
You must have knowledge of electrical engineering and technological processes.<br>
The program was written to restore the dead briquette press.

### Features of the work.
Automatic start, no preliminary preparation required.<br>
When the press is clogged, self-cleaning occurs, after self-cleaning, work continues.<br>
No encoder is required at the press outlet.

[youtube.com/watch?v=UAsh35nRsfA](https://www.youtube.com/watch?v=UAsh35nRsfA)

**Program for another Weima briquette press** - https://github.com/nvjob/custom-program-weima-th-series-b

-------------------------------------------------------------------

### Prerequisites
For large press with two engines on hydro station <br>
Siemens S7-200

#### INPUTS:
I0.0 - Power. Starting up the hydraulic station.(Network 1) <br>
I0.1 - Start the program in automatic mode. (Network 11 - 12) <br>
I0.2 - Stop the program in automatic mode. Manual mode. (Network 19) <br>
I0.3 - Not involved. <br>
I0.4 - Vertical piston, sensor, lower position. <br>
I0.5 - Vertical piston, sensor, upper position. <br>
I0.6 - Horizontal piston, sensor, position retracted. <br>
I0.7 - Horizontal piston, sensor, position extended. <br>
I1.0 - Not involved. <br>
I1.1 - Pressure switch. <br>
I1.2 - Accident, stop. (Normally closed. When opened, an emergency stop occurs.) <br>
I1.3 - Change in operating time of the screw. Min time.(Network 43 - 44) (Three position switch.) <br>
I1.4 - Change in the operating time of the screw. Max. time.(Network 47 - 48) (Three position switch.) <br>
When I1.3 and I1.4 are not included this corresponds to the average time.(Network 45 - 46) (Three position switch.) <br>
I1.5 - (optional) Sensor for supplying material to the tank. It is installed at the right level in the tank, to automatically feed the material into the tank, to maintain the same amount of material in the tank.

#### OUTPUTS:
Q0.0 - The engine of the hydraulic power station (star-delta). <br>
Q0.1 - Hydroelectric power station engine (star-delta). Main valve. <br>
Q0.2 - Fan. <br>
Q0.3 - Auger <br>
Q0.4 - Vertical piston, valve, up position (pushes down). <br>
Q0.5 - Vertical piston, valve, lower position (pushes up). <br>
Q0.6 - Horizontal piston, valve, retracts the piston. <br>
Q0.7 - Horizontal piston, valve, extends the piston. <br>
Q1.0 - Collet Piston. <br>
Q1.1 - The small engine of a hydraulic power station. <br>
Q2.1 - (optional) Auger for feeding sawdust into the tank.

-------------------------------------------------------------------

![GitHub Logo](https://raw.githubusercontent.com/nvjob/nvjob.github.io/master/repo/other%20sources/weima%20th%20a/28/pic/5.jpg)

-------------------------------------------------------------------

**Authors:** #NVJOB Nicholas Veselov - [nvjob.github.io](https://nvjob.github.io)

**License:** GNU GPL v3.0. Clarification of licenses - [nvjob.github.io/gnu-license](https://nvjob.github.io/gnu-license)

**Support:** [nvjob.github.io/support](https://nvjob.github.io/support)
