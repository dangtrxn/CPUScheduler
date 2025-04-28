## CPU-Simulator GUI
A grahical user interface application with these components: CPU Simulator, QR code and Barcode Generator. This project implements and compares multiple CPU scheduling algorithms within a GUI application. This version is an extension which includes two new algorithms, Shortest Remaining Time First and Multi-Level Feedback Queue.

Performance was evaluated based on:
- Average Waiting Time (AWT)
- Average Turnaround Time (ATT)
- CPU Utilization
- Throughput

## Algorithms Implemented

- First-Come-First-Serve (FCFS)
- Shortest Job First (SJF)
- Priority Scheduling
- Round Robin (Quantum = 2)
- **Shortest Remaining Time First (SRTF)** (New)
- **Multi-Level Feedback Queue (MLFQ)** (New)

## Usage

```
Please install the font: "IDAutomationHC39M Free Version". You can find it in the project root folder.
```

## Key Learnings

- SRTF is optimal for minimizing average waiting and turnaround time but introduces complexity with preemption.
- MLFQ balances responsiveness and fairness.
- GUI-based system integration enhances user experience for the algorithm simulation.

## License
This project is licensed under the terms of the [MIT license](https://choosealicense.com/licenses/mit/).
