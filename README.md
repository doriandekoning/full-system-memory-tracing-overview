# Full system after-cache memory tracing overview

The code used for my thesis titled "Full-system After-cache Memory Tracing for Multi-core Systems using a Distributed Cache Simulator" (todo add link to tudelft repository) can be found here:

- A modified version of QEMU capable of tracing all memory accesses made by the guest including instruction fetches https://github.com/doriandekoning/qemu
- A program to analyse gem5 and QEMU and convert them to a format used by the functional cache simulator: https://github.com/doriandekoning/memory-trace-analyser
- A distributed functional cache simulator using OpenMPI: https://github.com/doriandekoning/functional-cache-simulator 
- A tool to automate running QEMU and the functional cache simulator: https://github.com/doriandekoning/run-qemu-cache-distributed-sim
