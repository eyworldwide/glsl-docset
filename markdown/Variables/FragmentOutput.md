

# SPECIAL OUTPUT VARIABLES OF THE FRAGMENT SHADER



## Fragment color

    mediump vec4 gl_FragColor;

The built-in variable **gl_FragColor** is used by the fragment shader to hand over the color of the fragment to the OpenGL ES 2.0 pipeline. The variable is pre-declared as shown above that way the variable can be used in the fragment shader for an assignment without prior declaration.

The values of the color vector are interpreted in the RGBA color space.

The assignment of values to this variable is mandatory for the fragment shader.
