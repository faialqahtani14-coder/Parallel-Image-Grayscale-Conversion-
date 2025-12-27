 # Parallel Image Grayscale Conversion
This repository contains the implementation and experiments for a project on
parallel RGB-to-grayscale image conversion using Python.
 we offer Parallel Image Grayscale Conversion, which uses data parallelism to speed up the grayscale converting process.
 The objective is to emphasize the function of parallelization in contemporary image processing systems and show how it dramatically boosts performance when compared to  sequential execution


## Repository Contents
- Sequential implementation of grayscale conversion
- Parallel implementation with race condition
- Parallel implementation with synchronization (Lock) to ensure correctness

Execution time measurement and performance evaluation are integrated directly
within the code using Python’s time.perf_counter(). Different image sizes and
parallel configurations are tested to study performance and scalability.

This repository is provided as a reference for learners interested in parallel
programming, race conditions, and synchronization techniques.

