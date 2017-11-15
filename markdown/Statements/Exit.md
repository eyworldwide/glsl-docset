

# EXIT EXECUTION



## Return statement

    return;

The keyword **return** is used to define a proper exit for a function. If the function has the return type void no value is passed back to the caller of the function.

    return aValue;

If the function has a non-void return type a parameter of the same type has to be included in the statement. The value is passed back to the caller of the function.



## Discard statement

    discard;

The keyword **discard** is used to define an exceptionally exit for a fragment shader. It is used exit the fragment shader immediately and to signal the OpenGL ES 2.0 pipeline that the respective fragment should not be drawn.
