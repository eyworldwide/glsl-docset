

# STORAGE QUALIFIERS



## Constant

    const

The qualifier **const** is used for variables that are compile-time constants or for function parameters that are read-only.



## Attribute

    attribute

The qualifier **attribute** is used to declare variables that are shared between a vertex shader and the OpenGL ES environment.

Since the vertex shader is executed one time for each vertex attributes are used to specify per vertex data. They typically provide data such as the object space position, the normal direction and the texture coordinates of a vertex. Attributes are read-only variables, i.e. their value can not be changed in the vertex shader.

Side note: Since an attribute is never initialized in the shader it has to be loaded with data by the application executing the shader.



## Uniform

    uniform

The qualifier **uniform** is used to declare variables that are shared between a shader and the OpenGL ES environment.

Uniforms can be used in the vertex shader and the fragment shader and they must have global scope. The same uniform variable can be used in the vertex and the fragment shader, but since both shaders share the same name space the declaration has to be identical. Uniforms are used to specify properties of the object that is rendered. Examples are the projection matrix, the light position or the material color of the object. Uniforms are read-only variables, i.e. their value can not be changed in the shader.

Side note: Since a uniform is never initialized in the shader it has to be loaded with data by the application executing the shader.



## Varying

    varying

The qualifier **varying** is used to declare variables that are shared between the vertex shader and the fragment shader.

Varying are used for information that is calculated in the vertex shader and should be handed over to the fragment shader. Both shaders have to declare the varying and the declarations must be identical. The vertex shader initializes the varying for each vertex. After that the per vertex data of the varying is interpolated during rasterization before being handed over to the fragment shader.

The varying qualifier can only be used with floating point scalar, floating point vectors and (floating point) matrices as well as arrays containing these types.
