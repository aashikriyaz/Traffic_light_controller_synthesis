# Traffic_light_controller_Synthesis

## Aim:

Synthesize Traffic Light Controller design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Creating an SDC File

•	In your terminal type “gedit input_constraints.sdc” to create an SDC File if you do not have one.

### Step 3 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

#### Synthesis RTL Schematic :
![bf5ae70b-1583-4db6-a2ed-7494713a5993](https://github.com/user-attachments/assets/8840a534-9f4d-4884-a116-4a5736eb11bf)

#### Area report:
![6d938971-4782-4b3c-963a-4b796572c9a0](https://github.com/user-attachments/assets/16466af8-f6c5-429b-b7e4-815e59f80ab1)

#### Power Report:
![e841cb2a-3bab-40e8-a7e7-66138095f3aa](https://github.com/user-attachments/assets/71a50121-7358-427c-b727-032e3e8a3aac)


Result:

The generic netlist of Traffic Light Controller has been created, and area, power reports have been tabulated and generated using Genus.
