# Configurable FIFO Buffer in Verilog

This project implements a parameterized FIFO (First-In-First-Out) buffer in Verilog with configurable data width and depth. It includes full and empty flag support and is suitable for SoC/RTL digital design verification.

##  Features
- Synchronous FIFO with configurable depth and width
- Real-time `full` and `empty` flag status
- Simulated and verified using testbench on EDA Playground
- Easy integration into larger RTL designs

##  Files
- `fifo.v`: FIFO RTL module
- `fifo_tb.v`: Testbench for simulation

##  How to Run
You can run this on [EDA Playground](https://edaplayground.com) or locally using:
```sh
iverilog -o fifo_tb fifo.v fifo_tb.v
vvp fifo_tb
