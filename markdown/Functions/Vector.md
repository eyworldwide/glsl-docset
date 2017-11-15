

# VECTOR RELATIONAL FUNCTIONS



## Less than comparison

    bvec2 lessThan(vec2 x, vec2 y)  
    bvec3 lessThan(vec3 x, vec3 y)    
    bvec4 lessThan(vec4 x, vec4 y)  

    bvec2 lessThan(ivec2 x, ivec2 y)  
    bvec3 lessThan(ivec3 x, ivec3 y)  
    bvec4 lessThan(ivec4 x, ivec4 y)

The **lessThan** function returns a boolean vector as result of a component-wise comparison in the form of x[i] < y[i]. The function has two input parameters of the type floating point vector or signed integer vector.



## Less than or equal comparison

    bvec2 lessThanEqual(vec2 x, vec2 y)  
    bvec3 lessThanEqual(vec3 x, vec3 y)  
    bvec4 lessThanEqual(vec4 x, vec4 y)  

    bvec2 lessThanEqual(ivec2 x, ivec2 y)  
    bvec3 lessThanEqual(ivec3 x, ivec3 y)  
    bvec4 lessThanEqual(ivec4 x, ivec4 y)

The **lessThanEqual** function returns a boolean vector as result of a component-wise comparison in the form of x[i] <= data-preserve-html-node="true" y[i]. The function has two input parameters of the type floating point vector or signed integer vector.



## Greater than comparison

    bvec2 greaterThan(vec2 x, vec2 y)  
    bvec3 greaterThan(vec3 x, vec3 y)  
    bvec4 greaterThan(vec4 x, vec4 y)  

    bvec2 greaterThan(ivec2 x, ivec2 y)  
    bvec3 greaterThan(ivec3 x, ivec3 y)  
    bvec4 greaterThan(ivec4 x, ivec4 y)

The **greaterThan** function returns a boolean vector as result of a component-wise comparison in the form of x[i] > y[i]. The function has two input parameters of the type floating point vector or signed integer vector.



## Greater than or equal comparison

    bvec2 greaterThanEqual(vec2 x, vec2 y)  
    bvec3 greaterThanEqual(vec3 x, vec3 y)  
    bvec4 greaterThanEqual(vec4 x, vec4 y)  

    bvec2 greaterThanEqual(ivec2 x, ivec2 y)  
    bvec3 greaterThanEqual(ivec3 x, ivec3 y)  
    bvec4 greaterThanEqual(ivec4 x, ivec4 y)

The **greaterThanEqual** function returns a boolean vector as result of a component-wise comparison in the form of x[i] >= y[i]. The function has two input parameters of the type floating point vector or signed integer vector.



## Equal comparison

    bvec2 equal(vec2 x, vec2 y)  
    bvec3 equal(vec3 x, vec3 y)  
    bvec4 equal(vec4 x, vec4 y)  

    bvec2 equal(ivec2 x, ivec2 y)  
    bvec3 equal(ivec3 x, ivec3 y)  
    bvec4 equal(ivec4 x, ivec4 y)

The **equal** function returns a boolean vector as result of a component-wise comparison in the form of x[i] = y[i]. The function has two input parameters of the type floating point vector or signed integer vector.



## Not equal comparison

    bvec2 notEqual(vec2 x, vec2 y)  
    bvec3 notEqual(vec3 x, vec3 y)  
    bvec4 notEqual(vec4 x, vec4 y)  

    bvec2 notEqual(ivec2 x, ivec2 y)  
    bvec3 notEqual(ivec3 x, ivec3 y)  
    bvec4 notEqual(ivec4 x, ivec4 y)

The **notEqual** function returns a boolean vector as result of a component-wise comparison in the form of x[i] != y[i]. The function has two input parameters of the type floating point vector or signed integer vector.



## Any evaluation

    bool any(bvec2 x)  
    bool any(bvec3 x)  
    bool any(bvec4 x)

The **any** function returns a boolean value as result of the evaluation whether any component of the input vector is TRUE. The function has one input parameters of the type boolean vector.



## All evaluation

    bool all(bvec2 x)  
    bool all(bvec3 x)  
    bool all(bvec4 x)

The **all** function returns a boolean value as result of the evaluation whether all components of the input vector are TRUE. The function has one input parameters of the type boolean vector.



## Not evaluation

    bvec2 not(bvec2 x)  
     bvec3 not(bvec3 x)  
     bvec4 not(bvec4 x)

The **not** function returns a boolean vector as result of a component-wise logical complement operation. The function has one input parameters of the type boolean vector.
