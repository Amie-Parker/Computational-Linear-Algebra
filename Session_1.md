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

## Pseudocode for Solving System of Equations
```python
FUNCTION Solution(A,b):
    create augmented matrix:K=[A|b]
    reduce in Row Reduched Echelon Form
    Rank = no. of non zero rows of RREF
    IF Rank(K)!=Rank(A):
      print("System is inconsistent")
    ELSE IF:
      Solve using back substitution
END FUNCTION
```


