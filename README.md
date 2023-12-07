# Workload optimized SOC – baseline
# Firmware simulation

## 1. Matrix Multiplication
```sh
cd ~/caravel-soc_fpga-lab/lab-wlos_baseline/testbench/counter_la_mm
source run_clean
source run_sim
```
## 2. Quick Sort
```sh
cd ~/caravel-soc_fpga-lab/lab-wlos_baseline/testbench/counter_la_qs
source run_clean
source run_sim
```
## 3. FIR
```sh
cd ~/caravel-soc_fpga-lab/lab-wlos_baseline/testbench/counter_la_fir
source run_clean
source run_sim
```
## 4. ISR – UART/rx & t
```sh
cd ~/caravel-soc_fpga-lab/lab-wlos_baseline/testbench/uart
source run_clean
source run_sim
```

# Verification on FPGA
## Synthesis and Generate bitstream(Ubuntu)
```sh
cd ~/caravel-soc_fpga-lab/lab-wlos_baseline/vivado
source run_vivado
```
