# ⚙️ Operating Systems

Welcome to the **Operating Systems** section of my digital garden. This folder contains in-depth notes of the complex topics regarding Operating Systems

---

## 📚 Topics Covered 

The material covers most of the world behind Operating Systems, in particular topics such as:

* **1. Introduction to OS**: Introductory material on Operating Systems, covering the core concepts: OS roles, resource management, processes, memory hierarchy, I/O and interrupts, system calls, kernel architectures (monolithic, microkernel, modular), multitasking, multiprogramming, protection and security, virtualization, and modern hardware interactions.

* **2. Process and Threads**: Material covering processes and threads in modern operating systems: process structure, memory layout (text, data, heap, stack), process states, PCB, scheduling, multiprogramming, time‑sharing, context switching, process creation and termination, IPC (shared memory, message passing, sockets, RPC), synchronization, producer–consumer, thread models (user‑level, kernel‑level, many‑to‑one, one‑to‑one, many‑to‑many), multithreading, multicore execution, Pthreads, Java threads, Windows threads, signals, thread cancellation, and thread‑specific data.

* **3. CPU Scheduling and Process Synchronization**: Material focused on CPU scheduling and process synchronization: CPU bursts and I/O bursts, ready queues, dispatcher, scheduling algorithms (FCFS, SJF, SRTF, Round Robin, Priority, Multilevel Queue, MLFQ), multiprocessor and multicore scheduling, load balancing, processor affinity, real‑time scheduling (RMS, EDF), event and interrupt latency, critical‑section problem, mutual exclusion, Peterson’s solution, mutexes, semaphores, monitors, condition variables, and synchronization mechanisms for concurrent processes and threads.

* **4. Deadlocks**: Material focused on deadlocks and resource management in operating systems: deadlock definition, waiting states, circular dependencies, liveness failures, livelock, Coffman’s conditions, resource‑allocation graphs, cycle detection, deadlock prevention (mutual exclusion, hold‑and‑wait, no‑preemption, circular wait), avoidance strategies (safe states, safe sequences, claim edges), Banker’s Algorithm, deadlock detection with wait‑for graphs and multi‑resource algorithms, and recovery techniques (process termination, resource preemption).

* **5. Memory Management**: Material covering memory management in modern operating systems: memory as a byte‑addressable array, instruction execution and address flow, CPU–memory interaction, cache hierarchy, base/limit registers for protection, program loading and address binding, logical vs physical addresses, MMU translation, dynamic loading and dynamic linking (DLLs), contiguous allocation, variable partitions, fragmentation, paging (frames, page tables, logical address structure), TLB and effective access time, protection bits, shared reentrant code, hierarchical paging, hashed and inverted page tables, swapping and paged swapping, and memory management strategies in mobile OSes.
* **6. Virtual Memory**: Material starting from the key idea of separating logical from physical address spaces, the notes walk through demand paging and page fault handling, then analyse the main page replacement algorithms (FIFO, OPT, LRU and its approximations, Clock, enhanced Clock) with worked examples and performance calculations. The discussion continues with frame allocation strategies (equal, proportional, local vs global replacement) and NUMA-aware allocation. The final sections address thrashing, its relationship with CPU utilisation, and the working-set and page-fault frequency models used to prevent it, closing with an in-depth treatment of kernel memory allocation via the Buddy System and the Slab Allocator.
* **7. Mass-Storage Structure & I/O Systems**
* **8. File System**

---

## 🛠️ Technical Details
* **Format:** PDF ( compiled from LaTeX )
* **Approach:** Understanding how a OS works from the ground up

## 🚧 Status
This folder is constantly updated with new files and / or changes of readme or other files
