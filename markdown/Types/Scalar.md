

# SCALAR TYPES



## Void

    void main(void);
    int aFunction(void);
    void bFunction(float);

The data type **void** is used when the parameter list of a function is empty and when a function does not return a value.



## Boolean

    bool aBool = true;
    bool bBool = bool(aInt);
    bool cBool = bool(aFloat);

The data type **bool** is used for boolean values (true or false).

Side note: Implicit type conversions are not supported. Type conversions can be done using constructors as shown in the second and third example.



## Integer

    int aInt = 42;
    int bInt = int(aBool);
    int cInt = int(aFloat);

The data type **int** is used for integer values.

Side note: Implicit type conversions are not supported. Type conversions can be done using constructors as shown in the second and third example.



## Floating point

    float aFloat = 1.0;
    float bFloat = float(aBool);
    float cFloat = float(aInt);

The data type **float** is used for floating point (scalar) values.

Side note: Implicit type conversions are not supported. Type conversions can be done using constructors as shown in the second and third example.
