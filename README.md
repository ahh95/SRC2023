# SRC2023
This repository contains some pdf files extracted from Mathematica, the software which we used to aid our computations in our Mathematics SRC at AUB, 2023. The purpose of uploading these files here is to be able to link them in our submitted paper.
The viewer should note that the computations are not perfectly arranged and that the pdf files show some inputs and outputs that were unneeded or which were missing something and were later on corrected. Also, the notation used is not very standard.
Below, you will find a list of notations and commands used.
1) The "capital letter" notation for complex conjugate. For instance, Z is the complex conjugate of z.
2) The subscript notation used is the variable/unknown followed by a number. For example, z1 is z_1 (i.e. z with subscript 1), Z2 is Z_2, etc.
3) The "double subscript notation" for two independent subscripts. The way we used it was for instance denoting by z_(1,1) by z11, Z_(2,3) by Z23, etc. Something like z30 is to be understood as z_(3,0).
4) What we refer to as alpha, beta, and gamma in our paper are what are denoted in the pdf files by a, b, and g (respectively).
5) When A is a matrix, Aij is to be understood as A_(i,j) (i.e. the entry of the ith row and jth column).
6) For a function z of t, the notation dz denotes the derivative of z with respect to t (i.e. "z dot"). This definition is also displayed in the pdf files using the D[map,var] command. 
7) The p's are the conjugate momenta.
8) The command D[map,var] finds the derivative of "map" as a function of "var". For instance, D[x^2 + 2x, x] = 2x + 2.
9) The command Inverse[mat] finds the inverse matrix of a square matrix "mat".
10) The command Det[mat] finds the determinant of a square matrix "mat".
11) The command(s) A.B, A.B.C, etc. find the "matrix" product of the involved "matrices". One could also invoke vectors, and accordingly this dot command finds the output as a matrix or a vector or a scalar. For instance, u.A.v would return a scalar if u is a 1xn vector, A is an n x m matrix, and v is an m x 1 vector.
12) The curly brackets define vectors and matrices. For example, {1,2,3} is the vector (1,2,3), and {{1,2},{3,4}} is the matrix with first row (1,2) and second row (3,4).
13) The Dsolve command solves an ODE or a system of ODE's. More information about this command can be found on the Mathematica website.
14) The ci and di (along with their conjugagtes Ci and Di) are constants coming from solving ODE's.
15) The Collect[expression, var] factorizes and arranges a given "expression" with respect to suitable considerations for "var", for instance according to increasing powers of "var".
16) The TrigReduce command simplifies a given expression involving trigonometric functions, possibly invoking De Moivre's formula if it makes the expression more compact and reduced.
17) The % command returns the latest output.
18) The Expand command completely expands (and reduces) a given expression.
