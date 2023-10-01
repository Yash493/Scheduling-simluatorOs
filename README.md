#CPU Scheduling Simulator
Introduction

The CPU Scheduling Simulator is a Java program with a graphical user interface (GUI) designed to simulate different CPU scheduling algorithms. This project provides a hands-on experience and visual representation of various CPU scheduling algorithms, including Non-Preemptive Priority Scheduling, Non-Preemptive Shortest Job First (SJF), Shortest-Remaining Time First (SRTF), and a custom algorithm called AGAT Scheduling.

Overview

Scheduling is a fundamental function of operating systems, and CPU scheduling plays a vital role in determining which processes run when there are multiple runnable processes. This program aims to demonstrate the impact of different CPU scheduling algorithms on resource utilization and overall system performance. Additionally, it addresses the issue of process starvation for some scheduling algorithms.

Features

The CPU Scheduling Simulator provides the following features:
Supported Scheduling Algorithms
1.Non-Preemptive Priority Scheduling with context switching:
  Ensures the solution to the starvation problem.
2.Non-Preemptive Shortest Job First (SJF) with context switching:
  Solves the starvation problem.
3.Shortest-Remaining Time First (SRTF) Scheduling with context switching:
  Solves the starvation problem.
4.AGAT Scheduling:
  Implements a custom algorithm that combines Round Robin (RR) CPU scheduling with a unique factor based on priority, arrival time, and remaining service time.
  Each process in AGAT scheduling has a different quantum.
  Implements a non-preemptive phase for each process until reaching approximately 40% of the quantum, after which it becomes preemptive.
  Provides the ability to replace a process with the best (least) AGAT factor, if available, after the non-preemptive phase ends.
