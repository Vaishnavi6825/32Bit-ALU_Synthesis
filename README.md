# EXP5: 32Bit-ALU_Synthesis

## Aim:

Synthesize 32 Bit ALU design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being
used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

#### Synthesis RTL Schematic :
![Screenshot_(126) 1](https://github.com/user-attachments/assets/64ba74cc-932f-442a-b43a-bc25867ea6dd)


#### Area report:
![Screenshot_(127) 1](https://github.com/user-attachments/assets/84d67580-0700-4337-be51-2669de409ba1)

#### Timing Report:
![Screenshot_(129) 1](https://github.com/user-attachments/assets/3dc916a4-e92b-4531-94c4-192e3c2672bf)

#### Power Report:
![Screenshot_(128) 1](https://github.com/user-attachments/assets/cbe06492-6473-49ec-982e-f6f4cd5089b2)




#### Result: 

The generic netlist of 32 bit ALU  has been created, and area, power reports have been tabulated and generated using Genus.
