

# PARAMETER QUALIFIERS



## Input qualifier

    in

The qualifier **in** is used to mark a parameter as read-only when a function is declared. The parameter will be passed by value to the function and the value can not be modified by the function.

    int newFunction(in bvec4 aBvec4,   // read-only 
                    out vec3 aVec3,    // write-only
                    inout int aInt);   // read-write

The above function declaration shows the three possible parameter qualifiers. The usage of the read-only qualifier is not necessary since this is the default if no qualifier is specified.



## Output qualifier

    out

The qualifier **out** is used to mark a parameter as write-only when a function is declared. The parameter will be passed by reference to the function but it is not initialized, i.e. the value can not be read. The value can be modified by the function and the changes are preserved after the function exits.

    int newFunction(in bvec4 aBvec4,   // read-only 
                    out vec3 aVec3,    // write-only
                    inout int aInt);   // read-write

The above function declaration shows the three possible parameter qualifiers. The usage of the read-only qualifier is not necessary since this is the default if no qualifier is specified.

## Input-output qualifier

    inout

The qualifier **inout** is used to mark a parameter as read-write when a function is declared. The parameter will be passed by reference to the function and is initialized, i.e. the value can be read. The value can be modified by the function and the changes are preserved after the function exits.

    int newFunction(in bvec4 aBvec4,   // read-only 
                    out vec3 aVec3,    // write-only
                    inout int aInt);   // read-write

The above function declaration shows the three possible parameter qualifiers. The usage of the read-only qualifier is not necessary since this is the default if no qualifier is specified.
