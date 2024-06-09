**RISCV-Core Implementation**
This repository contains the source code for a **fully pipelined RISCV32I core.**
The core supports a comprehensive range of instruction types, including I-Type, B-Type, R-Type, S-Type, U-Type, and J-Type. 
Key features of the implementation include:
1. *5-Stage Pipeline Architecture* : The core is built using a five-stage pipeline comprising Fetch, Decode, Execute, Memory, and Writeback stages, ensuring efficient instruction processing.
2. *Seamless Inter-Stage Communication*: Interfaces are meticulously designed between each stage to facilitate the seamless transfer of values, enhancing pipeline efficiency and coherence.
3. *Branch Detection and Bypassing*: The core incorporates branch detection mechanisms along with MX, WX, and WM bypassing features to minimize pipeline hazards and improve execution flow.
4. A stalling mechanism is implemented using intermediate signals, effectively managing pipeline stalls and ensuring smooth operation under various conditions.
5. Optimized Power Strategy: The design is an attempt to reduce bit movement and adopting a strategy aimed at minimizing dynamic power consumption








