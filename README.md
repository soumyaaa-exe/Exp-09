Aim
To study and implement NumPy arrays in Python and perform basic array and matrix operations such as determining array properties, generating arrays using built-in functions, calculating determinant and transpose of matrices, and performing matrix multiplication.

Theory
NumPy (Numerical Python) is a powerful Python library used for numerical computations and handling large multidimensional arrays and matrices. It provides various mathematical functions to perform operations efficiently.
A NumPy array is a collection of elements arranged in rows and columns. Arrays allow fast mathematical and logical operations compared to normal Python lists.
Important properties of arrays include:
Dimension (ndim): Number of axes in the array.
Shape: Number of elements in each dimension.
Data type (dtype): Type of elements stored in the array.
Size: Total number of elements in the array.

NumPy also provides built-in functions such as:
zeros() – creates an array filled with zeros
ones() – creates an array filled with ones
eye() – creates an identity matrix
arange() – generates values in a given range
linspace() – generates evenly spaced values within a range

For matrix operations:
Transpose of a matrix interchanges rows and columns.
Determinant of a matrix is a scalar value that represents certain properties of the matrix.
Matrix multiplication combines two matrices following row-by-column multiplication rules.
NumPy provides functions like np.linalg.det(), .T, np.dot(), and @ operator to perform these matrix operations efficiently.

Algorithm 1
Program: Creation of NumPy Arrays and Basic Operations

Start the program.
Import the NumPy library using import numpy as np.
Create a one-dimensional array using np.array().
Create a two-dimensional array using np.array().
Display both arrays.
Determine the dimension of the arrays using .ndim.
Determine the shape of the arrays using .shape.
Determine the data type of elements using .dtype.
Determine the total number of elements using .size.
Generate arrays using NumPy built-in functions:
np.zeros() to create a matrix of zeros
np.ones() to create a matrix of ones
np.eye() to create an identity matrix
np.arange() to generate values within a range
np.linspace() to generate evenly spaced numbers
Perform arithmetic operations on arrays such as multiplication and addition.
Calculate statistical values like mean, median, and maximum.
Display all results.
Stop the program.

Algorithm 2
Program: Determinant and Transpose of a Matrix

Start the program.
Import the NumPy library.
Create a matrix using np.array() with rows and columns.
Display the original matrix.
Calculate the determinant of the matrix using np.linalg.det().
Calculate the transpose of the matrix using .T.
Display the determinant value.
Display the transpose of the matrix.
Stop the program.

Algorithm 3
Program: Matrix Multiplication Using NumPy

Start the program.
Import the NumPy library.
Define two matrices using np.array().
Display both matrices.
Perform matrix multiplication using np.dot(matrix1, matrix2).
Store the result in a variable.
Perform matrix multiplication using the @ operator.
Store the result in another variable.
Display both multiplication results.
Stop the program.

Conclusion
Thus, the implementation of NumPy arrays and matrix operations in Python was successfully performed. The experiment demonstrated how to create arrays, determine their properties, generate arrays using built-in functions, compute determinant and transpose of matrices, and perform matrix multiplication efficiently using NumPy functions.
