

# BUILT-IN CONSTANTS (FRAGMENT-SHADER)

The following constants can be read by the fragment shader to determine the limitations of the OpenGL ES 2.0 environment at runtime.



## Number of texture units

    const mediump int gl_MaxTextureImageUnits >= 8

The built-in constant **gl_MaxTextureImageUnits** provides the maximum number of texture units that can be used by the fragment shader. The value of this variable is dependent on the OpenGL ES 2.0 implementation but has to be at least 8.



## Number of fragment uniform vectors

    const mediump int gl_MaxFragmentUniformVectors >= 16

The built-in constant **gl_MaxFragmentUniformVectors** provides the maximum number of uniform vectors that can be used by the fragment shader. The value of this variable is dependent on the OpenGL ES 2.0 implementation but has to be at least 16.



## Number of draw buffers

    const mediump int gl_MaxDrawBuffers = 1

The built-in constant **gl_MaxDrawBuffers** provides the maximum number of the available draw buffers. The value of this variable is 1 for all OpenGL ES 2.0 implementations. This might change in future versions.
