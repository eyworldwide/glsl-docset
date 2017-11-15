

# COMMON FUNCTIONS



## Absolute value

    float abs(float x)  
    vec2 abs(vec2 x)  
    vec3 abs(vec3 x)  
    vec4 abs(vec4 x)

The **abs** function returns the absolute value of x, i.e. x when x is positive or zero and -x for negative x. The input parameter can be a floating scalar or a float vector. In case of a float vector the operation is done component-wise.



## Sign

    float sign(float x)  
    vec2 sign(vec2 x)  
    vec3 sign(vec3 x)  
    vec4 sign(vec4 x)

The **sign** function returns 1.0 when x is positive, 0.0 when x is zero and -1.0 when x is negative. The input parameter can be a floating scalar or a float vector. In case of a float vector the operation is done component-wise.



## Floor

    float floor(float x)  
    vec2 floor(vec2 x)  
    vec3 floor(vec3 x)  
    vec4 floor(vec4 x)

The **floor** function returns the largest integer number that is smaller or equal to x. The input parameter can be a floating scalar or a float vector. In case of a float vector the operation is done component-wise.

Side note: The return value is of type floating scalar or float vector although the result of the operation is an integer.



## Ceiling

    float ceil(float x)  
    vec2 ceil(vec2 x)  
    vec3 ceil(vec3 x)  
    vec4 ceil(vec4 x)

The **ceiling** function returns the smallest number that is larger or equal to x. The input parameter can be a floating scalar or a float vector. In case of a float vector the operation is done component-wise.

Side note: The return value is of type floating scalar or float vector although the result of the operation is an integer.



## Fractional part

    float fract(float x)  
    vec2 fract(vec2 x)  
    vec3 fract(vec3 x)  
    vec4 fract(vec4 x)

The **fract** function returns the fractional part of x, i.e. x minus floor(x). The input parameter can be a floating scalar or a float vector. In case of a float vector the operation is done component-wise.



## Modulo

    float mod(float x, float y)  
    vec2 mod(vec2 x, vec2 y)  
    vec3 mod(vec3 x, vec3 y)  
    vec4 mod(vec4 x, vec4 y)

The **mod** function returns x minus the product of y and floor(x/y). The input parameters can be floating scalars or float vectors. In case of float vectors the operation is done component-wise.

Side note: If x and y are integers the return value is the remainder of the division of x by y as expected.

    float mod(float x, float y)  
    vec2 mod(vec2 x, float y)  
    vec3 mod(vec3 x, float y)  
    vec4 mod(vec4 x, float y)

There is also a variation of the **mod** function where the second parameter is always a floating scalar.



## Minimum

    float min(float x, float y)  
    vec2 min(vec2 x, vec2 y)  
    vec3 min(vec3 x, vec3 y)  
    vec4 min(vec4 x, vec4 y)

The **min** function returns the smaller of the two arguments. The input parameters can be floating scalars or float vectors. In case of float vectors the operation is done component-wise.

    float min(float x, float y)  
    vec2 min(vec2 x, float y)  
    vec3 min(vec3 x, float y)  
    vec4 min(vec4 x, float y)

There is also a variation of the **min** function where the second parameter is always a floating scalar.



## Maximum

    float max(float x, float y)  
    vec2 max(vec2 x, vec2 y)  
    vec3 max(vec3 x, vec3 y)  
    vec4 max(vec4 x, vec4 y)

The **max** function returns the larger of the two arguments. The input parameters can be floating scalars or float vectors. In case of float vectors the operation is done component-wise.

    float max(float x, float y)  
    vec2 max(vec2 x, float y)  
    vec3 max(vec3 x, float y)  
    vec4 max(vec4 x, float y)

There is also a variation of the **max** function where the second parameter is always a floating scalar.



## Clamp

    float clamp(float x, float minVal, float maxVal)  
    vec2 clamp(vec2 x, vec2 minVal, vec2 maxVal)  
    vec3 clamp(vec3 x, vec3 minVal, vec3 maxVal)  
    vec4 clamp(vec4 x, vec4 minVal, vec4 maxVal)

The **clamp** function returns x if it is larger than minVal and smaller than maxVal. In case x is smaller than minVal, minVal is returned. If x is larger than maxVal, maxVal is returned. The input parameters can be floating scalars or float vectors. In case of float vectors the operation is done component-wise.

    float clamp(float x, float minVal, float maxVal)  
    vec2 clamp(vec2 x, float minVal, float maxVal)  
    vec3 clamp(vec3 x, float minVal, float maxVal)  
    vec4 clamp(vec4 x, flfloat minVal, float maxVal)

There is also a variation of the **clamp** function where the second and third parameters are always a floating scalars.



## Mix

    float mix(float x, float y, float a)  
    vec2 mix(vec2 x, vec2 y, vec2 a)  
    vec3 mix(vec3 x, vec3 y, vec3 a)  
    vec4 mix(vec4 x, vec4 y, vec4 a)

The **mix** function returns the linear blend of x and y, i.e. the product of x and (1 - a) plus the product of y and a. The input parameters can be floating scalars or float vectors. In case of float vectors the operation is done component-wise.

    float mix(float x, float y, float a)  
    vec2 mix(vec2 x, vec2 y, float a)  
    vec3 mix(vec3 x, vec3 y, float a)  
    vec4 mix(vec4 x, vec4 y, float a)

There is also a variation of the **mix** function where the third parameter is always a floating scalar.



## Step

    float step(float edge, float x)  
    vec2 step(vec2 edge, vec2 x)  
    vec3 step(vec3 edge, vec3 x)  
    vec4 step(vec4 edge, vec4 x)

The **step** function returns 0.0 if x is smaller then edge and otherwise 1.0\. The input parameters can be floating scalars or float vectors. In case of float vectors the operation is done component-wise.

    float step(float edge, float x)  
    vec2 step(float edge, vec2 x)  
    vec3 step(float edge, vec3 x)  
    vec4 step(float edge, vec4 x)

There is also a variation of the **step** function where the edge parameter is always a floating scalar.



## Smoothstep

    float smoothstep(float edge0, float edge1, float x)  
    vec2 smoothstep(vec2 edge0, vec2 edge1, vec2 x)  
    vec3 smoothstep(vec3 edge0, vec3 edge1, vec3 x)  
    vec4 smoothstep(vec4 edge0, vec4 edge1, vec4 x)

The **smoothstep** function returns 0.0 if x is smaller then edge0 and 1.0 if x is larger than edge1\. Otherwise the return value is interpolated between 0.0 and 1.0 using Hermite polynomials. The input parameters can be floating scalars or float vectors. In case of float vectors the operation is done component-wise.

    float smoothstep(float edge0, float edge1, float x)  
    vec2 smoothstep(float edge0, float edge1, vec2 x)  
    vec3 smoothstep(float edge0, float edge1, vec3 x)  
    vec4 smoothstep(float edge0, float edge1, vec4 x)

There is also a variation of the **smoothstep** function where the edge0 and edge1 parameters are always floating scalars.
