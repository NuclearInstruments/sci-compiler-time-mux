#Handling Time-Multiplexed (TM) Signals in Sci-Compiler 

In high-performance data acquisition systems such as the V2730 board, signals are provided in a Time-Multiplexed (TM) format to handle sampling rates exceeding 200 MHz. This application note demonstrates how to use SciCompiler IP blocks—specifically TM SPLITTER and TM PACKER—to split the TM data into parallel bit-vector signals, apply a scaling factor (less than 1) to each slice, and then reassemble the TM signal for further DSP operations.