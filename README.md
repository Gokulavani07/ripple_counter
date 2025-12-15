AIM:

To implement 4 Bit Ripple Counter using verilog and validating their functionality using their functional tables

SOFTWARE REQUIRED:

Quartus prime

THEORY

4 Bit Ripple Counter

A binary ripple counter consists of a series connection of complementing flip-flops (T or JK type), with the output of each flip-flop connected to the Clock Pulse input of the next higher-order flip-flop. The flip-flop holding the least significant bit receives the incoming count pulses. The diagram of a 4-bit binary ripple counter is shown in Fig. below.

<img width="722" height="324" alt="Screenshot 2025-12-15 153439" src="https://github.com/user-attachments/assets/a8a6f875-263a-4286-ad25-1ab0505ef9e4" />


In timing diagram Q0 is changing as soon as the negative edge of clock pulse is encountered, Q1 is changing when negative edge of Q0 is encountered(because Q0 is like clock pulse for second flip flop) and so on.



<img width="493" height="628" alt="Screenshot 2025-12-15 153450" src="https://github.com/user-attachments/assets/e6fff0c8-c8bc-4fe1-a1d2-9ed0e9e2863c" />


Procedure

/* write all the steps invloved */

PROGRAM

/* Program for 4 Bit Ripple Counter and verify its truth table in quartus using Verilog programming.

Developed by:GOKULAVANI.R

RegisterNumber:25017080 */

RTL LOGIC FOR 4 Bit Ripple Counter

TIMING DIGRAMS FOR 4 Bit Ripple Counter

RESULTS
