# Screenshots Directory

This directory contains design schematics, symbol definitions, testbench configurations, and Spectre simulation waveforms for the CMOS 1-bit full adder project.

### Image Files Inventory
1. **`full_adder.png`** — Full adder top-level schematic (`full_adder`) implemented with 2 `xor_2` gates and 3 `nand_2` gates.
2. **`full_adder_symbol.png`** — Full adder schematic symbol (`full_adder`) with input pins ($A, B, C_{in}$), outputs ($\text{Sum}, C_{out}$), and power rails ($V_{DD}, V_{SS}$).
3. **`full_adder_tb.png`** — Full adder testbench schematic (`full_adder_tb`) showing 1.8 V DC supply, 3 pulsed sources ($A, B, C_{in}$), and 10 fF load capacitors.
4. **`full_adder_waveforms.png`** — Spectre transient simulation waveforms over 0–80 ns verifying all 8 input states and resulting outputs.
5. **`average_power.png`** — Virtuoso calculator measurement showing an average $V_{DD}$ supply power of 20.8 µW over 0–80 ns.
6. **`sum_rising_delay.png`** — Approximate $C_{in}$-to-$\text{Sum}$ rising delay measurement with markers placed near 0.9 V (M4 = 10.052353 ns, M6 = 10.167004 ns; difference = 114.651 ps ≈ 115 ps).
7. **`sum_falling_delay.png`** — Approximate $C_{in}$-to-$\text{Sum}$ falling delay measurement with markers placed near 0.9 V (M8 = 50.04918 ns, M9 = 50.21079 ns; difference = 161.61 ps ≈ 162 ps).
8. **`nand_schematic.png`** — Transistor-level schematic of the 2-input CMOS NAND gate (`nand_2`) in gpdk180.
9. **`xor_2.png`** — Schematic symbol for the 2-input XOR gate (`xor_2`).
10. **`xor_2_tb.png`** — Simulation testbench schematic for verifying `xor_2`.
11. **`load_50ff_waveforms.png`** — Spectre transient simulation waveforms (0–80 ns) of `full_adder_load_tb` under a 50 fF capacitive load per output (`CL = 50f`).
