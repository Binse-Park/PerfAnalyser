Introduction
============

 The PerfAnalyser is an android application to check the performance of linux scheduler in the android system.
 The PerfAnalyser include simpleperf and ftrace command to check the detail system informance to advance the performance.
 
 
Motivations
===========

The main goals of Perf Analyser are:
- to start multiple periodic threads in order to simulate a real-time periodic load.
- to measure a period to migration a task to the outside or the inside of cluster.
- to measure a period to get access to I/O and memory.
- to measure cache hits rate after periodic threads are started.
- to measure page faults rate after periodic threads are started.
- to measure cpu-cycles after periodic threads are started.
- to measure bus rate after periodic threads are started.


External Links
==============

- [Linux-PSI(pressure stall information)](https://lwn.net/Articles/763629/) for CPU, memory, and IO
- [Simpleperf](https://android.googlesource.com/platform/system/extras/+/master/simpleperf/doc/README.md)


Tool is for analysis of performance.
