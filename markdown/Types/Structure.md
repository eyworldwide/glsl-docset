

# STRUCTURES AND ARRAYS



## Structure

    struct matStruct {
        vec4 ambientColor; 
        vec4 diffuseColor;
        vec4 specularColor;
        float specularExponent;
    } newMaterial;

    newMaterial = matStruct(vec4(0.1, 0.1, 0.1, 1.0),
                            vec4(1.0, 0.0, 0.0, 1.0),
                            vec4(0.7, 0.7, 0.7, 1.0),
                            50.0);

The data type **struct** is used to declare custom data structures based on standard types. A constructor for the structure with the same name is created automatically. The declaration of a variable (in this case "newMaterial") is optional.

Side note: There has to be an exact correspondence of the arguments of the constructor and the elements of the structure.

    vec4 ambientColor = newMaterial.ambientColor; 
    vec4 diffuseColor = newMaterial.diffuseColor;
    vec4 specularColor = newMaterial.specularColor;
    float specularExponent = newMaterial.specularExponent;

The elements of a structure can be accessed using the dot-operator.



## Array

    int newIntArray[9];
    vec3 newVec3Array[3];

The data type **array** is used to declare custom arrays based on standard types. The following restrictions apply for arrays:

*   An array can contain all basic data types as well as structures.
*   An array can not be initialized at the time when it is declared.
*   The elements of an array have to be initialized one after the other.

The elements of an array are initialized and accessed using the index of the respective element:

    newIntArray[0] = 5;
    newVec3Array[1] = vec3(1.0, 1.0, 1.0);

    int newInt = newIntArray[0];
    vec3 newVec3 = newVec3Array[1];

Side note: On iOS devices the elements of an array can not be accessed using a variable index, i.e. the value of the index has to be a compile time constant.
