# Dual-Clock Asynchronous FIFO (Verilog)

## Objective
Design a FIFO buffer to safely transfer data between asynchronous clock domains.

## Design
Implemented Gray-coded read/write pointers with synchronizer stages to mitigate metastability.

## Verification
Functional verification performed using simulation testbenches covering full, empty, and boundary conditions.

## Status
RTL verified via simulation.
