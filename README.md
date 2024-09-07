# Constructor_Overloading
Experiment_13

## Contents
- [Aim](#aim)
- [Software Used](#software-used)
- [Theory](#theory)
  * [Definition](#definition)
  * [Purpose](#Purpose)
  * [Properties](#Properties)
  * [Advantages](#Advantages)
- [Algorithms](#algorithms)
- [Conclusion](#conclusion)
## Aim 
To study and implement the Constructor Overloading.

## Software Used 
VS Code,Dev C++

### Theory:
Constructor overloading allows a class to have more than one constructor, each with different parameters. This feature provides flexibility in object initialization, enabling the creation of objects in various ways.
## Definition:
Constructors are special member functions that are automatically called when an object of a class is created. Overloading refers to having multiple constructors with the same name but different parameter lists.
## Purpose:
 - Constructor overloading enables initializing objects with different sets of data.
 - It allows setting default values or initializing objects with specific data based on the constructor used.
 - Provides more control over how objects are created and initialized, ensuring they start in a valid state.
 - By allowing multiple ways to initialize an object, it reduces the need for complex initialization code or additional setter methods.

### Properties:
 1. **Multiple Constructors**: A class can have multiple constructors as long as they have different parameter lists (i.e., different number or types of parameters).  
 2. **Default Arguments**: Constructors can have default arguments. If multiple constructors can be invoked with the same set of arguments due to default values, the most specific one is chosen.
 3. **No Return Type**: Constructors do not have a return type, not even `void`.
 4. **Initialization**: Constructors are called when an object is created, initializing the object's data members.

### Advantages
1. **Flexibility**: Constructor overloading provides flexibility in initializing objects with different sets of initial values.
2. **Convenience**: It allows for convenient initialization methods, reducing the need for multiple initialization methods or complex initialization code.
3. **Code Clarity**: It makes code more readable by using different constructors for different initialization scenarios, making object creation more intuitive.
4. **Default Initialization**: Allows the creation of objects with default values, enhancing the ease of use when certain parameters are not always needed.

Syntax: class ClassName {
    public:
    ClassName(); // Default constructor
    ClassName(int a); // Parameterized constructor
    ClassName(int a, int b); // Another parameterized constructor
};

**Operator overloading** is a feature that allows you to define custom behaviors for operators when they are used with user-defined types (classes). This feature extends the functionality of operators to work with objects of custom classes.

### Properties:
 1. **Custom Behavior**: Operators can be overloaded to perform operations that are specific to the class's requirements.
 2. **Syntax Similarity**: Overloaded operators use the same syntax as built-in operators, making the code more readable and intuitive.
 3. **Member or Non-Member Functions**: Overloaded operators can be implemented as member functions or non-member functions (friend functions).
 4. **Operators that can be Overloaded**: Most operators can be overloaded, including binary operators (`+`, `-`, `*`, `/`), unary operators (`++`, `--`), and others (`=`, `[]`, `()`, `<<`, `>>`).

### Advantages:
 1. **Enhanced Readability**: Makes code more intuitive and readable by allowing operators to work with user-defined types in a familiar way.
 2. **Improved Usability**: Allows user-defined types to be used with operators in a manner similar to built-in types, making custom classes easier to work with.
 3. **Consistency**: Provides a consistent interface for performing operations on objects, reducing the need for separate methods for operations.
 4. **Encapsulation**: Encapsulates the operation logic within the class, maintaining the integrity and functionality of the class's data.

### Importance
 1. **Natural Integration**: Integrates user-defined types seamlessly into expressions involving operators, making them more versatile and usable.
 2. **Custom Operations**: Enables defining custom behaviors for operators that are specific to the class's needs, enhancing the functionality of user-defined types.
 3. **Code Efficiency**: Improves code efficiency and reduces the complexity of operations by leveraging operator overloading for custom types.

---


## Algorithms
### Define method inside class

1. **Start**

2. **Define the `Student` Class**
   - **Public Section**
     - **Define the `myMethod` Function**
       - Print"I am studying in 2nd year"
3. **Main Function**
   - Create an object `s1` of type `Student`.
   - Call the `myMethod` function on the `s1` object.

4. **End**

### Define method outside class
1. **Start**

2. **Define the `Student` Class**
   - **Public Section**
     - **Declare the `myMethod` Function**
       - The function will be defined outside the class.

3. **Define the `myMethod` Function Outside the Class**
   - **Specify that this function belongs to the `Student` class**
   - Print the message "A Sophomore in SIT" to the console.

4. **Main Function**
   - Create an object `s1` of type `Student`.
   - Call the `myMethod` function on the `s1` object.

5. **End**

### Cuboid Volume
1. **Start**

2. **Define `Cubiod` Class**
   - **Public Section**
     - **Data Members**
       - `int length, breadth, height, volume;`
     - **Member Functions**
       - **`input()` Function**
         - Prompt the user to enter the length, breadth, and height of the cuboid.
         - Read the values and store them in t `length`, `breadth`, and `height` variables.
       - **`Volume()` Function**
         - Calculate the volume of the cuboid using the formula: `volume = length * breadth * height`.
       - **`Output()` Function**
         - Print : "The volume of the given Cuboid is : <volume>".

3. **Main Function**
   - Create an object `v1` of type `Cubiod`.
   - Call the `input()` function for `v1` to get the dimensions from the user.
   - Call the `Volume()` function for `v1` to calculate the volume.
   - Call the `Output()` function for`v1` to display the volume.

4. **End**

## Conclusion
We learnt to use the concepts of Class and Objects.
