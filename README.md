# VHDL Counter Overflow Bug

This repository demonstrates a common bug in VHDL code: counter overflow.  The `buggy_counter.vhdl` file contains a counter that lacks proper handling of the maximum count value, leading to unpredictable behavior once the counter reaches 15.

The `fixed_counter.vhdl` demonstrates how to fix the bug.