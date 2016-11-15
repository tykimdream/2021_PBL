# Malware-Detection-using-Machine-Learning
Malware detection example using machine learning classification algorithms.

** Check the recent commits in order to see the example with the real data examples collected on Windows OS. **
## Data
Data is extracted from the proc virtual file system. data.csv file contains the process samples from Ubuntu Desktop environment.
For now some of the processes are labeled as malware even though they are legit.

## Features
* RUSER: Real user id. Textual or decimal representation.
* PPID:  Select parent process by process id.
* UID: User id number
* PID: User id
* PGRP: Process group id
* %CPU: CPU utilization of the process in ##.# format
* %MEM: Memory usage of the process
* VSZ: Total virtual memory size in bytes
* TIME: Total accumulated CPU utilization time for the process
* SIZE: Memory size in kilobytes
* legitimate: Labeled as 1 if the process is legit. Labeled as 0 if the process is malware.

## TO-DO List
* data.csv file will be updated with real malware samples.
* Data extraction script will be pushed to the repository
* Feature selection algorithms will be applied for better results.
* More relevant features may be extracted from the kernel.
* A script will be written to do the whole process in real time at the user space.
* A kernel driver will be written to do the whole process in real time at the kernel level.
