# Vending-Machine-

This project is a Verilog-based implementation of a finite state machine (FSM) for simulating the functionality of a simple vending machine. The module has three states (s0, s1, s2) representing different levels of credit based on the user's coin inputs (00, 01, 10). It determines the appropriate state transition, dispenses an item (out), and calculates any change (change) when the required credit is met or exceeded. The design operates synchronously with a clock signal (clk) and includes a reset input (rst) for reinitialization.

Key Features:

State-Based Operation: Efficiently handles three states to process transactions and manage credit.
Dynamic Inputs: Supports multiple coin inputs and adapts state transitions accordingly.
Output Management: Dispenses items and returns the correct amount of change when applicable.
Synchronous Reset: Ensures the module initializes to the base state when reset is triggered.
Compact Design: Easy to integrate with larger systems for hardware simulation or FPGA deployment.
This project is a practical example of FSM design, ideal for applications in digital design learning, simulation, and embedded system development.
