# Insight Data Challenge

This project is design for accomplishing the [Insight Data Challenge](https://github.com/InsightDataScience/h1b_statistics), in which I am given a dataset that contains some information on H1B applications and need to write a program that does some data aggregation without using canned solutuions.

# How to Run

You can exucute it through **run.sh**:
```
$ run.sh
```
It will compile the source code and do the data aggregation. Or, alternatively, you may use the executable jar file ([H1bDataManipulation.jar](https://github.com/skuimsc/Insight_data_challenge/blob/master/H1bDataManipulation.jar "H1bDataManipulation.jar")) that I provided.
## Requirements
Java 8 and up. You don't need outside libraries to run this.

# Features

The program does three jobs:

 1. Read and parse a `.csv` file. As I am not allowed to use canned solutions (e.g., [OpenCSV](http://opencsv.sourceforge.net)),  I write my own CSV reader and writer.
 2. Count the number of entries based on a given counting field. 
 3. Sort the number of entries and write the largest ten into a separate `.csv` file.

Currently, the program is coded to fit the exact requirements of the challenge, but obviously it can be extended should the need arise.

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE0NTA4NDkxNzgsLTc1NzA1ODU4MCw5MD
U5NzAzMDgsMzIyMTgwODgsLTgzODQxODQzMSw0NTQ2ODMwMywt
MTI0MDA1NDM4MCwtMTQ5MDk4MzU3MSwxMjAxODE5MjgsNTg0MD
A2MTM4LC0xNTU5MzIxNzU3LC0xNzQzNDY0NDY5XX0=
-->