

# SPECIAL INPUT VARIABLES OF THE FRAGMENT SHADER



## Fragment coordinates

    mediump vec4 gl_FragCoord;

The built-in variable **gl_FragCoord** is used by the OpenGL ES 2.0 pipeline to hand over the coordinates of the fragment to the fragment shader. The variable is read-only and the value is assigned by the OpenGL ES 2.0 pipeline.

The values of the fragment coordinate vector are given in the window coordinate system.



## Fragment orientation

    bool gl_FrontFacing;

The built-in variable **gl_FrontFacing** is used by the OpenGL ES 2.0 pipeline to hand over the information to the fragment shader if the fragment is part of a front-facing primitive (triangle). The variable is read-only and the value is assigned by the OpenGL ES 2.0 pipeline.

The front-facing variable has a boolean value.



## Point coordinates

    mediump int gl_PointCoord;

The built-in variable **gl_PointCoord** is used by the OpenGL ES 2.0 pipeline to hand over the coordinates of a point sprite to the fragment shader. The variable is read-only and the value is calculated and assigned by the OpenGL ES 2.0 pipeline based on the position and radius of the point sprite..

Side note: A value for this variable is provided by the OpenGL ES 2.0 pipeline only if the rendered primitives are points.
