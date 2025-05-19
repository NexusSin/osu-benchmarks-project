# OSU Micro-Benchmarks ReFrame Tests
This repository contains ReFrame regression tests for measuring latency and bandwidth using OSU Micro-Benchmarks (v7.2) on ULHPC Iris and Aion clusters.

## Setup Instructions
1. Clone the repository: `git clone <repository-url>`
2. Load required modules: `module load env/testing/2023b system/hwloc`
3. Run tests: `reframe -c reframe_tests/ -r`

## Project Structure
- `reframe_tests/`: ReFrame test scripts for latency and bandwidth.
- `docs/`: Performance analysis report and test case documentation.
- `results/`: Test outputs and graphs.

## Expected Results
- Aion: Latency ~2.3 μs (intranode), ~3.9 μs (internode), Bandwidth ~12,000 MB/s
- Iris: [To be determined]
