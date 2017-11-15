

# VECTOR TYPES



## 2-component boolean vector

    bvec2 aBvec2 = bvec2(true, true);
    bvec2 bBvec2 = bvec2(true);

    bvec2 cBvec2 = bvec2(aBvec3);
    bvec2 dBvec2 = bvec2(aBvec3.x, aBvec3.y);

The data type **bvec2** is used for boolean vectors with two components. There are several ways to initialize a vector:

*   Components are specified by providing a scalar value for each component (first example).
*   Components are specified by providing one scalar value. This value is used for all components (the second example is equivalent to the first).
*   Components are specified by providing a vector of higher dimension. The respective values are used to initialize the components (the second and third example are equivalent).

Side note: The vector constructors can be used to cast between different vector types since type conversions are done automatically for each component.



## 3-component boolean vector

    vec3 aBvec3 = bvec3(true, true, true);
    vec3 bBvec3 = bvec3(true);

    vec3 cBvec3 = bvec3(aBvec4);
    vec3 dBvec3 = bvec3(aBvec4.x, aBvec4.y, aBvec4.z);

    vec3 eBvec3 = bvec3(aBvec2, aBool);
    vec3 fBvec3 = bvec3(aBvec2.x, aBvec2.y, aBool);

The data type **bvec3** is used for boolean vectors with three components. There are several ways to initialize a vector:

*   Components are specified by providing a scalar value for each component (first example).
*   Components are specified by providing one scalar value. This value is used for all components (the second example is equivalent to the first).
*   Components are specified by providing a vector of higher dimension. The respective values are used to initialize the components (the second and third example are equivalent).
*   Components are specified by providing a combination of vectors and/or scalars. The respective values are used to initialize the vector (the fifth and sixth example are equivalent). The arguments of the constructor must have at least as many components as the vector that is initialized.

Side note: The vector constructors can be used to cast between different vector types since type conversions are done automatically for each component.



## 4-component boolean vector

    vec4 aBvec4 = bvec4(true, true, true, true);
    vec4 bBvec4 = bvec4(true);

    vec4 cBvec4 = bvec4(aBvec2, aBool, aBvec3);
    vec4 dBvec4 = bvec4(aBvec2.x, aBvec2.y, aBool, aBvec3.x);

The data type **bvec4** is used for boolean vectors with four components. There are several ways to initialize a vector:

*   Components are specified by providing a scalar value for each component (first example).
*   Components are specified by providing one scalar value. This value is used for all components (the second example is equivalent to the first).
*   Components are specified by providing a combination of vectors and scalars. The respective values are used to initialize the components (the third and fourth example are equivalent). The arguments of the constructor must have at least as many components as the vector that is initialized.

Side note: The vector constructors can be used to cast between different vector types since type conversions are done automatically for each component.



## 2-component integer vector

    bvec2 aIvec2 = ivec2(1, 1);
    bvec2 bIvec2 = ivec2(1);

    bvec2 cIvec2 = ivec2(aIvec3);
    bvec2 dIvec2 = ivec2(aIvec3.x, aIvec3.y);

The data type **ivec2** is used for integer vectors with two components. There are several ways to initialize a vector:

*   Components are specified by providing a scalar value for each component (first example).
*   Components are specified by providing one scalar value. This value is used for all components (the second example is equivalent to the first).
*   Components are specified by providing a vector of higher dimension. The respective values are used to initialize the components (the second and third example are equivalent).

Side note: The vector constructors can be used to cast between different vector types since type conversions are done automatically for each component.



## 3-component integer vector

    vec3 aIvec3 = ivec3(1, 1, 1);
    vec3 bIvec3 = ivec3(1);

    vec3 cIvec3 = ivec3(aIvec4);
    vec3 dIvec3 = ivec3(aIvec4.x, aIvec4.y, aIvec4.z);

    vec3 eIvec3 = ivec3(aIvec2, aInt);
    vec3 fIvec3 = ivec3(aIvec2.x, aIvec2.y, aInt);

The data type **ivec3** is used for integer vectors with three components. There are several ways to initialize a vector:

*   Components are specified by providing a scalar value for each component (first example).
*   Components are specified by providing one scalar value. This value is used for all components (the second example is equivalent to the first).
*   Components are specified by providing a vector of higher dimension. The respective values are used to initialize the components (the second and third example are equivalent).
*   Components are specified by providing a combination of vectors and/or scalars. The respective values are used to initialize the vector (the fifth and sixth example are equivalent). The arguments of the constructor must have at least as many components as the vector that is initialized.

Side note: The vector constructors can be used to cast between different vector types since type conversions are done automatically for each component.



## 4-component integer vector

    vec4 aIvec4 = ivec4(1, 1, 1, 1);
    vec4 bIvec4 = ivec4(1);

    vec4 cIvec4 = ivec4(aIvec2, aInteger, aIvec3);
    vec4 dIvec4 = ivec4(aIvec2.x, aIvec2.y, aInt, aIvec3.x);

The data type **ivec4** is used for integer vectors with four components. There are several ways to initialize a vector:

*   Components are specified by providing a scalar value for each component (first example).
*   Components are specified by providing one scalar value. This value is used for all components (the second example is equivalent to the first).
*   Components are specified by providing a combination of vectors and scalars. The respective values are used to initialize the components (the third and fourth example are equivalent). The arguments of the constructor must have at least as many components as the vector that is initialized.

Side note: The vector constructors can be used to cast between different vector types since type conversions are done automatically for each component.



## 2-component floating point vector

    vec2 aVec2 = vec2(1.0, 1.0);
    vec2 bVec2 = vec2(1.0);

    vec2 cVec2 = vec2(aVec3);
    vec2 dVec2 = vec2(aVec3.x, aVec3.y);

The data type **vec2** is used for floating point vectors with two components. There are several ways to initialize a vector:

*   Components are specified by providing a scalar value for each component (first example).
*   Components are specified by providing one scalar value. This value is used for all components (the second example is equivalent to the first).
*   Components are specified by providing a vector of higher dimension. The respective values are used to initialize the components (the second and third example are equivalent).

Side note: The vector constructors can be used to cast between different vector types since type conversions are done automatically for each component.



## 3-component floating point vector

    vec3 aVec3 = vec3(1.0, 1.0, 1.0);
    vec3 bVec3 = vec3(1.0);

    vec3 cVec3 = vec3(aVec4);
    vec3 dVec3 = vec3(aVec4.x, aVec4.y, aVec4.z);

    vec3 eVec3 = vec3(aVec2, aFloat);
    vec3 fVec3 = vec3(aVec2.x, aVec2.y, aFloat);

The data type **vec3** is used for floating point vectors with three components. There are several ways to initialize a vector:

*   Components are specified by providing a scalar value for each component (first example).
*   Components are specified by providing one scalar value. This value is used for all components (the second example is equivalent to the first).
*   Components are specified by providing a vector of higher dimension. The respective values are used to initialize the components (the second and third example are equivalent).
*   Components are specified by providing a combination of vectors and/or scalars. The respective values are used to initialize the vector (the fifth and sixth example are equivalent). The arguments of the constructor must have at least as many components as the vector that is initialized.

Side note: The vector constructors can be used to cast between different vector types since type conversions are done automatically for each component.



## 4-component floating point vector

    vec4 aVec4 = vec4(1.0, 1.0, 1.0, 1.0);
    vec4 bVec4 = vec4(1.0);

    vec4 cVec4 = vec4(aVec2, aFloat, aVec3);
    vec4 dVec4 = vec4(aVec2.x, aVec2.y, aFloat, aVec3.x);

The data type **vec4** is used for floating point vectors with four components. There are several ways to initialize a vector:

*   Components are specified by providing a scalar value for each component (first example).
*   Components are specified by providing one scalar value. This value is used for all components (the second example is equivalent to the first).
*   Components are specified by providing a combination of vectors and scalars. The respective values are used to initialize the components (the third and fourth example are equivalent). The arguments of the constructor must have at least as many components as the vector that is initialized.

Side note: The vector constructors can be used to cast between different vector types since type conversions are done automatically for each component.
