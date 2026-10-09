# Assignment3
Discrete-Event CPU Scheduling Simulator
## Link to main.cpp and README.md
https://github.com/juanrsanchez2/Assignment3/blob/e6ae864388f0ef665c850d8d6566dc1a127b5aba/main
https://github.com/juanrsanchez2/Assignment3/blob/e6ae864388f0ef665c850d8d6566dc1a127b5aba/README.md

## 5 CPU Scheduling Simulator
The main purpose of the program is to show the difference between 5 different CPU scheduling simulators. It will use the exact same workload of 1000 processes across all 5 CPU scheduling simulators to ensure accuracy of evaluation metrics

The 5 Schedulers:
- First Come First Served (FCFS)
- Shortest Job First (SJF)
- Shortest Remaining Time First (SRTF)
- Round Robin (RR)
- Highest response Ratio Next (HRRN)

## Performance Metrics
The following performance metrics will be calculated for all 5 schedulers:

- <ins>**Total Completion Time:**</ins> The total time required to finish all 1000 processes
- <ins>**Average Turnaround Time:**</ins> The average time between a process's arrival and completion
- <ins>**Average Waiting Time:**</ins> The average time a process spends waiting in the ready queue
- <ins>**Average Response Time:**</ins> The average time of a process's arrival and its first execution
- <ins>**CPU Utilization:**</ins> The percentage of time the CPU spends executing processes
- <ins>**System Throughput:**</ins> The number of processes completed per second
- <ins>**Average Ready Queue Length:**</ins> The average number of processes waiting in the ready queue


## Simulation Results
Below is an example of what the summary table will look like. This is a data from a previous run of the program.

### CS 3360 Assignment 3 Performance Summary (1000 Processes)

| Metric | FCFS | SJF | SRTF | RR (q=2.0) | HRRN |
|---|---:|---:|---:|---:|---:|
| Total Completion Time (s) | 1007.185 | 1007.185 | 1007.185 | 1007.185 | 1007.185 |
| Average Turnaround Time (s) | 273.310 | 95.380 | 94.695 | 269.351 | 120.011 |
| Average Waiting Time (s) | 272.303 | 94.373 | 93.688 | 268.344 | 119.004 |
| Average Response Time (s) | 272.303 | 94.373 | 92.656 | 231.565 | 119.004 |
| CPU Utilization (%) | 99.972 | 99.972 | 99.972 | 99.972 | 99.972 |
| System Throughput (proc/s) | 0.993 | 0.993 | 0.993 | 0.993 | 0.993 |
| Avg. Ready Queue Length | 270.360 | 93.700 | 93.019 | 266.430 | 118.155 |


