

# TEXTURE TYPES



## 2D texture

    uniform sampler2D texture;

The data type **sampler2D** is used to provide access to a 2D texture. It can only be declared as a uniform variable since it is a reference to data that has been loaded to a texture unit.

Side note: On iOS devices this data type can only be used in the fragment shader since they don't have texture image units that can be accessed by the vertex shader.



## Cubemap texture

    uniform samplerCube texture;

The data type **samplerCube** is used to provide access to a cubemap texture. It can only be declared as a uniform variable since it is a reference to data that has been loaded to a texture unit.

Side note: On iOS devices this data type can only be used in the fragment shader since they don't have texture image units that can be accessed by the vertex shader.
