

# MATRIX TYPES



## 2x2 floating point matrix

    mat2 aMat2 = mat2(1.0, 0.0,  // 1\. column
                      0.0, 1.0); // 2\. column
    mat2 bMat2 = mat2(1.0);

    mat2 cMat2 = mat2(aVec2, bVec2);
    mat2 dMat2 = mat2(aVec3, aFloat);

The data type **mat2** is used for floating point matrices with two times two components in column major order. There are several ways to initialize a matrix:

*   Components are specified by providing a scalar value for each component (first example). The matrix is filled column by column.
*   Components are specified by providing one scalar value. This value is used for the components on the main diagonal (the second example is equivalent to the first).
*   Components are specified by providing a combination of vectors and scalars. The respective values are used to initialize the components column by column. The arguments of the constructor must have at least as many components as the matrix that is initialized.

The following examples show how the values of a matrix can be accessed to set or get the values:

    mat2 aMat2;
    aMat2[1][1] = 1.0;
    float aFloat = aMat2[1][1];

    aMat2[0] = vec2(1.0);
    vec2 aVec2 = aMat2[0];

The values of a matrix can be accessed component-wise or column by column:

*   In the first example the bottom right component of a matrix is set to a float value.
*   In the second example a new variable of type float is initialized with the value of the bottom right component of a matrix.
*   In the third example the first column vector of a matrix is set with a vector.
*   In the fourth example a new variable of type float vector is initialized with the column vector.



## 3x3 floating point matrix

    mat3 aMat3 = mat3(1.0, 0.0, 0.0,  // 1\. column
                      0.0, 1.0, 0.0,  // 2\. column
                      0.0, 0.0, 1.0); // 3\. column
    mat3 bMat3 = mat3(1.0);

    mat3 cMat3 = mat3(aVec3, bVec3, cVec3);
    mat3 dMat3 = mat3(aVec4, aVec3, bVec4, aFloat);

The data type **mat3** is used for floating point matrices with three times three components in column major order. There are several ways to initialize a matrix:

*   Components are specified by providing a scalar value for each component (first example). The matrix is filled column by column.
*   Components are specified by providing one scalar value. This value is used for the components on the main diagonal (the second example is equivalent to the first).
*   Components are specified by providing a combination of vectors and scalars. The respective values are used to initialize the components column by column. The arguments of the constructor must have at least as many components as the matrix that is initialized.

The following examples show how the values of a matrix can be accessed to set or get the values:

    mat3 aMat3;
    aMat3[2][2] = 1.0;
    float aFloat = aMat3[2][2];

    aMat3[0] = vec3(1.0);
    vec3 aVec3 = aMat3[0];

The values of a matrix can be accessed component-wise or column by column:

*   In the first example the bottom right component of a matrix is set to a float value.
*   In the second example a new variable of type float is initialized with the value of the bottom right component of a matrix.
*   In the third example the first column vector of a matrix is set with a vector.
*   In the fourth example a new variable of type float vector is initialized with the column vector.



## 4x4 floating point matrix

    mat4 aMat4 = mat4(1.0, 0.0, 0.0, 0.0,  // 1\. column
                      0.0, 1.0, 0.0, 0.0,  // 2\. column
                      0.0, 0.0, 1.0, 0.0,  // 3\. column
                      0.0, 0.0, 0.0, 1.0); // 4\. column
    mat4 bMat4 = mat4(1.0);

    mat4 cMat4 = mat4(aVec4, bVec4, cVec4, dVec4);
    mat4 dMat4 = mat4(aVec4, aVec3, bVec4, cVec4, aFloat);

The data type **mat4** is used for floating point matrices with four times four components in column major order. There are several ways to initialize a matrix:

*   Components are specified by providing a scalar value for each component (first example). The matrix is filled column by column.
*   Components are specified by providing one scalar value. This value is used for the components on the main diagonal (the second example is equivalent to the first).
*   Components are specified by providing a combination of vectors and scalars. The respective values are used to initialize the components column by column. The arguments of the constructor must have at least as many components as the matrix that is initialized.

The following examples show how the values of a matrix can be accessed to set or get the values:

    aMat4[3][3] = 1.0;
    float aFloat = aMat4[3][3];

    aMat4[0] = vec4(1.0);
    vec4 aVec4 = aMat4[0];

The values of a matrix can be accessed component-wise or column by column:

*   In the first example the bottom right component of a matrix is set to a float value.
*   In the second example a new variable of type float is initialized with the value of the bottom right component of a matrix.
*   In the third example the first column vector of a matrix is set with a vector.
*   In the fourth example a new variable of type float vector is initialized with the column vector.
