## Pseudocode for linear algebra
```python
FUNCTION matrix_sum(A,B):
   Get the number of rows and columns in matrix A
   Create an empty matrix C with same dimensions
   FOR each row:
      FOR each column:
           Set C[i][j] to the sum of A[i][j] and B[i][j]
   RETURN the matrix C 
END FUNCTION
```
$$A=\begin {pmatrix}
     1&2&3\\
     4&5&6\\
     7&8&9\\
     \end {pmatrix}$$

