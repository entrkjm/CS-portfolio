# OS memory and process management

# index

## Process and Process Scheduling
### What is process?
In computer science, a process refers to the active execution of a computer program by one or multiple threads. 

Scheduling plays a crucial role across various computing environments, particularly in determining which programs will utilize the CPU. 
The Operating System (OS) is responsible for managing this task, offering diverse configurations for program execution.

![image](/OSimages/Process-Scheduler.png)

### Process Scheduling
Process scheduling is the activity of the process manager that handles the removal of the running process from the CPU and the selection of another process based on a particular strategy.

Process scheduling is an essential part of a Multiprogramming operating system. Such operating systems allow more than one process to be loaded into the executable memory at a time and the loaded process shares the CPU using time multiplexing.

### Preemptive and non-preemptive scheduling
- Non-preemptive: In this case, a process’s resource cannot be taken before the process has finished running. When a running process finishes and transitions to a waiting state, resources are switched.
  - First Come First Serve(or FIFO), Shortest Job First(SJF) and HRN
- Preemptive: In this case, the OS assigns resources to a process for a predetermined period. The process switches from running state to ready state or from waiting for state to ready state during resource allocation. This switching happens because the CPU may give other processes priority and substitute the currently active process for the higher priority process.
  -  Round Robin (RR), Shortest Remaining Time First (SRT), Priority (preemptive version)


# Reference
[Link](https://www.geeksforgeeks.org/preemptive-and-non-preemptive-scheduling/)
