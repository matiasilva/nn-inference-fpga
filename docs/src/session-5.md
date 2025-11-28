# Session 5: FPGAs

FPGAs consists of a sea of look-up tables, each representing some logic function
like ‘x OR y AND z’ and some programmable routing. Using a hardware description
language (HDL) like SystemVerilog we can describe the behavior we want our FPGA
to execute and the synthesis tool will convert this into thousands of logic
functions, which we can then program onto the FPGA.
