# Overview
## This is a pipelined processor using digital logic design. It showcases a step-by-step pipeline approach including stages such as Instruction Fetch (IF), Decode (ID), Execute (EX), Memory (MEM), and Write Back (WB).

### Components
* ALU: Arithmetic Logic Unit handling all arithmetic and logical operations.
* Branch Unit: Manages branching and control flow changes.
* Hazard Unit: Detects and manages data hazards to ensure correct instruction execution.
* Register Files: Contains registers for storing data during processing.
* Decoders: Responsible for decoding instructions and generating control signals.

### Python Scripts
* mkdecoderom.py: Generates ROM files for instruction decoding.
* mkasciirom.py: Generates ASCII ROMs.
