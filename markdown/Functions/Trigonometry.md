

# ANGLE & TRIGONOMETRY FUNCTIONS



## Radians

    float radians(float degrees)  
    vec2 radians(vec2 degrees)  
    vec3 radians(vec3 degrees)  
    vec4 radians(vec4 degrees)

The **radians** function converts degrees to radians. The input parameter can be a floating scalar or a float vector. In case of a float vector all components are converted from degrees to radians separately.



## Degrees

    float degrees(float radians)  
    vec2 degrees(vec2 radians)  
    vec3 degrees(vec3 radians)  
    vec4 degrees(vec4 radians)

The **degrees** function converts radians to degrees. The input parameter can be a floating scalar or a float vector. In case of a float vector every component is converted from radians to degrees separately.



## Sine

    float sin(float angle)  
    vec2 sin(vec2 angle)  
    vec3 sin(vec3 angle)  
    vec4 sin(vec4 angle)

The **sin** function returns the sine of an angle in radians. The input parameter can be a floating scalar or a float vector. In case of a float vector the sine is calculated separately for every component.



## Cosine

    float cos(float angle)  
    vec2 cos(vec2 angle)  
    vec3 cos(vec3 angle)  
    vec4 cos(vec4 angle)

The **cos** function returns the cosine of an angle in radians. The input parameter can be a floating scalar or a float vector. In case of a float vector the cosine is calculated separately for every component.



## Tangent

    float tan(float angle)  
    vec2 tan(vec2 angle)  
    vec3 tan(vec3 angle)  
    vec4 tan(vec4 angle)

The **tan** function returns the tangent of an angle in radians. The input parameter can be a floating scalar or a float vector. In case of a float vector the tangent is calculated separately for every component.



## Arcsine

    float asin(float x)  
    vec2 asin(vec2 x)  
    vec3 asin(vec3 x)  
    vec4 asin(vec4 x)

The **asin** function returns the arcsine of an angle in radians. It is the inverse function of sine. The input parameter can be a floating scalar or a float vector. In case of a float vector the arcsine is calculated separately for every component.



## Arccosine

    float acos(float x)  
    vec2 acos(vec2 x)  
    vec3 acos(vec3 x)  
    vec4 acos(vec4 x)

The **acos** function returns the arccosine of an angle in radians. It is the inverse function of cosine. The input parameter can be a floating scalar or a float vector. In case of a float vector the arccosine is calculated separately for every component.



## Arctangent

    float atan(float y_over_x)  
    vec2 atan(vec2 y_over_x)  
    vec3 atan(vec3 y_over_x)  
    vec4 atan(vec4 y_over_x)

The **atan** function returns the arctangent of an angle in radians. It is the inverse function of tangent. The input parameter can be a floating scalar or a float vector. In case of a float vector the arctangent is calculated separately for every component.

    float atan(float y, float x)  
    vec2 atan(vec2 y, vec2 x)  
    vec3 atan(vec3 y, vec3 x)  
    vec4 atan(vec4 y, vec4 x)

There is also a two-argument variation of the **atan** function (in other programming languages often called atan2). For a point with Cartesian coordinates (x, y) the function returns the angle θ of the same point with polar coordinates (r, θ).
