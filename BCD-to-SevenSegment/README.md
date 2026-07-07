# BCD to Seven Segment Display Converter

## Aim

To design and simulate a BCD to Seven Segment Display Converter using Behavioral Modeling in Verilog HDL.

---

## Description

A Seven Segment Display is an electronic display device used to represent decimal numbers using seven individual LED segments named as a, b, c, d, e, f and g.

This project converts a 4-bit BCD input into the corresponding seven segment display output pattern.

The design is implemented using Behavioral Modeling in Verilog HDL using a `case` statement based on the conversion truth table.

---

## Folder Structure


BCD-to-SevenSegment
│
├── bcd_to_seven_segment.v
├── bcd_to_seven_segment_tb.v
├── output.txt
├── waveform.png
└── README.md


---

## Files Description

| File Name | Description |
|-----------|-------------|
| `bcd_to_seven_segment.v` | Verilog design module |
| `bcd_to_seven_segment_tb.v` | Testbench for simulation |
| `output.txt` | Simulation output |
| `waveform.png` | GTKWave waveform screenshot |
| `README.md` | Project documentation |

---

## Truth Table

| BCD Input | Seven Segment Output (abcdefg) |
|-----------|-------------------------------|
| 0000 | 0000001 |
| 0001 | 1001111 |
| 0010 | 0010010 |
| 0011 | 0000110 |
| 0100 | 1001100 |
| 0101 | 0100100 |
| 0110 | 0100000 |
| 0111 | 0001111 |
| 1000 | 0000000 |
| 1001 | 0000100 |

---



## Verilog Modeling Style

**Behavioral Modeling**

The design uses:

- `always @(*)` block
- `case` statement
- Truth table based implementation

---

## Simulation Procedure

### Compile Verilog Files

```bash
iverilog -o sim bcd_to_seven_segment.v bcd_to_seven_segment_tb.v
Run Simulation
vvp sim
Generate Waveform

The testbench creates:

bcd_to_seven_segment.vcd
View Waveform
gtkwave bcd_to_seven_segment.vcd
Expected Simulation Output
BCD = 0000 Seven Segment = 0000001
BCD = 0001 Seven Segment = 1001111
BCD = 0010 Seven Segment = 0010010
BCD = 0011 Seven Segment = 0000110
BCD = 0100 Seven Segment = 1001100
BCD = 0101 Seven Segment = 0100100
BCD = 0110 Seven Segment = 0100000
BCD = 0111 Seven Segment = 0001111
BCD = 1000 Seven Segment = 0000000
BCD = 1001 Seven Segment = 0000100
Tools Used
Verilog HDL
Icarus Verilog
GTKWave
Visual Studio Code
Git Commands

After completing the project:

git add .
git commit -m "Add BCD to Seven Segment Display Converter"
git push
Result

The BCD to Seven Segment Display Converter was successfully designed, simulated, and verified using Behavioral Modeling in Verilog HDL.


After saving:

```powershell
git add .
git commit -m "Add BCD to Seven Segment Display Converter"
git push