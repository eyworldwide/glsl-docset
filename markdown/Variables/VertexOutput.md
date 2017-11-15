

# SPECIAL OUTPUT VARIABLES OF THE VERTEX SHADER



## Vertex position

    highp vec4 gl_Position;

The built-in variable **gl_Position** is used by the vertex shader to hand over the transformed vertex position to the OpenGL ES 2.0 pipeline. The variable is declared as shown above and can be used in the vertex shader for an assignment without prior declaration.

The values of the position vector are interpreted in clip coordinate space. The vertex shader is responsible to execute all vertex manipulations, e.g. the transformation from object coordinates to clip coordinates.

The assignment of values to this variable is mandatory for the vertex shader.



## Point size

    mediump float gl_PointSize;

The built-in variable **gl_PointSize** is used by the vertex shader to hand over the point size of a vertex to the OpenGL ES 2.0 pipeline. The variable is declared as shown above and can be used in the vertex shader for an assignment without prior declaration.

The value of the the point size is interpreted as the radius in pixels of the point sprite. The actual drawing geometry is a quad (a rectangular primitive) that is derived from the position and the radius of the point sprite.

Side note: The value assigned to this variable is only taken into account by the OpenGL ES 2.0 pipeline if the rendered primitives are points.
