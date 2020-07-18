# java-performance-readings

## Chapter 1 - Introduction

There are different types of optimizations:
* Making sure the code you write is algorithmically efficient.
* Tuning the JVM to maximize the performance of your code.

Inversely, the performance of your application can get bottlenecked:
* By your database
* Other parts of the system (CPU usage, I/O latency, throughput)

## Chapter 2 - An Approach to Performance Testing

### Test a Real Application

#### Microbenchmarks
* Designed to measure a very small unit of performance.
  * E.g., the time it takes to call a synchronized method versus a unsynchronized method.
  
