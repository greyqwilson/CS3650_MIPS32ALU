# CS3650_MIPS32ALU
This is a bare bones implementation of a MIPS32 ALU with a limited set of operations. 
This implementation was made for CS 3650 using code from https://electrobinary.blogspot.com/2021/02/alu-design-in-verilog-using-mips.html
The purpose of this program was to familiarize ourselves with verilog and gain a deeper understanding of an ALU. 
Things and ideas learned were shared with a partner on this project.

Greyson W.:
There are many analogues between a GPL software language and an HDL that are implemented in a completely different way due to the
all-at-once behavior of a circuit. Specifically, I learned proper (and basic) syntax of Verilog, how to compile it to get waveforms,
and a liberal use of boolean logic.

Ryley G.:
Understanding the difference between a combinational circuit and a sequential circuit was definitely helpful in understanding how Verilog
functions as knowing when memory is required for designs. An interesting part of this was also learning the use of the 'always' block
within the program and how the statements within it will execute sequentially.

A single-cycle implementation of MIPS16 and MIPS32 was also made with this ALU: 
https://github.com/greyqwilson/MIPS32Processor_PreOwned


This code was originally created in October 2022.  
