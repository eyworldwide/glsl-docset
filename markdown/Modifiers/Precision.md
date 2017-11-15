

# PRECISION QUALIFIERS



## High precision

    highp

The qualifier **highp** is used to specify the highest available precision for a variable. The variable has to be an integer or a floating point scalar or a vector or matrix based on these types. The precision qualifier precedes the type in the variable declaration.

In the vertex shader the use of a precision qualifier is optional. If no qualifier is given all variables are of highest precision. In the fragment shader a precision qualifier has to be used when declaring a variable unless a default precision has been defined for the specific type.

    uniform highp vec3 lightDirection;

The actual range corresponding to a precision qualifier is dependent on the specific OpenGL ES implementation. Using a lower precision might have a positive effect on performance (frame rates) and power efficiency but might also cause a loss in rendering quality. The appropriate trade-off can only be determined by testing different precision configurations.



## Medium precision

    mediump

The qualifier **mediump** is used to specify a precision between the highest and lowest available precision for a variable. The variable has to be an integer or a floating point scalar or a vector or matrix based on these types. The precision qualifier precedes the type in the variable declaration.

In the vertex shader the use of a precision qualifier is optional. If no qualifier is given all variables are of highest precision. In the fragment shader a precision qualifier has to be used when declaring a variable unless a default precision has been defined for the specific type.

    varying mediump vec2 textureCoordinate;

The actual range corresponding to a precision qualifier is dependent on the specific OpenGL ES implementation. Using a lower precision might have a positive effect on performance (frame rates) and power efficiency but might also cause a loss in rendering quality. The appropriate trade-off can only be determined by testing different precision configurations.



## Low precision

    lowp

The qualifier **lowp** is used to specify the lowest available precision for a variable. The variable has to be an integer or a floating point scalar or a vector or matrix based on these types. The precision qualifier precedes the type in the variable declaration.

In the vertex shader the use of a precision qualifier is optional. If no qualifier is given all variables are of highest precision. In the fragment shader a precision qualifier has to be used when declaring a variable unless a default precision has been defined for the specific type.

    varying lowp vec4 colorVarying;

The actual range corresponding to a precision qualifier is dependent on the specific OpenGL ES implementation. Using a lower precision might have a positive effect on performance (frame rates) and power efficiency but might also cause a loss in rendering quality. The appropriate trade-off can only be determined by testing different precision configurations.



## Default precision

    precision

The keyword **precision** is used in conjunction with a precision qualifier and a data type to specify the default precision for that data type. The type has to be an integer or a floating point scalar or a vector or matrix based on these types.

In the vertex shader all variables are of highest precision by default. The default can be changed defining another default precision. In the fragment shader a precision qualifier has to be used when declaring a variable unless a default precision has been defined for the specific type.

    precision highp float;

The actual range corresponding to a precision qualifier is dependent on the specific OpenGL ES implementation. Using a lower precision might have a positive effect on performance (frame rates) and power efficiency but might also cause a loss in rendering quality. The appropriate trade-off can only be determined by testing different precision configurations.
