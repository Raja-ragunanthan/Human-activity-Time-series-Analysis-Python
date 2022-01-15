# Time_series_Analysis_Python

Project 3
The objective of project 3 is to extract time series features for human activity
monitoring.
Dataset
The following link provides human activity data for 15 subjects. Click on each subject to
access the time series data. For this project consider accelerometer data for all the 15
subjects for walking, running, climbing up and climbing down
Task 1
1. Apply natural visibility graph (NVG) and horizontal visibility graph (HVG) to the
aforementioned data
2. Compute average degree, network diameter, and average path length
3. For the above computations select sample size of 1024 data points ( from 1000
to 2024) for each of the 15 time series
4. Tabulate all the results
5. Generate scatter plots: average degree vs network diameter and color the points
according to walking and running (do this for each accelerometer signal and
each method (HVH and NVG))
6. Generate scatter plots: average degree vs network diameter and color the points
according to climbing up and climbing down (do this for each accelerometer
signal and each method (HVH and NVG))
Sample output table
Method Subject Accelero
meter
axis
Average
degree
Network
diameter
Average
path
length
Activity
HVG or
NVG
1 to 15 X or y or z Walking
or running
or
climbing
up or
climbing
down
Task 2
1. Compute permutation entropy and complexity for the aforementioned data.
Consider the accelerometer data in all three directions
2. Vary the following parameters
Embedded Dimension 3, 4, 5, 6
Embedded Delay 1, 2, 3
Signal length 1024, 2048, 4096
3. Generate scatter plots: permutation entropy vs complexity and color the points
according to walking and running (for signal length =4096, embedded delay = 1,
and embedded dimension = 3, 4, 5, 6, and all three accelerometer directions)
4. Generate scatter plots: permutation entropy vs complexity and color the points
according to climbing up and climbing down (for signal length =4096, embedded
delay = 1, and embedded dimension = 3, 4, 5, 6, all three accelerometer
directions)
Sample output table
Subject Accelero
meter
axis
Signal
length
Dimensi
on
Delay Permuta
tion
entropy
Complex
ity
Activity
1 to 15 x or y or
z
1024 or
2048 or
4096
3 or 4 or
5 or 6
1 or 2 or
3
Walking
or
running
or
climbing
up or
climbing
down
Submission Format
1. Submit all the solutions as a python notebook
2. This is a group effort
3. Only one member from each group needs to submit the solution
4. Submit the solution by Dec 16
