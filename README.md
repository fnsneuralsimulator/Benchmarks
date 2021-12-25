# Benchmarks

Through these packages the user will be able to reproduce the benchmark networks used in the provisional version of the paper "FNS: an event-driven spiking neural network based on the LIFL model" (under review):

- BENCHMARK_A - 1 node
- BENCHMARK_B (Default Mode Network-inspired long range connectivity) - 14 Nodes

In order to start the simulation and obtain the spiking and postsynaptic activity (firing_r.CSV and burning_r.CSV), the following "experiment command" can be used:

.\start.bat -BENCHMARK_x -r (Windows)

or

$ ./start BENCHMARK_x -r (Linux)


the simulation output will be generated in the folder FNS/BENCHMARK_x/output.
 
We recommend to set the JAVA 'heap size' before starting the simulations, to manage memory usage/problems. Please refer to the reference manuscript and to the FNS user manual for additional information:

https://docs.google.com/document/d/1TJ5vWIBHW81IaySHM5b81JeZehEwZXo8hFj2SIrKnKY/export?format=pdf
