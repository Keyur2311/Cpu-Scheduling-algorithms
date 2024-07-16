# Process Scheduling Algorithms

This repository contains a C++ program that demonstrates various process scheduling algorithms, including FCFS (First-Come, First-Served), SJF (Shortest Job First), SRTF (Shortest Remaining Time First), and RR (Round Robin).

## Getting Started

To run the program, follow these steps:

1. Clone this repository to your local machine.

   ```shell
   git clone git@github.com:Dhru08/Operating-System-Scheduling-algorithms.git
   ```

2. Navigate to the project directory.

   ```shell
   cd Operating-System-Scheduling-algorithms
   ```

3. Compile the C++ program.

   ```shell
   g++ main.cpp -o main
   ```

4. Run the executable.

   ```shell
   ./main
   ```

## Usage

1. When you run the program, it will prompt you to enter the number of processes and their arrival times and burst times. Follow the on-screen instructions to input the necessary data.

2. The program will then display a menu for selecting the scheduling algorithm you want to simulate (FCFS, SJF, SRTF, RR). Enter the corresponding number to choose an algorithm.

3. The program will simulate the selected algorithm and display the Gantt chart and various scheduling metrics, such as average turnaround time, average waiting time, average response time, and overall throughput.

4. You can repeat the process to try different scheduling algorithms or exit the program.

## Scheduling Algorithms

### FCFS (First-Come, First-Served)

This algorithm schedules processes in the order they arrive.

### SJF (Shortest Job First)

This algorithm schedules processes based on their burst times, selecting the shortest job first.

### SRTF (Shortest Remaining Time First)

SRTF is a preemptive version of SJF. It selects the process with the shortest remaining time to execute.

### RR (Round Robin)

RR is a time-sharing algorithm where each process is assigned a fixed time quanta for execution. If a process does not complete within its time quanta, it is moved to the back of the queue.

## Acknowledgments

- This code was created to demonstrate various process scheduling algorithms and can be used for educational purposes.
- Feel free to customize and extend this code for your own use.

