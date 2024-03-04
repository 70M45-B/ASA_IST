# Project 2
## Programming Language:
- C++
## Problem Description:
Professor João Caracol is conducting a study for the Government's task force responsible for researching transmissible diseases in Portugal. The task force is particularly interested in the transmission of diseases among the Portuguese population, aiming to study the best intervention mechanisms to contain the spread of diseases.

To facilitate this study, Professor João Caracol has access to the data from the social network TugaNet, which he believes accurately represents the real social interactions among individuals in the Portuguese population. In order to examine the worst-case scenario of disease propagation in Portugal, Professor João Caracol wants to understand the maximum number of jumps a given disease can make. However, considering the density of Portuguese cities, the Professor has decided to make a simplifying assumption: individuals who know each other directly or indirectly become infected instantly.

*Input:*
The input file contains information about the TugaNet network, defined as a directed graph of relationships between two individuals in the following format:

A line containing two integers: the number n of individuals (n ≥2) and the number of relationships m (m ≥0).
A list where each line i contains two integers x and y, representing that individual x knows individual y.
Any integers on a line are separated by exactly one white space, with no other characters except the end of the line.
Assume that the input graphs are directed (potentially) cyclic.

*Output:*
The program should write to the output an integer s corresponding to the maximum number of jumps that a disease can make in the TugaNet network.

```bash
# if you need to compile, the compilation parameters:
g++ -std=c++11 -O3 -Wall proj.cpp -o proj -lm

# program execution (you can change the input test, they are on the tests folder)
./proj < tests/01.in
```





