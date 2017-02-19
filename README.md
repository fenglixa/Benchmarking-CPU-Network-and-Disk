# Benchmarking-CPU-Network-and-Disk
CPU: Measure the processor speed, in terms of floating point operations per second (Giga FLOPS) and integer operations per second (IOPS), at varying levels of concurrency (1 thread, 2 threads, 4 threads).
Disk: Measure the disk speed. Hint: there are multiple ways to read and write to disk,explore the different APIs, and pick the fastest one out of all them. The parameter space should include read operations, write operations,sequential access, random access, varying block sizes (1B, 1KB, 1MB), and varying the concurrency (1 thread, 2 threads). The metrics you should be measuring are throughput (MB/sec) and latency (ms).
Network: Measure the network speed between 2 instances. The parameter space should include the TCP protocol stack, UDP, varying
packet/buffer size (1B, 1KB, 64KB), and varying the concurrency (1 thread & 2 threads). The metrics you should be measuring are throughput (Megabits per second, Mb/sec) and latency (ms).
