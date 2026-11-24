# Approximate Arithmetic Workbench

Interactive evaluation workbench for the capstone **"Design of a Dynamic Accuracy Configurable Arithmetic Unit for Energy-Efficient Image Processing Applications"**, ECE Dept., Thapar Institute of Engineering & Technology. Supervisor: Dr. Bharat Garg.

Team: Chaitanya Goyal, Kushal Tandon, Nia Malik, Rijul Malhotra, Tanisha Lal, Tushar Yadav.

## What it does
- **Adder Lab**: 23 adders (exact, approximate, and our WA-SASC/T). Compare ER, NMED, MRED, bias and a unit-gate area/delay estimate.
- **Multiplier Lab**: 26 8x8 multipliers, tested exhaustively (65,536 pairs), including the proposed modes M0-M3. RTL lookup tables can be imported.
- **CNN Application**: quantised UINT8 digit-recognition CNN run with any multiplier and adder in the MAC datapath.
- **Methodology & Validation**: definitions, reproduction of the WA-SASC paper's Table III, published sky130 numbers.

## Run
Open `index.html` in any browser. Single file, fully offline, no build step.

## Scope
Behavioural models only. Hardware columns are unit-gate estimates for relative comparison, not synthesis results. The proposed multiplier is a behavioural model and does not yet match the RTL for modes 1-3; import the RTL lookup table for bit-exact results.
