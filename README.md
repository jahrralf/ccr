ccr
===

Measurement and Modelling of Shared Memory Systems

  * Synthetic Benchmark: benchmark.zip (with password from paper)
  * Result Analysis: ComSyncEstimation.zip (with password from paper)
  
(1) Please run the benchmark on the target platform. It requires gcc and make as well as some standard libraries. Capture its console output for further processing.

(2) Start the analysis tool. It is a Netbeans java project relying on jMetal, which is delivered as source code. Start the tool and past the output of the benchmark to the window. Please the button and wait watching the console output of the program to finish. The last lines after a line starting with "DATA" is your result with the following schema: THREADS ERROR_IN_PERCENT for C_READ C_EXECUTE C_WRITE OVERHEAD

The source code will be released under a suitable open-source license after acceptance of the paper.
