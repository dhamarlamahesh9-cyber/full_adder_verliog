# Full Adder using Verilog HDL

## Description
This project implements a 1-bit Full Adder using Verilog HDL. A Full Adder adds three 1-bit binary inputs (A, B, and Cin) and produces two outputs: Sum and Carry Out (Cout).

## Truth Table

| A | B | Cin | Sum | Cout |
|---|---|-----|-----|------|
| 0 | 0 | 0 | 0 | 0 |
| 0 | 0 | 1 | 1 | 0 |
| 0 | 1 | 0 | 1 | 0 |
| 0 | 1 | 1 | 0 | 1 |
| 1 | 0 | 0 | 1 | 0 |
| 1 | 0 | 1 | 0 | 1 |
| 1 | 1 | 0 | 0 | 1 |
| 1 | 1 | 1 | 1 | 1 |

## Tools Used
- Verilog HDL
- Visual Studio Code
- Icarus Verilog
- Surfer Waveform Viewer

## Files
- full_adder.v
- full_adder_tb.v
- full_adder.vcd
- waveform.png

## Result
The simulation verified all possible input combinations, and the waveform matched the expected Full Adder outputs.