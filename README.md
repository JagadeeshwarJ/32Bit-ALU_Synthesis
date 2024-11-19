# 32Bit-ALU_Synthesis

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
![WhatsApp Image 2024-11-19 at 20 59 54_cf4fd5a7](https://github.com/user-attachments/assets/43cd25f8-2dbd-4cb4-92b5-a1ea38e39cf7)


#### Area report:
![WhatsApp Image 2024-11-19 at 20 59 54_1c3aad9d](https://github.com/user-attachments/assets/f9945c70-90f3-4d20-889f-f8c9bc555b4e)


#### Power Report:
![WhatsApp Image 2024-11-19 at 20 59 55_989e2926](https://github.com/user-attachments/assets/61254169-34c9-43a0-8a30-a7dc4b8fabbe)


#### Result: 

The generic netlist of 32 bit ALU  has been created, and area, power reports have been tabulated and generated using Genus.
