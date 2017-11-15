

# EXPONENTIAL FUNCTIONS



## Exponentiation

    float pow(float x, float y)  
    vec2 pow(vec2 x, vec2 y)  
    vec3 pow(vec3 x, vec3 y)  
    vec4 pow(vec4 x, vec4 y)

The **power** function returns x raised to the power of y. The input parameters can be floating scalars or float vectors. In case of float vectors the operation is done component-wise.



## Exponential function

    float exp(float x)  
    vec2 exp(vec2 x)  
    vec3 exp(vec3 x)  
    vec4 exp(vec4 x)

The **exp** function returns the constant e raised to the power of x. The input parameter can be a floating scalar or a float vector. In case of a float vector the operation is done component-wise.



## Natural logarithm

    float log(float x)  
    vec2 log(vec2 x)  
    vec3 log(vec3 x)  
    vec4 log(vec4 x)

The **log** function returns the power to which the constant e has to be raised to produce x. The input parameter can be a floating scalar or a float vector. In case of a float vector the operation is done component-wise.



## Exponential function (base 2)

    float exp2(float x)  
    vec2 exp2(vec2 x)  
    vec3 exp2(vec3 x)  
    vec4 exp2(vec4 x)

The **exp2** function returns 2 raised to the power of x. The input parameter can be a floating scalar or a float vector. In case of a float vector the operation is done component-wise.



## Logarithm (base 2)

    float log2(float x)  
    vec2 log2(vec2 x)  
    vec3 log2(vec3 x)  
    vec4 log2(vec4 x)

The **log2** function returns the power to which 2 has to be raised to produce x. The input parameter can be a floating scalar or a float vector. In case of a float vector the operation is done component-wise.



## Square root

    float sqrt(float x)  
    vec2 sqrt(vec2 x)  
    vec3 sqrt(vec3 x)  
    vec4 sqrt(vec4 x)

The **sqrt** function returns the square root of x. The input parameter can be a floating scalar or a float vector. In case of a float vector the operation is done component-wise.



## Inverse square root

    float inversesqrt(float x)  
    vec2 inversesqrt(vec2 x)  
    vec3 inversesqrt(vec3 x)  
    vec4 inversesqrt(vec4 x)

The **inversesqrt** function returns the inverse square root of x, i.e. the reciprocal of the square root. The input parameter can be a floating scalar or a float vector. In case of a float vector the operation is done component-wise.
