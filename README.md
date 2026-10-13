# mtm6302-week6
week 6 in class work

NOTES:
Creating Object Literals
    Any value that is not a ‘primitive data type’ is an object.
    JavaScript allows us to create custom objects known as object literals
    Made of properties(attributes), and functions(methods)
    To create an object we can use
        Object literal notation
            Example:    { studentNumber: 1, 
                        name: "Ervin Howell"
                        }
        Constructor function
            Example:    const student = new Object() 
                        student.studentNumber = 1 
                        student.name = "Ervin Howell"
        Object.create() method

Retrieving properties
    Dot notation objectName.propertyName
    Bracket notation objectName["propertyName"]

Updating properties
    Using either 'Dot' or 'Bracket' notation along with the assignment operator '=' is a straightforward and common practice to modify or update object properties.

Adding properties
    If the property doesn't exist in the object, it will be created, providing a simple way to add properties to the object.

Removing properties
    Use the delete operator to remove a property from an object.

Defining Object Methods
    Object methods are functions stored as object properties.

