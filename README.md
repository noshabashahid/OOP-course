# OOP-course
A complete Object-Oriented Programming (OOP) course with definitions, explanations, and C++ examples.
<br>
# Basics
<br>
Introduction to Object-Oriented Programming (OOP)

# What is Object-Oriented Programming (OOP)?

Object-Oriented Programming (OOP) is a programming paradigm based on the concept of "objects." Objects are instances of classes that contain both data (attributes) and functions (methods) that operate on the data. OOP is widely used in modern programming as it helps in organizing code efficiently and making it reusable.

# Key Features of OOP:

Encapsulation - Bundling data and methods that operate on the data into a single unit (class).
<br>
```cpp
class Student {
private: int age;
public:
void setAge(int a)
{ age = a; }  
        int getAge()
{ return age; }
};
```


Abstraction - Hiding implementation details and exposing only necessary parts of an object.
```cpp
class Shape {
 public:
 virtual void draw() = 0; };  
class Circle : public Shape {
 public: void draw() { /* Draw Circle */ } };
```

Inheritance - Allowing one class to derive properties and behavior from another class.
```cpp
class Animal {
 public: void eat()
{ /* Eating */ } };  
class Dog : public Animal {
public:
void bark() { /* Barking */ } };
```

Polymorphism - The ability of different classes to be treated as instances of the same class through a common interface.
```cpp
class Animal {
public:
 virtual void sound()
{ /* Animal sound */ } };  
class Dog : public Animal {
 public:
 void sound() override { /* Dog barks */ } };

```

# Why Use OOP?

OOP is beneficial because it:

Enhances code reusability through inheritance.

Improves maintainability by organizing code into objects.

Provides modularity making code easier to debug and extend.

Supports real-world modeling as everything is represented as objects.


