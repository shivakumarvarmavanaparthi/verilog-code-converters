# BCD to Excess-3 Code Converter

## Aim

To design and simulate a BCD to Excess-3 Code Converter using Behavioral Modeling in Verilog HDL.

---

## Description

BCD (Binary Coded Decimal) represents decimal numbers using 4-bit binary values. Excess-3 is a non-weighted code obtained by adding 3 to the BCD value.

This project implements a 4-bit BCD to Excess-3 code converter using Behavioral Modeling in Verilog HDL. The design uses a case statement to represent the conversion truth table.

---

## Folder Structure


BCD-to-Excess3
│
├── bcd_to_excess3.v
├── bcd_to_excess3_tb.v
├── output.txt
├── waveform.png
└── README.md


---

## Files Description

| File Name | Description |
|-----------|-------------|
| `bcd_to_excess3.v` | Verilog design module |
| `bcd_to_excess3_tb.v` | Testbench for simulation |
| `output.txt` | Simulation output |
| `waveform.png` | GTKWave waveform screenshot |
| `README.md` | Project documentation |

---

## Truth Table

| BCD Input | Excess-3 Output |
|-----------|-----------------|
| 0000 | 0011 |
| 0001 | 0100 |
| 0010 | 0101 |
| 0011 | 0110 |
| 0100 | 0111 |
| 0101 | 1000 |
| 0110 | 1001 |
| 0111 | 1010 |
| 1000 | 1011 |
| 1001 | 1100 |

---

## Verilog Modeling Style

**Behavioral Modeling**

The conversion is implemented using:

- `always @(*)` block
- `case` statement
- Truth table based design

---

## Simulation Procedure

### Step 1: Compile the Verilog Code

```bash
iverilog -o sim bcd_to_excess3.v bcd_to_excess3_tb.v
Step 2: Run Simulation
vvp sim
Step 3: Generate Waveform

The testbench generates a VCD waveform file:

bcd_to_excess3.vcd
Step 4: Open Waveform
gtkwave bcd_to_excess3.vcd
Expected Simulation Output
BCD = 0000 Excess-3 = 0011
BCD = 0001 Excess-3 = 0100
BCD = 0010 Excess-3 = 0101
BCD = 0011 Excess-3 = 0110
BCD = 0100 Excess-3 = 0111
BCD = 0101 Excess-3 = 1000
BCD = 0110 Excess-3 = 1001
BCD = 0111 Excess-3 = 1010
BCD = 1000 Excess-3 = 1011
BCD = 1001 Excess-3 = 1100
Tools Used
Verilog HDL
Icarus Verilog
GTKWave
Visual Studio Code
Git Commands

After completing the project:

git add .
git commit -m "Add BCD to Excess-3 Code Converter"
git push
Result

The BCD to Excess-3 Code Converter was successfully designed, simulated, and verified using Behavioral Modeling in Verilog HDL.