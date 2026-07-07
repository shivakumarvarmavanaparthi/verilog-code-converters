# Binary to Gray Code Converter using Verilog HDL

## Aim

To design and simulate a 4-bit Binary to Gray Code Converter using Behavioral Modeling in Verilog HDL.

## Theory

Gray code is a binary numeral system in which two successive values differ by only one bit. It is widely used in digital electronics to reduce errors during bit transitions.

In this project, the converter is implemented using **Behavioral Modeling** with a `case` statement that directly represents the truth table.

## Truth Table

| Binary | Gray |
| ------ | ---- |
| 0000   | 0000 |
| 0001   | 0001 |
| 0010   | 0011 |
| 0011   | 0010 |
| 0100   | 0110 |
| 0101   | 0111 |
| 0110   | 0101 |
| 0111   | 0100 |
| 1000   | 1100 |
| 1001   | 1101 |
| 1010   | 1111 |
| 1011   | 1110 |
| 1100   | 1010 |
| 1101   | 1011 |
| 1110   | 1001 |
| 1111   | 1000 |

## Project Files

* `binary_to_gray.v` – Behavioral Verilog module
* `binary_to_gray_tb.v` – Testbench
* `output.txt` – Simulation output
* `waveform.png` – GTKWave waveform screenshot

## Software Used

* Visual Studio Code
* Icarus Verilog
* GTKWave

## How to Run

```bash
iverilog -o sim binary_to_gray.v binary_to_gray_tb.v
vvp sim
```

## Applications

* Rotary encoders
* Analog-to-Digital Converters (ADCs)
* Error reduction in digital communication
* Position sensors

## Author

**Shiva**
ECE Student, Chaitanya Bharathi Institute of Technology (CBIT)
