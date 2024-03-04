# Project 3
## Programming Language:
- Python
## Problem Description:
Professor Natalino Caracol has been hired by the company UbiquityInc in Rovaniemi, Lapland, to develop a program that estimates the maximum profit achievable through the production and sale of toys during Christmas. The company produces a set of n wooden toys {x1, ..., xn} daily, where each toy xi yields a profit li. In addition to the maximum production limit for each toy due to assembly line restrictions, the company is also constrained by a total maximum quantity of toys that can be produced daily, owing to restrictions in the boreal forest.

This Christmas, the company has decided to not only sell each toy individually but also special packages containing three distinct toys. These packages generate higher profits than the sum of the individual toy profits. The goal is to provide Rüdolf, the CEO of UbiquityInc, with the maximum daily profit. UbiquityInc will handle the distribution problem separately.

The implementation should be based on Python using the PuLP library.

**Input:**
The input file contains information about the n products, their profits, and the production capacity of the company for each product in the following format:

A line containing three integers: t indicating the number of different toys that can be produced, p indicating the number of special packages, and max indicating the maximum number of toys that can be produced per day.
A list of n lines, where each line contains two integers li and ci, indicating the profit and production capacity of toy i.
A list of p lines, where each line contains four integers i, j, k, and li jk, indicating the profit li jk of the special package {i, j, k}, and the names of the products i, j, and k that constitute it.
Any integers in a line are separated by exactly one white space, with no other characters except the end of the line.

**Output:**
The program should write to the output an integer corresponding to the maximum profit that Rüdolf can obtain daily.

```bash

#The PuLP library should be installed using the following command:
python -m pip install pulp

#Ensure that you have a linear programming solver installed, such as [GLPK](https://www.gnu.org/software/glpk/) or LP_solve. To install GLPK, for example, on Ubuntu, use the following command:
sudo apt-get install glpk-utils

# program execution (you can change the input test, they are on the tests folder)
python3 proj.py < tests/01.in
```





