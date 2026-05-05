# Serial-to-Parallel Converter

## Files
- `serial_to_parallel.v`    – Main Verilog module (8-bit shift register design)
- `serial_to_parallel_tb.v` – Testbench (7 test vectors, all passing)
- `serial_to_parallel.vcd`  – GTKWave waveform dump (from simulation)
- `report.docx`             – Academic report

## How to Simulate
```bash
# 1. Compile
iverilog -o sim_out serial_to_parallel_tb.v serial_to_parallel.v

# 2. Run simulation
vvp sim_out

# 3. View waveforms
gtkwave serial_to_parallel.vcd
```

## Requirements
- iverilog (Icarus Verilog): sudo apt install iverilog
- gtkwave:                   sudo apt install gtkwave
