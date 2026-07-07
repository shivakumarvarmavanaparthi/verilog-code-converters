# Verilog Code Converters

Behavioral Verilog HDL implementations of commonly used digital code converters with simulation testbenches, developed as part of my Digital VLSI coursework and self-learning.

## Repository Contents

### 1. Binary to Gray Code Converter

* Behavioral Modeling
* Testbench
* Simulation Output
* Waveform
* Documentation

### 2. Gray to Binary Code Converter

* Behavioral Modeling
* Testbench
* Simulation Output
* Waveform
* Documentation

### 3. BCD to Excess-3 Code Converter

* Behavioral Modeling
* Testbench
* Simulation Output
* Waveform
* Documentation

### 4. BCD to Seven Segment Display Converter

* Behavioral Modeling
* Testbench
* Simulation Output
* Waveform
* Documentation

## Tools Used

* Verilog HDL
* Icarus Verilog
* GTKWave
* Visual Studio Code
* Git & GitHub

## Repository Structure

```text
Verilog-Code-Converters/
│
├── README.md
├── .gitignore
│
├── binary-to-gray/
├── gray-to-binary/
├── bcd-to-excess3/
└── bcd-to-seven-segment/
```

## Features

* Behavioral Modeling
* Simple and beginner-friendly Verilog code
* Well-commented source files
* Separate testbench for each design
* Simulation output
* Waveform generation using GTKWave
* Project-wise documentation

## How to Run

```bash
iverilog -o sim design.v design_tb.v
vvp sim
```

## Future Updates

This repository will be updated with additional code converter implementations and improved documentation as part of my Verilog HDL learning journey.

## Author

**Shiva**

Electronics and Communication Engineering (ECE)
Chaitanya Bharathi Institute of Technology (CBIT), Hyderabad
