# Class-and-Object

## Aim

To study and implement **classes and objects** in C++.

------------------------------------------------------------------------

##  Tools

-   **IDE**: Visual Studio Code
-   **Compiler**: g++ / MinGW / any C++ compiler

------------------------------------------------------------------------

##  Theory

### What is Object-Oriented Programming (OOPs)?

Object-Oriented Programming (OOP) is a programming paradigm that uses
**objects** to design computer programs.
OOPs promotes **code reusability, maintainability, and flexibility**,
particularly for large and complex projects, by using key concepts:
- **Encapsulation** → Wrapping of data and functions together.
- **Inheritance** → Reuse properties from one class to another.
- **Polymorphism** → One entity behaving in multiple forms.
- **Abstraction** → Hiding implementation details.

------------------------------------------------------------------------

### Classes

-   A **class** is a blueprint for creating objects.
-   It defines properties (data members) and behaviors (member
    functions).

**Example:**

``` cpp
class Car {
    string brand;
    int year;
};
```

------------------------------------------------------------------------

### Objects

-   An **object** is an instance of a class.\
-   Example: If `Car` is a class, then `Car myCar;` is an object.\
-   Objects allow us to **use** and **manipulate** class data.

------------------------------------------------------------------------

##  Algorithms

### 1. Create a class Car and its related objects

1.  Start
2.  Define a class `Car` with attributes: `brand` and `year`.
3.  Declare an array of Car objects.
4.  For each car, input `brand` and `year`.
5.  Display car details.
6.  End

------------------------------------------------------------------------

### 2. Calculate area and volume of cube/cuboid

1.  Start
2.  Define class `Area` with members: `length`, `width`, `height`.
3.  Input values.
4.  If `length == width` → print "Cube", else print "Cuboid".
5.  If any input \< 0 → print error.
6.  Else calculate
    -   Area = `length × width`
    -   Volume = `length × width × height
7.  Display results.
8.  End

------------------------------------------------------------------------

### 3. Volume of cube using methods inside & outside the class

1.  Start
2.  Define class `Cube` with members: `length, width, height`.
3.  Define `volume_in()` inside the class.
4.  Declare `volume_out()` inside but define outside class.
5.  Input dimensions.
6.  Call `volume_in()` and `volume_out()`.
7.  End

------------------------------------------------------------------------

### 4. Cube volume (public & private members)

1.  Start
2.  Define class `Cube` with **private data members**:
    `length, width, height`.
3.  Define public function `volume()` that calculates and returns
    `length × width × height`.
4.  Create object of Cube.
5.  Call `volume()` and display result.
6.  End

------------------------------------------------------------------------

##  Conclusion

In this experiment, we learned:
- Basics of **Object-Oriented Programming (OOPs)**.
- How to define and use **classes** and **objects** in C++.
- How to implement **methods inside and outside** a class.
- Use of **private and public members** for data security.
