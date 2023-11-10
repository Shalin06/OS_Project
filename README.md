# Concurrent_process_analysis_using_Gantt_chart

## System Monitor and Gantt Chart Tool

This is a Python application for monitoring system resources and displaying a Gantt Chart for running processes.

### Overview

- The System Monitor provides real-time information about the total CPU and memory usage, as well as a list of the top 100 running processes with details such as PID, Process Name, CPU Usage, and Memory Usage. You can also sort the processes based on CPU or memory usage. Additionally, you can select processes and reset the selection.

- The Gantt Chart displays a visual representation of running processes over time. Each process is represented as a bar on the chart, and you can interact with them by right-clicking to kill a process or view its details. The chart is updated in real-time to reflect changes in the running processes.

### Prerequisites

- Python 3.x
- PyQt5
- pyqtgraph
- sqlite3
- psutil

### Getting Started

1. Clone this repository to your local machine:


   #### `git clone https://github.com/your-username/system-monitor-gantt-chart.git`

2. Install the required dependencies using pip:


   #### `pip install PyQt5 pyqtgraph psutil`

3. Run the application:

   #### `python system_monitor.py`


### Features
#### System Monitor

    Real-time display of total CPU and memory usage.
    List of the top 100 running processes with PID, Process Name, CPU Usage, and Memory Usage.
    Sort processes by CPU or memory usage.
    Select processes and reset the selection.
    Details of each process, including PID, Name, Start Time, CPU%, Mem%, and Status.

#### Gantt Chart

    Visual representation of running processes as bars over time.
    Right-click on a process to kill it or view its details.
    Real-time updates to reflect changes in running processes.

### Contributors

- Shalin Jain
- Shashwat Roy
- Pranav Pant
- Sameer Sharma

Enjoy monitoring your system and visualizing process data with this System Monitor and Gantt Chart tool!