# Verilog Practice — Combinational Logic

A collection of Verilog modules I wrote and verified while learning digital design.
I started learning Verilog in September 2026 and am building toward VLSI roles in
Digital Design, Verification, and DFT.

## What is here

| Folder | Topic | Modules | Status |
|--------|-------|---------|--------|
| 01_logic_gates | Basic gates | and, or, nand, nor, xor, xnor | Added |
| 02_buffers | N-bit buffers | copy4, copy8, copy16 | Coming soon |
| 03_multiplexers | MUXes | mux2to1, mux2to1_4bit, mux4to1 | Coming soon |
| 04_decoder_encoder | Decoder / encoder | decoder2to4, encoder4to2 | Coming soon |
| 05_adders | Adders | half_adder, full_adder | Coming soon |

All modules are combinational. I am currently learning sequential logic
(flip-flops, counters, shift registers) and FSMs.

## How I verify

Each module was simulated in EDA Playground using Icarus Verilog. I checked
outputs against truth tables and inspected waveforms. Testbenches were written
by me from scratch.

## Skills demonstrated

- Verilog module structure and port declarations
- Dataflow modelling with `assign`
- Behavioural modelling with `always @(*)` and `case`
- Vectors, binary literals, MSB/LSB
- Ternary operator
- Rule: `assign` → `wire`, `always` → `reg`
- Testbench writing: stimulus, `$monitor`, `$dumpvars`, `$finish`

## What I have not covered yet

- Sequential logic (flip-flops, counters, shift registers)
- Finite state machines
- SystemVerilog
- UVM
- DFT implementation

## Tools

- EDA Playground
- Icarus Verilog
