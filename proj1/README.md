# Project 2
## Programming Language:
- C++
## Problem Description:
Engineer João Caracol has been hired by the SuperMarble factory to optimize one of its marble sheet cutting lines. The line receives a marble sheet that needs to be cut to produce pieces with dimensions required by the factory's customers. The line is equipped with a machine featuring two disks capable of cutting sheets from one side to the other.

The cutting process works as follows:

The sheet is cut vertically or horizontally.
Each of the two new sheets produced either re-enters the cutting line or exits the line if it matches the dimensions of one of the pieces to be produced or is no longer possible to convert into a piece.
The factory is currently able to sell its entire production, so priority should be given to the manufacture of higher-value pieces. Engineer Caracol's goal is to build a program that, given a marble sheet, calculates the maximum value that can be obtained by cutting it into pieces corresponding to the dimensions requested by the customers.

Engineer Caracol can produce multiple copies of the same piece as he deems appropriate. Specifically, the line receives a rectangular marble sheet of dimensions X × Y. Additionally, Engineer Caracol has access to a list of n types of pieces to be produced, all with different dimensions. Each piece type i ∈ {1, ..., n} corresponds to a marble rectangle with dimensions ai × bi and is sold at a price pi.

***Input:***
The input file contains the dimensions of the sheet to be cut and the dimensions of the various types of pieces requested. These values are represented as follows:

The first line contains two positive integers X and Y, separated by a white space, corresponding to the dimensions of the sheet.
The second line contains a positive integer n, corresponding to the number of types of pieces that can be produced.
n lines describing each of the i types of pieces that can be produced. Each line consists of three positive integers ai, bi, and pi separated by a white space, where ai × bi corresponds to the dimensions of the piece type, and pi is the price of the piece.
***Output:***
The program should write to the output the maximum value that can be obtained from the given sheet as input; if no piece can be produced, it should simply print 0.

```bash
# if you need to compile, the compilation parameters:
g++ -std=c++11 -O3 -Wall proj.cpp -o proj -lm

# program execution (you can change the input test, they are on the tests folder)
./proj < tests/01.in
```





