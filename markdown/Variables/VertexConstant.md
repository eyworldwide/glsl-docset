

# BUILT-IN CONSTANTS (VERTEX-SHADER)

The following constants can be read by the vertex shader to determine the limitations of the OpenGL ES 2.0 environment at runtime.



## Number of vertex attributes

    const mediump int gl_MaxVertexAttribs >= 8

The built-in constant **gl_MaxVertexAttribs** provides the maximum number of attributes that can be used by the vertex shader. The value of this variable is dependent on the OpenGL ES 2.0 implementation but has to be at least 8.



## Number of vertex uniform vectors

    const mediump int gl_MaxVertexUniformVectors >= 128

The built-in constant **gl_MaxVertexUniformVectors** provides the maximum number of uniform vectors that can be used by the vertex shader. The value of this variable is dependent on the OpenGL ES 2.0 implementation but has to be at least 128.

## Number of varying vectors

    const mediump int gl_MaxVaryingVectors >= 8

The built-in constant **gl_MaxVaryingVectors** provides the maximum number of varying vectors that can be used by the vertex shader to hand over data to the fragment shader. The value of this variable is dependent on the OpenGL ES 2.0 implementation but has to be at least 8.

## Number of texture units

    const mediump int gl_MaxVertexTextureImageUnits >= 0

The built-in constant **gl_MaxVertexTextureImageUnits** provides the maximum number of texture units that can be used by the vertex shader. The value of this variable is dependent on the OpenGL ES 2.0 implementation but has to be at least 0.

Side note: This number is actually 0 on all iOS devices. This is the reason why there is no access to textures data in the vertex shader.

## Number of combined texture units

    const mediump int gl_MaxCombinedTextureImageUnits >= 8

The built-in constant **gl_MaxCombinedTextureImageUnits** provides the maximum number of texture units that are available in the vertex shader or the fragment shader respectivley. The value of this variable is dependent on the OpenGL ES 2.0 implementation but has to be at least 8.
