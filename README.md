# OS Laboratory Activity 3
## Multilevel Queue and Real-Time CPU Scheduling

### Student Information
- **Name:** Kent Jesser Neri


### I. Introduction
This laboratory activity explores Multilevel Queue (MLQ) scheduling and real-time CPU scheduling algorithms — Rate Monotonic Scheduling (RMS) and Earliest Deadline First (EDF). Simulations are implemented in Python, with Gantt charts generated to visualize execution, and performance metrics analyzed.

### II. Objectives
1. Explain the operation of MLQ, RMS, and EDF scheduling algorithms.
2. Implement MLQ scheduling using Round Robin and FCFS.
3. Implement preemptive RMS and EDF scheduling simulations using Python.
4. Generate and interpret Gantt charts showing process and task execution.
5. Calculate CPU utilization, waiting time, turnaround time, and deadline compliance.
6. Create and manage a GitHub repository containing Python source code and laboratory documentation.

### III. Scheduling Algorithms
1. **Multilevel Queue Scheduling** — Ready queue divided into separate queues. Queue 1 (interactive) uses Round Robin (quantum = 2 ms) with strict priority over Queue 2 (batch), which uses FCFS.
2. **Rate Monotonic Scheduling (RMS)** — Fixed-priority preemptive algorithm. Shorter period = higher priority.
3. **Earliest Deadline First (EDF)** — Dynamic-priority preemptive algorithm. Earliest absolute deadline = highest priority.

### IV. Program Implementation
- `multilevel_queue/mlq.py` — Simulates MLQ with RR (q=2) and FCFS.
- `real_time_scheduling/rms.py` — Simulates preemptive RMS.
- `real_time_scheduling/edf.py` — Simulates preemptive EDF.

*(Note: Actual results and outputs will be added after running the simulations.)*