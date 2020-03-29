# Advanced Operating System - Project 1

## Student information
Name: Bao Dien Quoc Nguyen
R#: 11660127

## Instructions
![Results](results.png)
![Running steps](Running.gif)

[Link to the code](https://texastechuniversity-my.sharepoint.com/:u:/g/personal/bao_d_nguyen_ttu_edu/EaUmMKaBAq9IuzEV8l0SqccB57KqUjnnuNoSJviChP5Xwg?e=UJXIEu)

#### Step 1:
Download and open the source code by [PyCharm CE](https://www.jetbrains.com/pycharm/download/#section=mac)

#### Step 2:
Change paths to graph1.txt for reading graph input in Algorithm1.py, Algorithm2.py, and BothAlgorithms.py
![read](Path_to_graph_file.png)

and paths to the location for saving files in these three codes
![save](Path_to_save_file.png)

Change paths to saving files above in drawResult.py

#### Step 3:
Run in order: Algorithm1.py, Algorithm2.py, BothAlgorithms.py, and drawResult.py.

## Results
### Tables
[Prim algorithm](PrimAlgorithm.csv)

[Kruskal algorithm](KruskalAlgorithm.csv)

[Both algorithms](BothAlgorithms.csv)

### CPU usage as percentage
![CPU](CPU_usage.png)

### Memory usage as percentage
![Memory](Memory_usage.png)

### Hard drive usage in kB
![Hard drive](Hard_drive_usage.png)

### Resident set size in Bytes
![RSS](RSS.png)

### Number of page faults
![page faults](Page_faults.png)

### Comments
CPU usage and hard drive usage are equal for three running conditions.

Kruskal algorithm requires less memory resource than Prim algorithm.

The memory resource for running both algorithms in one process is less than the sum of that for running each algorithms in two separately process.

There is no virtual memory in all three running conditions
