# Gray to Binary Code Converter

## Aim

To design and simulate a 4-bit Gray to Binary Code Converter using Behavioral Modeling in Verilog HDL.

## Description

Gray code is a binary numeral system in which two successive values differ by only one bit. This project converts a 4-bit Gray code input into its equivalent Binary code using Behavioral Modeling with a `case` statement.

## Files

* `gray_to_binary.v` — Verilog design file
* `gray_to_binary_tb.v` — Testbench
* `output.txt` — Simulation output
* `waveform.png` — GTKWave output

## Truth Table

| Gray | Binary |
| ---- | ------ |
| 0000 | 0000   |
| 0001 | 0001   |
| 0011 | 0010   |
| 0010 | 0011   |
| 0110 | 0100   |
| 0111 | 0101   |
| 0101 | 0110   |
| 0100 | 0111   |
| 1100 | 1000   |
| 1101 | 1001   |
| 1111 | 1010   |
| 1110 | 1011   |
| 1010 | 1100   |
| 1011 | 1101   |
| 1001 | 1110   |
| 1000 | 1111   |

## Simulation

Compile:

```bash
iverilog -o sim gray_to_binary.v gray_to_binary_tb.v
```

Run:

```bash
vvp sim
```

View Waveform:

```bash
gtkwave gray_to_binary.vcd
```

## Tools Used

* Verilog HDL
* Icarus Verilog
* GTKWave
* Visual Studio Code

## Result

The Gray to Binary Code Converter was successfully designed, simulated, and verified using Behavioral Modeling in Verilog HDL.
