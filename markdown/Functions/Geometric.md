

# GEOMETRIC FUNCTIONS



## Length

    float length(float x)  
    float length(vec2 x)  
    float length(vec3 x)  
    float length(vec4 x)

The **length** function returns the length of a vector defined by the Euclidean norm, i.e. the square root of the sum of the squared components. The input parameter can be a floating scalar or a float vector. In case of a floating scalar the length function is trivial and returns the absolute value.



## Distance

    float distance(float p0, float p1)  
    float distance(vec2 p0, vec2 p1)  
    float distance(vec3 p0, vec3 p1)  
    float distance(vec4 p0, vec4 p1)

The **distance** function returns the distance between two points. The distance of two points is the length of the vector d = p0 - p1, that starts at p1 and points to p0\. The input parameters can be floating scalars or float vectors. In case of floating scalars the distance function is trivial and returns the absolute value of d.



## Dot product

    float dot(float x, float y)  
    float dot(vec2 x, vec2 y)  
    float dot(vec3 x, vec3 y)  
    float dot(vec4 x, vec4 y)

The **dot** function returns the dot product of the two input parameters, i.e. the sum of the component-wise products. If x and y are the same the square root of the dot product is equivalent to the length of the vector. The input parameters can be floating scalars or float vectors. In case of floating scalars the dot function is trivial and returns the product of x and y.



## Cross product

    vec3 cross(vec3 x, vec3 y)

The **cross** function returns the cross product of the two input parameters, i.e. a vector that is perpendicular to the plane containing x and y and has a magnitude that is equal to the area of the parallelogram that x and y span. The input parameters can only be 3-component floating vectors. The cross product is equivalent to the product of the length of the vectors times the sinus of the(smaller) angle between x and y.



## Normalize

    float normalize(float x)  
    vec2 normalize(vec2 x)  
    vec3 normalize(vec3 x)  
    vec4 normalize(vec4 x)

The **normalize** function returns a vector with length 1.0 that is parallel to x, i.e. x divided by its length. The input parameter can be a floating scalar or a float vector. In case of a floating scalar the normalize function is trivial and returns 1.0.



## Faceforward

    float faceforward(float N, float I, float Nref)  
    vec2 faceforward(vec2 N, vec2 I, vec2 Nref)  
    vec3 faceforward(vec3 N, vec3 I, vec3 Nref)  
    vec4 faceforward(vec4 N, vec4 I, vec4 Nref)

The **faceforward** function returns a vector that points in the same direction as a reference vector. The function has three input parameters of the type floating scalar or float vector: N, the vector to orient, I, the incident vector, and Nref, the reference vector. If the dot product of I and Nref is smaller than zero the return value is N. Otherwise -N is returned.



## Reflect

    float reflect(float I, float N)  
    vec2 reflect(vec2 I, vec2 N)  
    vec3 reflect(vec3 I, vec3 N)  
    vec4 reflect(vec4 I, vec4 N)

The **reflect** function returns a vector that points in the direction of reflection. The function has two input parameters of the type floating scalar or float vector: I, the incident vector, and N, the normal vector of the reflecting surface.

Side note: To obtain the desired result the vector N has to be normalized. The reflection vector always has the same length as the incident vector. From this it follows that the reflection vector is normalized if N and I are both normalized.



## Refract

    float refract(float I, float N, float eta)  
    vec2 refract(vec2 I, vec2 N, float eta)  
    vec3 refract(vec3 I, vec3 N, float eta)  
    vec4 refract(vec4 I, vec4 N, float eta)

The **refract** function returns a vector that points in the direction of refraction. The function has two input parameters of the type floating scalar or float vector and one input parameter of the type floating scalar: I, the incident vector, N, the normal vector of the refracting surface, and eta, the ratio of indices of refraction.

Side note: To obtain the desired result the vectors I and N have to be normalized.

