

# MATRIX FUNCTIONS



## Component-wise matrix multiplication

    mat2 matrixCompMult(mat2 x, mat2 y)  
    mat3 matrixCompMult(mat3 x, mat3 y)  
    mat4 matrixCompMult(mat4 x, mat4 y)

The **matrixCompMult** function returns a matrix resulting from a component-wise multiplication. The function has two input parameters of the type floating point matrix and returns a matrix of the same type. The indices of the returned matrix are calculated as follows: z[i][j] = x[i][j] * y[i][j]

Side note: This is NOT the matrix multiplication known from linear algebra. To obtain the "normal" matrix multiplication the _operator is used: z = x_ y
