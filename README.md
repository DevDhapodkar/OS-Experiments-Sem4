# Operating Systems Lab Experiments

This repository contains solutions and implementations for Operating Systems laboratory experiments. Each experiment focuses on different OS concepts and includes both source code and output visualizations.

## Repository Structure

### Experiment 1-3: Basic OS Concepts
- `Experiment_1/image_01.jpg`: Documentation and output
- `Experiment_2/image_01.jpg`: Documentation and output
- `Experiment_3/image_01.jpg`: Documentation and output

### Experiment 4: Process Management - Fork
- `experiment4_fork.c`: Implementation of fork system call
- `experiment4_fork.png`: Output visualization

### Experiment 5: CPU Scheduling - First Come First Serve (FCFS)
- `experiment5_fcfs.c`: Implementation of FCFS scheduling algorithm
- `experiment5_fcfs.png`: Output visualization

### Experiment 6: CPU Scheduling - Shortest Job First (SJF)
- `experiment6_sjf.c`: Implementation of SJF scheduling algorithm
- `experiment6_sjf.png`: Output visualization

### Experiment 7: CPU Scheduling - Priority Scheduling
- `experiment7_priority.c`: Implementation of Priority scheduling algorithm
- `experiment7_priority.png`: Output visualization

### Experiment 8: Deadlock - Banker's Algorithm
- `experiment8_bankers.c`: Implementation of Banker's algorithm for deadlock avoidance
- `experiment8_bankers.png`: Output visualization

### Experiment 9: Shell Programming Basics
- `experiment9_bash.c`: Basic shell programming examples
- `experiment9_screenshot.png`: Output visualization

### Experiment 10: Shell Programming Advanced
- `experiment10_bash.png`: Shell programming concepts visualization
- `experiment10_ifelse.c`: Implementation of if-else constructs in shell
- `experiment10_marks.c`: Program for handling marks using shell scripts

## How to Use

### Quick Start
1. Make sure you have GCC installed on your system
2. Run all experiments using the provided script:
   ```bash
   ./run.sh
   ```
   This will compile and execute all C programs in sequence.

### Manual Execution
1. Each experiment is contained in its own directory
2. Source code files (`.c` files) contain the implementation
3. Image files (`.png` and `.jpg`) show the output and execution results
4. To compile and run a specific experiment:
   ```bash
   cd Experiment_X
   gcc experimentX_name.c -o experimentX_name.out
   ./experimentX_name.out
   ```

## Topics Covered
- Process Management
- CPU Scheduling Algorithms
- Deadlock Avoidance
- Shell Programming
- System Calls
